# machine-learning-challenge

Kaleah French
May 12, 2020

Data preprocessing was critical for the performance of both models that were used in this assignment. Several features were removed, the y column had to be changed from string to categorical, in addition to many other preprocessing measures. 

I used the koi_impact at the independent variable after running the models several times with other features. The koi_disposition (candidate or false positive) was the dependent variable (per the instructions). The “CANDIDATE” rows were removed from the koi_disposition as it was the third value found in the dependent variable column. 

Model 1: Linear Regression
o Mean Squared Error (MSE): 0.39369727495044143
o R-squared (R2 ): -0.7541424638853655


Model 2: Classification with SVR
o R-squared (R2 ): -4.468411805146828 Train
o R-squared (R2 ): -4.468380100152639 Test


Based on the two models, Model 1, the Linear Regression model is a much more valid model to use given the low MSE value and the R2 value of -0.75 indicating that the disposition is negatively correlated to the koi_impact but it is a strong correlation based on its proximity to negative 1. I think the model requires more fine-tuning to support its use in determining exoplanets, but it is well on its way. 
