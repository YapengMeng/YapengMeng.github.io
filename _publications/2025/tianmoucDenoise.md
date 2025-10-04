---
title:          "An adaptive filter for denoising brain-inspired complementary vision sensor"
date:           2025-09-23 00:01:00 +0800
selected:       false
pub:            "Neuromorphic Computing and Engineering (NCE)"
pub_date:       "2025"
abstract: >-
  Recent advancements in brain-inspired complementary vision chips (CVS) with intensity, multi-bit temporal difference (TD) and spatial difference (SD) sensing capabilities offer a promising solution to the limitations of traditional image sensors by enabling high-speed, high-precision sensing with reduced bandwidth consumption. However, noise characterizations and denoising strategies for these sensors remain underexplored. In this study, leveraging a recently developed state-of-the-art CVS, Tianmouc, we present a theoretical analysis of its noise characteristics, revealing the main challenge for denoising: a distinctive distribution that varies with local illumination. Building on this analysis, we develop a suite of novel denoising algorithms named locally adaptive direction-aware filter (LADF). LADF implements multi-stage denoising algorithms consisting of preprocessing followed by an adaptive threshold filter that adjusts parameters locally to mitigate noise variability. Additionally, considering the distinct characteristics of SD, we develop a multi-directional and polarity-aware separation strategy, while for TD, we exploit the inherent time-space correlation between TD and SD to suppress noise further. To enable rigorous evaluation, we construct a large-scale paired dataset through a novel synthetic-real approach that combines accurately labeled synthetic images with real-world captured data. Experimental results demonstrate that LADF achieves an average signal-to-noise ratio (SNR) of 10.11 in SD, outperforming two baseline methods by factors of 1.54× and 2.73×, respectively, and an average SNR of 4.52 in TD, surpassing the baselines by 1.47× and 3.57×, respectively. Furthermore, our method reduces errors in motion estimation by 28.9%, and enhances the peak SNR in reconstruction by 3.35 dB, demonstrating its effectiveness in downstream tasks. Our algorithm establishes a new benchmark for CVS denoising and demonstrates significant potential to enhance the performance of application systems utilizing CVS.
# cover:          /assets/images/covers/genrec.jpg
authors:
- Taoyi Wang
- Yuxiang Li
- Yihan Lin
- Yapeng Meng
- Yuguo Chen
- Rong Zhao
links:
  Paper: https://iopscience.iop.org/article/10.1088/2634-4386/ae0a76/meta
---