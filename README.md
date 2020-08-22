# Credit-Risk
#Challenge
For the Random Oversampling method, the balanced accuracy score is 0.69. For high risk customers, the precision score is 0.01, which means the model will predict a lot of low risk as high risk customers. The recall score is 0.77 and the f1 score is 0.02, which means it can detect 77% of the high risk customers. For low risk customers, the precision score is high 1.0, which can predict the low risk customers correctly. The recall score is 0.6 and the f1 score is 0.75, which is low and cannot detect most low risk customers.

For the SMOTE Oversampling method, the balanced accuracy score is 0.66. For high risk customers, the precision score for high risk customers is 0.01, which means the model will predict a lot of low risk as high risk customers. The recall score is 0.63 and the f1 score is 0.02, which means it can detect 63% of the high risk customers. For low risk customers, the precision score is high, 1.0, which can predict the low risk customers correctly. The recall score is 0.69 and the f1 score is 0.82, which is low and cannot detect most low risk customers.

For the Undersampling method, the balanced accuracy score is 0.55. For high risk customers, the precision score is 0.01, which means the model will predict a lot of low risk as high risk customers. The recall score is 0.68 and the f1 score is 0.01, which means it can detect 68% of the high risk customers. For low risk customers, the precision score is high, 1.0, which can predict the low risk customers correctly. The recall score is 0.41 and the f1 score is 0.58, which is low and cannot detect most low risk customers.

For the Combination sampling method, the balanced accuracy score is 0.64. For high risk customers, the precision score for high risk customers is 0.01, which means the model will predict a lot of low risk as high risk customers. The recall score is 0.72 and the f1 score is 0.02, which means it can detect 68% of the high risk customers. For low risk customers, the precision score is high, 1.0, which can predict the low risk customers correctly. The recall score for is 0.57 and the f1 score is 0.72, which is low and cannot detect most low risk customers.

Among all the four sampling methods, the random oversampling method provides the highest accuracy score and the recall score for high risk customers. However, I do not recommend any of these four methods since all provide low precision score for the high risk customers. These methods will false predict a lot of low risk customers as high risk ones. More data or other model parameters will be needed to create a better model.
