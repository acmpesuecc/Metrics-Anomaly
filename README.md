# Metrics-Anomaly
> Forecasts and finds anomalies in cloud metrics data. 


## Before you begin -

Before you begin, feel free to go through the following resources -  
* Time Series Data - Go through https://www.aptech.com/blog/introduction-to-the-fundamentals-of-time-series-data-and-analysis/  
* AWS Cloudwatch Metrics - Go through https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/working_with_metrics.html  

## Prerequisites - 

We expect you to have been using Jupyter Notebooks.In case you pictured a planet instead :innocent:,  
Install everything below ASAP before your friend goes ahead makes a PR :) 

*  Git - https://git-scm.com/downloads. OSX and Linux machines typically have this already installed.  
*  Anaconda - https://docs.anaconda.com/anaconda/install/,  Jupyter Notebook should come along.(you'll need a Jupyter Notebook Server configured on your machine. If you have not installed Jupyter before, you may find the Anaconda Individual Edition the simplest to install.)  


## Installation  

To install, just run the following commands in order.  

### 1. Setup a conda environment.
```shell
conda create -n time fbprophet==0.7.1 plotly nbdev
```
Here "time" is the name of your environment, and fbprophet, plotly, and nbdev are the libraries being setup in it.

### 2. Activate your newly created environment.
```shell
conda activate time
```

### 3. Clone our Repo in the directory you want to work in.
```shell
git clone https://github.com/acmpesuecc/Metrics-Anomaly.git
```
### 4. cd into our Repo
```shell
cd Metrics-Anomaly/
```

### 5. Install git hooks  
Jupyter Notebooks can cause challenges with git conflicts, but life becomes much easier when you use nbdev. As a first step, run nbdev_install_git_hooks in the terminal from your project folder.  
```shell
nbdev_install_git_hooks
```

### 5. Depending on the Issue make your changes 

### 6.Build lib and docs
Now you can build the python module and docs. Run these commands from anywhere inside the project directory.
```shell
nbdev_build_lib
nbdev_clean_nbs
nbdev_build_docs
```

---
> :warning: **All these steps must be done before you commit and make a PR!**
---

### We have already made an implementation using Facebook's Prophet.
Checkout the project page and repo. The python quick start guide can help you get started. <br>
Website: https://facebook.github.io/prophet/ <br>
Repo: https://github.com/facebook/prophet

Check 01_prophet-ec2.ipynb
