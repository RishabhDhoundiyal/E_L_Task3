# E_L_Task3
Titanic Survival Analysis: Exploratory data analysis of the Titanic dataset with a focus on data cleaning, preprocessing, and visualizations using Python (Pandas, NumPy, Matplotlib, Seaborn).


# Titanic Survival Analysis – EDA, Cleaning, and Visualizations
- Overview
  - This repository contains an Exploratory Data Analysis (EDA) of the Titanic dataset, focused  on data cleaning and visualizations using Pandas, NumPy, Matplotlib, and Seaborn. The notebook walks through handling missing values, summarizing key features, and exploring high-level survival patterns by passenger class, sex, age, fare, and embarkation port.
- About the Data
  - Dataset: Classic Titanic passenger dataset (train.csv-style).
  - Target: Survived (0 = No, 1 = Yes).
  - Key features:
      - Demographics: Sex, Age
      - Socio-economic: Pclass (1/2/3), Fare
      - Family: SibSp (siblings/spouse), Parch (parents/children)
      - Others: Ticket, Cabin, Embarked (C/Q/S)
  - Common data issues: Missing values in Age and Cabin, a few in Embarked, skewed Fare, and mixed data types.
- What This Project Does (High-Level)
    - Loads and inspects the data (shape, head, info, describe).
    - Cleans data:
      - Handles missing values (Age imputation, Embarked fill, Cabin treated/dropped).
      - Basic categorical/type cleanup.
  - Prepares simple groupings for analysis (Age bins, Fare ranges, group-by summaries).
- Visual EDA:
  - Histograms of Age, Fare, SibSp, and Parch 
  - Pair plot of numerical columns
  - Correlation heatmap of numerical columns
  - Scatter plot of Age vs. Fare colored by Survived 
  - Box plots of Age and Fare by Survived, Pclass, and Sex 
  - Violin plots of Age and Fare distribution by Survived
  - Bar plots of Survival Rate by Sex, Pclass, and Embarked
  - Stacked bar plots of Survived Count by Pclass, Sex, and Embarked
- Repository Structure
  - TSA.ipynb: Main notebook with cleaning steps and visualizations.
  - data: Place dataset files here (e.g., train.csv).
  - TSA_PDF.docx: Project report/summary (EDA and insights)


# Author
[Rishabh Dhoundiyal](https://github.com/RishabhDhoundiyal)
