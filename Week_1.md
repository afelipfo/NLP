# Logistic Regression


## Learning classifier

1. Given a characteristic representation of the input (feature representation), the feature i for the input x (j) is x_i. 
2. A classification function that computes y_hat, the estimated output, via p(y|x). (e.g. sigmoid, softmax).
3. Then, we define a learning objective function (loss function). (e.g. cross-entropy-loss)
4. Optimization algorithm of the loss function: stochastic gradient descent.

## Logistic Regression:

1. Training step
2. Test step

WHat about the input?

Docs with their respective labels. We can suppose a binary case: positive/negative. 

How does the classification work?

Each input x_i has a weight w_i which indicates the importance of x_i

$ z = wx + b $

Given a number, z, how do we get a probability?

We can use sigmoid function to transform into a probability ranging from 0 to 1.

### Weights

Supervised Learning: We know the correct label y for each x, and our linear regression classifier produces an estimation y_hat

- We need a distance estimator: a loss function or a cost function (cross-entropy loss)
- We need an optimization algorithm to update w and b to minimize the loss. (Stochastic gradient descent)

- THe weights /theta in Logistic Regression originate from a supervised learning process in which we adjust the model to minimize the difference between its predictions and the correct answers.
- We use the loss function like cross-entropy to measure this difference, and an optimization algorithm like the stochastic gradient descent.
- The stochastic gradient descent is the technique that we use to find the weights /theta that minimize the loss function in a classification model.