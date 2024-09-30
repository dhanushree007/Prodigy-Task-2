# Prodigy-Task-2

# README for Prodigy - Task 2

## Overview

This project analyzes the famous Titanic dataset, focusing on survival outcomes based on various factors like age, gender, and passenger class. The dataset is processed by handling missing values and performing exploratory data analysis (EDA) to uncover insights into the survival rates and other key patterns. Visualizations are used to display the relationships between survival and other variables.

---

## Requirements

To successfully run this notebook, you need the following Python libraries:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For plotting and visualizations.
- `seaborn`: For statistical data visualization.

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Data

The dataset used in this analysis is the Titanic dataset, which is publicly available and can be directly loaded from the URL:

- **Dataset URL**: [Titanic Dataset on GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## Steps in the Analysis

### 1. **Data Loading and Exploration**
   - The dataset is loaded using `pandas`.
   - Initial data checks, including missing values, data types, and a quick look at the first few records, are performed to understand the structure of the dataset.

### 2. **Handling Missing Values**
   - Missing values in the `Age` column are filled with the median age.
   - Missing values in the `Embarked` column are filled with the mode (most frequent) value.
   - The `Cabin` column is dropped due to a high percentage of missing values.
   - The data is cleaned by ensuring that there are no more missing values.

### 3. **Data Type Conversions**
   - The `Survived` and `Pclass` columns are converted to categorical data types to better reflect their discrete nature.

### 4. **Exploratory Data Analysis (EDA)**
   - Summary statistics (`df.describe()`) are calculated to provide insights into the data distribution.
   - The number of passengers who survived is counted and broken down by gender.
   - Various visualizations are used to illustrate the key insights from the data.

---

## Visualizations

### 1. **Survival Distribution**
   - A count plot shows the overall survival distribution (`Survived` vs. `Not Survived`).

### 2. **Survival by Gender**
   - A count plot shows survival rates based on gender (`Male` vs. `Female`), highlighting the significant gender difference in survival rates.

### 3. **Survival by Passenger Class**
   - A count plot breaks down survival rates by passenger class (`Pclass`), indicating the likelihood of survival based on socio-economic status.

### 4. **Age Distribution**
   - A histogram shows the distribution of ages among passengers, providing insights into the age demographics on the Titanic.

---

## How to Run the Script

1. Load the data by running the code in your Python environment, Jupyter Notebook, or Google Colab.
2. The script will automatically handle missing data, convert data types, and generate visualizations.
3. After running, you will get a clear understanding of the survival patterns and other insights from the Titanic dataset.

---

## Output

1. **Cleaned Dataset**: Missing values handled and unnecessary columns removed.
2. **Visual Insights**: Visualizations showing relationships between survival rates, gender, age, and passenger class.

---

## Contact

If you have any questions or issues related to this project, feel free to reach out via email: [dhanushree2607@gmail.com].
