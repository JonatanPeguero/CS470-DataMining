README.txt
==========

Title: Heart Disease Prediction Using Custom Decision Tree & Random Forest
Author: [Jonatan Peguero ]
Date: [3/31/25]

Description:
------------
This project implements heart disease prediction using a Random Forest classifier (using scikit-learn)

The program reads patient data from a CSV file ("hw3data.csv"), preprocesses the data 
(by mapping binary features, converting gender from "M"/"F" to numeric values, one-hot 
encoding categorical variables, and binning the age column), and then splits the data 
into a 70/30 training/testing hold-out set. The corresponding person IDs for the training 
and testing sets are written to "para2_file.txt" and "para3_file.txt" respectively. 
Predictions for the testing set are output to "para4_file.txt".

Input Files:
------------
1. hw3data.csv:
   - Contains anonymized patient information with columns including:
     - person ID
     - age
     - gender
     - chest pain type
     - resting blood pressure
     - serum cholesterol in mg/dl
     - fasting blood sugar > 120 mg/dl
     - resting electrocardiographic results
     - maximum heart rate achieved
     - exercise induced angina
     - oldpeak = ST depression induced by exercise relative to rest
     - the slope of the peak exercise ST segment
     - number of major vessels (0-3) colored by flourosopy
     - Has heart disease? (Prediction Target)
   
2. para2_file.txt:
   - Contains a list of person IDs for the training set (one per line).

3. para3_file.txt:
   - Contains a list of person IDs for the testing set (one per line).

4. para4_file.txt:
   - Contains the model predictions for the test set in the format:
     <person ID> <prediction ("yes" or "no")>

Environment & Language:
-------------------------
- Programming Language: Python 3.8
- Environment: Can be run in a Jupyter Notebook or as a standalone Python script.
- Software: Recommended to use an environment like Anaconda.

Required Libraries:
---------------------
- pandas
- numpy
- scikit-learn


Usage:
------
1. Place "hw3data.csv" in the same directory as the code.
2. Run the script (or notebook).
3. The program will:
   - Preprocess the data.
   - Split the data into 70% training and 30% testing.
   - Write the training IDs to "para2_file.txt" and testing IDs to "para3_file.txt".
   - Train a Random Forest classifier.
   - Output predictions for the test set to "para4_file.txt".
   - Print evaluation metrics (accuracy, precision, recall, F1 score, specificity, sensitivity) for both models to the console.