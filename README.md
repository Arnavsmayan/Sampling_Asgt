# Sampling_Asgt

| Sampling Method     | Random Forest | Logistic Regression | Decision Tree | KNN   | SVM   |
|---------------------|---------------|----------------------|---------------|-------|-------|
| Random Sampling     | **0.9902**    | 0.9020               | **0.9706**    | 0.8170| 0.6569|
| Stratified Sampling | 0.9935        | 0.9052               | 0.9641        | 0.8268| 0.6536|
| Cluster Sampling    | 0.9935        | 0.9052               | 0.9641        | 0.8268| 0.6536|
| Systematic Sampling | 0.9935        | 0.9052               | 0.9641        | 0.8268| 0.6536|
| Bootstrap Sampling  | 0.9935        | **0.9183**           | 0.9608        | **0.8333**| **0.6830**|

- **Random Forest**: The best sampling method is **Random Sampling** with an accuracy of 0.9902.
- **Logistic Regression**: The best sampling method is **Bootstrap Sampling** with an accuracy of 0.9183.
- **Decision Tree**: The best sampling method is **Random Sampling** with an accuracy of 0.9706.
- **KNN**: The best sampling method is **Bootstrap Sampling** with an accuracy of 0.8333.
- **SVM**: The best sampling method is **Bootstrap Sampling** with an accuracy of 0.6830.
