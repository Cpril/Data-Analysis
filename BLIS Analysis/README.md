# Basic Literacy In Statistics Analysis

**Basic Literacy in Statistics(BLIS) assessment** is a test developed by Dr Ziegler to test post-secondary students' statistical literacy. For the past several years, Calvin University statistics students have completed Ziegler’s BLIS assessment near the start and end of the introductory statistic courses. This analysis uses *programming language R* to analyze these results, investigating how effective are the courses. 

**Table of Content**: 
1. BLIS dataset: blis-time.csv
    Dataset includes 293 rows and 4 variables: 
    - *Timepoint*: “pre” (start of semester) or “Post” (end of semester)
    - *Percent*: score on the BLIS assessment, as a percentage
    - *Duration*: time the student took to complete the BLIS, in minutes
    - *Course*: the course that the student took or will take
2. PDF report: BLIS_Analysis.pdf
3. HTML report: BLIS_Analysis.html

**Exploritory Data Analysis** suggest a higher mean for students post-course relative to pre-course.
![image](https://github.com/user-attachments/assets/3ba823a7-b59a-404f-8ba0-bc43ea3e521e)

**Model Fitting** fits a linear regression model with predictors timepoint, duration, and course. 
![image](https://github.com/user-attachments/assets/2b45d642-3f5e-4f2b-aaae-3c028ab3546a)

**Model Assessment**: Model passes all assessments needed. Full model assessment is included in the technical report pdf.

**Prediction Plot** reveal a signifigant difference between pre-course and post-course BLIS score, such that students underwent the introductory statitic courses have higher BLIS score than those who did not.
![image](https://github.com/user-attachments/assets/2600242e-1270-42cf-8a5d-42428e8c2aca)

For detailed technical report on this project, please check out the technical report pdf or html. 

For more projects, please visit my portfolio: https://Cpril.github.io/portfolio
