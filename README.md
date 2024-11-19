# Student Performance Analysis Using Machine Learning

### Introduction
Student performance is a critical topic today as academic success increasingly shapes future opportunities. Understanding the most influential factors behind student performance can inform targeted interventions to support students. This study aims to identify the key variables that predict students’ grades, using machine learning to develop models that give us a better understanding of academic success.

### Background
Previous studies have shown that student performance is influenced by factors such as socioeconomic background, study time, and preparation for courses/exams. This research builds on existing literature by incorporating datasets that include demographics and academic features to predict students' performance based on average grades.

For example, a 2005 study by Sirrin used a meta-analysis to explore the relationship between socioeconomic status and academic achievement. Our study leverages more recent and diverse datasets to expand on these findings.

### Research Question and Hypothesis
Research Question: What are the key factors that influence student performance the most?
Hypothesis: Students who engage in test preparation courses and study more will perform better academically.

### Methodology
Data and Tools
Data Source: Kaggle datasets containing demographics and academic features.
Tools Used: Python and Google Colab for analysis.
Analyses Conducted
Data Cleaning: Ensuring datasets were consistent and free of errors.
Encoding Categorical Variables: Converting non-numeric data for analysis.
Normalizing Numeric Features: Scaling features to a standard range.
Modeling: Used Random Forest algorithms to analyze and predict student performance.
Created probabilities for students being in five different grade classes (GradeClass 0 = A, 1 = B, 2 = C, 3 = D, 4 = F).

### Preliminary Results and Findings
Key Influences
"Hours studied": Moderate positive correlation with grades (correlation: 0.46).
Practicing sample questions: Positive correlation with grades (correlation: 0.25).
Attendance Impact
Absences: Found to be the most significant factor correlating to lower grades across two datasets, contrary to the hypothesis.
Probabilities of Grades
Random Forest models calculated the likelihood of students achieving different grades. This analysis is visualized in the accompanying figures.

### Discussion and Results
The hypothesis that test preparation and more study hours improve academic performance was partially supported:

Hours studied had a moderate influence (0.46).
Practicing sample questions showed a smaller but still positive effect (0.25).
Absences were the most critical factor, with significant negative impacts on performance.
The findings suggest a complex interplay between attendance, study habits, and other factors. Figures 2 and 3 illustrate feature importance for different datasets, while Figure 1 shows a correlation matrix for the dataset.

Limitations
Data Quality: Self-reported data may be unreliable.
Sample Size: The datasets were limited in size and scope.
Correlation vs. Causation: Relationships between variables do not necessarily imply causation.
### Acknowledgments
Chaminade University Data Science Analytics and Visualization Program
NSF ALL-SPICE ALLIANCE program
