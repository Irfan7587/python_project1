# MLP for Multi-Vehicle Accident Prediction 
## Implemented by: Mohammed Irfan Battegeri 
Objective: Predict whether an accident involves multiple vehicles. 
Key Steps: 
1. Feature Selection: 
o Correlation analysis and Chi-Square tests to identify significant features. 
o Features included weather conditions, light conditions, and number of 
casualties. 
2. Class Imbalance Handling: 
o Applied ADASYN oversampling to balance the dataset. 
3. Fine-Tuning: 
o Experimented with hyperparameter tuning, additional dropout layers, and 
increased MLP depth. 
o Added early stopping to prevent overfitting. 
o Adjusted classification thresholds (optimal: 0.44) to improve recall for 
minority classes. 
4. Results: 
o Accuracy: 74.3% 
o Precision-Recall AUC: 91.2% 
o Observations: 
ADASYN significantly improved recall for the minority class (single-vehicle accidents).
