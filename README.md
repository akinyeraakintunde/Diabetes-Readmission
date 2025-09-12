# Diabetes Readmission Prediction Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)

## Overview

This project demonstrates **data analysis, machine learning, and Python programming skills** through a healthcare dataset. It is part of my portfolio for the **Global Talent Visa**, showcasing my ability to solve real-world problems using data-driven insights.

The project is fully reproducible and designed to run on **Kaggle** or any local Python environment with zero extra setup.

## Table of Contents

- [Project Objective](#project-objective)  
- [Dataset](#dataset)  
- [Technologies & Libraries](#technologies--libraries)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Results](#results)  
- [License](#license)  
- [Contact](#contact)  

## Project Objective

The goal of this project is to:

1. Explore and clean the dataset.  
2. Perform exploratory data analysis (EDA).  
3. Build predictive models to identify patients at risk of readmission.  
4. Evaluate model performance and provide actionable insights.  
5. Demonstrate reproducible and professional data science workflows.

## Dataset
- Source: [Diabetes Healthcare Dataset (Kaggle)](https://www.kaggle.com/datasets/uciml/diabetes-healthcare-dataset)
- Records: 101,766
- Features: 50+
- Target: `readmitted` (<30 days, >30 days, No)


**Key Features:**

- **Rows:** 101,766  
- **Columns:** 50+  
- **Target Variable:** `readmitted` (e.g., <30 days, >30 days, or no readmission)

**Applications:**

- Predict patient readmission using machine learning models  
- Perform exploratory data analysis to identify trends in healthcare data  
- Visualize insights for data-driven decision making  

## Technologies & Libraries

This project is built with **Python 3.11** and uses the following libraries:

- `pandas` – data manipulation  
- `numpy` – numerical computations  
- `matplotlib` & `seaborn` – data visualization  
- `scikit-learn` – machine learning models  
- `jupyter` – interactive notebooks  

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/diabetes-readmission-project.git
cd diabetes-readmission-project
```
## Installation
Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```
##Install dependencies:
```bash
pip install -r requirements.txt
```
##Usage
Open the notebook notebooks/Diabetes_Readmission_Analysis.ipynb in Jupyter Notebook or VS Code and run cells sequentially.
The notebook includes:
Data cleaning and preprocessing
Exploratory data analysis (EDA)
Predictive model building and evaluation
Visualizations and actionable insights

##Project Structure
```bash

diabetes-readmission-project/
├── notebooks/
│   └── Diabetes_Readmission_Analysis.ipynb
├── data/
│   └── diabetes_data.csv
├── scripts/
│   ├── data_cleaning.py
│   ├── eda.py
│   └── model_training.py
├── requirements.txt
├── LICENSE
└── README.md
```

## Results & Insights
 ```bash 
- Random Forest model achieved the best accuracy and F1-score.
- Patients with multiple prior visits are more likely to be readmitted.
- Age groups and admission types are strong predictors.
- Insights can support hospital resource allocation and patient care strategies.
 ```

## Results & Insights
 ```bash 
- Random Forest model achieved the best accuracy and F1-score.
- Patients with multiple prior visits are more likely to be readmitted.
- Age groups and admission types are strong predictors.
- Insights can support hospital resource allocation and patient care strategies.
```
## License
This project is licensed under the MIT License.

## Contact
Ibrahim Akintunde Akinyera 
Email: akinyeraakintunde@gmail.com


---



