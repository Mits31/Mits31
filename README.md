Digital Futures Capstone Project: Detecting Fraud in Insurance Claims
======
The following outlines the capstone project I completed to end my time at the Digital Futures Academy.

Project Aims
------
This project was created to showcase the skills I have gained since joining the Digital Futures Academy.
Fraud is a problem which has plagued insurance companies and is one of the most common problems that insurers face. It is something
which I find deeply interesting and wanted to determine if it was possible to predict actions to use measure to prevent this form of
cyber crime. This project was aimed to analyse and develop a Machine Learning model to detect potential fraudulent claims from a 
supervised dataset. 

Dataset Acquisition
------

Initially looking for an datasets around fraud, I wanted the dataset to be anonymous with no personal information. Luckily
I managed to access a dataset from Kaggle which contains approximately 15,000 rows with 33 feature columns and being supervised
also. The dataset can be accessed through the link - https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection


Approach Overview
------
After obtaining the data from Kaggle, I began through Data Exploration to understand it further to understand my proportion
of fraudulent cases as well as other characteristics that may be important. This helped to spot any issues with the data to
ensure I could clean it throroughly, i.e Null values/unimportant data. I chose to use three baseline models, including
Logistic Regression, Random Forest Classifiers and Decision Tree's. These would be measured in 4 areas, Accuracy, F1 Score,
Matthews Correllation Coefficient and ROC AUC score. With initally poor results, I needed to adjust the data further where
I used downsampling and upsampling using "Resample" and "SMOTE", with a view to use stacking to get a better result.

Project Conclusions
------
My best model resulted in using Stacking on my dataset and applying "SMOTE" to upsample the instances of Fraudulent Claims yielding
an accuracy of 0.99, which F1 score of 0.9 and ROC AUC Score of 0.91, only classifying 51 cases of fraud as non fraudulent.
I had found that the data behind fraud is naturally imbalanced regardless of the nature which makes it fiddicult to predict without
the risk of false positive results (classifying genuine claims with fraudulent). Fraud data is non stationary where methods are
being adapted to avoid detection.

Future Improvements
------
To improve on this project, I would like to explore clustering to see if this would yield a better result compared to the models
I have already used in particular KNN clustering which I believe may be useful. It would also be important to retrain my models
with new datasets to understand where I have missed key information. 

Capstone Presentation
------
[You can view my capstone presentation here](https://github.com/Mits31/Mits31/blob/bf451dfa725e859576c29470001002c3e3533d4b/Capstone%20Project%20-%20Mitesh%20Acharya.pptx)
