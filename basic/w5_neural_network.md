## Neural network
### Training a neural network
1. Randomly initialize the weights  
2. Implement forward propagation to get h_theta(x)  
3. Implement the cost function  
4. Implement backpropagation to compute partial derivatives  
5. Use gradient checking to confirm that your backpropagation works. Then disable gradient checking.  
6. Use gradient descent or a built-in optimization function to minimize the cost function with the weights in theta.  
```javascript
for i = 1:m,
   Perform forward propagation and backpropagation using example (x(i),y(i))
   (Get activations a(l) and delta terms d(l) for l = 2,...,L
