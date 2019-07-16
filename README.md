# spark-basic-structure
Java on Piku Micro PaaS on Ubuntu 18 and Linux Mint 19
This is an example of one possible way of structuring a Spark application.

This is a simple Java app that demonstrates deploying your apps on Piku.

To publish this app to `piku`, make a copy of this folder and run the following commands:

```bash
cd sparkAppp_copy
git init .
git remote add piku piku@your_server:sparkApp
git add .
git commit -a -m "initial commit"
git push piku master
```

The application has filters, controllers, views, authentication, localization, error handling, and more. 
It contains the source code for the tutorial found at https://sparktutorials.github.io/2016/06/10/spark-basic-structure.html

## Critique welcome
If you find anything you disagree with, please feel free to create an issue.

## Screenshot
![Application Screenshot](https://sparktutorials.github.io/img/posts/sparkBasicStructure/screenshot.png)
