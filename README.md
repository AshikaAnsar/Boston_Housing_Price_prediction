# Boston Housing Analysis
## Project Overview
In this project , we analyze the Boston Housing dataset to predict median
housing prices using various regression models . The goal is to evaluate
the relationship between different features and housing prices , and to
identify the best model for predicting prices .
## Dataset
The Boston Housing dataset contains 13 features and the target variable ,
MEDV ( median value of homes ) . Other features are CRIM ( crime rate ) ,
RM ( average number of rooms ) , and LSTAT ( percentage of lower - status
population ), ZN, INDUS, CHAS, NOX, AGE, DIS, RAD, TAX, and PTRATIO 

## Steps
1. Exploratory Data Analysis ( EDA )
2. Data Preprocessing
3. Building Linear Regression and other regression models
4. Comparing model performance
## Results
| Model | MSE | R - squared |
| - - - - - - - - - - - - - - - - - - - - - -| - - - - - - -| - - - - - - - - - - -|
| Linear Regression | 0 . 03 | 0. 78 |
| Ridge Regression | 0 . 03 | 0. 78 |
| Lasso Regression | 0 . 56 | -3. 03 |
| Decision Tree | 0 . 86 | -5. 18 |
| Random Forest | 0 . 55 | -2. 96 |
** Best Model **: Linear Regression & Ridge Regression , with the lowest MSE and highest R - squared .
## Visualizations
![ Scatter Plot ]( images / scatter_plot . png )
* Figure 1: Scatter plot showing the relationship between RM ( average
number of rooms ) and MEDV ( housing prices ) .*



## Reflection and Insights
During the project , the Linear Regression & Ridge Regression performed best due to its
ability to handle complex relationships between features . One key
finding was the strong positive correlation between RM and MEDV , while
LSTAT had a negative correlation with housing prices .
## Next Steps
- 