# Human Words Audio Classification
There are 610 audio files divided as:
193 for birds
207 for cats
210 for dogs
This is a small part of a public dataset for single-word speech recognition, which can be found [here](https://www.kaggle.com/datasets/warcoder/cats-vs-dogs-vs-birds-audio-classification).
Applied a Convolutional Neural Network (CNN) with batch normalization and max-pooling layers, followed by fully connected layers for audio classification due to its ability to automatically learn hierarchical features from audio spectrograms and its incorporation of batch normalization for improved training stability.