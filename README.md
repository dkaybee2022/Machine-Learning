# Molecular Solubility Prediction Model

## Overview

### This project involves the development of a machine learning model to predict the solubility of molecules, which is crucial for biologists to determine the suitability of molecules as drug candidates. The model is built using Python and the scikit-learn library.

## Table of Contents

	1.	Introduction
	2.	Dataset
	3.	Installation
	4.	Usage
	5.	Model Development
	6.	Results
	7.	Contributing
	8.	License
	9.	Contact

## Introduction

### This project aims to assist biologists in evaluating molecular solubility to identify potential drug candidates. Solubility is a key factor in drug design and development, and accurate predictions can streamline the drug discovery process.

## Dataset

### The dataset used in this project contains information on the solubility of various molecules. Key features include molecular descriptors that are essential for the prediction model.

###	•	Source: [here](https://github.com/dkaybee2022/Machine-Learning/blob/main/delaney_solubility_with_descriptors.csv)
###	•	Target Variable: Solubility

## Installation

### To run this project, you need to have Python installed along with the following libraries:

	•	scikit-learn
	•	pandas
	•	numpy
	•	matplotlib (if applicable)

## Use the following commands to install the required libraries:

### pip install scikit-learn pandas numpy matplotlib

### Usage

## To use the model, follow these steps:

###	1.	Clone the repository:

 git clone [https://github.com/dkaybee2022/Machine-Learning/blob/main/delaney_solubility_with_descriptors.csv]


##	2.	Run the main script:

### python main.py



## instructions on input data and ouput.

### Data Preperation
To prepare the model, I started off by seperating the data frame for testing and training. I did this by splitting x and y. After this step, I split the dataset for testing and training using sklearn; splittting the data created four new variables: x_test, x_train, y_test, y_train. The training set has about 80% of the data while the test set has 20%. The same tests were done to train the random frest model. 

## Model Training

### Machine learning algorithms used:
Linear regression: Imported from sklearn, I created a variable, lr, to train the regression model on the x and y train variables. I used this algorithm as it is efficient with the variables in this dataset being linear. I used this model to make a prediction on the training sets. 
Random forest: I used a random forest model to average the results to use more than one decision tree. I used the regressor model as the data is quantitative. 

## Evaluation

In the evaluation, I evaluated the predicted value with the actual value. ("y_train"  with "y_lr_train..". I did this by seeing if they correlated in a trend line and checked for the type of dispertion. (If dispertion is low, the performance is good).

I imported mean_square and used the r2_score function.

## Results

	- Linear Regression:
 <img width="1074" alt="image" src="https://github.com/dkaybee2022/Machine-Learning/assets/147632964/bfeb0a4c-9756-44a6-a6d6-1f687418b2e7">
 
 	- Random Forest: 
<img width="1074" alt="image" src="https://github.com/dkaybee2022/Machine-Learning/assets/147632964/a253d87d-b6cc-4500-9608-1572035891d0">

        - Model Comparison: 
<img width="683" alt="image" src="https://github.com/dkaybee2022/Machine-Learning/assets/147632964/05476d11-fd5c-4f5e-951c-756a31aacb94">



## Data Visualization 
<img width="466" alt="image" src="https://github.com/dkaybee2022/Machine-Learning/assets/147632964/0cf535ad-f94f-4d2f-bdd1-a4956f7ed9a7">

   
## Key Findings

	•	Linear Regression: This model performed adequately given the linear nature of the variables in the dataset. However, it may be limited in capturing complex relationships in the data.
	•	Random Forest: This model provided better performance by leveraging multiple decision trees, which typically leads to improved accuracy and robustness.

Overall, the Random Forest model demonstrated superior performance in predicting molecular solubility compared to Linear Regression, making it a more suitable choice for this task. The visualizations and evaluation metrics clearly indicate the effectiveness of each model, guiding the selection of the best predictive approach for biologists in drug discovery.

## Contact

For any questions or feedback, please contact:

	•	Name: Diamond Burton
	•	Email: Diamond.Burton919@gmail.com
