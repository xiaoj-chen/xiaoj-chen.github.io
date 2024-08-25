---
title: "CipherDM: Secure Three-Party Inference for Diffusion Model Sampling (ACCEPTED)"
collection: publications
category: pubpapers
permalink: /publication/202403-IJCNN-STMS
date: 2024-03-18
venue: 'European Conference on Computer Vision 2024'
#paperurl: ''
---
**Authors:** Xin Zhao, **Xiaojun Chen**, Xudong Chen, He Li, Tingyu Fan, Zhendong Zhao

**KeyWords:** *Privacy Preserving Machine Learning*

**Abstract:** Abstract. Diffusion Models (DMs) achieve state-of-the-art synthesis results in image generation and have been applied to various fields. However, DMs sometimes seriously violate user privacy during usage, making the protection of privacy an urgent issue. Using traditional privacy computing schemes like Secure Multi-Party Computation (MPC) directly in DMs faces significant computation and communication challenges. To address these issues, we propose CipherDM, the first novel, versatile and universal framework applying MPC technology to DMs for secure sampling, which can be widely implemented on multiple DM based tasks. We thoroughly analyze sampling latency breakdown, find time-consuming part and design corresponding secure MPC protocols for computing nonlinear activations including SoftMax, SiLU and Mish. CipherDM is evaluated on popular architectures (DDPM, DDIM) using MNIST dataset and on SD deployed by diffusers. Compared to direct implementation on SPU, our approach improves running time by approximately 1.084× ∼ 2.328×, and reduces communication costs by approximately 1.212× ∼ 1.791×.
