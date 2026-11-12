# Student-Learning-Performance-Academic-Risk-Analysis
# Project Overview
This project analyzes student learning behaviour, academic performance, and background characteristics to identify factors associated with student success and potential academic risk.
The main objective is to understand how study hours, attendance percentage, and study methods relate to students' overall academic scores and identify students who may require additional academic support.
# Project Objectives
- Analyze student academic performance.
- Identify relationships between study hours and overall scores.
- Examine the relationship between attendance and academic performance.
- Compare academic performance across different study methods.
- Identify students who may be academically at risk.
- Provide data-driven recommendations for improving student performance.
# Dataset Description
Dataset Name: Student_Performance.csv
- Initial records: 25,000
- Records after cleaning: 15,000
- Total columns: 16
- Missing values after cleaning: 0
- Duplicate records removed: 10,000
Important columns:
- student_id
- age
- gender
- school_type
- parent_education
- study_hours
- attendance_percentage
- internet_access
- travel_time
- extra_activities
- study_method
- math_score
- science_score
- english_score
- overall_score
- final_grade
# Tools and Technologies
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
# Data Cleaning
- Checked missing values and duplicate records.
- Removed 10,000 exact duplicate rows.
- Verified unique student IDs.
- Checked numerical ranges and data consistency.
- Retained original category labels and values.
After cleaning, 15,000 records remained with no missing values or repeated student IDs.
# Exploratory Data Analysis
Performed exploratory analysis to understand:
- Overall student grade distribution.
- Study hours versus overall academic scores.
- Attendance percentage versus academic scores.
- Performance across different study methods.
- Academic risk distribution.
- Relationship between student characteristics and performance.
# Statistical Analysis
Applied the following statistical methods:

Pearson Correlation: Examined linear relationships between study hours, attendance percentage, and overall academic scores.

Spearman Correlation: Validated relationships using rank-based correlation.

Kruskal-Wallis Test: Compared academic score distributions across six different study-method groups.
# Key Findings
- Study hours showed a strong positive association with overall academic scores (Pearson correlation: 0.906).
- Attendance showed a modest positive association with overall scores (Pearson correlation: 0.288).
- The Kruskal-Wallis test returned a p-value of 0.070, indicating no statistically significant difference in score distributions across study methods at the 0.05 significance level.
- Using a provisional E/F grade-based screening rule, 5,174 students (34.49%) were classified as potentially at risk.
- Sensitivity analysis showed that the study-hours correlation remained strong (0.902) after excluding extreme observations.
# Recommendations
- Encourage structured study planning.
- Monitor student attendance and identify attendance-related challenges.
- Provide additional academic support to students with previous academic difficulties.
- Evaluate learning-support programmes through future performance monitoring.
- Use academic-risk screening as a starting point for human review rather than automated decisions.
# Limitations
- Dataset provenance could not be independently verified.
- The sampling method and collection dates were unavailable.
- The analysis identifies associations, not causal relationships.
- The academic-risk classification is provisional.
- Further validation using independently collected student data is required.
# Conclusion
The analysis indicates that study hours have a strong positive association with academic performance, while attendance has a weaker positive association. No statistically significant differences were detected across the six study-method groups.
The project demonstrates how data analytics and statistical methods can help educational institutions understand student performance patterns and identify learners who may benefit from additional academic support.
