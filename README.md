# High Traffic Recipe Prediction
DataCamp Data Science Professional Certification Project

## Project Description
### Overview
The goal of this project is to develop a predictive model that accurately forecasts high traffic recipes 80% of the time for a recipe discovery website. By identifying and promoting high traffic recipes, the company aims to increase site visits and, consequently, paid subscriptions.

### Background
The project involves preprocessing recipe data to examine its reliability, performing preliminary data analysis, and then building predictive models to identify high traffic recipes. The business objective is to enhance website traffic and subscription rates by strategically selecting recipes for promotion.

## Data Analysis and Model Building
- Preprocessed data checking for reliability, missing values, and duplicate entries.
- Conducted exploratory data analysis to understand distributions and relationships, with a notable find that pork, potato, and vegetable dishes drive high traffic, while beverages and breakfast dishes do not.
- Developed and compared logistic regression and random forest classifier models, focusing on precision as the key metric due to the business need of correctly predicting high traffic recipes.

### Key Findings
- The random forest model was selected due to its superior recall and comparable precision to logistic regression, achieving over 80% cross-validated precision in predicting high traffic recipes.
- Feature importance analysis indicated a relationship between recipe category and traffic, with calories playing a significant role.

## Conclusions and Business Implications
- Deploying the predictive model will automate the selection of high-traffic recipes, expected to boost site traffic and reduce bounce rates.
- Recommendations include monitoring model precision over time and evaluating the correlation between high-traffic recipes and monthly recurring revenue after three months of implementation.

## Media
### Model Precision and Feature Importances
Pending

## Link to Project Notebook
[Notebook](https://github.com/yourusername/Recipe-Prediction/blob/main/Recipe-Traffic-Prediction-Final.ipynb)

## Demo Video
Pending

## Installation and Deployment
### System Requirements
- Python 3.9.16
- Jupyter Notebook, and essential libraries (Pandas, NumPy, Scikit-learn, Matplotlib).
