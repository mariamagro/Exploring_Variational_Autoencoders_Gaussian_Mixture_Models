# Neural Networks: Exploring Variational Autoencoders with Gaussian Mixture Models

**Credit:**
The implementation is based on tasks provided by Pablo M. Olmos.

**Completed by:**
- **María Ángeles Magro Garrote** - [mariamagro](https://github.com/mariamagro)
- **Marina Gómez Rey** - [MarinaGRey](https://github.com/MarinaGRey)
- **Ángela Durán**

## Overview

This project explores the application of Variational Autoencoders (VAEs) in the context of generating synthetic data from a 3-dimensional Gaussian Mixture Model (GMM). Our aim is to evaluate the VAE's capability to capture the intricate structure of multi-modal distributions and produce samples that closely emulate the ground truth distribution.

The project consists of the following components:
- **Synthetic Data Generation**: We use a Gaussian Mixture Model (GMM) to create a synthetic dataset for training and evaluating the VAE.
- **VAE Architecture**: We construct and train a VAE using dense layers, and analyze its performance in capturing and reconstructing the data.
- **Clustering and Mode Identification**: We use clustering techniques and mode identification to analyze the VAE's latent space and compare it with the ground truth data.
- **T-SNE Visualization**: We visualize the latent space representations using T-SNE to gain insights into the VAE's performance and the structure of the data.

## Contents

- `report.pdf`: A comprehensive report detailing the project, including methodology, results, and insights.
- `part1.ipynb`: Jupyter Notebook containing the implementation of synthetic data generation and VAE model definition.
- `part2.ipynb`: Jupyter Notebook for training the VAE, generating samples, performing clustering, mode identification, and T-SNE visualization.
