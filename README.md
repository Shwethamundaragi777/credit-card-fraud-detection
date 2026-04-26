Credit Card Fraud Detection

Objective
The objective of this project is to detect fraudulent credit card transactions using machine learning techniques and improve the identification of suspicious activities.

---

Tools & Technologies
- Python  
- pandas  
- scikit-learn  
- matplotlib  

---

Approach
The project was completed using the following steps:

- Performed data cleaning and preprocessing  
- Handled categorical variables using encoding techniques  
- Split the dataset into training and testing sets  
- Built machine learning models:
- Logistic Regression  
- Random Forest  
- Evaluated model performance using classification metrics  

---

Key Insights
- The dataset was highly imbalanced (very few fraud cases)  
- Accuracy alone was misleading for evaluating performance  
- Logistic Regression showed high accuracy but poor fraud detection  
- Random Forest improved the detection of fraudulent transactions  
- Recall is a critical metric for fraud detection  

---

Results
- Achieved high overall accuracy  
- Improved fraud detection performance using Random Forest  
- Better balance between precision and recall compared to initial model  

---

Conclusion
This project demonstrated that high accuracy does not necessarily indicate effective fraud detection due to class imbalance. While initial models performed well on normal transactions, they failed to detect many fraudulent cases. By applying Random Forest and focusing on evaluation metrics such as recall and confusion matrix, the model improved its ability to identify fraud. This highlights the importance of selecting appropriate models and evaluation metrics in real-world fraud detection systems.

---

Future Improvements
- Apply techniques like SMOTE to handle class imbalance  
- Try advanced models like XGBoost  
- Perform hyperparameter tuning for better performance  
- Deploy the model as a simple web application  


