# Practice-Project-Repo
Home Credit Default Risk — Individual Portfolio

Author: Miles McCunniff
MSBA, University of Utah

Project Overview

Home Credit provides loans to individuals who often lack traditional credit histories, making it difficult to assess repayment risk. The goal of this project was to build a predictive model that estimates the probability of loan default, helping the lender reduce financial losses while expanding responsible access to credit. The dataset required extensive cleaning, joining multiple tables, and addressing substantial missingness in key features.

Group Solution

As a team, we created a unified modeling dataset from application records, credit bureau data, previous loans, and credit card balances. We engineered new features, compared several algorithms, and tuned hyperparameters to improve accuracy. Our final model achieved a Kaggle score of 0.73399, outperforming the baseline and offering meaningful lift for identifying high-risk borrowers.

My Individual Contribution

The notebooks in this repo reflect my personal analysis and modeling work. I performed exploratory data analysis, engineered features that include missingness indicators for the external credit score variables, and trained several models, including logistic regression and gradient boosting. I also conducted threshold analysis to understand the business implications of classifying high-risk applicants, created confusion matrices, and wrote detailed interpretations throughout my workflow. All code is commented and structured to ensure reproducibility.

Business Value

A strong predictive model helps Home Credit minimize charge-offs, improve loan portfolio quality, and allocate review resources more efficiently. Better risk prediction also supports fairer lending decisions by enabling more precise evaluation of under-documented applicants. Even modest performance gains translate into significant financial and operational value at scale.

Challenges and Learning

Key challenges included managing missing data, avoiding leakage, handling class imbalance, and working with a large relational dataset. Addressing these issues strengthened my skills in data preparation, modeling, evaluation, and interpretation. This project reinforced the importance of connecting technical model outputs to meaningful business decisions.
