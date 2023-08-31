This competition's task was to impute the missing equilibrium qualities of the provided dataset.  I finished 3rd out of 693 competitors during this competition.  Additional writeup on my approach can be found here https://www.kaggle.com/competitions/playground-series-s3e15/discussion/414027.

# CSV Files
data.csv - This is the competition provided dataset.  It contains both the train and test data.  Can be found here https://www.kaggle.com/competitions/playground-series-s3e15/data.

sample_submission.csv - This is the competition provided sample submission file that outlines the format that inferences must be in when submitted.  Can be found here https://www.kaggle.com/competitions/playground-series-s3e15/data.

original.csv - Additional training data provided by Saurabh Shahane https://www.kaggle.com/datasets/saurabhshahane/predicting-heat-flux.

predictions.csv - The output file from notebook Competition_Submission.ipynb that contains inferences for each missing equilibrium quality in data.csv.


# Python Notebooks

Feature_Imputation_EDA.ipynb - Exploratory Data Analysis of the data.csv file provided for the competition.

Competition_Submission.ipynb - Notebook containing ensemble model training and inference of equilibrium quality for missing values in data.csv.  Outputs predictions.csv.

