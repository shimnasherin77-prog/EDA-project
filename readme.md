# Medical Insurance Cost Dataset
This dataset contains medical insurance cost information for 1338 individuals. It includes demographic and health-related variables such as age, sex, BMI, number of children, smoking status, and residential region in the US. The target variable is charges, which represents the medical insurance cost billed to the individual.
## 📊 Dataset

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/).
**Dataset Name:** Medical Cost Personal Dataset  
**Source:** [Medical Cost Personal Datasets - Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
**Description:**  
This dataset contains information about individuals such as age, sex, BMI, number of children, smoking status, and region, along with their medical insurance charges.  
It is used to predict insurance costs based on personal and lifestyle factors.

# 1) Which region has the most smokers?
## Objective
 the goal of this analysis is to identify which region has the highest number of smokers among the insured individuals in the dataset. Understanding smoking patterns across regions helps analyze regional health risks and potential insurance cost variations.

## Dataset Description

The dataset contains health insurance data with the following key columns:
-age – Age of the individual
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children
-smoker – Smoking status (yes/no)
-region – Residential region (northeast, northwest, southeast, southwest)
-charges – Medical insurance charges

## Analysis
We used a Pie Chart to visualize the number of smokers in each region.

## Observation
The Southeast region has the most smokers in this dataset.

# 2) Average Medical Charges by Region
## Objective
The main goal of this analysis is to find out which region has the highest average medical charges.
This helps us understand how medical costs change in different areas and what factors might affect them — like lifestyle or health care quality.

## Dataset Description

The dataset contains health insurance data with the following key columns:
-age – Age of the individual
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children
-smoker – Smoking status (yes/no)
-region – Residential region (northeast, northwest, southeast, southwest)
-charges – Medical insurance charges

# Visualization
The bar chart shows which region has the highest average medical charges.
The region with the tallest bar means that people there spend more on average.

# Conclusion
The analysis shows that the Southeast region has the highest average medical charges.
This means that, on average, people living in the Southeast spend more money on medical expenses compared to other regions.

# 3)Average BMI by Gender
## Objective
The goal of this analysis is to find the average Body Mass Index (BMI) of males and females in the dataset.

## Dataset Description

The dataset contains health insurance data with the following key columns:
-age – Age of the individual
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children
-smoker – Smoking status (yes/no)
-region – Residential region (northeast, northwest, southeast, southwest)
-charges – Medical insurance charges

## Analysis
We will group the data by gender and calculate the average BMI for each.

## Visualization
The bar chart shows the average BMI for both males and females.
It allows us to quickly compare their average body mass values.

## Conclusion
The analysis shows that males have a higher average BMI than females

# 4)Number of Insured People by Region
## Objective
The goal of this analysis is to find out which region has the highest number of insured people in the dataset.

## Dataset Description

The dataset contains health insurance data with the following key columns:
-age – Age of the individual
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children
-smoker – Smoking status (yes/no)
-region – Residential region (northeast, northwest, southeast, southwest)
-charges – Medical insurance charges

## Analysis
We will count how many people are from each region and find the region with the highest number.

## Conclusion
The analysis shows that the Southeast region has the highest number of insured people.

# 5)Average Charges Based on Number of Children

## Objective
The goal of this analysis is to find out whether people with more children pay higher average medical charges.

## Dataset Description

The dataset contains health insurance data with the following key columns:
-age – Age of the individual
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children
-smoker – Smoking status (yes/no)
-region – Residential region (northeast, northwest, southeast, southwest)
-charges – Medical insurance charges

## Analysis
We will calculate the average charges for each number of children and check if charges increase as the number of children increases.

## Visualization
The bar chart shows the average medical charge for people with 0, 1, 2, 3, or more children.
The height of each bar represents the average cost for that group.

## Conclusion
3 children pay the highest average medical charges compared to others

# Medical Charges Prediction using Linear Regression
## Objective

The goal of this project is to predict medical insurance charges based on personal and lifestyle factors such as age, gender, BMI, children, smoking status, and region.

## Dataset Information
The dataset contains the following columns:
-age – Age of the insured person
-sex – Gender (male/female)
-bmi – Body Mass Index
-children – Number of children covered by insurance
-smoker – Smoking status (yes/no)
-region – Residential area in the US (northeast, southeast, southwest, northwest)
-charges – Medical insurance cost (target variable)

## Step 1: Data Preprocessing

-Converted categorical data (sex, smoker, region) into numerical format using LabelEncoder.
-Separated features (X) and target (y).

## Step 2: Splitting the Data

Divided the dataset into training (80%) and testing (20%) sets to evaluate model performance.

## Step 3: Model Training

Trained a Linear Regression model using the training data.

## Step 4: Prediction

Predicted medical charges for the test data.

## Step 5: Model Evaluation

Evaluated the model using Mean Squared Error (MSE) and R² Score.

## Step 5: Model Evaluation

Evaluated the model using Mean Squared Error (MSE) and R² Score.
Predicted medical charge: 4549.17

## Conclusion

The Linear Regression model achieved:

-Mean Squared Error (MSE): 33,635,210.43

-R² Score: 0.78

This means the model explains about 78% of the variation in medical insurance charges based on factors like age, BMI, smoking status, number of children, and region.