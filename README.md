# Deep Learning Case-Study-2

### Project Overview
This project is part of a group assignment to explore image generation and sentiment analysis using the Yelp dataset. The main objectives are:

Build and evaluate generative models (DCGAN, WGAN, VAE, and cGAN) to generate images based on Yelp categories.
Compute evaluation metrics like Inception Score (IS) and Frechet Inception Distance (FID).
Deploy generative models, a CNN model, and transformer models for sentiment analysis.
Demonstrate model performance and share insights into tuning efforts and challenges.
Generative Models
1. DCGAN (Deep Convolutional GAN)
Generates realistic images by training a generator and discriminator model using convolutional layers.
2. WGAN (Wasserstein GAN)
Introduces a Wasserstein loss function for improved training stability and diversity of generated images.
3. VAE (Variational Autoencoder)
Uses probabilistic latent variables to reconstruct and generate new images.
4. cGAN (Conditional GAN)
Conditions the generator and discriminator on specific labels (food, drink, inside, outside).
