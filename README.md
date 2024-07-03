This repository carries the code and file for enforcing and comparing superior generative modeling strategies the use of Vector Quantized Variational Autoencoder (VQ-VAE) and PixelRCNN. The models are applied to the ISIC dataset, which includes pix of numerous skin situations.

Introduction

The VQ-VAE version combines the variational autoencoder framework with vector quantization techniques, the use of a discrete latent space and a learnable codebook to successfully encode and decode excessive-dimensional enter information. The PixelRCNN version is an autoregressive generative model that generates snap shots pixel by using pixel, ensuring sharp and practical samples.

Objective
The number one obligations of this project are:

Training a VQ-VAE to encode and decode skin lesion snap shots whilst shooting meaningful latent representations.
Training a PixelRCNN to generate realistic pores and skin lesion snap shots based totally on the found out latent area representations.

Dataset

The ISIC dataset is used, which incorporates schooling and check photographs of pores and skin lesions, including melanoma, nevus, basal cell carcinoma, actinic keratosis, benign keratosis-like lesions, dermatofibroma, and vascular lesions.

Methodology

VQ-VAE: Consists of a CNN encoder, a decoder, and a vector quantization layer. The version is trained the usage of Adam optimizer and MSE loss.
PixelRCNN: Utilizes residual masked convolutional layers for autoregressive photograph generation. Trained the usage of Adam optimizer and MSE loss.
Results

VQ-VAE effectively captures and reconstructs significant latent representations of skin lesion photographs.
PixelRCNN generates numerous and sensible skin lesion snap shots through leveraging the discovered latent area.
