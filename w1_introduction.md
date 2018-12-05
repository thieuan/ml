## Modern definition:  
"A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."

## Supervised learning:
we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output  
- Regression: predict results within a continuous output, meaning that we are trying to map input variables to some continuous function.  
- Classification: predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.  

## Unsupervised Learning:  
Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.  

We can derive this structure by clustering the data based on relationships among the variables in the data.  

With unsupervised learning there is no feedback based on the prediction results.  
- Clustering

## Model and cost function
### Model Representation
To describe the supervised learning problem slightly more formally, our goal is, given a training set, to learn a function h : X → Y so that h(x) is a “good” predictor for the corresponding value of y. For historical reasons, this function h is called a hypothesis. Seen pictorially, the process is therefore like this:  
![hepothesis](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/H6qTdZmYEeaagxL7xdFKxA_2f0f671110e8f7446bb2b5b2f75a8874_Screenshot-2016-10-23-20.14.58.png?expiry=1544140800000&hmac=3itbLoDtPPkQtQ9cEgFZrB9mEZgrV69goUQ70pOnG0Q)

When the target variable that we’re trying to predict is continuous, such as in our housing example, we call the learning problem a regression problem. When y can take on only a small number of discrete values (such as if, given the living area, we wanted to predict if a dwelling is a house or an apartment, say), we call it a classification problem.

