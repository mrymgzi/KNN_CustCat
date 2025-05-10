**CustCat dataset Analysis Using KNN Model**
In this study, customer data—including age, region, marital status, and income—has been analyzed to provide personalized service recommendations. The KNN model was used to classify customers into four service groups, but results indicate that the model performs poorly.

**Model Evaluation Results:**

Precision: Between 0.31 and 0.33, indicating weak performance in correctly identifying classes.

Recall: Ranges from 0.18 to 0.45, with class 4 showing significant weakness.

F1-score: Between 0.23 and 0.37, reflecting challenges in classification.

Overall Accuracy: 0.32, meaning only 32% of instances were correctly classified.

**Results Analysis:** 
Increasing k has minimal impact (between 0.25 and 0.40). 
After k = 38, the model stabilizes with negligible improvements. 
The model is not optimized and performs poorly even with higher k values.
