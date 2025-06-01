# This Repository Contains Two Projects Using Variational Autoencoders (VAEs)

# Project 1: VAE on MNIST – Digit Generation

Basic VAE for unsupervised digit generation

Conditional VAE (CVAE) for generating specific digits by conditioning on class labels

β-VAE for learning disentangled representations

Features
Train VAE, CVAE, and β-VAE from scratch using PyTorch

Explore the latent space and interpolation

Experiment with different β values to observe their effect on disentanglement

Generate digits for specific classes using the trained decoder

---------------------------------------------------------------

# Project 2: VAE for Anomaly Detection – Credit Card Fraud Detection
A VAE is trained only on non-fraudulent transactions from the Credit Card Fraud Detection dataset.
After training, reconstruction error is used to detect anomalous (fraudulent) transactions.

Features
Preprocess and normalize transaction features

Train the VAE using only normal (non-fraud) data

Compute reconstruction error on test data that includes both normal and fraudulent transactions

Set a threshold to flag outliers as potential fraud cases

Evaluate the model using:

ROC-AUC

PR-AUC

Confusion matrix
