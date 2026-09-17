# real-estate-price-prediction

This project develops an optimized real estate price prediction engine by benchmarking three advanced regularization methods: Ridge, Lasso, and Elastic Net. 

Using a real-world housing dataset, the pipeline covers the complete machine learning workflow:
* **Feature Engineering:** Dummy encoding for categorical variables (furnishing status) and quantile-based categorization for property area to maximize predictive weight.
* **Model Pipeline:** 2nd-degree Polynomial Features transformation followed by StandardScaler normalization.
* **Evaluation:** Hyperparameter tuning via 5-fold Cross-Validation, comparative analysis of MSE/R² metrics on both training and test sets, and residual distribution testing.

The final model effectively eliminates overfitting, maintaining high generalization stability on unseen data while managing feature complexity.

To see more, extended explanation in the project.
