# Binary-Classifier
I  have taken just the first element of the MNIST dataset which turns out to be a 5 and used Binary Classifier to classify it as True or False. I have used Stochastic Gradient Descent to accomplish this task. So the classifier returns true if it sees 5 or False if a 5 is not present. So the second element happens to be 0 and thus it returns False. 

#Metric Calculation
A good way is to use Cross Validation to control cross_val_score. But as the dataset is skewed we will get an unexpectedly highly accuracy 93% by just prediciting 5s'. So we use a Confusion Matrix. 
                 Another way to calculate the metric is by using ROC curve. The performance metric is compared between Stochastic Gradient Descent and Random Forest Classifier. We see that we can improve more and eventually achieve a 99% accuracy score by using Random Forest Classifier whereas in case of SGD it was 96%
