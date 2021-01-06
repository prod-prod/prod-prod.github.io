---
title: "Genearete TV script with RNN"
excerpt: "Use RNN (LSTM) to generate TV scripts<br/><img src='/images/projects/GAN.jpg'>"
collection: portfolio
---

### About

We use [recurrent neural network](https://en.wikipedia.org/wiki/Recurrent_neural_network) to generate the text.For training we will use [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv). [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) is the network architecture, that will be used.

We will implement and train simple network. No paper available.

The script takes a string as an input (beginning of the script) and the network will generate the rest of the script.

Te quality is not the purpose of the project. Quality will be highly correlated with the data set, network size and training time.

The purpose of the project is just to demo the usage of LSTM and how powerful simple LSTM can be.


### Implementation

For the implementation we will use Python3 and [PyTorch](https://pytorch.org/).


### Environment

We use [Jupyter notebooks](https://jupyter.org/) to run the code and observe the results.


### Code

All code is available on the [Github](https://github.com/kurbakov/generate-tv-scripts)
