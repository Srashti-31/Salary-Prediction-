# Salary-Prediction-
For this project, I have examined the Census Income data set available at the UCI Machine Learning Repository named Adult Data set. The ML model predict whether an individual’s income will be greater than $50,000 per year based on several attributes from the census data.

## About Project
This notebook have done analysis on salary prediction from the data provided by UCI machine learning repository.
The project aims to predict whether the salary of a person is above or below or equal to 50k.
The orginal data was modified, analyzed, changed, corrected and cleaned.
Some of the features were removed from the data and rest were used in this notebook for better accuracy.
The features used are mentioned below:
1)age: continuous. (Age of an individual)
2)capital-loss: continuous.
3)fnlwgt: continuous. (this is the number of people the census believes the entry represents)
4)education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. (highest level of education achieved by an individual)
5)education-num: continuous. (education level in numeric form)
6)marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
7)hours-per-week: continuous. (the hours an individual has reported to work per week)
8)relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
9)race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
10)sex: Female, Male.
11)capital-gain: continuous.

## Installation
Salary_Prediction.ipynb is a jupyter notebook file. You need to install jupyter in your system.
Along with jupyter some of ther following python libraries are also required to be installed:
1) Pandas : pip install pandas
2) Numpy : pip install numpy
3) Sklearn : pip install sklearn
4) joblib : pip install joblib
5) matplotlib

## About the Files
#### Salary_Prediction.ipynb is the main file which contains the code.
#### output.txt shows the error and accuracy rate of the project when tested on different models.
#### Features.txt gives details about all the attributes of dataset.
#### raw_data is the original file downloaded from UCI ML repository.
#### data.csv is the excel file which contains the modified and cleaned data set.
#### About_Data.names is the orginal file from UCI downloaded along raw_data
#### adults.test is the testing data - used for prediction



## Credits
The dataset was downloaded from the following link:
https://archive.ics.uci.edu/ml/datasets/adult


##License
MIT License
Copyright (c) 2020 Srashti-31
