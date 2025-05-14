# H1_python-data-analysis-fundamentals

This repository focuses on fundamental data analysis techniques using Python, with a special emphasis on the key libraries NumPy and Pandas.

## Project Overview

This project demonstrates practical data science workflows using two important datasets:
- **Penguins Dataset**: Contains detailed measurements of different penguin species (bill dimensions, flipper length, body mass, sex)
- **Titanic Dataset**: Contains comprehensive passenger information from the Titanic disaster (survival status, age, sex, ticket class)

## Core Files

- `Hafta_1_Odev.ipynb`: **Main assignment notebook** containing:
  - Complete data loading procedures from Google Drive
  - Comprehensive data exploration techniques
  - Detailed analysis of both datasets with practical examples
  - Data manipulation, filtering, and transformation techniques
  - Statistical analysis of penguin measurements and Titanic passenger data
  - Data visualization of key relationships and distributions

- Supporting datasets:
  - `penguins.csv`: Contains measurements across different penguin species
  - `titanic.csv`: Contains Titanic passenger information and survival data

## Key Techniques Demonstrated

The assignment notebook showcases several essential data analysis skills:

### 1. Data Loading and Connection
```python
# Example code for loading data
import pandas as pd
penguins_df = pd.read_csv('penguins.csv')
titanic_df = pd.read_csv('titanic.csv')
```

### 2. Data Exploration and Understanding
- Examining dataset structure with `df.shape`, `df.columns`, `df.info()`
- Statistical summaries using `df.describe()`
- Handling missing values with various techniques
- Data type conversion and preparation

### 3. Advanced Data Analysis
- Filtering data based on multiple conditions
- Creating derived features
- Grouping and aggregating data
- Statistical analysis by categories (mean, median, mode, standard deviation)
- Data cleaning and preprocessing

### 4. Data Visualization
- Distribution plots for continuous variables
- Relationship visualization between key features
- Categorical data visualization

### 5. Feature Engineering
- One-hot encoding for categorical variables using `get_dummies`
- Handling missing values with appropriate strategies
- Feature selection for analysis

## Datasets Description

### Penguins Dataset
The Penguins dataset contains information about different penguin species found in Antarctica, including:
- Species (Adelie, Gentoo, Chinstrap)
- Islands where observed (Torgersen, Biscoe, Dream)
- Bill dimensions (length and depth in mm)
- Flipper length (in mm)
- Body mass (in grams)
- Sex and observation year

### Titanic Dataset
The Titanic dataset provides information about passengers aboard the Titanic, including:
- Survival status (0 = No, 1 = Yes)
- Passenger class (1st, 2nd, 3rd)
- Name, Sex, and Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket number and fare
- Cabin and port of embarkation

## Learning Outcomes

By studying the notebooks in this repository, particularly the main assignment:
- You'll master practical data manipulation techniques with real-world datasets
- Learn how to approach a new dataset systematically
- Understand how to extract meaningful insights from raw data
- Develop skills in data cleaning and preprocessing
- Learn visualization techniques to communicate findings effectively

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook/Google Colab

```python
# Example code for loading the datasets
import pandas as pd

# Load penguins dataset
penguins_df = pd.read_csv('penguins.csv')

# Load titanic dataset
titanic_df = pd.read_csv('titanic.csv')
```
