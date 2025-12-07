# Practice-Project-Repo
Home Credit Default Risk — Individual Portfolio

Author: Miles McCunniff
MSBA, University of Utah

Project Overview

Home Credit is a global lender that provides financing to individuals who often lack traditional credit histories, making it challenging to evaluate borrower risk. The goal of this project was to build a predictive model that estimates the probability that an applicant will default on a loan. This work supports Home Credit’s mission of expanding responsible access to credit while reducing financial losses through better risk assessment. Because the dataset spans multiple relational tables and contains substantial missingness, it closely mirrors real-world credit risk modeling challenges and required thoughtful data preparation and modeling choices.

Group Modeling Approach

As a group, we combined data from several sources into a unified modeling dataset, which included application data, bureau history, previous loan applications, and credit card balance information. We engineered new features from these sources, compared multiple supervised learning algorithms, and tuned model hyperparameters to optimize predictive performance. Our final group model achieved a Kaggle score of 0.73399, outperforming the majority-class baseline and providing meaningful lift for identifying applicants with a higher likelihood of defaulting.

My Individual Contribution

The notebooks in this repository represent my individual work throughout the project. I conducted exploratory data analysis, engineered features such as missingness indicators for the external credit score variables, and built several models including logistic regression and gradient boosting. I also performed threshold analysis to understand the effect of classifying the riskiest borrowers, created confusion matrices for key cutoffs, and documented the interpretation of model results. My notebooks are structured for reproducibility and include narrative explanations, commented code, and labeled visualizations.

Business Value

A strong predictive model allows Home Credit to identify high-risk borrowers earlier, reduce charge-offs, and improve overall loan portfolio quality. Better risk estimates also make it possible to extend credit more equitably by approving applicants who might have previously been rejected due to insufficient documentation. Even incremental improvements in predictive accuracy can translate into significant financial and operational impact for a lender operating at scale.

Difficulties Our Group Encountered

Throughout the project, our team faced several challenges related to the complexity of the dataset and the modeling process. One major difficulty was handling missing data, particularly in features such as the EXT_SOURCE variables, which required thoughtful imputation and the creation of missingness indicators. The multi-table structure of the data created merging and memory constraints, requiring careful coordination of preprocessing workflows. We also had to navigate issues such as class imbalance, potential data leakage, and model instability when including unscaled or highly skewed features. Addressing these challenges deepened our understanding of both data engineering and model development in a credit-risk context.

What I Learned

Working through this project strengthened my ability to build end-to-end modeling pipelines, from data preparation to model interpretation. I gained experience managing large relational datasets, applying principled approaches to missingness, and tuning models while avoiding pitfalls such as leakage and inappropriate feature inclusion. I also learned how to frame technical results in business terms and communicate insights clearly through writing and visualizations. Overall, this project helped me develop a more rigorous, structured approach to applied predictive modeling and improved my confidence working with complex real-world datasets.
