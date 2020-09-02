# F1-Precision-and-Recall-from-Confusion-matrix---Reverse
Sometimes it might happen that we considered only precision score from the computed model. We saved the confusion matrix for multiclass, and we have calculated the precision score. However, after some time, you might be needing to calculate the Recall, and F1 score from that confusion matrix.  

It is possible to calculate through the equations. You can easily see the description of precision, recall and F1 score from this link: https://en.wikipedia.org/wiki/Precision_and_recall. However, for multiclass classification, it is often very tough to back calculate all the things.  


So in this code, I have attempted to find out a way to calculate all the measurement paramters from the confusion matrix. You just need to provide the confusion matrix to the code, and it will calculate the rest for you.

## thank you
