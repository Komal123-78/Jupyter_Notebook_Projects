# Jupyter_Notebook_Projects# Titanic Dataset Analysis 🚢

## Project Overview

This project analyzes the **Titanic dataset** using Python and explores the factors that affected passenger survival.

The analysis includes data cleaning, exploration, statistical summaries, and visualizations to understand the relationships between passenger characteristics and survival.

## Objectives

* Understand the Titanic dataset.
* Clean and prepare the data for analysis.
* Analyze passenger survival.
* Study survival based on gender and passenger type.
* Analyze survival based on passenger class.
* Analyze the effect of age on survival.
* Analyze the relationship between `SibSp`, `Parch`, and survival.
* Analyze fare patterns based on `Parch` and passenger type.
* Create tables and visualizations to understand the data.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The project uses the Titanic dataset available through Seaborn:

```python
file = sns.load_dataset('titanic')
```

The dataset contains **891 rows and 15 columns**.

Some important columns used in the analysis are:

* `survived` – Survival status
* `pclass` – Passenger class
* `sex` – Passenger gender
* `age` – Passenger age
* `sibsp` – Number of siblings/spouses aboard
* `parch` – Number of parents/children aboard
* `fare` – Passenger fare
* `who` – Passenger type (`man`, `woman`, `child`)

## Analysis Performed

### 1. Data Exploration

The dataset was explored using functions such as:

* `head()`
* `info()`
* `describe()`
* `shape`
* `columns`
* `isnull().sum()`

### 2. Survival Analysis

Survival counts were analyzed to determine how many passengers survived and did not survive.

### 3. Survival by Passenger Type

The `who` column was used to compare survival among:

* Men
* Women
* Children

### 4. Survival by SibSp

A summary table was created to analyze survival based on the number of siblings/spouses aboard.

**Table Name:**
**Survival Summary by SibSp and Passenger Type**

### 5. Fare Analysis by Parch

A summary table was created to analyze passenger fares based on the number of parents/children aboard and passenger type.

**Table Name:**
**Parch-Wise Fare Summary by Passenger Type**

The table includes:

* Count
* Mean fare
* Total fare

### 6. Data Visualization

Different charts were created using Matplotlib and Seaborn to understand patterns in the Titanic dataset.

## Key Findings

The analysis helps identify differences in survival rates based on:

* Passenger gender
* Passenger type
* Passenger class
* Age
* Number of siblings/spouses aboard
* Number of parents/children aboard
* Passenger fare

## Project Structure

```text
Titanic-Dataset/
│
├── Titanic Dataset.ipynb
└── README.md
```

## Conclusion

The Titanic dataset provides useful insights into passenger survival. The analysis shows how different passenger characteristics can be compared using Python, Pandas, Matplotlib, and Seaborn.

This project demonstrates basic **data analysis, data manipulation, aggregation, and data visualization** using Python.
