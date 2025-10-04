---
title:          "Text-driven Physically Interpretable Face Editing"
date:           2025-06-30 00:01:00 +0800
selected:       true
pub:            "IEEE International Conference on Multimedia and Expo Workshops (ICMEW)"
pub_date:       "2025"
abstract: >-
  This paper proposes a novel and physically interpretable method for face editing with arbitrary text prompts. Different from previous GAN-inversion editing methods that manipulate its latent space or diffusion methods conduct manipulation as a reverse process, we regard the face editing process as imposing vector flow fields on face images, representing the offset of spatial coordinates and color for each pixel. Under this paradigm, we represent the vector flow field in two ways: 1) explicitly represent the flow vectors with rasterized tensors, and 2) implicitly parameterize the flow vectors as continuous, smooth, and resolution-agnostic neural fields. The flow vectors are iteratively optimized under the guidance of the pre-trained CLIP model by maximizing the correlation between the edited image and the text prompt. We also propose a learning-based one-shot face editing framework, which is fast and adaptable to any text prompt input. Compared with SOTA text-driven face editing methods, our method can generate physically interpretable face editing results with high identity consistency and image quality.
cover:          /assets/images/covers/faceedit.jpg
authors:
- Songru Yang*
- Yapeng Meng*
- Zhenwei Shi
- Zhengxia Zou
links:
  Paper1: https://ieeexplore.ieee.org/abstract/document/11152090
  Paper2: https://arxiv.org/abs/2308.05976
---