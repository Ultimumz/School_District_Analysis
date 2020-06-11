# School_District_Analysis

## Project Overview
After replacing the reading and math scores with NaN for 9th graders in Thomas High School, how does the new data affect the original analysis.

## Resources
- Data Source:
    - clean_students_complete.csv
    - missing_grades.csv
    - schools_complete.csv
    - students_complete.csv
- Software: 
    - Python 3.7.6
    - Jupyter Notebook 6.0.3
    - Anaconda 1.7.2

## Summary
- District summary affected:
    - Average Math Score drops by 0.1%
    - Average Reading Score remains the same
    - % Passing Math drops by 1.1%
    - % Passing Reading drops by 1.1%
    - % Overall Passing drops by 1.1%
    
- Thomas High School summary affected:
    - Average Math Score drops by 0.1%
    - Average Reading Score increases by 0.1%
    - % Passing Math drops by 26.4%
    - % Passing Reading drops by 27.6%
    - % Overall Passing drops by 25.8%
    
- Performance comparing to other schools after replacing 9th graders' math and reading scores:
    - % Overall Passing Ranking in the district drops from 2 to 8

- Math and Reading Scores by Grade:
    - All other grades remains unchanged besides the grades for 9th graders are NaN

- Scores by School Spending affected:
    - Spending Ranges: < $584, $585-$629, and $645-$675 remains unchanged
    - Spending Range $630-$644 has following changes:
        - Average Math and Reading Scores remains the same
        - % Passing Math drops by 6.6%
        - % Passing Reading drops by 6.9%
        - % Overall Passing drops by 6.5%

- Scores by School Size affected:
    - School Size: Small (< 1000), Large (2000-5000) remains unchanged
    - Medium (1000-2000) has following changes:
        - Average Math and Reading Scores remains the same
        - % Passing Math drops by 5.3%
        - % Passing Reading drops by 5.5%
        - % Overall Passing drops by 5.2%
        
- Scores by School Type affected:
    - District remains unchanged
    - Charter has following changes:
        - Average Math and Reading Scores remains the same
        - % Passing Math drops by 3.3%
        - % Passing Reading drops by 3.5%
        - % Overall Passing drops by 3.2%
