# Federated_learning
A federated learning model trained on MNIST dataset. 
Here we have 108 clients.
We are using the flower library for it.
The steps which are done for the model to perform.
1. We will divide the dataset into 108 clients.
2. We will setup a neural network which will act as our model.
3. Each chunk of dataset will be trained on the local device of each client.
4. New weights will be calculated and will be taken to the master server.
5. After every epoch the weights will be taken to server and weights will be updated
6. After some epochs our new model will be trained.

Here we are applying FedAvg strategy, it is being offered by the flower library. We can use other strategies also.
https://flower.dev/docs/framework/tutorial-series-get-started-with-flower-pytorch.html
