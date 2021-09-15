# predicting-Yelp-star-ratings
Using Multinomial Logistic Regressions to predict star ratings for restaurants in Arizona.

**Scope:** In this analysis we compare the performance of two different multinomial logistic regression models
in predicting star ratings for restaurant businesses in Arizona. We then use the best model to
identify the most important features that contribute to higher predictive accuracy of the ratings
category. The two models are structurally the same but ther feature space is different. 
- In Model 1 feature selection is based on the multi-collinearity analysis
- In Model 2 feature selection is based on the PCA analysis.

We select the best performing model based on the out-of-sample accuracy and the class-based
comparisons of the F1 and AUC scores. The selected model is used for the interpretation of results.

We observe that Model 1 performs significantly better, and it can be considered a reliable
predictor of the star-ratings category. On the other hand, Model 2 that relies on PCA falls behind,
potentially because in PCA does not work well with categorical data.

# This repo consists of:
- A pdf report summarising the methodology and findings
- A Jupyter Notebook for data pre-processing, exploratory data analysis and correlation analysis
- Matlab code for multinomial LR analysis.
