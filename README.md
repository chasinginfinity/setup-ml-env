# How to set up your Machine Learning Environment
Write-up for the video : https://youtu.be/gx9_L7BnUhc  
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
#### Matplotlib
```
pip instal matplotlib
```
#### Pandas
```
pip install pandas
```
#### Scikit-learn
```
pip install scikit-learn
```
#### Tensorflow
```
pip install tensorflow
```
#### Keras
```
pip install keras
```