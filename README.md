# Generative Models
This repository contains literature reviews on papers in generative modeling


Title    |Description    |Code    
:------:|:-------:|:-------:
[Variational Diffusion Models](https://arxiv.org/abs/2107.00630)| This paper attempts to understand diffusion loss in terms of the signal-to-noise ratio at each time step. Their proposed method improves the log-likelihood estimation of the data.|[link](https://github.com/addtt/variational-diffusion-models) |
[Simple diffusion: End-to-end diffusion for high resolution images](https://arxiv.org/abs/2301.11093)| This paper fine-tunes the training of the variation diffusion models for generating high-resolution images.|[link](https://github.com/faverogian/simpleDiffusion) |
[Align your Latents: High-Resolution Video Synthesis with Latent Diffusion](https://arxiv.org/abs/2304.08818)|This paper attempts to transform pretrained latent diffusion models for image generation into high-resolution videos. They introduce temporal layers (temporal attention and 3-D convolution) in the U-Net architecture to learn the temporal dynamics of the video frames. |[link](https://github.com/srpkdyy/VideoLDM) |
[Soft Mixture Denoising: Beyond the Expressive Bottleneck of Diffusion Models](https://arxiv.org/pdf/2309.14068)|This paper shows that the diffusion model faces an expressive bottleneck to generate samples from highly multimodal datasets. They introduce soft-mixture denoising which helps the denoiser to sample from diverse modes. |NA|
