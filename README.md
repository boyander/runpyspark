# Easy to use apache spark script

**IMPORTANT:** Before runing the `runPySpark.sh` script, ensure you have followed the checklist for your OS.
Copy the runPySpark script into your prefered folder and inside it run the following:
    $ bash runPySpark.sh

## Checklist for Ubuntu
* Install spark following this [medium post](https://medium.com/@josemarcialportilla/installing-scala-and-spark-on-ubuntu-5665ee4b62b1)
* Create an alias of spark in your home directory or rename the installation to just "spark"
    $ ln -s ~/spark-2.4.0-bin-hadoop2.7 ~/spark
* Ensure you have spark-shell in your $PATH variable
    $ echo 'export PATH="$PATH:~/spark/bin"' >> ~/.zshrc
* Run the `runPySpark.sh` script and enjoy!

## Checklist for MacOSX
* You need brew installed
* brew install jq 
* brew install spark-shell
* Run the `runPySpark.sh` script and enjoy!