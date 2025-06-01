This repository contains two complete projects using Variational Autoencoders (VAEs):

Project 1: VAE on MNIST – Digit generation using standard VAE, Conditional VAE (CVAE), and β-VAE.

Project 2: VAE for Anomaly Detection – Detecting fraudulent transactions in the Credit Card Fraud Detection dataset using reconstruction error.

Project 1: VAE on MNIST
Description
This notebook implements:

Basic VAE for unsupervised digit generation

Conditional VAE (CVAE) for generating specific digits by conditioning on class labels

β-VAE for learning disentangled representations

Features
Train VAE, CVAE, and β-VAE from scratch using PyTorch

Explore the latent space and interpolation

Play with different β values to see their effect on disentanglement

Generate digits for any class using the trained decoder

Project 2: VAE for Anomaly Detection (Credit Card Fraud)
Description
In this notebook, we train a VAE only on non-fraudulent transactions from the Credit Card Fraud Detection Dataset. After training, we use reconstruction error to detect anomalous (fraudulent) transactions.

Features
Preprocess and normalize transaction features

Train VAE on clean (normal) data only

Calculate reconstruction error on mixed test data (normal + fraud)

Set a threshold to flag outliers as fraud

Evaluate model using ROC-AUC, PR-AUC, and confusion matrix
