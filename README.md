# Excel-Data-Insights
This project highlights my Excel skills through hands-on analysis of clean, publicly available datasets. Various data operations were performed to demonstrate my ability to organize, analyze, and derive insights effectively.

The below link will provide you detailed and honest work skills
https://docs.google.com/spreadsheets/d/1odxqnobIKxnu5iXPWp74HKwF-SqnSWvixw0i2gXsLEg/edit?usp=sharing

📌 Project Overview
This project involves cleaning, analyzing, and visualizing a dataset of student awards and certifications for the year 2024. The goal was to identify peak performance periods, understand the distribution between individual and team-based success, and build an interactive tool for record retrieval.
📌 Tools Used
* Microsoft Excel: Data Cleaning, Pivot Tables, and Visualization.
* Functions: XLOOKUP, FILTER, COUNTIF, MATCH, TRIM, and PROPER.
* Power Query: Used for data normalization and sorting.
📌 Key Analysis Phases
Phase 1: Data Cleaning & Integrity
Objective: To convert a "dirty" raw dataset into a structured format ready for high-level analysis.

Actions Taken:

* Standardization: Normalized capitalization and removed white spaces to ensure 100% record matching.
* Error Correction: Performed a manual audit and automated substitution to fix spelling errors in award categories.
* Logical Ordering: Developed a chronological sorting system to replace default alphabetical sorting.
* The Result: Reduced data redundancy by approximately 20% and prepared the dataset for accurate visual trending.

Phase 2: Data Analysis & Insight Generation
Objective: To extract meaningful patterns and identify top-performing students and categories.

2.1 Monthly Performance Extraction

Goal: Isolate specific months to analyze seasonal peaks in student activity.
Technical Implementation: Used the FILTER function to create month-specific views, identifying September as the peak month for 2024.

2.2 Collaboration Analysis (Team vs. Individual)

Goal: Determine the ratio of solo wins vs. group collaborations.
Technical Implementation: Summarized data via Pivot Tables and used "Show Values As %" to visualize the 52/48 split.

2.3 Student Achievement Leaderboard

Goal: Rank students based on the frequency of their awards.
Technical Implementation: Combined UNIQUE names with COUNTIF and Descending Sorts to create a live leaderboard of top achievers.

The Result: Transformed 60+ rows of unstructured data into three distinct business-intelligence metrics that highlight institutional strengths.

Phase 3: Data Visualization & Reporting
Objective: To create a visual narrative of student success patterns for 2024.

3.1 Monthly Achievement Trend (Line Graph)

Goal: To visualize the chronological flow of awards throughout the year.
Insight: The graph highlights a significant surge in September. This visual helps in resource planning for students during high-competition months.
Chart Type: Line Graph with Markers (linked to chronological helper column).

3.2 Team vs. Individual Distribution (Pie Chart)

Goal: To represent the ratio of collaboration versus solo achievements.
Insight: The Pie Chart visually emphasizes the balanced academic environment, with Team-based wins slightly leading at 52%.
Chart Type: 2D Pie Chart with Percentage Data Labels.

3.3 Student Leaderboard (Data Set Sheet)

Goal: To provide a clear, sorted table of the top 5 student achievers.
Technical Detail: This sheet acts as the "Record of Truth," showcasing the top performers identified through the COUNTIF analysis.
Format: Structured Data Table with Conditional Formatting for high values.

The Result: The combination of these visuals transforms the raw CSV data into a comprehensive Student Achievement Dashboard, making the information accessible to both technical and non-technical stakeholders.
