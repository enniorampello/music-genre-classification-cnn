# CNN music genres classifier
Classification of music genres using a Convolutional Neural Network.

## Resources on VAEs in Python

- [General tutorial on VAEs with tensorflow](https://learnopencv.com/variational-autoencoder-in-tensorflow/).
- [Generate music with VAEs](https://www.kaggle.com/code/basu369victor/generate-music-with-variational-autoencoder) using the (GTZAN Dataset)[https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/code].
- [How to build a VAE with Keras](https://keras.io/examples/generative/vae/)

## Possible workflow

1. Consider a single music genre to use for generation
2. Use the MFCCs as input to the encoder
3. Split the dataset of MFCCs into training and test sets
4. For each song, pass the set of MFCCs to the encoder (`shape=(1, 13, 216)`)
5. Train the convolutional variational autoencoder similarly to [here](https://learnopencv.com/variational-autoencoder-in-tensorflow/)