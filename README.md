# Thyroid_Diff_Classification_Model
This repository contains python code for different classification models that are trained on the "Thyroid_Diff.csv" dataset.
The Dataset includes 17 features.
Input Features : Age, Gender, Smoking ......., Stage, Response
Target : Recurred
The models are trained using different classification algorithms
STEPS:
- Import the libraries
- Load the Dataset
- Split the dataset into input features and target
- Encode the columns which include categorical data
- Split the Dataset into Training and Test Set
- Apply the Model
- Predict the test results
- Use Hyper Parameter Tuning to get the Best Model with Best Features
- Generate the Classification Report and Find the Evaluation Metrics for each model

MODELS INFERENCE
LOGISTIC REGRESSION - Accuracy: 0.896, Precision: 0.896, Recall: 0.896, F1Score: 0.896
K NEAREST NEIGHBOUR - Accuracy: 0.883, Precision: 0.901, Recall: 0.883, F1Score: 0.876
DECISION TREE       - Accuracy: 0.909, Precision: 0.909, Recall: 0.909, F1Score: 0.908
RANDOM FOREST       - Accuracy: 0.961, Precision: 0.961, Recall: 0.961, F1Score: 0.961
SUPPORT VECTOR MACH - Accuracy: 0.909, Precision: 0.91,  Recall: 0.909, F1Score: 0.909
NAIVE BAYES         - Accuracy: 0.909, Precision: 0.91, Recall: 0.909, F1Score: 0.909
FROM THE ABOVE EVALUATION METRICS WE CAN CONCLUDE THAT RANDOM FOREST CLASSFIFICATION MODEL GIVES THE BEST RESULTS.
