# Auto-Encoder-using-the-MNIST-dataset

This github project is a simple implementation of the autoencoder on the MNIST dataset. Autoencoder is a neural network that learns how to compress data and then reconstruct the data back to a representation that is as close as the original input. It is an unsupervised method. The MNIST dataset contains 60000 training samples and 10000 testing samples of handwritten digits. 

For the autoencoder implementation, a neural network with 2 hidden layers (each containing 10 neurons) is created. The model is then trained for 200 epochs. Adam optimizer and Mean Squared Error (MSE) loss are used. 

The link (https://github.com/Aritro30/Auto-Encoder-using-the-MNIST-data-/blob/main/pytorch/Autoencoder.ipynb) contains the overall implementation. The first two cells install torch vision and import the necessary libraries. The next 2 cells are used to download the dataset and create the autoencoder class. As said earlier, it contains two hidden layers. Sigmoid activations are used to incorporate the non linearity. The next few cells are used for initializing the model, training and saving the model, loading the model and testing the model on the test set respectively.  
