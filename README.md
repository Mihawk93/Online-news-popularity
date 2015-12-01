# Online-news-popularity
As a part of Automated Learning and Data Analysis in R, we have implemented SVM, ANN and Naive Bayes to predict the popularity of the news article using the dataset from UCI's Machine Learning repository. Using KL measure, we have tried to estimate the most important features in the dataset. We have also tried to suggest changes in the news article to make it popular using KNN.

Run main.R to run the program as whole.

We have created the following files:

1) main.R - calls all other files
2) sampling.R - This file samples the data
3) ann.R      - This file transforms the data which is passed to ANN
4) svm.R      - This file transforms the data and applies SVM technique on the data
5) nb.R       - This file transforms the data and applies Naive Bayes to the data
6) kl.R       - This file implements KL measure to weigh each feature and find their importance
7) suggest.R  - A very simple approach using KNN has been used to suggest the changes to improve the popularity of the article
