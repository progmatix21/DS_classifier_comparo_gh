# Comparison of classifiers

## Logistic Regression

Logistic Regression is a type of binary classifier whose characteristic can be expressed in the form of a sigmoid curve.

The logistic regression model is used in places where there is a chance of a binary event occuring. Typical examples are predicting whether an email is spam, predicting whether a bank transaction is fraudulent. Logistic Regression is also used in predicting "Yes" and "No" outcomes.

Logistic Regression is easier to implement compared to the other models. It works best when the
dependent and independent variables have a linear relationship.  This is also a disadvantage
because rarely do we find such linear relationships in real life.

## Naive Bayes

Naive Bayes classifier is a simple classifier based on the principle of the Naive Bayes theorem. The Bayes theorem finds out the probability of an event ocurring given the probability of another event occuring. Classification is done on one or more class labels.

Naive Bayes classifiers are used in multilabel or multiclass operations such as playing a sport based on various conditions such as Weather, Wind, Temperature. Predictions are based on finding the conditional probability of playing the sport based on the given conditions. 

Naive Bayes gives a different perspective of solving the problem. We can take any number of class labels for doing our predictions as compared to a binary classifier which can take only two. The other advantages are usage of categorical variables mostly rather than continuous variables. This classifier works best for text classification and spam detection.

The word 'naive' comes from the assumption that the features are unrelated. However, this is rarely the case in the real world.



## kNN

kNN is a clustering algorithm used for classification. kNN can be expanded as k Nearest Neighbour algorithm. It classifies a particular point based on the k closest points in its neighbourhood.  

This algorithm is easy to understand and interpret. It can be used for classification as well as regression. It has high accuracy, but there are even better algorithms compard to kNN.

It is computationally expensive because it stores all the training data. It is very sensitive to scale of data and irrelevant features.

kNN has extensive use in the banking system. kNN can be used in the banking system to decide whether a loan applicant is suitable for granting a loan and if he/she is sufficiently different from typical loan defaulters. kNN can also be used to estimate a person's credit rating by comparing him/her to similar persons.

Another interesting use of kNN is predicting voter behaviour. For example, people who vote or don't vote have similar traits. Apart from these, there are applications for knn in Speech Recognition, Handwriting Detection, Image Recognition and Video Recognition.


## Conclusion

There are two ways we can compare the classifiers. 

Comparing the ROC curves, Logistic Regression has the best AUC and hence scores better than the other two classifiers. 

Comparing the confusion matrix of the classifiers, Logistic Regression scores again because it has better precision and recall. 











