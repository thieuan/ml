https://medium.com/@lachlanmiller_52885/machine-learning-week-1-cost-function-gradient-descent-and-univariate-linear-regression-8f5fe69815fd

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
![hypothesis](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/H6qTdZmYEeaagxL7xdFKxA_2f0f671110e8f7446bb2b5b2f75a8874_Screenshot-2016-10-23-20.14.58.png?expiry=1544140800000&hmac=3itbLoDtPPkQtQ9cEgFZrB9mEZgrV69goUQ70pOnG0Q)

When the target variable that we’re trying to predict is continuous, such as in our housing example, we call the learning problem a regression problem. When y can take on only a small number of discrete values (such as if, given the living area, we wanted to predict if a dwelling is a house or an apartment, say), we call it a classification problem. \
The hypothesis looks like
![hypothesis](https://cdn-images-1.medium.com/max/1600/1*XfDb8XhzTy1nVnwSy1mv6g.png)

### Cost function
We can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference (actually a fancier version of an average) of all the results of the hypothesis with inputs from x's and the actual output y's.  
One common function that is often used is mean squared error, look like  
![MSE](https://cdn-images-1.medium.com/max/1600/1*20m_U-H6EIcxlN2k07Z7oQ.png) \
We end up with:  
![hypothesis](https://cdn-images-1.medium.com/max/1600/1*VanG05Ab6yknqJ2bRGFzrQ.png)

## Parameter learning
### Gradient Descent
![gradient descent](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MYm8uqafEeaZoQ7hPZtKqg_c974c2e2953662e9578b38c7b04591ed_Screenshot-2016-11-09-09.07.04.png?expiry=1544572800000&hmac=lkM8_nytzl86xV9yKCq8qUICENKrkgiGDAPUWQoyoOk) \
*should use when number of feature > 10000
### Normal Equation
![normal equation](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dykma6dwEea3qApInhZCFg_333df5f11086fee19c4fb81bc34d5125_Screenshot-2016-11-10-10.06.16.png?expiry=1544572800000&hmac=gTlPxBM-WSm4jnO96JfBO1EiU-9IkPo9gVVoAHZ1JM4) \
*should use when number of feature < 10000
