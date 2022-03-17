# Prediction using Neural Network in Tensorflow
## Objective
The goal is to predict the compressive strength of a kind of Concrete.

## Data Source
Data is from the public source, containing the different property parameters of the concrete.

## Structure
(1) Introduction.

- Explain the Stochastic Gradient Descent's mechanism of action in the Neural Network.

(2) Data preprocessing

- Scaling the data to stabilize the gradient descent.

(3) Build Neural Network and predict.

- Define the model as Sequential MLP. 

- Architect the network as the input being 8, the hidden layer being 5, output being 1.

- Select Stochastic Gradient Descent as the algorithm to perform the optimization procedure.

- Choose MSE as the loss function.

- Evaluate predictions using MSE, RMSE, MAE.

- To avoid overfitting, a dropout layer with 10% dropout is inserted between the first hidden layer and the output layer.

## Conclusion
The model can predict the result pretty well:

MSE: 0.135, RMSE: 0.368, MAE: 0.295

