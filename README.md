# PHP2550_Project2

## Abstract

### Background
Smoking cessation is particularly challenging for individuals with major depressive disorder (MDD), as nicotine dependence and psychological factors related to depression can reduce motivation to quit. This study builds on prior findings (Roufosse F, Kahn JE, Rothenberg ME, et al. (2020)) by investigating baseline predictors and potential moderators of behavioral and pharmacotherapy treatments on smoking abstinence among adult smokers who had a life-time diagnosis of MDD.

### Methods
A randomized, placebo-controlled 2x2 factorial trial was conducted, comparing Behavioral Activation for Smoking Cessation (BASC) and standard treatment (ST) with or without adjunctive varenicline. Logistic LASSO and random forest models were constructed to evaluate the predictive power of baseline variables on smoking abstinence, with and without interaction terms to explore potential moderating effects.

### Results
FTCD score, Non-Hispanic White ethnicity, and current MDD status emerged as significant predictors of abstinence, with FTCD score possibly moderating the effects of behavioral treatment. Varenicline demonstrated a positive effect on abstinence, and its impact may be moderated by smoking-related variables, such as nicotine metabolism ratio. In contrast, BASC did not significantly contribute to abstinence, aligning with previous findings. Further research is needed to fully explore the interactions between BASC, anhedonia, and abstinence.

## Files

Project2_JT.Rmd: The Rmarkdown version of the Regression Analysis report, which includes both written text interpretations and raw code used in the analysis.

Project2_JT.pdf: The PDF version of the Regression Analysis report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis.

## Dependencies
The following packages were used in this analysis:

- **Data Manipulation:**  tidyverse

- **Table Formatting:** gtsummary, knitr, kableExtra

- **Data Visualization:** corrplot, VIM

- **Model building:** glmnet, randomForest, pROC
