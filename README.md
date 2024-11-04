# Data-Camp-Practice3-Customer-Analytics-Preparing-data-for-modeling
Preparing data for modeling. Create a proof-of-concept of a much more efficient storage solution.

# Customer Analytics: Preparing Data for Modeling

A common problem when creating models to generate business value from data is that datasets can be so large that it may take days for the model to generate predictions. Ensuring that the dataset is stored as efficiently as possible is crucial to allow these models to run on a more reasonable timescale, without reducing the dataset size.

## Project Overview

You've been hired by a major online data science training provider called **Training Data Ltd.** to optimize one of their largest customer datasets. This dataset will eventually be used to predict whether students are looking for a new job, a feature that will help direct them to prospective recruiters.

This project involves creating a proof-of-concept for an efficient data storage solution using a sample dataset (`customer_train.csv`). The goal is to streamline the dataset to facilitate faster, more efficient model training and prediction processes.

## Dataset Description

The dataset provided, `customer_train.csv`, contains anonymized information on students, including their background, experience, and education. Each record indicates whether the student is seeking a new job. Below is a description of the columns in the dataset:

| Column                  | Description                                                               |
|-------------------------|---------------------------------------------------------------------------|
| `student_id`            | A unique ID for each student                                             |
| `city`                  | A code for the city the student lives in                                 |
| `city_development_index`| A scaled development index for the city                                  |
| `gender`                | The student's gender                                                     |
| `relevant_experience`   | An indicator of the student's work-relevant experience                   |
| `enrolled_university`   | The type of university course enrolled in (if any)                       |
| `education_level`       | The student's education level                                            |
| `major_discipline`      | The educational discipline of the student                                |
| `experience`            | The student's total work experience (in years)                           |
| `company_size`          | The number of employees at the student's current employer                |
| `company_type`          | The type of company employing the student                                |
| `last_new_job`          | The number of years between the student's current and previous jobs      |
| `training_hours`        | The number of hours of training completed                                |
| `job_change`            | An indicator of whether the student is looking for a new job (1 = Yes, 0 = No) |

## Project Objectives

1. **Optimize Storage Efficiency**: Convert data types to more efficient formats (e.g., booleans, categorical types, and appropriate numeric types) to reduce memory usage.
2. **Prepare for Modeling**: Clean and structure the dataset to be ready for predictive modeling.
3. **Proof-of-Concept**: Demonstrate the effectiveness of an efficient storage solution using the sample dataset.

## Getting Started

1. Clone this repository.
2. Install required packages (if any).
3. Load `customer_train.csv` and run the provided data transformation scripts.

## License

This project is for educational and demonstration purposes, provided by Training Data Ltd.
