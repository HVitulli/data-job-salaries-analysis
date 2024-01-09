# Data treatment and Exploratory Data Analysis

## job_salary_treated:
- I obtained  the database from Kaggle: [Link](https://www.kaggle.com/datasets/lorenzovzquez/data-jobs-salaries?resource=download&select=salaries.csv)
- The main changes were made to the following fields:
  - exp_level_values: Acronyms were replaced with their full names, for instance, EN -> Junior.
  - employment_type_values: Acronyms were replaced with their full names, for instance, PT -> Part-time.
  - company_size_values: Acronyms were replaced with their full names, for instance, S -> Small.
  - company_location & employee_residence: Acronyms were replaced with their full names, for instance, BR -> Brazil.
- Only one field was created from the original database, called work_model. It's based on the remote_ratio, for instance, if remote_ratio = 0, then work_model = In-Person.
- If you prefer to access the code on Google Colab, (click here.)[https://colab.research.google.com/drive/1FZuYBHNml6CFe0g2nEx1sjyl6QelpeH4?usp=sharing]
---
## job_salary_eda:
- Here was made the data exploration.
- The libraries used were Pandas, NumPy, Matplotlib and Seaborn.
- It was explored:
  1. How many jobs are there(databse)?
  2. Over the years, what has been the behavior of salaries by career?
  3. Which are countries with the highest salaries in 2023?
  4. Which are the countries with the lowest salaries in 2023?
  5. Which countries have the highest number of salary records by career in 2023?
  6. What is the average salary by company size?
- If you prefer to access the code on Google Colab, (click here.)[https://colab.research.google.com/drive/1rxwhyHy3zaldyQ6dWf1nvEicyAdwyGr3?usp=sharing]







