# Data Quality
Script that automatically assess the data quality of a dataset.
## Installation
Install required libraries using requirements file using the following instruction.
```
pip install -r requirements.txt 
```
## Motivation
Idea behind this project was to create a script that we have to run for almost every dataset to check its qualtiy and view all its attributes in one go before doing any manual work.

## Working
Code uses NLP and checks data quality by looking for missing values, Inconsistency between input values and output labels. It also looks at Skewness and class imbalance of output classes.
We also train a mode to see performance.
Data is thresholded based on rules and models are trained again to see if performance is improved.
