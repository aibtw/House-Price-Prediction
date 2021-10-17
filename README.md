# Gradient Descent Implementation
__________________________________________

This project implements the gradient descent algorithm for machine learning (Regression Classifier), as a part of 
**Introduction to Artificial Intelligence** course at **KAU**. The goal is to train the model to predict
houses price based on a provided dataset. Only a part of the dataset is going to be used. Specifically, 
only the following features are taken into account:  

**a. MSSubClass  
b. LotArea  
c. Overall Quality  
d. Overall Condition  
e. Year Built  
f. 1stFlrSF  
g. 2ndFlrSF  
h. GrLivArea  
i. GarageArea  
j. YrSold**

## How to use
__________________________________________
To run the program, use the following commands:\
<pre>
python regression_classifier_gd.py T1 :     Train a linear model
python regression_classifier_gd.py T2 :     Train a polynomial model of order 2
python regression_classifier_gd.py T3 :     Train a polynomial model of order 3
python regression_classifier_gd.py V :      validate(test) the trained models
</pre>

## Output files
__________________________________________
**For training, there are 6 output files**
* *linear_thetas.npy*
* *Linear_Train_Results.txt*
* *Polynomial_order2_thetas.npy*
* *Polynomial_order2_Train_Results*
* *Polynomial_order3_thetas*
* *Polynomial_order3_Train_Results*

**2 files for each model:**
<pre>
.npy files: these contain the values of (thetas) that the validation program reads.
.txt files: these show the loss value and thetas values for the last run.
</pre>

**For validation, there are no output files. The results are printed in command line directly**

These results are simply an overview of predicton (first and last 3 predicted prices to be compared with those in test.csv),
in addition to the loss. These are shown for all the 3 trained models.


