# Stable Diffusion from Scratch in PyTorch

Welcome to the repository for implementing **Stable Diffusion Models** from scratch using **PyTorch**. This project focuses on building latent diffusion models while simplifying the math behind **Denoising Diffusion Probabilistic Models (DDPM)**. 

## What is Stable Diffusion?

Stable Diffusion is a **text-to-image** deep learning model introduced in 2022 by the CompViz group. It leverages a diffusion process to generate high-quality images based on prompts. Unlike traditional models, **latent diffusion** works with a latent representation of the data to reduce computation, allowing for faster and more efficient image generation.

## Overview

This project walks through the implementation of Stable Diffusion models with explanations for key concepts, including:
- **Latent Diffusion Models**
- **Classifier-Free Guidance**
- **Text-to-Image** and **Image-to-Image** functionality
- Mathematical background for **diffusion models**
  
## Topics Covered
1. **Latent Diffusion Models** - Detailed implementation and usage for generating images.
2. **Mathematics of Diffusion Models** - Simplified explanations based on the DDPM paper by **Ho et al.** (2020).
3. **Classifier-Free Guidance** - A modern technique for conditioning the reverse process without the need for a separate model.
4. **Text-to-Image** and **Image-to-Image** - Different image generation techniques.
5. **U-Net Architecture** - Core architecture used in the reverse diffusion process.



## Pretrained Weights

The pretrained model weights used for generating images were sourced from the **Inkpunk-Diffusion** model available on **Hugging Face**. You can find the pretrained weights [here](https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main).



  ## Acknowledgements

Special thanks to:

- [Inkpunk Diffusion Model](https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main) for the pretrained model weights
- [PyTorch Stable Diffusion](https://github.com/hkproj/pytorch-stable-diffusion) by Umar Jamil, for the inspiration and code references
- [Denoising Diffusion Probabilistic Models (DDPM) Paper](https://arxiv.org/pdf/2006.11239) by Ho et al., for the foundational work on diffusion models


