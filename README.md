# Face Image Representation: PCA, NMF, and CNN Autoencoder Comparison


## Project Overview

This project explores and compares different methods for extracting compact feature representations from face images, focusing on three approaches:

- **PCA (Principal Component Analysis)**
- **NMF (Non-negative Matrix Factorization)**
- **CNN Autoencoder**

The goal is to analyze their effectiveness in reconstructing images and learning separable embeddings. Visualization with t-SNE is used to compare the clustering quality of the learned representations.

## Key Highlights

- PCA and NMF provide linear decompositions, with NMF offering more interpretable parts-based features.
- CNN autoencoder learns nonlinear compact encodings from image data.
- t-SNE visualizations show that NMF encodings cluster more distinctly, while CNN autoencoder features are more generalized.
- This work serves as an initial step toward image reconstruction, with potential extensions to segmentation and classification using improved models and real datasets.

