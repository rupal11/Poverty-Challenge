# Poverty-Challenge

Sustainable Development Goal Solved: **No Poverty**

---- Information from driven data ----

The data for this project comes from The World Bank Development Data Group.

With funding from the World Bank's Knowledge for Change Program, this project aims to engage data scientists from developing countries and apply a cost-effective solution to testing a diverse set of approaches to poverty prediction.

The surveys used to come from three developing countries. Each country offers a different demographic makeup, so successful poverty prediction across these countries will help identify a robust set of predictors that can be used in future poverty measurement efforts.

--- Data Preprocessing ---

    Standardization
    Encoding
    Column Enforcement in train and test set
    Replacing missing values

--- Sampling ---

SMOTE

---- Dimensionality Reduction ---

    SVD
    PCA

--- Algorithm Experimented ---

    Random Forest
    Logistic Regression
    AdaBoost Classifier
    Gradient Boosting
    Decision Tree
    Gaussian NB
    Extra Tree Classifier
    XGBoost

--- Winning Algorithm ---

XGBoost without any sampling or dimensionality reduction.
