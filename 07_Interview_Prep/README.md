# Machine Learning Interview Preparation

This section is dedicated to preparing for AI/ML Engineering, Data Science, and GenAI roles. It covers standard concepts, system design, and coding patterns.

## 1. Top Conceptual Themes
Interviews often test your intuition behind the math and algorithms.
*   **Bias-Variance Tradeoff:** Can you explain it simply? How do you fix high bias (underfitting) vs. high variance (overfitting)?
*   **Metrics:** When would you use Recall instead of Precision? (e.g., Cancer detection where false negatives are fatal). How does the ROC curve work?
*   **Algorithm specifics:**
    *   Why does Random Forest not overfit as easily as a single Decision Tree?
    *   What is the kernel trick in SVM?
    *   How does L1 (Lasso) vs L2 (Ridge) regularization work, and why does L1 lead to sparsity?
*   **Deep Learning specifics:**
    *   What causes vanishing gradients and how do ResNets fix it?
    *   Why use ReLU instead of Sigmoid in hidden layers?
    *   Explain the Self-Attention mechanism in Transformers.

## 2. ML System Design (The REQ Framework)
For senior roles, you will be asked to design end-to-end ML systems (e.g., "Design YouTube's recommendation system" or "Design a fraud detection system"). Use a structured approach:

1.  **Requirements & Metrics:**
    *   What is the business goal?
    *   Offline metrics (e.g., NDCG, log-loss, AUC) vs. Online metrics (e.g., Click-Through Rate, User Retention).
2.  **Data Formulation:**
    *   What data is available? What are the labels? 
    *   Feature engineering (e.g., User features, Item features, Context features).
3.  **Model Selection:**
    *   Start simple (e.g., Logistic Regression as a baseline).
    *   Move to complex (e.g., Two-tower neural network or Gradient Boosted Trees).
4.  **Training Data Generation:**
    *   How do you handle class imbalance? (SMOTE, downsampling).
    *   How to handle negative sampling in recommendations?
5.  **Serving & Infrastructure:**
    *   Latency constraints?
    *   Batch vs. Real-time inference.
    *   Monitoring for concept drift.

## 3. Practical Coding
*   **Pandas & Data Manipulation:** You must be fluent in data wrangling (groupby, merge, imputing missing values).
*   **Writing ML from Scratch:** Often you'll be asked to code K-Means, K-Nearest Neighbors, or Linear Regression from scratch in Python to prove you know the math.
*   **DSA:** Standard Data Structures and Algorithms (Strings, Arrays, Graphs, Trees) are still tested for ML Engineering roles.

## 4. Modern GenAI Interview Questions
*   How do you evaluate an LLM's output?
*   What is the difference between RAG and Fine-tuning? When would you use which?
*   Explain the architecture of a Vector Database and how cosine similarity works.
*   How would you reduce latency in an LLM application?
