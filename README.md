# NN_USING_PYTHON
Implementation from James Loy Book.

Autoencoders for compression and Document Denoising.

Autoencoder --> has encoder to compress the input representation (Latent representation) and a decoder to regenerate the input as better as it can. 

to train we provide pair of same image, just to let the network learn that it should regenerate the same image(close approximation). 

I have used MNIST dataset to perfrom image compression and decompression- tired out with different hidden layer of various nodes (2,4,8,16,32).
More the number of nodes in the hidden layer, better the decompressed output- more information preserved.
Hidden layer with 32 nodes does better just of decoding the image.


For Denoising I have used clean and stained document of the same image, provided stained image as input and clean image as label -- so that the network can learn to 
regenerate the cleaner version of the stained and old document. 
