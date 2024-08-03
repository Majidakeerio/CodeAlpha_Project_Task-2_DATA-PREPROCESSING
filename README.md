# CodeAlpha_Project_Task-2_DATA-PREPROCESSING
This project is part of my internship with CodeAlpha. This repository contains a preprocessing pipeline for the Titanic dataset. The preprocessing steps include handling missing values, detecting and capping outliers, normalizing/scaling features, and splitting the data into training and testing sets.

#Project Overview
The project involves the following steps:

Handle Missing Values:
Fill missing values for 'Age' and 'Fare' with the median.
Fill missing values for 'Embarked' with the mode.
Drop the 'Cabin' column due to a high number of missing values.

Handle Outliers:
Identify and cap outliers in the 'Age' and 'Fare' columns using the IQR method.

Normalize or Scale Features:
Encode categorical variables ('Sex' and 'Embarked').
Scale numerical columns ('Age', 'Fare', 'Parch', 'SibSp') using StandardScaler.

Split the Data into Training and Testing Sets:
Define the target variable (Survived) and feature set.
Split the dataset into training and testing sets.


#Summary of Preprocessing Steps:

Handling Missing Values: Address missing data in 'Age', 'Embarked', and 'Fare' columns and drop the 'Cabin' column.
Handling Outliers: Cap the outliers in 'Age' and 'Fare' columns using the IQR method.
Normalization/Scaling: Encode categorical variables and scale numerical features.
Splitting Data: Divide the dataset into training and testing sets.
