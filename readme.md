# Student Dataset Analysis
## Overview
This repository contains the results of data analysis and exploratory data analysis (EDA) conducted on the Student_Dataset. The analysis focuses on understanding various factors affecting student grades and visualizing these relationships using Matplotlib and Seaborn.

### Dataset
The Student_Dataset includes the following columns:

math_score: Score in mathematics.
history_score: Score in history.
physics_score: Score in physics.
chemistry_score: Score in chemistry.
biology_score: Score in biology.
english_score: Score in English.
geography_score: Score in geography.
grade: Final grade of the student.
gender: Gender of the student.
part_time_job: Whether the student has a part-time job (True or False).
Data Analysis and EDA
####  1. Data Cleaning
Handling Missing Values: Removed any missing or null values from the dataset.
Column Creation: Added columns for total score and percentage.
Grade Calculation: Added a grade column based on the total score and percentage.
#### 2. Summary Statistics
Computed descriptive statistics to understand the distribution of scores and grades.
#### 3. Visualizations
##### a. Distribution of Grades
Created a bar plot to show the distribution of student grades.
##### b. Effect of Gender on Grades
Used a box plot to visualize the relationship between gender and grades.
##### c. Effect of Part-Time Job on Grades
Analyzed how having a part-time job affects student grades using a box plot.
##### d. Correlation Analysis
Generated a correlation matrix to examine the relationships between different academic scores.
##### e. Impact of Part-Time Job on Grades, Segmented by Gender
Created a grouped bar plot to investigate how part-time employment influences grades, with gender as a hue.
