# Pima-Indian-Diabetes-Prediction-R

A research conducted by National Institute of Diabetes and Digestive and Kidney diseases (NIH), one of the prominent medical research centers, shows that diabetes affects 30.30 million people closely in United States. Also, NIH claims that diabetes is the seventh leading cause of death. U.S. Department of Health & Human Services, a government organization reports 15 million women in the United States have diabetes. Therefore, this project aims to awake our awareness of diabetes and help detect whether a patient has diabetes or not.

The dataset that is chosen is originally from the ‘National Institute of Diabetes and Digestive and Kidney Diseases’, Maryland, US and is named as ‘Pima Indians Diabetes Database’. The dataset consists of eight medical predictor variables and one target variable, ‘Outcome’. The predictor variables include the number of pregnancies the patient has had, their BMI (Body Mass Index) level, insulin levels, age, blood pressure, glucose, skin thickness, and diabetes pedigree function.

R, a statistical computing and graphics tool was used for building the BI model. At first, the dataset was explored to understand and develop a general idea for further analysis. Correlations were found among variables, for example, there was a negative relationship between pregnancies and skin thickness; also, the distribution of BMI is symmetric.

Then, classification models were built using this dataset, including decision tree model and logistic regression model, to predict whether a given female patient, with certain diagnostic measurements, has diabetes or not. For the decision tree model, unusual number of zeroes weere addressed, 60% of records were sampled as training data sets and 40% of records as validation data sets, decision tree was plotted, and decision tree model was evaluated using confusion matrix and ROC. For logistic regression model, I data imputation was performed prior, training data sets and validation data sets were sampled similarly, the logistic regression model was built, odds ratios computed, and the logistic regression model was evaluated using confusion matrix and ROC.

After running and evaluating both the models, it was concluded that decision tree model is better than logistic regression model in this project. Not only because decision tree model has a higher accuracy rate in confusion matrix and a higher area in ROC than logistic regression model has, but also because logistic regression model relies largely on the independent variables, if we include wrong independent variables, there is no predictive value for this model.
