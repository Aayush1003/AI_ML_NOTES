# Traditional Machine Learning

This section covers the core algorithms that formed the foundation of modern AI before the deep learning boom.

## 1. Supervised Learning
Learning from labeled data (input-output pairs).

*   **Regression (Predicting Continuous Values):**
    *   Linear Regression
    *   Polynomial Regression
    *   Ridge & Lasso Regression (Regularization)
*   **Classification (Predicting Categories):**
    *   Logistic Regression
    *   K-Nearest Neighbors (KNN)
    *   Support Vector Machines (SVM)
    *   Decision Trees & Naive Bayes

## 2. Unsupervised Learning
Finding patterns in unlabeled data.

*   **Clustering:**
    *   K-Means Clustering
    *   Hierarchical Clustering
    *   DBSCAN
*   **Dimensionality Reduction:**
    *   Principal Component Analysis (PCA)
    *   t-SNE / UMAP (for visualization)

## 3. Ensemble Methods
Combining multiple weak models to create a strong one. These dominate traditional tabular data competitions (like Kaggle).

*   **Bagging:** Random Forests
*   **Boosting:** AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost.

## 4. Model Evaluation & Lifecycle
*   **Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC curve (Classification). MSE, RMSE, MAE, R-Squared (Regression).
*   **Trade-offs:** Bias-Variance Tradeoff (Underfitting vs. Overfitting).
*   **Validation:** K-Fold Cross Validation, Train/Test/Validation splits.
*   **Hyperparameter Tuning:** Grid Search, Random Search, Bayesian Optimization.
