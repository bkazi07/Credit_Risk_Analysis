# Module 17 Challenge

# Overview of the loan prediction risk analysis:

The purpose of this challenge was to create supervised machine learning models to predict credit risk we've built and evaluate using Scikit-Learn to recommend which model is most effective. The categories of machine learning used to predict a credit risk were the resampling models, SMOTEEN techniques, and ensemble classifier models. The tools that were used in this challenge were JupyterNotebook, sckikit-learn machine learning libraries, as well as the csv peer to peer data. 

# Results
## Use Resampling modules to predict credit risk
![Screen Shot 2022-11-23 at 11.26.57 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.26.57%20AM.png?raw=true)
Accuracy Score – 66%

Precision - The model’s precision is low (1%), meaning that the model’s ability to measure positive classification is not reliable.

Recall – The model presented a good level of positive instances (74%), confirming that almost three quarters of its classification were correctly identified.

F1 – Shows a low balance between precision and sensitivity, the best score for F1 is 1.0.

![Screen Shot 2022-11-23 at 11.27.10 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.27.10%20AM.png?raw=true)
Accuracy Score – 65%

Precision - 1%, ability to measure positive classification is not reliable.

Recall – 62%, shows weak ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.

## Undersampling
![Screen Shot 2022-11-23 at 11.27.20 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.27.20%20AM.png?raw=true)
Accuracy Score – 54%

Precision - 1%, ability to measure positive classification is not reliable.

Recall – 69%, shows weak to good ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.

## Combination
![Screen Shot 2022-11-23 at 11.27.40 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.27.40%20AM.png?raw=true)
Accuracy Score – 68%

Precision - 1%, ability to measure positive classification is not reliable.

Recall – 77%, shows strong ability to correctly identify positive instances.

F1 – Low balance between precision and sensitivity.

## Use Ensemble Classifiers to predict credit risk.
![Screen Shot 2022-11-23 at 11.27.55 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.27.55%20AM.png?raw=true)
Accuracy Score – 68%

Precision - 88%, reliable ability to measure positive classification.

Recall – 37%, weak ability to correctly identify positive instances.

F1 – medium balance between precision and sensitivity.
![Screen Shot 2022-11-23 at 11.28.05 AM.png](https://github.com/bkazi07/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-11-23%20at%2011.28.05%20AM.png?raw=true)
Accuracy Score – 93% 

Precision - 9%, ability to measure positive classification is not reliable. 

Recall – 92%, shows strong ability to correctly identify positive instances. 

F1 – Low balance between precision and sensitivity.

# Summary:
Due to the lack of balance in the different components that were analyzed, the recommendation I would make would be to NOT recommend the use of these models for credit risk. The results for the resampled classifiers showed a pretty fair accuracy score, but the precision and F1 were low. On the other hand, in the combination model, there was lots of accuracy, but the precision and balance between the precision and sensitivity were low. Even though there was a strong ability to identify positive instances, there was still no balance. 





