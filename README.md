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
    - Linear Regression Model
    - Decision Tree Regressor Model
    - Tuned Decision Tree Regressor Model
    - Random Forest Regressor Model
    - Tuned Random Forest Regressor Model
    
    
## Models Evaluated & Results

- Linear Regression Model (Testing Set):
  - MAE = 803.687
  - MSE = 1,187,857.066
  - RMSE = 1,089.889
  - R^2 = 0.569
    
- Decision Tree Regressor Model (Testing Set):
  - MAE = 1,039.842
  - MSE = 2,229,380.534
  - RMSE = 1,493.111
  - R^2 = 0.192
    
- Tuned Decision Tree Regressor Model (Testing Set):
  - MAE = 738.203
  - MSE = 1,118,036.621
  - RMSE = 1,057.373
  - R^2 = 0.595

- Random Forest Regressor Model (Testing Set):
  - MAE = 772.198
  - MSE = 1,228,760.100
  - RMSE = 1,108.495
  - R^2 = 0.555

- Tuned Random Forest Regressor Model (Testing Set):
  - MAE = 728.683
  - MSE = 1,097,379.432
  - RMSE = 1,047.559
  - R^2 = 0.602


- The Final Model Chosen was a `Random Forest Regressor Model` with the n_estimators tuned to 60.
- For the testing set on the model, `60.02%` of the variance in y was explained by x. 
- The Mean Absolute Error was off by about `$728.683`.
- The Mean Squared Error was `$1,097,379.432`.
- The Root Mean Squared Error had a calculation of `$1,074.559`.

Using this model to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. Considering the previous regression metrics from how the model performed, there is a disparity between the R^2 score and also the Root Mean Squared Error that cannot be ignored.

## Recommendations

Sales Predictions

- For those who are interest based on Item type:
  - Fruits and vegatables appears more than  other item types.
    
- For those who are interest based on outlet type:
  - Suppermarket Type1 is the most outlet type.
  
- For those who are interest based on location type:
  - Tier 3 is the most location type.
  

Model Performance
- Overall, the best model is definitely the tuned Random Forest Regressor Model. 


## Limitations & Next Steps

We only used a few visuals, we could add more to have more insight about the prediction of the sales.. 

## For further information
- For any additional questions, please contact **Nombulelo Zizi**: zizinombu@gmail.com
