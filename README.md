# Stack Overflow Developer Survey Analysis

## Project Overview

This project analyzes data from the 2017 [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey) to uncover insights about developer demographics, job satisfaction, work environments, and salary trends. By examining factors such as company type, years of experience, remote work preferences, and compensation, this analysis provides a deeper understanding of developer experiences and industry patterns.

![Untitled design-4](https://github.com/user-attachments/assets/1e84f2e3-4562-4950-b4a6-f3cfab52a19d)

## Dataset

- **Data Files**:
  - `survey_results_public.csv`: Contains individual responses to the Stack Overflow survey.
  - `survey_results_schema.csv`: Describes each column in the survey responses.
- **Key Variables**:
  - `CompanyType`: Type of company employing the developer.
  - `YearsProgram`: Years of programming experience.
  - `JobSatisfaction`: Self-reported job satisfaction level.
  - `HomeRemote`: Preference for remote work.
  - `Salary`: Self-reported annual salary.

- **Source**: [Stack Overflow Developer Survey 2017](https://insights.stackoverflow.com/survey).

## Project Structure

1. **Data Understanding**: 
   - Load and inspect the datasets for an initial overview.
   - Display column names, data types, and basic statistics.

2. **Data Cleaning**:
   - Handle missing values in key columns, particularly those relevant to company type, years of experience, job satisfaction, and salary.
   - Apply transformations to clean and prepare the data for analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Explore key relationships and patterns in the data:
     - Distribution of job satisfaction and salary.
     - Correlation between years of experience and compensation.
     - Analysis of remote vs. in-office work preferences.

4. **Visualizations**:
   - Generate visualizations to represent the data:
     - Salary distribution across different experience levels.
     - Job satisfaction levels by company type.
     - Developer preferences for remote work.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: `Pandas` for data manipulation, `Matplotlib` and `Seaborn` for visualization.

## Insights & Key Findings

- Analysis of job satisfaction across company types and experience levels.
- Salary distribution patterns based on experience and other factors.
- Trends in remote work preferences among developers.

## Future Work

I am working on a few advanced visualizations (heatmap etc)

## Usage

1. Clone the repository.
2. Install necessary Python libraries:
   ```bash
   pip install pandas matplotlib seaborn
