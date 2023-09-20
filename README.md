## Blood Transfusion Service Center Project
This project aims to apply the RFMTC marketing model (a modified version of RFM) to the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The goal is to segment and predict the donors’ behavior using machine learning techniques such as Xgboost.

## Dataset
The dataset contains 748 records of donors who donated blood at the Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The dataset has five attributes:

R (Recency - months since last donation)  
F (Frequency - total number of donation)  
M (Monetary - total blood donated in c.c.)  
T (Time - months since first donation)  
D (Binary variable representing whether he/she donated blood)  

The dataset can be downloaded from here: [http://archive.ics.uci.edu/dataset/176/blood+transfusion+service+center].

## Results
The Xgboost classifier was trained on the dataset using 10-fold cross-validation and tested on a hold-out set. The classifier achieved a mean cross-validation score of 81% and an accuracy of 0.73 on the testing set. 
The plot shows that the most important feature for the classifier was Recency, followed by Frequency, Time and Monetary.

# Conclusion
The results of this project demonstrate that the RFMTC model can be applied to donor segmentation and prediction using machine learning techniques such as Xgboost. However, the performance of the classifier can be improved by tuning the parameters, using more features or applying different algorithms. Further research is needed to explore the best ways to optimize the RFMTC model for donor behavior analysis and marketing strategies.

I hope this text is helpful for your project. If you have any feedback or suggestions, please let me know.
