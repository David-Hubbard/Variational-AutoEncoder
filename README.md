I used this dataset of celebrity images: https://www.kaggle.com/greg115/celebrities-100k#

The variational autoencoder is a generative model. Inputs are compressed in the encoding stage and decompressed in the decoding stage.
The variational aspect involves the compressed representation forming the mean and variance of a distribution which is sampled from to create instances of the input.
In this way we can generate new inputs by sampling from the distribution.
