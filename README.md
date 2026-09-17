# real-estate-price-prediction

## Abstract

This project focuses on the engineering and analytical reasoning required to build a reliable real estate price prediction engine. Rather than relying on simple linear metrics, the core objective is to analyze how different regularization strategies—Ridge, Lasso, and Elastic Net—react to expanded feature complexity while preventing overfitting.

The pipeline is driven by an end-to-end analytical workflow:
* **Exploratory Data Analysis:** Investigating distribution skewness and linear trends to evaluate whether target transformations or structural feature categorization (such as grouping house areas) yield better predictive performance.
* **Pipeline Expansion:** Testing how models handle complexity by introducing 2nd-degree polynomial interactions, ensuring data normalization through rigorous scaling.
* **Regularization & Complexity Trade-offs:** Benchmarking the algorithms not just on raw accuracy, but on their ability to manage feature weight—evaluating Lasso’s aggressive feature elimination against the predictive stability of Ridge and Elastic Net.

By validating the results through 5-fold cross-validation and analyzing the adequacy of residual distributions, the project demonstrates a thorough decision-making process to ensure high model generalization on unseen data.

To see more, extended explanation in the project.

