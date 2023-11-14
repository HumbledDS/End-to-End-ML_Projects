## End to End Machine learning project

# Project Name

Short description of your project.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Introduction](#introduction)
- [Setup and Organization](#Setup)

## Requirements

All packages needed for this project are written in "requirements.txt" file.

- Python 3.10

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/HumbledDS/End-to-End-ML_Projects.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-project
    ```

3. Create a virtual environment (recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source venv/bin/activate
        ```

5. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Stricly for learning purpose.

```bash
python src/main.py

## Introduction

Student Performance Indicator : This project aims to understand how students' performance (test scores) is affected by various variables such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.
We will built an end-to-end project on this data: 

## Setup and Organization
-  Setting up the environnement
-  Managing exceptions and the logs
-  Data ingestion
-  Data transformation (EDA)
-  Model picking and training
-  Pipeline Creation using Flask
-  Deployment in AWS Cloud using CI/CD pipelines

Life Cycle of Machine Learning Project
Understanding the Problem Statement
Data Collection
Data Checks to Perform
Exploratory Data Analysis
Data Pre-Processing
Model Training
Choose the Best Model
1) Problem Statement
This project aims to understand how students' performance (test scores) is affected by various variables such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course.

2) Data Collection
Dataset Source: Student Performance in Exams
The dataset consists of 8 columns and 1000 rows.

2.2 Dataset Information
gender: sex of students (Male/female)
race/ethnicity: ethnicity of students (Group A, B, C, D, E)
parental level of education: parents' final education (bachelor's degree, some college, master's degree, associate's degree, high school)
lunch: having lunch before the test (standard or free/reduced)
test preparation course: complete or not complete before the test
math score
reading score
writing score
3) Data Checks to Perform
Check Missing values
Check Duplicates
Check data type
Check the number of unique values of each column
Check statistics of the dataset
3.1 Check Missing Values
# There are no missing values in the dataset
3.2 Check Duplicates
# There are no duplicate values in the dataset
3.3 Check Data Types
3.4 Checking the Number of Unique Values of Each Column
3.5 Check Statistics of Data Set
# Insights...
3.7 Exploring Data
# Exploring data and insights...
3.8 Adding Columns for "Total Score" and "Average"
4. Exploring Data (Visualization)
5. Conclusions
Student's performance is related to lunch, race, and parental level of education.
Females lead in pass percentage and are also top-scorers.
Student's performance is not significantly related to the test preparation course.
Finishing the preparation course is beneficial.


