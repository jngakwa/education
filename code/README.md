# Is School Performance, Measured by ACT Scores, Predicted by social Economic Factors?

The goal of this project is to utilize data to determine whether socioeconomic factors and the number of teachers in a school play a significant role in influencing student performance. 

---

## Project Overview

This project investigates how socioeconomic factors and the number of teachers in a school influence student performance. Using educational and demographic data, the analysis aims to uncover patterns and relationships between student achievement, teacher availability, and community conditions.
Provide a short and concise overview of the project. Mention the problem it solves, the data used, and the key outcomes or findings.

- **Objective:** Clearly state the main goal of the project.
- **Domain:** (e.g., Healthcare, Finance, E-commerce, etc.)
- **Key Techniques:** Multiple Linear Regression

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://nces.ed.gov/ccd/elsi/tablegenerator.aspx, https://nces.ed.gov/
- **Description:** This dataset contains information from 7,986 school-level observations with a total of 14 variables that describe both academic performance and socioeconomic characteristics of schools. Key numerical columns include socioeconomic indicators such as unemployment rate, percentage of adults with college degrees, percentage of married-couple families, median household income, and percentage of students receiving free or reduced lunch. The main performance metric is average ACT score, while teachers represents the number of teachers available at each school. Additional categorical variables such as state, zip code, school type, school level, charter status, and year provide contextual information about each observation.
- **License:** (if applicable)

---

## Analysis

The three datasets used were cleaned as needed to ensure consistency across schools and merged to create one dataset for the analysis. Created a multiple linear regression model that can predict 63% of the data used in the project with an error of approximately 1 in predicting ACT scores based on a student's socioeconomic conditions

---

## Results

In conclusion, this project examines whether socioeconomic factors and the number of teachers in a school influence students’ performance, which is measured by the average ACT score or equivalent of the SAT. An analysis of the variables such as the number of teachers in a school and the other socioeconomic factors reveals that the percentage of students receiving free or reduced lunch showed the strongest correlation, while the teacher availability showcased a weaker but still positive relationship.  A linear regression model comparing the average ACT score and either of the observations offers moderate explanatory power, while the multiple linear regression model combining all variables resulted in an R-squared of 0.631. This shows that approximately 63% of the variation in the score could be predicted with the model. Additionally, a MAE of 1.136 obtained from the model suggests that predictions are accurate within a one-point difference. Overall, the study shows that socioeconomic conditions have a substantially stronger impact on students’ performance than the number of teachers. 

---

## Authors

- Njenga Gakwa - [@jngakwa](https://github.com/jngakwa/education)

---

## Acknowledgements

- Libraries used - Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Stastsmodels

