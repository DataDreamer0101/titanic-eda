# Titanic EDA

**Exploratory Data Analysis (EDA) on the Titanic Dataset using Python**  
Part of the **Elevvo Pathways internship** and my journey to learn data analysis, visualization, Python, and its libraries.

---

## Overview
This project analyzes the classic Titanic dataset from Kaggle: *“Titanic: Machine Learning from Disaster”*.  
The goal is to explore the dataset, clean it, generate insights, and visualize patterns related to passenger survival.

---

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)  
- Contents: Passenger information such as Age, Sex, Class, Embarked, etc.

---

## Steps Performed
1. **Data Exploration**
   - View top rows, check data types, summary statistics
2. **Data Cleaning**
   - Handle missing values
   - Convert categorical columns to appropriate types
3. **Summary Statistics & Group-based Insights**
   - Survival by Gender
   - Survival by Class
   - Survival by Age Group & Gender
   - Survival by Embarkation Port & Class
4. **Visualization**
   - Bar plots, stacked bars, heatmaps, violin/KDE plots
   - Highlight patterns and correlations
5. **Tools & Libraries**
   - Python, Pandas, Matplotlib, Seaborn

---

## Key Insights
- Females had higher survival rates than males  
- 1st class passengers survived more than lower classes  
- Age, gender, class, and embarkation port influenced survival  

Some of the **visualizations** are shared in the notebook.  

---

## Setting Up the Environment

This project uses a dedicated **Conda environment** to ensure all packages and versions are consistent.

1. **Clone or download the repository**  
```bash
git clone https://github.com/your-username/titanic-eda.git
cd titanic-eda
```
2. **Create the environment from the YAML file**
```bash
conda env create -f environment.yml
```

3. **Activate the environment**
```bash
conda activate titanic-eda
```

4. **Launch Jupyter Notebook or VS Code to run Titanic_EDA.ipynb.**

This ensures you have all the same Python packages and versions used in the project.
