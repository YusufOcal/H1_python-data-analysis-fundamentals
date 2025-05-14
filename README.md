# Python Data Analysis Fundamentals

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

- `1.hafta.ipynb`: Supplementary notebook covering:
  - Introduction to Python basics for data analysis
  - NumPy array manipulation fundamentals
  - Pandas DataFrame operations

- Supporting datasets:
  - `penguins.csv`: Contains measurements across different penguin species
  - `titanic.csv`: Contains Titanic passenger information and survival data

## Key Techniques Demonstrated in the Main Assignment

The `Hafta_1_Odev.ipynb` notebook showcases several important data analysis skills:

### 1. Data Loading and Connection
```python
from google.colab import drive
drive.mount('/content/drive')
file_path = '/content/drive/MyDrive/Acun Medya/Hafta_1/penguins.csv'
data = pd.read_csv(file_path)
```

### 2. Data Exploration and Understanding
- Examining dataset structure with `df.shape`, `df.columns`, `df.info()`
- Statistical summaries using `df.describe()`
- Handling missing values
- Data type conversion and preparation

### 3. Advanced Data Analysis
- Filtering data based on multiple conditions
- Creating derived features
- Grouping and aggregating data
- Statistical analysis by categories

### 4. Data Visualization
- Distribution plots for continuous variables
- Relationship visualization between key features
- Categorical data visualization

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
