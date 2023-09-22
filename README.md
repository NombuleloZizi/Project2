<p align = "center"> 
  <img src = "https://www.legalexaminer.com/wp-content/claris-images-uploads/car-insurance@large.jpg">
</p>


# Car Insurance Data

**Author**: Nombulelo Zizi

### Business problem:
The company has shared its annual car insurance data. Now, you have to find out the real customer behaviors over the data
## Data Source: 
Car Insurance Data
[https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)

For this dataset, there were 607 rows and 12 columns.

## Description

Use Insurance Data to check if the customer took the lolan.

### Exploratory Data Analysis
<p align = "center"> 
  <img src = "https://github.com/NombuleloZizi/Project2/blob/main/age_vs_speed.png">
</p>

This graph shows the drivers who 65+ and who have 30y+ driving experience have more speeding violations


 ### Expanatory Data Analysis

<p align = "center"> 
  <img src = "https://github.com/NombuleloZizi/Project2/blob/main/age_vs_accidents.png">
</p>

This graph shows the drivers who 65+ and who have 30y+ driving experience have more past accidents.


 ### Maching Learning Using the Following Models:
    - K-Nearest Neighbors
    - Tuned K-Nearest Neighbors
    - Logistic Regression
    - Tuned Logistic Regression
    - Decision Tree Classifier
    - Random Forest

    
    
## Models Evaluated & Results

- **K-Nearest Neighbors**:
 Train Report
              precision    recall  f1-score   support

           1       0.90      0.91      0.90      5150
           0       0.80      0.77      0.79      2350

    accuracy                           0.87      7500
   macro avg       0.85      0.84      0.85      7500
weighted avg       0.87      0.87      0.87      7500

Test Report
              precision    recall  f1-score   support

           1       0.85      0.86      0.86      1717
           0       0.69      0.68      0.68       783

    accuracy                           0.80      2500
   macro avg       0.77      0.77      0.77      2500
weighted avg       0.80      0.80      0.80      2500

    
- **Tuned K-Nearest Neighbors**:
Train
               precision    recall  f1-score   support

         0.0       1.00      1.00      1.00      5150
         1.0       1.00      1.00      1.00      2350

    accuracy                           1.00      7500
   macro avg       1.00      1.00      1.00      7500
weighted avg       1.00      1.00      1.00      7500

Test
               precision    recall  f1-score   support

         0.0       0.85      0.87      0.86      1717
         1.0       0.71      0.67      0.69       783

    accuracy                           0.81      2500
   macro avg       0.78      0.77      0.78      2500
weighted avg       0.81      0.81      0.81      2500


   - **Logistic Regression**

Train Report
              precision    recall  f1-score   support

           1       0.88      0.90      0.89      5150
           0       0.77      0.73      0.75      2350

    accuracy                           0.85      7500
   macro avg       0.83      0.81      0.82      7500
weighted avg       0.85      0.85      0.85      7500

Test Report
              precision    recall  f1-score   support

           1       0.88      0.88      0.88      1717
           0       0.74      0.74      0.74       783

    accuracy                           0.84      2500
   macro avg       0.81      0.81      0.81      2500
weighted avg       0.84      0.84      0.84      2500


    - **Tuned Logistic Regression**
    
Train
               precision    recall  f1-score   support

         0.0       0.88      0.90      0.89      5150
         1.0       0.77      0.73      0.75      2350

    accuracy                           0.85      7500
   macro avg       0.83      0.81      0.82      7500
weighted avg       0.85      0.85      0.85      7500

Test
               precision    recall  f1-score   support

         0.0       0.88      0.88      0.88      1717
         1.0       0.74      0.74      0.74       783

    accuracy                           0.84      2500
   macro avg       0.81      0.81      0.81      2500
weighted avg       0.84      0.84      0.84      2500

    
    - **Decision Tree Classifier**

    train
              precision    recall  f1-score   support

         0.0       1.00      1.00      1.00      5150
         1.0       1.00      1.00      1.00      2350

    accuracy                           1.00      7500
   macro avg       1.00      1.00      1.00      7500
weighted avg       1.00      1.00      1.00      7500

test
              precision    recall  f1-score   support

         0.0       0.85      0.84      0.84      1717
         1.0       0.66      0.67      0.66       783

    accuracy                           0.79      2500
   macro avg       0.75      0.76      0.75      2500
weighted avg       0.79      0.79      0.79      2500

    - Random Forest

    Train Report
              precision    recall  f1-score   support

   malignant       1.00      1.00      1.00      5150
      benign       1.00      1.00      1.00      2350

    accuracy                           1.00      7500
   macro avg       1.00      1.00      1.00      7500
weighted avg       1.00      1.00      1.00      7500

Test Report
              precision    recall  f1-score   support

   malignant       0.86      0.88      0.87      1717
      benign       0.72      0.68      0.70       783

    accuracy                           0.82      2500
   macro avg       0.79      0.78      0.78      2500
weighted avg       0.81      0.82      0.82      2500
 


- The Final Model Chosen was a `Logistic Regression Model` with the accuracy of 88.


Using this model to help the stakeholders understand the real customer behaviors play crucial roles in predicting outcome of the insurance. .

## Recommendations

Car Insurance Outcome

-Based on speed viaolation:
  - We see that the younger the driver with less years of driving experience, the lesser the speed violation. And the older the driver with more years of driving experience, the higher the speed violation.
    
-Based on past accidents:
  - We also see that the younger the driver with less years of driving experience, the lesser the speed accidents in the past. And the older the driver with more years of driving experience, the higher the accidents in the past.
  

  

Model Performance
- Overall, the best model is definitely the Logistic Regression. 


## Limitations & Next Steps

We only used a few visuals, we could add more to have more insight about the prediction of the sales.. 

## For further information
- For any additional questions, please contact **Nombulelo Zizi**: zizinombu@gmail.com
