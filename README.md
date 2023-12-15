# 🟣 Project - Gaussian Processes 🟣

### Alexander Sabelström - @[Linkedin](https://www.linkedin.com/in/alexander-sabelstr%C3%B6m-484256293/)

# 🟣 Table of Contents 🟣
* [Introduction](#introduction)  
* [Folders in Repository ](#folders)  
* [Requirements](#introduction)  

# 🟣 Introduction <a name="introduction"/> 🟣
Gaussian Process Project for the course: Project in Data Science (1DL505), Uppsala University
  
Main tasks:   
⚪ Learn about making Gaussian Processes (GPs) using https://gpytorch.ai/  
⚪ Learn about inducing points and implement them with gpytorch  
⚪ Craft kernels to match the datasets  
⚪ Measure the difference of speed and accuracy with and without inducing points  

# 🟣 What is Inducing Points? 🟣
A major challenge of applying GPs in real-world applications is their computational complexity.
This complexity arises from the need to handle large covariance matrices whose dimensions depend on the number of data points.
Several methods have been proposed to resolve this issue, such as inducing points.
The idea behind inducing points is to approximate the whole set of observations by a smaller set of points.
various methods exist for selecting inducing points in Gaussian process models, and one of the approaches used in this project is the K-means method.
The K-means method partitions the dataset into 'K' clusters and selects the centroids from each cluster to act as inducing points.
![image](https://github.com/Sabelz/Gaussian_Processes_Inducing_Points/assets/61190192/1a0bcd8b-46c0-471d-bfdc-c009adf68889)

![image](https://github.com/Sabelz/Project18/assets/61190192/d4269e04-756c-4a6d-836b-ae9f549ade1c)
# 🟣 Folders in Repository  <a name="folders"/> 🟣
## ⚪ [datasets](./datasets) - All different datasets
## ⚪ [GPs](./GPs) - All different Gaussian Processes:
### 〰️ Wiggle dataset 〰️
#### ⚪ [GPWiggle](./GPs/GPWiggle.ipynb) - Visual example on wiggle dataset
#### ⚪ [GPWiggleInducingPoints](./GPs/GPWiggleInducingPoints.ipynb) - Visual example with and without inducing points on wiggle dataset

<div style="text-align:center">
  <img src="https://github.com/Sabelz/Gaussian_Processes_Inducing_Points/assets/61190192/a6d68c88-bbdc-47a4-b187-de5862402786" alt="Image 1">
</div>

<div style="text-align:center">
  <img src="https://github.com/Sabelz/Gaussian_Processes_Inducing_Points/assets/61190192/6de9a0a9-473a-40eb-a5ce-478906d59497" alt="Image 2">
</div>



### 🧸 Toy dataset 🧸
#### ⚪ [GPToy](./GPs/GPToy.ipynb) - Visual example on toy dataset
#### ⚪ [GPToyInducingPoints](./GPs/GPToyInducingPoints.ipynb) - Visual example with and without inducing points on toy dataset
![image](https://github.com/Sabelz/Gaussian_Processes_Inducing_Points/assets/61190192/1a0bcd8b-46c0-471d-bfdc-c009adf68889)

![image](https://github.com/Sabelz/Project18/assets/61190192/d4269e04-756c-4a6d-836b-ae9f549ade1c)
### 🪨 Concrete dataset 🪨
#### ⚪ [GPConcrete](./GPs/GPConcrete.ipynb) - In depth analysis using UCI Concrete dataset
### ⚡️ Power Plant dataset ⚡️
#### ⚪ [GPPowerPlant](./GPs/GPPowerPlant.ipynb) - In depth analysis using UCI Power Plant dataset

# 🟣 Requirements <a name="requirements"/> 🟣
Project was developed in Google Colab, installing gpytorch was required. Other packages already included<br /> 
Check [requirements](requirements.txt) for packages already included in Google Colab


