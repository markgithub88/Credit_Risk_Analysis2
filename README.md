# Credit_Risk_Analysis2

# Deliverable 4: Written Report on the Credit Risk Analysis

Overview. I think the overall theme is, “How do we save money, AND keep the data accurate, too?”  This is add/deleting columns b/c that’s money.  After sorting the features in the challenge, it appears that anything below num_op_rev_tl : ( 0.00997151296328166 ) is useless and could be removed.  That would save money.

This module and challenge are also all about finding the balance and accuracy.  Overall, what we did in this module is tune and sift the dataset and look at scores.  The question we ask ourselves, Is there a good fit for the model?

![image](https://user-images.githubusercontent.com/115684964/221448616-546f6f77-e6a9-4e47-a160-4c6a7dbd6437.png)


Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
Describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

These are the six machine learning models.
1.	Logistic regression with oversampling.  
a.	Generally, oversampling is used when the amount of data collected is insufficient.  
b.	SMOTE; synthetic Minority Over sampling Technique  is used here and randomly samples the minority class.
![image](https://user-images.githubusercontent.com/115684964/221448661-77bd7645-f077-40df-a938-518f0400aa30.png)

2.	Logistic regression with smote oversampling.  See # 1
3.	Logistic regression with Undersampling
a.	Undersampling tries to balance uneven datasets by keeping all the data in the minority class and decreasing the majority class size.

![image](https://user-images.githubusercontent.com/115684964/221448692-42f4aa37-9871-4b8b-93b5-9ae2049dc5cb.png)

4.	Logistic regression with oversampling and under.
a.	We used the combination method to further sift the data. We duplicated the smaller class and deleted some from the bigger class

![image](https://user-images.githubusercontent.com/115684964/221448712-4b97635b-6dfc-4173-8253-99fde8517f49.png)

5.	Balanced Random Forest Classifier
a.	We increased the number of features - n_estimators=100 
![image](https://user-images.githubusercontent.com/115684964/221448732-44298048-d690-466c-97db-4ca4fd621600.png)

6.	Easy Ensemble AdaBoost Classifier
a.	Ensemble combined all the weak classifiers into one group and call that group a strong classifier.
![image](https://user-images.githubusercontent.com/115684964/221448751-ba2f24d5-ac40-4fae-a404-6194b05916e4.png)

# Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.








































