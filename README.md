# Fraud Detection using Variable Autoencoder

The project aims to predict Credit card fraud with the help of Autoencoder.


## Approach

Trained a simple autoencoder featuring one hidden layer on both the encoder and decoder sides. 
The autoencoder is designed to be asymmetrical and overcomplete, meaning the dimensions of the hidden layers and the latent space were larger and not symmetrical compared to the input size. 

Despite this unconventional structure, the autoencoder performed reasonably well when the latent encoding was passed through a simple linear classifier. 

Additionally, idea is to experiment with an adversarial network, using it solely as an alternative classifier to the linear benchmark. 

This approach shows promise and needs further improvement.


