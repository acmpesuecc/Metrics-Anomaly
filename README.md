# Metrics-Anomaly
> Finds anomalies in cloud metrics data. 


[![Open Source? Yes!](https://img.shields.io/badge/Version-0.1-green)](https://img.shields.io/badge/Version-0.1-green)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)
[![Maintenance](https://img.shields.io/badge/OS-Linux%2C%20Mac-red)](https://img.shields.io/badge/OS-Linux%2C%20Mac-red)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Documentation Status](https://img.shields.io/badge/Python-v3.6-blue)](https://img.shields.io/badge/Python-v3.6-blue)
[![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](http://ansicolortags.readthedocs.io/?badge=latest)

## Before you begin -

Before you begin we recommend you to know more about -  
* Time Series Data - Go through https://www.aptech.com/blog/introduction-to-the-fundamentals-of-time-series-data-and-analysis/  
* AWS Cloudwatch Metrics - Go through https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html  

## Prerequisites - 

We expect you to have been using Jupyter Notebooks.In case you pictured a planet instead :innocent:,  
Install everything below ASAP before your friend goes ahead makes a PR :) 

*  Git - https://git-scm.com/downloads. OSX and Linux machines typically have this already installed.  
*  Anaconda - https://docs.anaconda.com/anaconda/install/,  Jupyter Notebook should come along.(you'll need a Jupyter Notebook Server configured on your machine. If you have not installed Jupyter before, you may find the Anaconda Individual Edition the simplest to install.)  


## Installation  

To install, just run the following commands in order.  




### 1. Clone our Repo
```shell
git clone https://github.com/manikyabard/Metrics-Anomaly.git (Change it later)
```
### 2. cd into our Repo
```shell
cd Metrics-Anomaly/
```
### 3. Install nbdev
```shell
python -m pip install nbdev
```
### 4. Install git hooks  
Jupyter Notebooks can cause challenges with git conflicts, but life becomes much easier when you use nbdev. As a first step, run nbdev_install_git_hooks in the terminal from your project folder.  
```shell
nbdev_install_git_hooks
```

### 5. Depending on the Issue make your changes 

### 6.Build lib
Now you can create your python module. To do so, just run nbdev_build_lib from the terminal when anywhere in your project folder.
```shell
nbdev_build_lib
```
```shell
nbdev_clean_nbs
```  
### 7. Edit index.ipynb(If required)
create your documentation home page and readme file by making changes to index.ipynb


### 8. Build docs
Now you can create your documentation. To do so, just run nbdev_build_docs from the terminal when anywhere in your project folder.  
```shell
nbdev_build_docs
```
---
> :warning: **All these steps must be done before you commit and make a PR!**
---

## We have already made an implementation using Facebook's Prophet
