# Student Placement Intelligence Dashboard

An interactive Power BI dashboard project built to analyze student placement outcomes and identify the academic, skill-based, and career-related factors that influence employability and salary trends.

## Project Overview

This project focuses on analyzing student placement data using Power BI. Traditional placement reporting often highlights only summary metrics such as total students placed or average package offered, but it does not clearly explain which factors actually influence placement outcomes.

To address this, this project presents a multi-page dashboard that examines the impact of academic performance, internships, certifications, projects, coding skills, communication skills, aptitude score, degree, and branch on placement success and salary outcomes.

The dashboard is designed to provide meaningful insights that can help institutions better understand placement patterns and improve student placement readiness.

## Problem Statement

Traditional placement reporting focuses mainly on overall placement numbers and average salary. It does not clearly show which academic and skill-related factors drive student placement outcomes. As a result, institutions may struggle to identify employability gaps and improve placement readiness effectively.

## Objectives

- Analyze student placement outcomes in a structured and meaningful way
- Identify the major academic and skill-based factors influencing placement success
- Compare placement trends across branches, degrees, and student profiles
- Analyze salary patterns across company types and academic segments
- Build an interactive and easy-to-understand Power BI dashboard for placement intelligence

## Dataset Information

The dataset used in this project contains the following columns:
Link: https://www.kaggle.com/datasets/sakharebharat/indian-student-placement-dataset-2025?resource=download

- `student_id`
- `gender`
- `age`
- `degree`
- `branch`
- `cgpa`
- `backlogs`
- `internships`
- `certifications`
- `coding_skills`
- `communication_skills`
- `aptitude_score`
- `projects`
- `placed`
- `company_type`
- `package_lpa`

## Tools and Technologies Used

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**

## Data Preparation

The dataset was imported into Power BI and cleaned using Power Query.

The following preprocessing steps were performed:
- verified column data types
- checked for missing and invalid values
- created readable placement labels
- created grouped analytical columns for better analysis

The following derived columns were created:
- Placement Status
- CGPA Band
- Internship Band
- Certification Band
- Projects Band
- Backlog Category
- Age Group

## Key DAX Measures

The following important measures were created in the dashboard:

- Total Students
- Placed Students
- Unplaced Students
- Placement Rate %
- Average CGPA
- Average Package
- Highest Package
- Average Internships
- Average Certifications
- Average Coding Skills
- Average Communication Skills
- Average Aptitude Score
- Placement Rate by Group %
- Product Company Hires

## Dashboard Pages

### 1. Executive Overview
This page provides a high-level summary of the overall placement situation.

It includes:
- Total Students
- Placed Students
- Unplaced Students
- Placement Rate %
- Average CGPA
- Average Package
- Highest Package
- Placement distribution
- Placed Students by Branch
- Placed Students by Degree
- Placed Students by CGPA Band

### 2. Placement Drivers Analysis
This page focuses on identifying the factors that influence placement outcomes.

It includes:
- Average Internships
- Average Certifications
- Average Coding Skills
- Average Communication Skills
- Average Aptitude Score
- Placement Rate by Internship Band
- Placement Rate by Certification Band
- Placement Rate by Projects Band
- Placement Rate by Backlog Category
- Average Coding Skills by Placement Status
- Average Communication Skills by Placement Status
- Average Aptitude Score by Placement Status

### 3. Salary & Company Insights
This page focuses on salary trends and hiring patterns.

It includes:
- Average Package
- Highest Package
- Placed Students
- Placement Rate %
- Product Company Hires
- Average Package by Branch
- Highest Package by Branch
- Average Package by Degree
- Placed Students by Company Type
- Average Package by Company Type
- Average Package by CGPA Band

## Key Insights

- Students with stronger academic and skill-based profiles tend to show better placement outcomes
- Internships, certifications, and projects contribute positively to placement performance
- Coding skills and aptitude scores show a noticeable difference between placed and unplaced students
- Placement performance varies across branches and degrees
- Salary outcomes differ across company types and academic segments
- Higher CGPA bands generally show stronger package trends among placed students

## How to Use

1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
3. Explore the three dashboard pages
4. Use the slicers to filter and interact with the dashboard visuals

## Project File

This repository contains the Power BI project file:

- `Student_Placement_Intelligence_Dashboard.pbix`

## Results

The final output of this project is a 3-page interactive Power BI dashboard that transforms raw placement data into meaningful and easy-to-understand insights.

The dashboard helps answer questions such as:
- What is the overall placement rate?
- Which branches and degrees perform better?
- How do internships, certifications, and skills affect placement?
- How do salary outcomes vary across company types and student segments?

## Future Scope

This project can be extended further by:
- adding year-wise placement trend analysis
- integrating data from multiple colleges
- including interview scores and soft skill evaluations
- building a predictive model for placement likelihood
- publishing the dashboard through Power BI Service

## Author

**Amrish Yadav**  
M.Tech Computer Science 
IIIT Lucknow

## Contact

mcs24020@iiitl.ac.in

## License

This project is created for academic and internship submission purposes.
