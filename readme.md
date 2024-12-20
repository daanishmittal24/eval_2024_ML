# Model Performance Comparison

In this project, various regression models were evaluated to predict the target variable. Below are the models tested along with their respective scores for evaluation:

| Model                         | Score (R²)  | Score (RMSE) |
|-------------------------------|-------------|--------------|
| Linear Regression              | 4.899193    | -0.016989    |
| Ridge Regression               | 4.895903    | -0.016307    |
| Lasso Regression               | 4.935546    | -0.024536    |
| Random Forest Regressor        | 5.077443    | -0.053991    |
| Gradient Boosting Regressor    | 5.443308    | -0.129939    |
| Support Vector Regressor       | 4.937407    | -0.024922    |
| K-Nearest Neighbors Regressor  | 5.865306    | -0.217538    |

## Best Performing Model

Based on the results above, the **K-Nearest Neighbors Regressor** has the highest R² score (5.865306) and also has the lowest RMSE value (-0.217538). This suggests that the K-Nearest Neighbors Regressor provides the most accurate predictions among the models tested.

## Other Notable Models

- **Gradient Boosting Regressor** performed well with an R² score of 5.443308, though it did have a higher RMSE (-0.129939) compared to K-Nearest Neighbors.
- **Random Forest Regressor** also showed strong performance with an R² of 5.077443.
