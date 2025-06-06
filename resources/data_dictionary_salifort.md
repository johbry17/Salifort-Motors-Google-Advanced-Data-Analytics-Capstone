# Data Dictionary

This project uses a dataset called `HR_capstone_dataset.csv`. It represents 10 columns of self-reported information from employees of a multinational vehicle manufacturing corporation.

### Dataset Overview:
- **Rows:** 14,999 (each row is a different employee’s self-reported information)
- **Columns:** 10

### Columns and Descriptions:

| **Column Name**           | **Type**  | **Description**                                                                 |
|----------------------------|-----------|---------------------------------------------------------------------------------|
| **satisfaction_level**     | int64     | The employee’s self-reported satisfaction level [0-1]                           |
| **last_evaluation**        | int64     | Score of employee's last performance review [0–1]                               |
| **number_project**         | int64     | Number of projects employee contributes to                                      |
| **average_monthly_hours**  | int64     | Average number of hours employee worked per month                               |
| **tenure**     | int64     | How long the employee has been with the company (years)                         |
| **work_accident**          | int64     | Whether or not the employee experienced an accident while at work               |
| **left**                   | int64     | Whether or not the employee left the company                                    |
| **promotion_last_5years**  | int64     | Whether or not the employee was promoted in the last 5 years                    |
| **department**             | str       | The employee's department                                                       |
| **salary**                 | str       | The employee's salary (low, medium, or high)                                    |