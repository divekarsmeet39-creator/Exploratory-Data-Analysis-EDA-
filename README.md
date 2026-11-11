# Task 5 – Exploratory Data Analysis (EDA) – Titanic Dataset

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to explore passenger data, identify patterns, analyze relationships between variables, and discover meaningful insights through statistical analysis and data visualization.

## Objectives
- Understand the structure and characteristics of the dataset.
- Identify and handle missing values and duplicate records.
- Perform descriptive statistical analysis.
- Analyze passenger survival patterns.
- Create meaningful visualizations using different charts.
- Identify trends, correlations, relationships, and outliers.

## Tools and Technologies Used
- **Python** – Programming and data analysis.
- **Jupyter Notebook** – Writing and executing analysis.
- **Pandas** – Data cleaning and manipulation.
- **Matplotlib** – Creating data visualizations.
- **Seaborn** – Statistical data visualization.

## Dataset
**Dataset Name:** Titanic Dataset

The dataset contains information about Titanic passengers, including:

- Passenger ID
- Passenger Class
- Name
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Number
- Fare
- Cabin
- Embarked Location
- Survival Status

## Project Files

| File Name | Description |
|---|---|
| `Task_5_Titanic_EDA.ipynb` | Main Jupyter Notebook containing the complete analysis. |
| `titanic.csv` | Dataset used for analysis. |
| `Task_5_EDA_Report.pdf` | PDF report containing findings and visualizations. |
| `Titanic_EDA.py` | Python script containing the analysis. |

## Analysis Performed

### 1. Data Understanding
- Displayed the first few records using `head()`.
- Examined dataset structure using `info()`.
- Generated statistical summaries using `describe()`.

### 2. Data Cleaning
- Identified missing values.
- Checked for duplicate records.
- Handled missing Age values using the median.
- Handled missing Embarked values using the mode.

### 3. Data Visualization
Created various visualizations to understand passenger data:

- Survival Count Plot
- Age Distribution Histogram
- Survival by Gender
- Fare Distribution Boxplot
- Age vs. Fare Scatterplot
- Correlation Heatmap
- Pairplot

## Key Findings
- Approximately 38.4% of passengers survived the Titanic disaster.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher
