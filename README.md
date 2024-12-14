# PHP2550_Project2

## Abstract

### Background
Smoking cessation is particularly challenging for individuals with major depressive disorder (MDD), as nicotine dependence and psychological factors related to depression can reduce motivation to quit. This study builds on prior findings (Roufosse F, Kahn JE, Rothenberg ME, et al. (2020)) by investigating baseline predictors and potential moderators of behavioral and pharmacotherapy treatments on smoking abstinence among adult smokers who had a life-time diagnosis of MDD.

### Methods
A randomized, placebo-controlled 2x2 factorial trial was conducted, comparing Behavioral Activation for Smoking Cessation (BASC) and standard treatment (ST) with or without adjunctive varenicline. Missing values in the data were imputed by multiple imputation. Logistic LASSO and random forest models were constructed to evaluate the predictive power of baseline variables on smoking abstinence. Logistic LASSO models, both with and without interaction terms, were used to explore potential moderating effects.

### Results
The two logistic LASSO models and the random forest model were evaluated using an external test set. The random forest model achieved the highest performance in terms of AUC (0.707). However, the tow logistic LASSO models showed poor predictive performance. All the three models overestimates the probability of abstinence. FTCD score emerged as the most significant predictor of abstinence, and it may also moderate the effects of behavioral treatment. Varenicline demonstrated a positive effect on abstinence, and its impact may be moderated by smoking-related variables. In contrast, BASC did not significantly contribute to abstinence, aligning with previous findings. Further research is needed to fully explore the interactions between BASC, anhedonia, and abstinence.

## Files

Project2_update_Jizhou.Rmd: The Rmarkdown version of the Regression Analysis report, which includes both written text interpretations and raw code used in the analysis.

Project2_update_Jizhou.pdf: The PDF version of the Regression Analysis report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis.

## Dependencies
The following packages were used in this analysis:

- **Data Manipulation:**  tidyverse

- **Table Formatting:** gtsummary, knitr, kableExtra

- **Data Visualization:** corrplot, VIM

- **Model building:** glmnet, randomForest, pROC
