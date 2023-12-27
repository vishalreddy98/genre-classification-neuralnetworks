# Spotify Genre Classification Using Neural Networks
Designed a neural network named SpotifyNet for a specific task, related to music classification on Spotify using PyTorch. The network has three hidden layers with 256 units in each, followed by batch normalization to improve training stability and ReLU activation functions to introduce non-linearity. The final layer utilizes softmax activation to produce probabilities for multiple classes. 

When we feed input data through this network using the forward method, it generates predictions in the form of probabilities for each class. To train the network, we've defined a loss function based on cross entropy and used Adam with weight decay as the optimizer.

