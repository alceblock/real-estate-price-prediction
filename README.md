# real-estate-price-prediction

## Abstract

This project develops an optimized real estate price prediction engine by benchmarking three advanced regularization methods—Ridge, Lasso, and Elastic Net—to analyze how they balance market complexity and model stability.

Using a real-world housing dataset, the pipeline covers an end-to-end analytical workflow:
* **Exploratory Data Analysis & Feature Engineering:** Investigating distribution skewness and linear trends to justify preprocessing choices, implementing dummy encoding for furnishing status and quantile-based categorization for property area to maximize predictive weight.
* **Model Pipeline & Expansion:** Testing how models handle structural complexity by introducing 2nd-degree Polynomial Features, ensured by StandardScaler normalization.
* **Evaluation & Regularization Trade-offs:** Tuning hyperparameters via 5-fold Cross-Validation to benchmark the algorithms not just on raw accuracy (MSE/R²), but on their ability to manage feature weight—comparing Lasso’s aggressive feature elimination against the stability of Ridge and Elastic Net.

By validating metrics across both training and test sets and testing residual distributions, the final model effectively eliminates overfitting, maintaining high generalization while managing feature complexity.

To see more, extended explanation in the project.

