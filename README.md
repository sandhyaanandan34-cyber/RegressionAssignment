# Regression Assignment
<u>Overview</u>
The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset.

Preprocessing Steps:

Ensure data consistency and integrity before proceeding with analysis.
Added checks for missing values and fetching datatypes of specific columns to make sure the data is consistant.

<h3>Findings</h3>
<h4><u>- Best Performing → Gradient Boosting Regressor</u></h4>

Lowest MSE and MAE, highest R².
Sequential boosting captures subtle non-linear patterns in housing data.
Handles feature interactions (income, rooms, population) very effectively

<h4><u>- Worst Performing → Linear Regression</u></h4>

Struggles with non-linear relationships in housing data.
Provides interpretability but sacrifices accuracy
