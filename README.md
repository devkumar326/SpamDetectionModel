# SpamDetectionModel
This Repository contains a ML model to detect Spam Messages.

## Develop a ML model from given dataset to classify/detect spam messages using Naive Bayes Classifier.
Accuracy of Model
~98.60%

### Procedure
1>Convert the words ham and spam from dataset to a binary indicator variable(0/1)

2>Convert the text to a sparse matrix of TFIDF vectors

3>Fit a Naive Bayes Classifier

4>Measure the accuracy using roc_auc_score

