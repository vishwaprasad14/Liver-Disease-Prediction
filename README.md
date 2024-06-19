# Introduction:
This project is about how to predict risk of liver disease for a person, based on the blood test report result of the user. The risk of liver disease was predicted using machine learning algorithms. The final output was predicted based on the most accurate machine learning algorithm.

Based on the accurate model I designed a system which asks a person to enter the details of his/her blood test report. Then the system uses the most accurate model which is trained to predict, whether a person has risk of liver disease or not.

# Data collection:
In this project, I collect a dataset from the Kaggle. In addition, the original dataset was collected from the northeast of Andhra Pradesh, India. This dataset consists of 583 liver patient’s data whereas 75.64% male patients and 24.36% are female patients. This dataset has contained 11 particular parameters whereas we choose 10 parameters for our further analysis and 1 parameter as a target class. Such as
Age of the patient,
Gender of the Patients,
Total Bilirubin,
Direct Bilirubin,
Alkaline Phosphotase,
Alamine Aminotransferase,
Asparatate Aminotransferase,
Total Proteins,
Albumin,
Albumin and Globulin Ratio.

# Data Exploration:
Imported the dataset using Python pandas Library.
Executed the first few and last few rows to understand the structure and format of the data.
Obtained descriptive statistics (mean, median, standard deviation, min, max, etc.) for numerical features.
Identifed the data types of each column (numeric, categorical, text, etc.).
Detected and handled missing data through imputation or removal.
Created visual representations like histograms, box plots etc., to gain insights into the data.

# Data Splitting:
Divided the dataset into training and testing sets. The typical split is around 70-30 or 80-20 for training and testing, respectively.

# Model Development:
Selected suitable machine learning algorithms, Logistic Regression for  predictive model. Trained the model on the training dataset using the selected algorithm. Evaluated the model's performance on the testing dataset using metrics such as accuracy, precision.
