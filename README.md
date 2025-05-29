# Logistics-Regression
Healthy_meal_plans

graph TD
    A[Raw Data] --> B[Label Encoding]
    B --> C[SMOTE Balancing]
    C --> D[GridSearchCV Tuning]
    D --> E[Pipeline]
    E --> F[Classification Report]
    F --> G[Confusion Matrix]: 
#    - classification_report()
#    - confusion_matrix()
