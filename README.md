# Predicting Chest Discomfort and Blood Pressure Categories using NHANES 2017–2018  
**Author:** Ritesh KC  
**Date:** May 9, 2023  

## 📊 Project Overview  
I used this portfolio as a part of my statistical modeling class. This project applies statistical modeling and machine learning techniques to analyze and predict chest discomfort and blood pressure categories using data from the **2017–2018 NHANES (National Health and Nutrition Examination Survey)** dataset.

The primary goals of the project are to:
- Identify variables associated with reported chest discomfort.
- Blood pressure categories prediction using different predictors.
- Use interpretable models to generate actionable health insights.

## 🛠️ Key Methods and Tools  
- **Data Source:** NHANES 2017–2018 public dataset  
- **Programming Language:** R  
- **Analysis Platform:** RMarkdown (rendered to HTML via Quarto)  
- **Techniques Used:**
  - Data cleaning and preprocessing  
  - Exploratory Data Analysis (EDA)  
  - Logistic regression for binary classification of chest discomfort  
  - Multinomial logistic regression to categorize blood pressure levels  
  - Model diagnostics and performance evaluation  
  - Visualizations using `ggplot2` and other R packages  

## 🔍 Main Findings  
- Several demographic and clinical variables were significantly associated with self-reported chest discomfort.
- Blood pressure classification models showed good predictive performance using routinely collected variables such as age, BMI, and cholesterol levels. However, these metrics indicate poor model fit. Only main effects were used for this prediction. Adding nonlinear terms or interactions could improve performance.
- The project highlights the potential of open-access survey data in supporting public health research and predictive modeling.

## 📁 Project Structure  
```
├── projectBportfolio_riteshkc.html     # Rendered HTML report of the full analysis
├── projectBportfolio_riteshkc.qmd      # Full analysis quarto file
├── projectBportfolio_df2               # Cleaned NHANES datasets for the project
└── README.md                           # Project description and usage notes
``` 

## 📚 Requirements  
This analysis was conducted using R and RMarkdown (via Quarto). To reproduce or extend the analysis:
- Install R and RStudio
- Required packages include:
  - `tidyverse`
  - `nnet`
  - `ggplot2`
  - `dplyr`
  - `readr`
  - `quarto` (for rendering)

## 📌 Citation  
If you use or adapt this project, please cite the NHANES data source:  
Centers for Disease Control and Prevention (CDC). National Health and Nutrition Examination Survey. [https://www.cdc.gov/nchs/nhanes/](https://www.cdc.gov/nchs/nhanes/)
