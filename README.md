## End to End Machine learning project

# End-to-End-ML_Projects : Student Performance Indicator

Short description of your project.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

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

### Data Collection
Dataset Source: Student Performance in Exams
The dataset consists of 8 columns and 1000 rows.

### Dataset Information
gender: sex of students (Male/female)
race/ethnicity: ethnicity of students (Group A, B, C, D, E)
parental level of education: parents' final education (bachelor's degree, some college, master's degree, associate's degree, high school)
lunch: having lunch before the test (standard or free/reduced)

### Conclusions (EDAs)
Student's performance is related to lunch, race, and parental level of education.
Females lead in pass percentage and are also top-scorers.
Student's performance is not significantly related to the test preparation course.
Finishing the preparation course is beneficial.

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



