
# Titanic Survival Analysis

## Project Overview
This project explores the Titanic passenger dataset to understand survival patterns based on gender, passenger class, and age.

The analysis uses Python data analysis libraries to perform data cleaning, exploratory data analysis (EDA), data visualization, and extract meaningful insights.

## Objectives
- Explore and understand the dataset.
- Handle missing values and clean the data.
- Analyze survival rates by gender.
- Analyze survival rates by passenger class.
- Analyze survival rates by age group.
- Create visualizations and draw conclusions.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab

## Dataset
The dataset contains information about 891 Titanic passengers, including passenger class, age, gender, fare, ticket details, and survival status.

Dataset source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

## Data Cleaning
- Removed the Cabin column due to a large number of missing values.
- Filled missing Age values using the median age (28).
- Filled missing Embarked values using the most frequent category.
- Checked for duplicate records.

## Analysis Performed
- Overall passenger survival analysis.
- Survival rate analysis by gender.
- Survival rate analysis by passenger class.
- Survival rate analysis by age group.
- Data visualization using Seaborn and Matplotlib.

## Key Findings
- 342 passengers survived (38.38%).
- Female passengers had a survival rate of 74.20%.
- Male passengers had a survival rate of 18.89%.
- First-class passengers had the highest survival rate (62.96%).
- Third-class passengers had the lowest survival rate (24.24%).
- Children had the highest survival rate among the analyzed age groups (57.97%).

## Conclusion
The analysis identified differences in survival rates across gender, passenger class, and age groups. Female passengers, first-class passengers, and children had higher observed survival rates in this dataset.

## Limitations
- Missing age values were replaced using the median.
- The Cabin column was removed because most values were missing.
- The analysis identifies associations but does not establish causation.

## Project Notebook
The complete analysis, Python code, and visualizations are available in the Jupyter Notebook included in this repository.
