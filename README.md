# Student Management System — SQL Data Analysis Report

## 1. Overview

This project developed a relational **Student Management System** using SQL. The database manages students, instructors, courses, enrollments, and academic grades through linked tables and primary/foreign-key relationships.

## 2. Data Summary

* **Students:** 20
* **Instructors:** 5
* **Courses:** 5
* **Enrollments:** 40
* **Grades:** 40
* **Average score:** 81.89
* **Highest score:** 96
* **Lowest score:** 67.50

Each student is enrolled in two courses, providing a balanced dataset for performance analysis.

## 3. Key Findings

### Course Performance

| Course             | Students | Average Score |
| ------------------ | -------: | ------------: |
| Power BI           |        7 |         88.36 |
| Python Programming |        8 |         84.88 |
| Machine Learning   |        7 |         80.29 |
| SQL Fundamentals   |       10 |         79.35 |
| Data Analysis      |        8 |         77.81 |

**Power BI recorded the highest average performance**, while Data Analysis had the lowest average among the five courses.

### Student Performance

The analysis identified the **top five students based on their individual assessment scores**, with the highest recorded score being 96. The dataset contains no scores below 50, indicating that none of the recorded students fell into the low-performance category defined by the SQL query.

### Enrollment

SQL Fundamentals has the highest enrollment with **10 students**, followed by Python Programming and Data Analysis with 8 students each. The enrollment analysis also identifies courses with more than five students.

## 4. Recommendations

1. Investigate the factors contributing to the strong performance in **Power BI** and consider applying similar teaching approaches to other courses.
2. Provide additional academic support or learning resources for **Data Analysis**, which has the lowest course average.
3. Continue monitoring student grades to identify high-performing students and students who may require additional support.
4. Use the relational database structure to support future analysis of attendance, course completion, instructor performance, and academic progression.

## 5. Conclusion

The SQL project successfully demonstrates how a relational database can be used to organize and analyze academic information. The EDA queries provide useful insights into **student enrollment, course performance, instructor-course relationships, and academic achievement**, creating a strong foundation for further educational data analysis.
