---
title:          "Large-factor super-resolution of remote sensing images with spectra-guided generative adversarial networks"
date:           2022-11-14 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Geoscience and Remote Sensing (TGRS)"
pub_date:       "2022"
abstract: >-
  Large-factor image super-resolution (SR) is a challenging task due to the high uncertainty and incompleteness of the missing details to be recovered. In remote sensing images, the subpixel spectral mixing and semantic ambiguity of ground objects make this task even more challenging. In this article, we propose a novel method for large-factor SR of remote sensing images named spectra-guided generative adversarial networks (SpecGANs). In response to the above problems, we explore whether introducing additional hyperspectral images (HSIs) to GAN as conditional input can be the key to solving the problems. Different from previous approaches that mainly focus on improving the feature representation of a single source input, we propose a dual-branch network architecture to effectively fuse low-resolution (LR) red, green, blue (RGB) images and corresponding HSIs, which fully exploit the rich hyperspectral information as conditional semantic guidance. Due to the spectral specificity of ground objects, the semantic accuracy of the generated images is guaranteed. To further improve the visual fidelity of the generated output, we also introduce the Latent Code Bank with rich visual priors under a generative adversarial training framework so that high-resolution, detailed, and realistic images can be progressively generated. Extensive experiments show the superiority of our method over the state-of-art image SR methods in terms of both quantitative evaluation metrics and visual quality. Ablation experiments also suggest the necessity of adding spectral information and the effectiveness of our designed fusion module. To our best knowledge, we are the first to achieve up to 32x SR of remote sensing images with high visual fidelity under the premise of accurate ground object semantics.
cover:          https://github.com/YapengMeng/SpecGAN/raw/main/imgs/teaser.jpg?20x15
authors:
- Yapeng Meng
- Wenyuan Li
- Sen Lei
- Zhengxia Zou
- Zhenwei Shi
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/9950553
  Code: https://github.com/YapengMeng/SpecGAN
---
