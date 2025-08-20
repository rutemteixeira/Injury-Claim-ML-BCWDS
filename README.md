# Work Injury Claim's Severity Predictive classification model

Predicted workplace injury claim severity using supervised machine learning on predominantly categorical data. Exhaustive Preprocessing pipeline.

## Project Overview

This solution was developed as the final project for the Machine Learning course in the MSc in Data Science and Advanced Analytics program at NOVA IMS, Lisbon.<br>

The project involved developing a predictive model to automate classification of injury severity claims in the workplace for NYC's Workers Compensation Bank. Complete structured pipeline involving data exploration, cleaning, preprocessing, and feature selection. Build and evaluate classification models using cross-validation, confusion matrix analysis, and derived performance metrics.

## Repository structure
- 4 notebooks in html format that should be ran sequentially from 0 to 4
 
## Technical Approach

| Phase              |	          Techniques                                  |
|--------------------|--------------------------------------------------------|
|Data Preparation    | SMOTE oversampling, Frequency Encoding                 |
|Feature Engineering | Time-based features, binary flags, category grouping   |
|Model Selection     | Light GBM with custom class weights                    |
|Evaluation	         | F1-score macro, Precision, Confusion matrix            |


  

## Key Challenges
- Little context about Domain Knowledge
- Highly imbalanced classes
- Missing data in majority of features
- 90% categorical features requiring special encoding

 
## Results
- **74% Accuracy** - F1-Score macro of 42% on imbalanced classes


## Key Observations and Future Improvements
- First Machine Learning project
- Few predictors led to best results
- Grid search required a broader parameter range to improve the search space.



### More details on https://rutemteixeira.github.io/generic/p1-injury-claim.html
