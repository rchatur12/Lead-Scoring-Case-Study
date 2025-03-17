# Lead-Scoring-Case-Study
##  Problem Statements & Objectives of Case Study
##  Problem statement
X Education acquires huge number of leads everyday, however current lead conversion rate is only ~30%.
The sales team spends significant time and effort reaching out to all leads, many of whom do not convert.
Company wants to identify high-potential leads (also called Hot Leads) to improve efficiency and conversion rates.
The goal is to increase the lead conversion rate to around 80% by prioritising the most promising leads.

## Business Impacts:
Higher conversion rates → More revenue.
Optimized sales efforts → Focus on quality leads.
Data-driven decision-making → Efficient resource allocation.

## Objectives
Develop a Lead Scoring Model using Logistic Regression.
Identify Hot Leads with high probability of conversion.
Improve lead conversion rate to 80%.
Enhance sales team efficiency by focusing on quality leads.

## Major steps involved in case study:

1) Data Source for Analysis
  - Checking provided data files.
  - Basic inspection of the CSV file and data dictionary.
2) Data Preprocessing
  - Checking for duplicates, 
  - Handling missing values and removing features with excessive missing data., 
  - Data imputation.
  - Identifying and resolving data issues.
  - Detecting and removing outliers.
3) Exploratory Data Analysis
    - Univariate Analysis. Bivariate Analysis (Split data analysis).
    -  Extracting insights from numerical and categorical features.
4) Data preparation.
    - Encoding categorical data and generating dummy features. Feature Scaling. 
    - Removing non-feature columns.
    - Splitting the data into Test and Train data set.
    - Scaling test and train datasets.
5) Model Selection & Training.
   - Using Logistic Regression to predict lead conversion probability.
   - Feature selection using Recursive Feature Elimination (RFE).
   - Refining the model by eliminating features based on p-values and Variance Inflation Factor (VIF).
   - Generating the final model and predicting the target variable using the training data.
6) Lead Scoring & Model Performance.
     - Classifying leads using a probability threshold of 0.5 and evaluation of Model performance using different metrics- Accuracy, Sensitivity, specificity, precision, recall, etc 
        (on train dataset predictions).
     - Assign lead scores → Rank leads from 0 to 100
     - Determining the optimal probability cutoff using Sensitivity-Specificity and Precision-Recall analysis.
     - Re-evaluate model performance with optimal cutoffs and finalising the optimal cutoff.
7) Validation of model
   - Predicting the target variable using test data
   - Evaluating model performance.


 ##   Details of files given
   - Lead_Scoring_final.ipynb : The python file showing coding and data analysis
   - Lead Score Assignment Subjective Questions.pdf : Subjective questions answered
   - Lead Score Case Study Presentation.pdf : Final Presentation
   - Leads.csv : Data provided 
   - Leads Data Dictionary.xlsx : Data Dictionary
   - Lead Score Case Study Summary.pdf : Summary on what's done in the entire py file
