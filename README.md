<div align="center">

# 🚢 Titanic Dataset — Exploratory Data Analysis

### 📊 Elevate Labs | Task 5

**Discovering Patterns • Exploring Data • Visualizing Insights**

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic passenger dataset.

The objective is to understand the dataset, identify missing values, analyze passenger characteristics, explore survival patterns, and visualize relationships between important features.

This project was completed as part of **Task 5: Exploratory Data Analysis (EDA)**.

## 🎯 Objectives

- Understand the structure of the Titanic dataset.
- Identify missing values and analyze data quality.
- Explore passenger demographics and ticket fares.
- Investigate survival patterns across passenger groups.
- Create meaningful visualizations using Python.
- Summarize findings through data-driven observations.

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Structure

```text
ElevateLabs_Task5_EDA/
│
├── README.md
├── titanic.CSV
├── titanic_eda.ipynb
└── Titanic_EDA_Report.pdf
```

## 📊 Dataset Information

The dataset contains information about Titanic passengers.

**Dataset size:** 891 rows × 12 columns

Important features include:

- `PassengerId` — Passenger identification number
- `Survived` — Survival status
- `Pclass` — Passenger class
- `Name` — Passenger name
- `Sex` — Passenger gender
- `Age` — Passenger age
- `SibSp` — Number of siblings or spouses aboard
- `Parch` — Number of parents or children aboard
- `Ticket` — Ticket number
- `Fare` — Ticket fare
- `Cabin` — Cabin information
- `Embarked` — Port of embarkation

## 🔍 Analysis Performed

### 1. Data Loading and Inspection
Loaded the dataset using Pandas and examined its structure and sample records.

### 2. Data Quality Analysis
Checked missing values and reviewed the distribution of available data.

### 3. Statistical Analysis
Explored descriptive statistics for numerical features.

### 4. Data Visualization
Created visualizations to investigate:

- Passenger age distribution
- Ticket fare distribution
- Survival rates across age groups
- Relationships between numerical features

### 5. Survival Analysis
Compared survival patterns across passenger categories to identify potential relationships.

## 📈 Key Observations

- The dataset contains **891 passenger records and 12 columns**.
- The `Age` column contains 177 missing values.
- The `Cabin` column contains 687 missing values.
- The `Embarked` column contains 2 missing values.
- The age distribution shows that passengers were represented across a broad range of ages.
- The fare distribution contains high-value outliers.
- The notebook explores survival rates across different age groups.

*These observations are based on the dataset inspection and analysis performed in the notebook.*

## 📁 Project Files

| File | Description |
|---|---|
| `titanic.CSV` | Dataset used for analysis |
| `titanic_eda.ipynb` | Jupyter Notebook containing code, analysis, and visualizations |
| `Titanic_EDA_Report.pdf` | PDF report of the analysis |

### 📓 View the Notebook

[Open Titanic EDA Notebook](./titanic_eda.ipynb)

### 📄 View the Report

[Open Titanic EDA Report](./Titanic_EDA_Report.pdf)

### 📊 View the Dataset

[Open Titanic Dataset](./titanic.CSV)

## 🚀 How to Run This Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. Open the project folder in your terminal.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `titanic_eda.ipynb` and run the cells.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Data inspection using Pandas
- Missing-value analysis
- Descriptive statistical analysis
- Data visualization
- Exploratory data analysis
- Communicating findings through charts and reports

## 👨‍💻 Project Information

**Project:** Titanic Exploratory Data Analysis  
**Program:** Elevate Labs Internship  
**Task:** Task 5  
**Status:** Analysis and report uploaded to GitHub

---

<div align="center">

### ⭐ Thank you for visiting this project!

**Explore the data. Discover the patterns. Understand the story.**

</div>
