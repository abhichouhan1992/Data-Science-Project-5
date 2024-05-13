# Spam Prediction Project
Prediction of spam on Spam-Ham dataset using Naive Bayes algorithm.
# Introduction
The spam-ham dataset consists of five thousand one hundred seventy one samples. Each sample include a Number,Label,text and Label_number. 
# Problem Domain
We have Csv file of Spam dataset and now we see There are  features in dataset , which is in numerical form and 1 label which is in categorical (string) form so we use Supervised machine learning for better prediction our model. our model doesn't take string format so we convert string format to numerical format.
# Solution Domain
For spam dataset we use Naive Bayes classifier Naive Bayes algorithm is used for classification problems.
It is highly used in text classification. In text classification tasks, data contains high dimension (as each word represent one feature in the data). It is used in spam filtering, sentiment detection, rating classification etc. The advantage of using naïve Bayes is its speed. It is fast and making prediction is easy with high dimension of data.This model predicts the probability of an instance belongs to a class with a given set of feature value. It is a probabilistic classifier. It is because it assumes that one feature in the model is independent of existence of another feature. It uses Bayes theorem in the algorithm for training and prediction.
# Technology Used
We used Jupyter Notebook for Iris dataset algorithm and also used diffent types of library from python such as numpy, pandas ,matplotlib, seaborn and Scikit-Learn.
# Mathematical Formula
Bayes’ Theorem finds the probability of an event occurring given the probability of another event that has already occurred.
Bayes’ theorem is stated mathematically as the following equation:
P(A∣B)=P(B∣A)P(A)P(B)P(A∣B)=P(B)P(B∣A)P(A)
where A and B are events and P(B) ≠ 0
Basically, we are trying to find probability of event A, given the event B is true. 
Event B is also termed as evidence.
P(A) is the priori of A (the prior probability, i.e. Probability of event before evidence is seen). 
The evidence is an attribute value of an unknown instance(here, it is event B).
P(B) is Marginal Probability: Probability of Evidence.
P(A|B) is a posteriori probability of B, i.e. probability of event after evidence is seen.
P(B|A) is Likelihood probability i.e the likelihood that a hypothesis will come true based on the evidence.
# Conclusion
For this project, I mainly worked through the Python documentation manuals of the Pandas, Matplotlib and Seaborn modules as well as the Python 3 documentation. There are many resources freely available for learning how to use Python and applying it to analysing datasets such as the Spam dataset. The pandas library is quite intuitive and in a valuable tool in investigating and analysing multi-class multi-variates datasets such as the Spam dataset. I looked at the statistical properties of the Spam data set in this project. Visualising the data gives a better understanding of the data and what can be done with it.
The Spam data set is referenced quite a bit in machine learning(Specially for Naive Bayes), and many resources on the internet use it to demonstrate their product or to teach machine learning methods.We used Scikit-Learn library to implement better prediction of model.
