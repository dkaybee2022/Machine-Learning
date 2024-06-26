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
To prepare the model, I started off by seperating the data frame for testing and training. I did this by splitting x and y. After this step, I split the dataset for testing and training using sklearn; splittting the data created four new variables: x_test, x_train, y_test, y_train. The training set has about 80% of the data while the test set has 20%. 
## Model Training

### Machine learning algorithms used:
Linear regression: Imported from sklearn, I created a variable, lr, to train the regression model on the x and y train variables. I used this algorithm as it is efficient with the variables in this dataset being linear. I used this model to make a prediction on the training sets. 
Random forest:

## Evaluation

Explain the metrics used to evaluate the model’s performance, such as RMSE, MAE, or R² score.

## Results

	•	Performance metrics
	•	Visualizations (if any)
	•	Examples of predictions

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or feedback, please contact:

	•	Name: Diamond Burton
	•	Email: Diamond.Burton919@gmail.com
