# University Resource & Scheduling Analysis

## Project Overview

This project focuses on analyzing university operations through data, with an emphasis on classroom allocation, academic scheduling, instructor distribution, and course enrollment.

The objective was to explore how classroom resources are scheduled, understand differences in instructor workloads across departments, and identify patterns in student course enrollment.

Using MySQL for data analysis and Tableau for visualization, I developed an interactive dashboard that presents operational metrics and helps communicate insights from the data.

## Technologies Used

- **MySQL:** Data querying, joining, aggregation, and analysis
- **Tableau Public:** Interactive dashboard development
- **Python:** Generation of supporting datasets
- **CSV/Excel:** Data preparation and exchange

## Dataset Structure

The project uses the following related datasets:

| Dataset | Description |
|---|---|
| Students | Student information and academic details |
| Courses | Course names, departments, and credits |
| Enrollments | Student course enrollment records |
| Instructors | Instructor information and departments |
| Classrooms | Classroom details and seating capacities |
| Schedule | Course, instructor, room, and time assignments |

Primary keys and foreign keys were established to define relationships between the datasets and support relational analysis.

## Analytical Objectives

### 1. Classroom Resource Analysis
- Determine the total number of classrooms.
- Examine how frequently each classroom is scheduled.
- Identify classrooms with zero or one scheduled class.
- Compare underutilized classrooms with other classrooms.

### 2. Department Performance Analysis
- Compare scheduled classes across academic departments.
- Analyze instructor distribution by department.
- Examine the number of scheduled classes assigned to each department.

### 3. Course Enrollment Analysis
- Compare enrollment counts across courses.
- Identify courses with relatively high student demand.
- Explore enrollment differences across academic departments.

### 4. Scheduling Pattern Analysis
- Identify the day with the highest number of scheduled classes.
- Analyze class schedules by day of the week.
- Examine class starting hours to identify peak scheduling periods.

## Dashboard Components

The interactive Tableau dashboard includes:

- **KPI Metrics:** Total classrooms, scheduled classes, and instructors.
- **Department Analysis:** Scheduled classes by department.
- **Classroom Analysis:** Underutilized versus other classrooms.
- **Instructor Analysis:** Instructor counts and scheduled classes by department.
- **Course Analysis:** Student enrollment by course.
- **Scheduling Analysis:** Peak scheduling day and class patterns by day and hour.

## Technical Skills Applied

**Database and SQL**
- Relational database concepts
- Primary and foreign key implementation
- INNER JOIN and LEFT JOIN
- GROUP BY and aggregate functions
- Common Table Expressions (CTEs)
- Date and time extraction
- Data validation and consistency checks

**Data Visualization**
- KPI creation
- Bar charts and pie charts
- Treemap visualization
- Line charts
- Dashboard organization and formatting
- Analytical storytelling

## Project Workflow

1. Explored the initial college dataset.
2. Prepared additional supporting datasets using Python.
3. Created related tables and relationships in MySQL.
4. Validated data and performed SQL analysis.
5. Exported analytical results for Tableau.
6. Developed visualizations and assembled the interactive dashboard.

## Dataset Disclaimer

This project was developed for educational and portfolio purposes. The initial college dataset was supplemented with generated data for instructors, classrooms, and scheduling. The dataset does not represent actual university operational records.

## Conclusion

This project provided an opportunity to apply database management, SQL querying, data analysis, and visualization techniques to a university operations scenario.

The resulting dashboard brings together several operational metrics to make classroom scheduling, instructor distribution, and course enrollment patterns easier to explore and understand.
