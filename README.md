Name: Mythreya Grandhe

Id: 700757164

Video link: https://drive.google.com/file/d/1zo4Z3Qx0wZ1-bX9dfzkMUJgt9N7b6GC_/view?usp=drive_link

Implement Naïve Bayes method using scikit-learn library Use dataset available with name glass Use train_test_split to create training and testing part Evaluate the model on test part using score and classification_report(y_true, y_pred)

Implement linear SVM method using scikit library Use the same dataset above Use train_test_split to create training and testing part Evaluate the model on test part using score and classification_report(y_true, y_pred)

Which algorithm you got better accuracy? Can you justify why?

In summary, SVM outperforms Naïve Bayes in terms of accuracy and performance across various evaluation metrics, indicating its suitability for this dataset. This could be attributed to SVM's capability to capture intricate relationships and manage class imbalances better than Naïve Bayes.

This assertion is supported by the following evaluations:

1.	Precision, Recall, and F1-Score: SVM consistently demonstrates higher precision, recall, and F1-scores across multiple classes compared to Naïve Bayes. Naïve Bayes exhibits lower performance, particularly in recall for certain classes.
	
2. Class Imbalance: The dataset likely contains class imbalances, which adversely affect Naïve Bayes due to its assumption of feature independence. SVM, being less reliant on this assumption, tends to perform better under such circumstances.
 
3. Model Complexity: SVM, particularly with a linear kernel, is more adept at capturing the underlying data relationships, especially if the decision boundary isn't strictly linear.
 	
4. Handling of Class 3: Naïve Bayes predicts class 3 with precision, recall, and F1-scores of 0.40, 0.67, and 0.50 respectively. However, SVM struggles with class 3, yielding precision, recall, and F1-scores of 0.00, 0.00, and 0.00. This significant discrepancy could have a notable impact on overall performance
