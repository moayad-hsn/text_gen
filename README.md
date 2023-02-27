# Language Modelling and Text Generation using LSTMs

This project uses LSTMs trained on the WikiText-2 dataset in a text generation task. I used a 3-layer lstm and a pytorch embedding layer as an encoder and a linear layer at the decoder. 

The project uses a number of regularizing techniques inspired by the paper [Regularizing and Optimizing LSTM Language Models](https://arxiv.org/pdf/1708.02182.pdf). The selected regularization techniques are:

* Variable length backpropagation sequences
* Weight Decay
* Weight Tying 
* LSTM Dropout
* Embedding Dropout