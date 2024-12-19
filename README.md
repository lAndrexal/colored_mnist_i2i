# Image-to-Image Translation with DDPM

This repository contains implementations of Image-to-Image translation tasks using Denoising Diffusion Probabilistic Models (DDPM). We explore two approaches:

1. Dual Diffusion Implicit Bridges (DDIB)
2. Custom Latent Space Transforms

## Notebooks

- `ddib_implementation.ipynb`: Implementation of the DDIB approach
- `latent_transforms.ipynb`: Our custom latent space transformation method

## Results

Our latent transformation approach achieves:
- FID score: 42.559 (vs DDIB's 99.614)
- Average color difference: 0.271 (comparable to DDIB's 0.270)

## Dataset

The experiments were conducted on colored MNIST digits (specifically digits '2' and '3').
