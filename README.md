# Java Koans 

[![Build Status](https://travis-ci.org/matyb/java-koans.png?branch=master)](https://travis-ci.org/matyb/java-koans)

Installiation:
===================
* Visit https://github.com/pairing4good/java-koans
* Click the `Fork` button in the upper right. (https://help.github.com/en/articles/fork-a-repo)
* Clone your fork copy to your local computer. (https://help.github.com/en/articles/cloning-a-repository)

Running Instructions:
=====================
* Open a terminal and cd to the directory you cloned:
```cd <the directory you just unarchived>```
* Within it you'll find:
    * *koans*: this directory contains the application and its lessons, it is all that is needed to advance through the koans themselves and **it can be distributed independently**
    * *lib*: this directory contains the code the koans engine is comprised of and built with
    * *gradle*: wrapper for build library used to build koans source, setup project files in eclipse/idea, run tests, etc. you probably don't need to touch anything in here
* Change directory to the koans directory: ```cd koans```
* If you are using windows enter: ```run.bat``` or ```./run.sh``` if you are using Mac or Linux

Something's wrong:
==================
* If the koans app is constantly timing out compiling a koan, your computer may be too slow to compile the koan classes with the default timeout value. Update the compile_timeout_in_ms property in koans/app/config/config.properties with a larger value and try again.
