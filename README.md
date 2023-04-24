# Gaussian Classification for Airline Passenger Satisfaction

This repository contains code for the Classification of Airline Passenger Satisfaction using the Gaussian process and determining the uncertain attributes. 

This project was created as part of the coursework for module 7135CEM Modelling and Optimisation under Uncertainty for [Coventry University](https://www.coventry.ac.uk/course-structure/pg/eec/data-science-and-computational-intelligence-msc/). Any use of the code needs to be cited appropriately. 

## Usage

The code can be executed in google colab - <https://colab.research.google.com/>

Make sure you upload the dataset files and specify the path for the same in the code. 

Code Example:
```
# Reading the CSV files from Google Drive
train_data = pd.read_csv('/content/drive/MyDrive/Datasets/Uncertainty/train.csv')
test_data = pd.read_csv('/content/drive/MyDrive/Datasets/Uncertainty/test.csv')
```

## Data

The dataset used as a part of this project contains data from an airline passenger satisfaction survey. There are a variety of factors that contribute towards the satisfaction of the service for a customer. Various attributes are considered while classifying the customers into two sections **satisfied and neutral or dis-satisfied**.

This dataset is available at - <https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?datasetId=522275&select=test.csv>

 If the above link is not accessible then you can find the dataset under the Data Files folder.

## Techniques used

As a part of this experiment, I have used three methods of classification for comparing their performance.

 1. Gaussian Process Classification
 2. Bayesian Process Classification
 3. Random Forest Classification
