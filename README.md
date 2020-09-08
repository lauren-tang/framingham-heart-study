# Framingham Heart Study:

### Summary
This project investigates the relation between the quantified risk of coronary heart disease (CHD)
with some explanatory factors based on the data collected from 2306 individuals participating in the
Framingham Heart Study. Two candidate models are developed by automated model selection and
manual construction with exploration of colinear predictors, significance of covariates, and outstanding interaction effects. After the diagnostics regarding assumption violation, outlier, leverage, influential observation, and explanatory and predictive power, the automatedly selected model is chosen to be the final model. 

The final model consists of 56 predictors with significant ones such as myocardial infarction history (covariate prevmi) and hypertension (covariate prevhyp). Additionally, some interaction effects between continuous and categorical variables (e.g., interaction between high density lipoprotein
cholesterol and presence of myocardial infarction history) are vitally significant to predict the risk of CHD.


### Files
- **fhs.csv**: the Excel file that contains information on 2306 individuals participating in the Framingham Heart Study with the values of predictive and explanatory variables;
- **Framingham Heart Study.rmd**: the main R Markdown file that consists of the R scripts to generate and diagnose the linear regression models with the corresponding analysis, explanation, and documentation;
- **Framingham-Heart-Study.pdf**: the report generated by running "Framingham Heart Study.rmd";
- **mspe_calc.rds**: the rds file that stores the calculation results of the mean squared prediction error (MSPE); This file is automatically used when the "Framingham Heart Study.rmd" is run;
- **AutoModels.rds**: the rds file that stores the generating process of the box plot that represents the cross-validation model comparison results; This file is automatically used when "Framingham Heart Study.rmd" is run;


### How to Excecute Files:
- Run "Framingham Heart Study.rmd"; Click "Knit" if R Studio is used to run this rmd file;
- Make sure that all files are put under the same directory when "Framingham Heart Study.rmd" is run;
