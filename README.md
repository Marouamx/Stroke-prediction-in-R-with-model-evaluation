# Stroke prediction in R with data oversampling

RMD is the R markdown file. Only previewed by R studio, so I added an HTML rendered version to read the full report.

Dataset given for stroke prediction contains target variable which is a binary categorical variable and the predictor categorical variables are gender, ever married, work type, Residence type, heartdisease, Hypertension, smoking status and the numerical predictor variables are age, average glucose level and BMI. Exploratory data analysis is performed where numerical variables are scaled and missing or NA values are removed from the observations. Variables heart_disease, hypertension are converted as factors and variable BMI is converted to numerical from factor.

The dataset is imbalanced so data oversampling was performed to randomly duplicate examples from the minority class in the training dataset. Results showed an improved accuracy after that.  
