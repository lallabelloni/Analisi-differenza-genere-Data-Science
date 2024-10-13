Gender Disparity Analysis at the University of Genoa
This repository contains the code used for my thesis, which analyzes gender disparity in the Bachelor's degree program in Computer Science at the University of Genoa. The analysis is based on two datasets provided by CEDIA, covering graduation data from 2010 to 2023 and exam grades from 1997 to June 2024.

Data Processing
The data was cleaned to include only positively graded exams. Courses with fewer than 50 participants, elective courses, qualifications, OFA exams, and English language exams were excluded. In some cases, old and new versions of courses were merged for aggregated analyses.

Tools and Libraries
The analysis was conducted using Python, with the following key libraries:

Pandas: Data manipulation and processing
Seaborn: Data visualization
Scipy: Statistical analysis
Analysis Overview
The main analyses performed in this project include:

Enrollment trends by course
Grade distribution by gender
Graduation data (year, duration, and final grades)
Correlation between high school diploma grades and university performance
Grade trends during the pandemic
Performance in written vs. oral exams
Analysis of grades by year of study and by instructor gender
Additionally, a specific analysis was performed on data from the "Database" course, comparing quiz, written exam, and project performance by gender.

Sample Size
A sample size of 90 students was determined to be necessary for the analysis based on standard deviation and a 95% confidence interval.
