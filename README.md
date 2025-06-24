<<<<<<< HEAD
**# CSE_676_Final_raghulch_dongyoon**

**CSE 676 Final Project – Deep Learning in Supply Chain Optimization**

This project was created as part of CSE 676 (Deep Learning) at SUNY Buffalo, and follows the use of more specialized deep learning models to predict demand of products in a retail and/or warehouse situation. We aim to enhance the accuracy of demand prediction and to assist data-driven decision-making in inventory and supply chain management.

**Dataset Overview**

The focus of this project is a data set of historical retail and warehouse sales records. It consists of around 300K transactions and has several time-variant and categorical factors including:

Date of transaction

Product ID and Category

Store or warehouse where located

Quantity Sold

Further metadata (e.g., promotion status, seasons)

The data is based on actual supply chain dynamics and was pre-processed to produce time series sequences that are related to the deep learning models.

**Project Objective**

The key objective is to develop and compare multiple deep learning models for the accurate prediction weekly product demand. This entails studying how different architectures cope with noise-enhanced inputs, gradual dependencies and typical data-scarcity that is present in supply chain settings.

The project emphasizes:

Sequence Learning of Sales Historically

Modeling of seasonality and trends

Robustness under noisy testing conditions

Multiple product categories and different locations hypocorises.

The Deep Learning Architectures Involved

The neural net models developed and tested included the:

LSTM (Long short term memory): This captures the long term dependencies in sales sequences.

GRU (Gated Recurrent Unit): A recurrent block that is less complex and more efficient than LSTM

CNN-RNN: Employ convolution layers to capture local patterns and then LSTM to learn sequence information.

Transformer: A self-attention model that is capable of understanding some dependencies without relying on recurrence.

Denoising Autoencoder + LSTM: Noise is removed from input sequences in the first place, then forecast with LSTM.

The forecasting performance and generalization are discussed of each model trained on difference training data configuration.

**Contributors**
Raghulch

Dongyoon Shin

This project was submitted as part of the final coursework for CSE 676: Deep Learning (Spring 2025), SUNY Buffalo.

---

## Acknowledgements

- SUNY Buffalo – Department of Computer Science and Engineering   

- Open-source contributors to PyTorch, NumPy, and related ML libraries
=======
# Welcome to your organization's demo respository
This code repository (or "repo") is designed to demonstrate the best GitHub has to offer with the least amount of noise.

The repo includes an `index.html` file (so it can render a web page), two GitHub Actions workflows, and a CSS stylesheet dependency.
>>>>>>> 486acaf (Initial commit)
