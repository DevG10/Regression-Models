# Regression-Models

## Ridge Regression:
Ridge regression is a type of linear regression that addresses multicollinearity (correlations among predictors) and overfitting issues in the model. It does this by adding a penalty term to the linear regression cost function, which discourages large coefficients for the predictors. This regularization technique helps prevent the model from becoming too complex and provides a more stable and interpretable solution, especially when dealing with datasets with high dimensionality.

## Lasso Regression:
Lasso regression, similar to Ridge regression, is a type of linear regression that also addresses multicollinearity and overfitting. Lasso regression adds a penalty term to the linear regression cost function, but unlike Ridge, Lasso uses an L1 regularization term. Lasso regularization encourages sparsity in the model by forcing some of the coefficients to be exactly zero. This property makes Lasso useful for feature selection, where it automatically selects a subset of relevant features, making the model simpler and potentially improving its generalization performance. It is mostly used for Feature Selection.

## Elastic Net Regression:
Elastic Net regression is a hybrid regularization technique that combines both L1 (Lasso) and L2 (Ridge) regularization terms in the linear regression cost function. Elastic Net is beneficial when dealing with datasets where multiple features are correlated. It balances the advantages of Lasso regression's feature selection and Ridge regression's stability by finding a middle ground. Elastic Net is particularly useful when there are many features and some of them are highly correlated, providing a more robust and generalizable model compared to using Lasso or Ridge regression alone.
