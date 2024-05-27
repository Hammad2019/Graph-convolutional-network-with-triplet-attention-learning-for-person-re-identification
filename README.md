Residual Attention Network for Image Classification

This repository contains the implementation of a Residual Attention Network designed for image classification tasks. The code was developed by Shimaa Saber and was used in the research article: "Attention-Based Residual Networks for Image Classification", published in the Information Sciences Journal.
Overview

The implemented network combines residual connections with attention mechanisms to enhance the performance of image classification models. The key components of the network include:

    Residual Attention Network
    Triplet Attention Module
    Classifier Block with Batch Normalization and Dropout

Prerequisites

    Python 3.x
    PyTorch
    Torchvision

File Structure

    weights_init_kaiming: Function to initialize weights using Kaiming normalization.
    weights_init_classifier: Function to initialize weights for classifier layers.
    ClassBlock: Defines the new fully connected (fc) layer and classification layer.
    Residual_attention_Net: Defines the encoder-decoder attention network.
    BasicConv: Basic convolutional block with optional BatchNorm and ReLU activation.
    ChannelPool: Pools channels using max and average pooling.
    SpatialGate: Applies spatial attention to the input feature map.
    TripletAttention: Combines three attention mechanisms for spatial attention.
    Attention: Combines channel attention with residual attention.
    Network: Main network class combining ResNet101 with the custom attention mechanisms.

Reference

This code was used in our published paper: "Attention-Based Residual Networks for Image Classification", available in the Information Sciences Journal at: https://www.sciencedirect.com/science/article/pii/S0020025522012257
