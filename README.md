# Concrete-Compressive-Strength


This is a classical regression case in which the concrete compressive strngth is predicted based on different process parameters.

### Dataset

https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength

Number of instances 1030

Number of Attributes 9

Attribute breakdown 8 quantitative input variables, and 1 quantitative output variable




### Name -- Data Type -- Measurement -- Description

Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable

Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable

Fly Ash (component 3) -- quantitative -- kg in a m3 mixture -- Input Variable

Water (component 4) -- quantitative -- kg in a m3 mixture -- Input Variable

Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable

Coarse Aggregate (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable

Fine Aggregate (component 7) -- quantitative -- kg in a m3 mixture -- Input Variable

Age -- quantitative -- Day (1~365) -- Input Variable

Concrete compressive strength -- quantitative -- MPa -- Output Variable


The following algorithms were used calculate RMSE and R2 metrics

(1) Linear Regression

(2) Ridge Regression (L2 Penalty)

(3) Lasso Regression (L1 Penalty)

(4) KNN

(5) Decision Tree

(6) Random Forest Regressor

(7) Gradient Boosing Regressor

(8) Adaboost Regressor

(9) Neural Network ( Work in progress)


So far, Gradient Boosting seems to be the best option with R2 = 0.90 and RMSE = 5.3





