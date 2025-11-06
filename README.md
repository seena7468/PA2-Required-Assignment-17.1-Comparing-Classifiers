# Comparing-Classifiers

Jupyter NoteBook link - 

### Business Objective:

The goal is to use historical data from previous marketing campaigns to build a predictive model that helps the bank efficiently target clients who are most likely to respond positively (i.e., subscribe to a term deposit). By accurately predicting client responses, the bank can:

- Increase the success rate of marketing campaigns
-  Optimize resource allocation (e.g., focus efforts on high-probability clients)
-  Reduce costs associated with unsuccessful contacts
-  Improve customer satisfaction by targeting relevant offers

Predict which clients will subscribe to a term deposit, enabling the bank to improve the effectiveness and efficiency of future marketing campaigns.

### Findings:
**Evaluation of Results and Business Implications**

- Accuracy: All models have similar test accuracy, around 88%. Decision Tree has the highest train accuracy (91%) but the lowest test accuracy (87.18%), suggesting some overfitting. Logistic Regression and SVM have identical train and test accuracy, indicating stable performance. KNN is fast but has slightly lower test accuracy.
- Train Time: KNN and Decision Tree are extremely fast to train. Logistic Regression is reasonably fast. SVM is much slower (over 25 seconds), which may be a concern for large datasets or frequent retraining.
- Effectiveness: KNN and Decision Tree are highly efficient for rapid deployment or frequent model updates. Logistic Regression is also efficient and interpretable. SVM is much slower to train, which may limit its practicality for large-scale or real-time applications.
- Efficiency: KNN and Decision Tree are highly efficient for rapid deployment or frequent model updates. Logistic Regression is also efficient and interpretable.SVM is much slower to train, which may limit its practicality for large-scale or real-time applications.
- Interpretability: Logistic Regression and Decision Tree are easier to explain to stakeholders, which is valuable in banking for regulatory compliance and business trust. SVM and KNN are less interpretable.
- Scalability: SVM’s long training time may be a bottleneck to retrain often or scale to larger datasets.

  
**Recommendation for Business Proposal Based on the results** - For improving the effectiveness and efficiency of future marketing campaigns, Logistic Regression provides the best balance of accuracy, speed, and interpretability. It will enable the bank to reliably identify clients most likely to subscribe to term deposits, optimize marketing efforts, and maintain transparency for business and regulatory needs.

### Data:
Dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns.
