
# Hospital Readmission Analysis and Prediction
## Ironhack Data Analytics Bootcamp Final Project
## Description

In this project, I analyse hospital readmissions, build and compare machine learning models to predict readmissions.
My goal is to assess if initial diagnoses, number of procedures, or other variables could help better understand the probability of readmission.
Some doctors believe diabetes might play a central role in readmission. Explore the effect of a diabetes diagnosis on readmission rates.

## Data

[Diabetes 130-US hospitals for years 1999-2008 Data Set](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008#) from UCI Machine Learning Repository.

Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore, “Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol. 2014, Article ID 781670, 11 pages, 2014.

## Project approach

### 1. Cleaning Data: 
First notebook is about preparing data for analysis. 
Check duplicate, null values, fill or drop nulls. Check categorical and numerical columns seperately.
Feature selection with Kbest (even though I had very few columns, I wanted to see the importance)
Correlation between numerical values.

### 2. Models-results:
Check correlation between categorical values using chi2 contingency.
Fix the imbalance by undersampling.
Builded and compared 3 models: Logistic Regression, Random Forest Classifier, Decision Tree Classifier

### 3. Web-Scraping:
Scraped some additional information for the topic from [Agency for Healthcare Research and Quality](https://www.ahrq.gov/)
- All-cause 30-day readmissions ranked by the most frequently treated conditions* in U.S. hospitals, 2010
- All-cause 30-day readmissions ranked by conditions with the highest readmission rates,* U.S. hospitals, 2010

## Requirements

Please install the following libraries:\
*pandas*\
*numpy*\
*sklearn*\
*matplotlib*\
*seaborn*\
*BeautifulSoup*\


## Instructions to run the code
1. Download the data from the link above
2. Run the notebooks in order


Asli Veenstra- [@aslivns](https://github.com/aslivns/)
