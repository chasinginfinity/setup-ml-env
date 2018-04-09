# How to set up your Machine Learning Environment
Write-up for the video : 
In this tutorial I show you how to set up an environment for your machine learning projects using Anaconda. 

## Step 1 - Download & Install Anaconda 
You can download Anaconda from here : https://www.anaconda.com/download/
I would recomend to download the Python3 version.

## Step2 - Create a new Environment
Go to the start menu and search for Anaconda Prompt.
In the Anaconda prompt type : 
```
conda create -n machine-learning-env pip python=3.6
```
Where `machine-learning-env` is your environment name. 
This creates a new environment in Anaconda.
To activate the environment type : 
```
activate machine-learning-env
```
Now your prompt should change and will begin with `(machine-learning-env)`

## Step 3 - Install the required packages
#### Scipy
```
pip install scipy
```
#### Numpy
```
pip install numpy
```
scipy: 0.18.1
numpy: 1.11.1
matplotlib: 1.5.3
pandas: 0.18.1
statsmodels: 0.6.1
sklearn: 0.17.1