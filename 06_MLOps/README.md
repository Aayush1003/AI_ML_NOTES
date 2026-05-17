# MLOps (Machine Learning Operations)

MLOps is the intersection of Machine Learning, DevOps, and Data Engineering. It aims to deploy and maintain ML systems in production reliably and efficiently.

## 1. Model Serving & Deployment
Once a model is trained, it needs to be accessible to applications.
*   **APIs:** Wrapping the model in a REST API using Flask or FastAPI (Python).
*   **Containerization:** Packaging the app and model dependencies using Docker.
*   **Orchestration:** Using Kubernetes to scale the model across multiple servers based on traffic.
*   **Inference Types:** Batch Inference (running predictions on a schedule) vs. Real-time Inference (predicting immediately on user request).

## 2. Model Tracking & Registry
Tracking experiments to ensure reproducibility.
*   **Tools:** MLflow, Weights & Biases (W&B).
*   **What is tracked:** Hyperparameters, Metrics (Loss, Accuracy), Datasets used, and the Model Artifacts (.pkl or .h5 files).
*   **Model Registry:** A central repository to manage model versions (Staging -> Production -> Archived).

## 3. CI/CD for ML (CT - Continuous Training)
Standard code has CI/CD (Continuous Integration/Continuous Deployment). ML adds Continuous Training.
*   **Data Drift:** When the statistical properties of the input data change over time.
*   **Concept Drift:** When the relationship between input and output changes (e.g., consumer behavior changes during a pandemic).
*   **Automated Retraining Pipelines:** Using tools like Apache Airflow or Kubeflow to automatically retrain the model when drift is detected.

## 4. Cloud ML Platforms
Major cloud providers offer end-to-end MLOps platforms:
*   AWS SageMaker
*   Azure Machine Learning
*   Google Cloud Vertex AI
