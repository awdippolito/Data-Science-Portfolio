This competition's task was to predict whether a patient had a kidney stone or not based on urine analysis.

# CSV Files
train.csv - This is the competition provided training dataset.  Can be found here https://www.kaggle.com/competitions/playground-series-s3e12/data.

test.csv - This is the competition provided test dataset that participants must make predictions/inferences for.  Can be found here https://www.kaggle.com/competitions/playground-series-s3e12/data.

sample_submission.csv - This is the competition provided sample submission file that outlines the format predictions must be in when submitted.  Can be found here https://www.kaggle.com/competitions/playground-series-s3e12/data.

kidney stone urine analysis.csv - Additional training data provided by Vuppala Adithya Sairam https://www.kaggle.com/datasets/vuppalaadithyasairam/kidney-stone-prediction-based-on-urine-analysis.

predictions.csv - The output file from notebook Competition_Submission.ipynb that contains predictions for each patient listed in the file test.csv.


# Python Notebooks

Kidney_Stone_EDA.ipynb - Exploratory Data Analysis of the test.csv file provided for the competition.  It was found that utilizing just 2 variables (conductivity of urine and calcium concentration) is effective at predicting kidney stone presence in patients.

Competition_Submission.ipynb - Notebook containing XGBoost model training and prediction of kidney stone presence in patients from test.csv.  Outputs predictions.csv.
