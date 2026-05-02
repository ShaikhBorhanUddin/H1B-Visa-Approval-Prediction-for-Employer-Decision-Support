# H1B Visa Approval Prediction for Employer Decision Support (project ongoing)
![dashboard](Assets/title.png) 

## Dataset 
The [Dataset](https://www.kaggle.com/datasets/zongaobian/h1b-lca-disclosure-data-2020-2024) is sourced from Kaggle. It provides a comprehensive record of Labor Condition Application (LCA) disclosures for H1B visa petitions filed with the U.S. Department of Labor (DOL) from 2020 to 2024. The H1B visa is a non-immigrant visa that allows U.S. companies to employ foreign workers in specialty occupations requiring theoretical or technical expertise. These roles typically include fields such as IT, engineering, finance, healthcare, and more. The H1B program is critical for addressing skill gaps in the U.S. workforce and supporting economic growth. 

## Data Cleaning 
Keep SOC_CODE JOB_TITLE FULL_TIME_POSITION PREVAILING_WAGE WAGE_RATE_OF_PAY WAGE_UNIT_OF_PAY PW_LEVEL WORKSITE_STATE WORKSITE_CITY NAICS_CODE H1B_DEPENDENT WILLFUL_VIOLATOR YEAR 

## Feature Engineering 
calculate job duration from BEGIN_DATE and END_DATE.
