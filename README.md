# Boston Housing Analysis
## Project Overview
In this project, we analyze the Boston Housing dataset to predict median
housing prices using various regression models. The goal is to evaluate
the relationship between different features and housing prices and to
identify the best model for predicting prices.
## Dataset
The Boston Housing dataset contains 13 features and the target variable MEDV ( median value of homes ) . 
Other features are: 
CRIM ( crime rate )
RM ( average number of rooms )
LSTAT ( percentage of lower-status population )
ZN( Proportion of residential land zoned for lots larger than 25,000 square feet.)
INDUS( Proportion of non-retail business acres per town.)
CHAS (Charles River dummy variable (1 if tract bounds river; 0 otherwise).)
NOX( Nitric oxide concentration (parts per 10 million).)
AGE( Proportion of owner-occupied units built before 1940.)
DIS( Weighted distances to five Boston employment centers.)
RAD(Index of accessibility to radial highways)
TAX( Full-value property tax rate per 10, 000)
PTRATIO( Pupil-teacher ratio by town)

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
| Lasso Regression | 0 . 50 | 0.64 |
| Decision Tree Regressor | 0 . 04 | 0.73 |
| Random Forest | 0 . 02 | 0. 84 |
** Best Model **: Random forest regressor, with the lowest MSE and highest R - squared.
## Visualizations
![ Scatter Plot ]( images / scatter_plot . png )
* Figure 1: Scatter plot showing the relationship between RM ( average
number of rooms ) and MEDV ( housing prices ) .*

![Alt Text](relative/path/to/image.png)


## Reflection and Insights
During the project, the RandomForest Regressor performed best due to its
ability to handle complex relationships between features. One key
finding was the strong positive correlation between RM and MEDV, while
LSTAT had a negative correlation with housing prices.
## Next Steps
- 
