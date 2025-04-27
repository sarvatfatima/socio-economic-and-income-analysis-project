# Socioeconomic and Income Data Analysis Project

This project performs an in-depth analysis of a structured socioeconomic [dataset](https://www.kaggle.com/datasets/hesh97/titanicdataset-traincsv) containing demographic, educational, occupational, and financial information. It uses both **Python** (Pandas, Seaborn, Matplotlib, Scikit-learn) and **SQL** (SQLite) to extract meaningful insights and visualize patterns.

----------

## 🧠 Objective

To analyze the relationships between demographic factors (such as age, sex, marital status, education) and economic variables (primarily income), and to identify behavioral trends, disparities, and clustering patterns in the population.

----------

## 📁 Dataset Description

Column

Description

ID

Unique identifier

Sex

0 = Female, 1 = Male

Marital status

Marital situation of the individual

Age

Age in years

Education

Highest education level attained

Income

Annual income in local currency

Occupation

Employment category

Settlement size

0 = Rural, 1 = Semi-Urban, 2 = Urban

----------

## 🔍 Key Insights Extracted

### 📊 Demographics

-   Gender and marital status distributions
    
-   Age groups (Young, Middle-aged, Senior)
    

### 💰 Income Insights

-   Average income by education, occupation, and settlement size
    
-   Income distribution by marital status and gender
    

### 📈 Trends & Patterns

-   Correlation between income and age
    
-   Relationship heatmap between education and marital status on income
    
-   Income segmentation by urban/rural setting
    

### 🧠 Advanced Analytics


    
-   Predictive model to estimate income using regression
    

    

----------

## 📌 Tech Stack

-   **Python** (Pandas, Seaborn, Matplotlib, NumPy)
    
-   **SQLite3** (via `sqlite3` module)
    
-   **Scikit-learn** (for clustering and predictive modeling)
    
-   **Jupyter Notebook** (for development)
    

    



----------

## 📈 Sample Visualizations

-   Bar charts of income by education
    
-   Boxplots of income by marital status
    
-   Heatmaps for multi-variable comparisons
    
-   KMeans cluster scatterplots
    

----------

## ✅ Future Improvements

-   Build a Streamlit dashboard for real-time exploration
    
-   Integrate geospatial mapping if location data is added
    
-   Add more predictive modeling: Decision Trees, Random Forests
    
-   Automate reporting via PDF export
    



----------
