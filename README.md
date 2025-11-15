# cocoa-bean-analysis
# Computational Statistics: Cocoa Bean Analysis

This is an individual project(Computational Statistics) 

### [Click here for the full PDF report](./STA457_project.pdf)
### [Click here for the R code output](./STA457proj_outpit.pdf)

---

## 1. Project Goal

The goal of this project was to analyze a high-dimensional cocoa bean dataset. The dataset had more chemical features (p) than samples (n), making standard regression unsuitable.

The main objectives were:
* To identify the key chemical properties (e.g., Lactic acid, Acetic acid) that best predict cocoa bean flavour scores.
* To apply and compare advanced regression models (Ridge, LASSO, Elastic Net) designed for high-dimensional data.
* To use Bootstrap resampling to construct robust confidence intervals for the model coefficients.

## 2. Technical Stack

* **Programming Language:** `R`
* **Key Packages:** `glmnet` (for Ridge/LASSO/Elastic Net), `boot` (for Bootstrap)
* **Key Statistical Methods:**
    * Ridge Regression
    * LASSO Regression
    * Elastic Net
    * Bootstrap Resampling
    * Feature Selection

## 3. Key Findings & Results

* The Elastic Net model was selected as the best-performing model for this dataset, providing a good balance between the feature selection of LASSO and the coefficient handling of Ridge.
* The Bootstrap analysis provided stable 95% confidence intervals for the coefficients of the final model, confirming the significance of key predictors.
* This project successfully demonstrated the application of advanced computational statistics to solve a complex, high-dimensional problem.
