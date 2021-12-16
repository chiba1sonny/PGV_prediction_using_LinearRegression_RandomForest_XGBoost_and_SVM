# PGV-prediction-using-LR-RF-XGBoost-and-SVM
# What is PGV attenuation
The attenuation relationship is a method to predict the ground motion intensity of earthquake that may occur in the future based on the ground motion records of past earthquakes.
# Introduction
This project tries to develop new attenuation relationships of peak ground velocity using machine learning methods: random forest and neural network. 
In order to compare with the predictors obtained by machine learning, we have also constructed a new attenuation relationship of peak ground velocity using three-stage regression procedure.
# Dataset
6,944 ground motion records at 1,184 seismic observation stations which were observed during the 32 earthquakes from 1997 to 2011 in Japan are employed to construct the attenuation relationships. Ground motion records from the 4 recent earthquakes are used as the test set. 
# Variables
The objective variable---PGV;
The explanatory variables---Mw,r,H,Si
# Construction of attenuation equation
log⁡PGV=-1.541+0.648Mw-0.00153r-log⁡(⁡r+0.0033*10^(0.5*Mw))+0.00299H+Ci 
![image](https://user-images.githubusercontent.com/68838083/122856360-9fb23480-d351-11eb-9d60-27cca906cc14.png)
# Construction of machine learning models
![image](https://user-images.githubusercontent.com/68838083/122856433-c3757a80-d351-11eb-9d6c-4c869c1ee882.png)
![image](https://user-images.githubusercontent.com/68838083/122856445-c7a19800-d351-11eb-948c-ad01d5d1e5b0.png)
![image](https://user-images.githubusercontent.com/68838083/122856461-cd977900-d351-11eb-8352-b810c332e591.png)
