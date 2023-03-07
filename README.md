# Zomato-Cost-Prediction
#Zomato-Cost-Prediction
Supervised Learning - Regression


Project Objective:
To develop a predictive model that estimates the cost for two guests at a time, so that recently opened and prospective restaurants will know how much money to invest in other stuff like ambiance and customer service

Data:
The data used in this project is a dataset containing features related to newly opened restaurants. The dataset has 51717 observations and 17 variables and the data is extremely unclean.  The data is preprocessed to handle missing values and categorical features.

Methods:
• Random Forest Algorithms: This algorithm can be used for both regression and classification tasks. RandomForest Regressor combines multiple decision trees to improve accuracy and reduce overfitting.

• Decision Tree: This algorithm can be used for both regression and classification tasks. Decision Tree Regressor is a decision-making tool that uses a tree-like model of decisions and their possible consequences.

• Logistic Regression: This is an algorithm used only for classification problems. It finds a linear equation that best describes the correlation of the explanatory variables with the dependent variable. This is achieved by fitting a line to the data using least squares.

• Regularization: Regularized regression is a regression method with an additional constraint designed to deal with a large number of independent variables (a.k.a. predictors). It does so by imposing a larger penalty on unimportant ones, thus shrinking their coefficients towards zero. Lasso,Ridge and Elasticnet are used. The only difference between Lasso and Ridge is that Ridge converges faster, while Lasso is more commonly used for feature selection.Elastinethis method is a combination of the previous two approaches

Conclusion:
The model's performance will be evaluated using R2_score on the test set. The results will be compared to a baseline model and other models in the literature. The resulting model will help the newly opened restaurants and cafes with identifying the approximate cost for two people based on the various features they have provided about the restaurants. This will give a clear idea to the owners on to how well to make the investment into other aspects. 
