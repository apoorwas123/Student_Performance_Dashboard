# Student Performance Analysis

##  Project Overview

This project analyzes student academic performance using Maths and Portuguese student datasets. The analysis focuses on understanding overall performance and identifying factors that may influence students' final grades.

The project was created using Power BI, Power Query, and DAX to transform the data, calculate performance metrics, and build an interactive dashboard.

##  Objectives

- Analyze subject-wise student performance
- Analyze overall academic performance
- Identify factors affecting final grades
- Study the relationship between study time and performance
- Analyze the impact of student absences
- Compare performance across schools
- Compare performance by gender
- Analyze the effect of previous failures
- Visualize G1, G2 and G3 performance trends

##  Tools & Technologies

- Power BI
- Power Query
- DAX
- CSV Dataset

##  Dataset

The project uses two datasets:

- `Maths.csv` – Student performance data for Mathematics
- `Portuguese.csv` – Student performance data for Portuguese

The datasets contain information such as:

- Student demographics
- Study time
- Absences
- Previous failures
- School information
- G1, G2 and G3 grades
- Family and social factors

##  Data Preparation

The datasets were loaded and cleaned using Power Query.

Main preprocessing steps included:

- Promoting column headers
- Setting appropriate data types
- Combining Maths and Portuguese datasets
- Adding a Subject column
- Creating a Pass/Fail classification based on final grade
- Creating Study Time categories
- Creating Absence categories

## 📈 Dashboard Analysis

The Power BI dashboard includes:

- Average Final Grade
- Pass Rate
- Average Absences
- Average Study Time
- Total Records
- Subject-wise Average Final Grade
- Pass vs Fail Distribution
- G1 to G3 Performance Trend
- Average Final Grade by School
- Study Time vs Average Final Grade
- Absences vs Average Final Grade
- Study Time vs Final Grade
- Average Final Grade by Gender
- Subject-wise Performance by Gender
- Previous Failures vs Average Final Grade

##  Key Insights

- The overall average final grade is **11.33**.
- The overall pass rate is approximately **77.86%**.
- Portuguese students show a higher average final grade than Maths students.
- Students with higher study-time categories generally show better average final grades.
- Higher absence levels are associated with lower average final grades.
- Students with more previous failures tend to have lower final grades.
- Female and male students show relatively similar overall average final grades.
- Final grades generally improve from G1 to G3.

##  Recommendations

- Encourage students to maintain consistent study habits.
- Monitor students with high absence levels.
- Provide additional academic support to students with previous failures.
- Identify low-performing students early using G1 and G2 results.
- Encourage regular attendance and structured study schedules.
- Provide subject-specific support where performance is lower.

##  Dashboard Preview

![Student Performance Analysis Dashboard]
<img width="1355" height="786" alt="Dashboard" src="https://github.com/user-attachments/assets/d811c4ae-f8dc-4d92-ba56-9fe55ff28c04" />



##  Project Structure

```text
Student-Performance-Analysis/
│
├── README.md
├── Student_Performance_Analysis.pbix
│
├── Dataset/
│   ├── Maths.csv
│   └── Portuguese.csv
│
└── Screenshots/
    └── Dashboard.png
