# Logistics-Regression
Healthy_meal_plans

## ML Workflow
```mermaid
graph TD
    A[Raw Data] --> B[Label Encoding]
    B --> C[SMOTE Balancing]
    C --> D[GridSearchCV Tuning]
    D --> E[Pipeline]
    E --> F[Classification Report]
    F --> G[Confusion Matrix]
