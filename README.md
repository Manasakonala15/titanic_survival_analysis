Titanic Survival Statistical Analysis
Project Overview

This project performs a complete statistical analysis of the Titanic Survival dataset using Python. The analysis is carried out using concepts such as loops, recursion, functional programming, conditional statements, exception handling, feature engineering, and statistical computations.

The project aims to analyze the factors affecting passenger survival during the Titanic disaster.

Dataset Information
Dataset Name: Titanic Dataset
Rows: 891
Columns: 12
Source: Kaggle Titanic Dataset

The dataset contains passenger details such as:

Passenger Class
Name
Sex
Age
Fare
Number of Siblings/Spouses
Number of Parents/Children
Embarked Port
Survival Status
Technologies Used
Python
Pandas
NumPy
Random Module
Functional Programming Concepts
File Handling
Python Concepts Implemented

1. Exception Handling

Used try-except blocks for:

File reading
File writing
Division by zero handling

2. Loops and Conditional Statements

Implemented:

for loops
if-elif-else
Logical operators
Relational operators

Used for:

Filtering passengers
Counting missing values
Group analysis

3. Missing Value Handling
Missing Age values filled using manually computed class-wise median
Invalid Fare values replaced using median fare

5. Feature Engineering

Created new columns:

FamilySize
FarePerPerson
IsChild
WC_Flag

5. Statistical Analysis

Computed:

Mean
Median
Mode
Minimum
Maximum

Using:

Manual calculations
Pandas methods
Recursive summation

6. Functional Programming

Used:

filter()
map()
reduce()

For fare analysis and transformation.

7. Random Sampling

Randomly selected:

50 Survivors
50 Non-Survivors

Compared:

Age
Fare
Family Size
Project Workflow
Load Titanic dataset
Explore dataset structure
Handle missing values
Create new features
Analyze women and children survival
Perform random sampling
Calculate statistics
Apply functional programming
Generate final report
Output Generated

The program generates:

titanic_analysis_report.txt

This report contains:

Dataset overview
Missing value analysis
Feature engineering details
Survival analysis
Statistical summary
Functional programming results
Final conclusions
Key Findings
Women and children had significantly higher survival rates.
First-class passengers had better survival probability.
Higher fare passengers showed higher survival chances.
Passenger class strongly influenced survival outcomes.
How to Run the Project
Step 1

Install required libraries:

pip install pandas numpy
Step 2

Place titanic.csv in the project folder.

Step 3

Run the Python file:

python titanic_analysis.py

Step 4

Check the generated report:

titanic_analysis_report.txt
Author

Manasa Konala
B.Tech Computer Science Engineering
SRM University AP

Conclusion

This project demonstrates practical implementation of:

Data Analysis
Statistical Computation
Python Programming
Functional Programming
File Handling
Data Cleaning
Feature Engineering

using the Titanic Survival dataset.
