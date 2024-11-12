# PHP2550_Project2

## Abstract

### Background
Endurance exercise performance is well-known to be affected by environmental conditions. Previous research has shown that rising environmental temperatures negatively impact the performance, with more significant effects in longer-distance events such as marathons (Ely et al., 2007), and the extent of this impact may vary depending on both sex and age. 

### Methods
In this study, we analyzed data from five major marathon races to investigate the effects of weather on marathon performance across the lifespan in both men and women. We conducted an exploratory analysis aimed at three key objectives: examining how increasing age affects marathon performance in both men and women, exploring how environmental conditions influence performance and whether these effects vary by age and gender, and identifying which weather factors have the greatest impact on marathon outcomes.

### Results
Our results indicate that age and sex are the most significant predictors of performance, with men generally performing faster than women across all age groups, and marathon times increasing with age, particularly after the age of 60. Among the environmental factors, WBGT (Wet Bulb Globe Temperature) had the most pronounced effect when not adjusting for other factors, as higher temperatures led to longer finishing times. When identifying the weather condition factor that has the most impact on marathon performance, a random forest model shows that the effects of weather conditions, such as WBGT, wind speed, and AQI, though present, are less substantial.

## Files

Project2_JT.Rmd: The Rmarkdown version of the Exploratory Data Analysis report, which includes both written text interpretations and raw code used in the analysis.

Project2_JT.pdf: The PDF version of the Exploratory Data Analysis report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis.

## Dependencies
The following packages were used in this analysis:

- **Data Manipulation:**  tidyverse, lubridate

- **Table Formatting:** gtsummary, knitr, kableExtra

- **Data Visualization:** corrplot

- **Model building:** randomForest
