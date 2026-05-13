# H1B Visa Approval Prediction for Employer Decision Support (project ongoing)
![dashboard](assets/title.png) 

## Overview 
This project presents an end-to-end machine learning system for H-1B visa approval prediction designed to support employer decision-making using the USCIS H-1B petition dataset from Kaggle containing approximately 3.5 million records from 2020–2024. Multiple machine learning models including XGBoost, LightGBM, Random Forest, and ElasticNet are trained and evaluated using performance metrics and SHAP-based explainability to identify the most influential approval drivers. The final selected model is deployed through a Gradio interface on Hugging Face for real-time inference, with future plans for scalable cloud deployment using FastAPI, Docker, AWS, and a React frontend for production-grade serving and interactive user experience. 

## Use Cases 

## Project Workflow 
![dashboard](assets/wf.png) 

## Dataset 
The [Dataset](https://www.kaggle.com/datasets/zongaobian/h1b-lca-disclosure-data-2020-2024) is sourced from Kaggle. It provides a comprehensive record of Labor Condition Application (LCA) disclosures for H1B visa petitions filed with the U.S. Department of Labor (DOL) from 2020 to 2024. The H1B visa is a non-immigrant visa that allows U.S. companies to employ foreign workers in specialty occupations requiring theoretical or technical expertise. These roles typically include fields such as IT, engineering, finance, healthcare, and more. The H1B program is critical for addressing skill gaps in the U.S. workforce and supporting economic growth. 

## Folder structure 

```bash
project/
│
├── app/
│   ├── app.py
│   │
│   ├── templates/
│   │   └── index.html
│   │
│   └── static/
│       └── style.css
│
├── assets/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_training.ipynb
│
├── src/
│   ├── __init__.py
│   ├── preprocessing.py
│   ├── train.py
│   ├── evaluate.py
│   └── inference.py
│
├── requirements.txt
├── runtime.txt
├── Procfile
└── README.md
```

## Data Cleaning 
Keep SOC_CODE JOB_TITLE FULL_TIME_POSITION PREVAILING_WAGE WAGE_RATE_OF_PAY WAGE_UNIT_OF_PAY PW_LEVEL WORKSITE_STATE WORKSITE_CITY NAICS_CODE H1B_DEPENDENT WILLFUL_VIOLATOR YEAR 

## Feature Engineering 
calculate job duration from BEGIN_DATE and END_DATE. 

## EDA 

## Model Training 

## Test Results 

## Result Visualization and Explanations 

## Deployment 

## Limitations 

## Tools and Technology Used 

## Licence 

## Contact 


