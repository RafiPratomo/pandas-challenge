# School Performance Analysis

## Overview
This project analyzes the performance of various schools based on their student test scores, budget, and size. The analysis is performed using Python and Pandas, and the results are presented in a series of aggregated data tables.

## Data
The project uses two CSV files:
- `schools_complete.csv`: Contains data about schools, including their names, types, budgets, and student counts.
- `students_complete.csv`: Contains data about students, including their names, school names, and test scores in maths and reading.

## Analysis
The analysis includes the following steps:

1. **Data Loading and Merging**:
    - Load the school and student data into Pandas DataFrames.
    - Merge the two DataFrames into a single dataset.

2. **Calculations**:
    - Calculate the total number of schools and students.
    - Calculate the total budget.
    - Calculate the average maths and reading scores.
    - Calculate the number and percentage of students passing maths and reading.
    - Calculate the overall passing rate.

3. **Grouping and Aggregation**:
    - Calculate averages and passing rates by spending ranges per student.
    - Calculate averages and passing rates by school size.
    - Calculate averages and passing rates by school type.

4. **Data Presentation**:
    - Present the results in summarized DataFrames.

## Results
### Spending Summary
The spending summary categorizes schools based on their per student budget and shows average scores and passing rates for each spending range.

### Size Summary
The size summary categorizes schools based on their total student population and shows average scores and passing rates for each size category.

### Type Summary
The type summary categorizes schools based on their type (Charter or District) and shows average scores and passing rates for each type.

### Usage
To run the analysis, ensure you have the required CSV files in the appropriate directory and run the provided Python scripts.

### Dependencies
  - Python 3.x
  - Pandas
