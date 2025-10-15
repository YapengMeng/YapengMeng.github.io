---
title:          "Diffusion-Based Extreme High-speed Scenes Reconstruction with the Complementary Vision Sensor"
date:           2025-10-05 00:01:00 +0800
selected:       true
pub:            "Proceedings of the IEEE/CVF international conference on computer vision (ICCV)"
pub_date:       "2025"
abstract: >-
  Recording and reconstructing high-speed scenes poses a significant challenge. While high-speed cameras can capture fine temporal details, their extremely high bandwidth demands make continuous recording unsustainable. Conversely, traditional RGB cameras, typically operating at 30 FPS, rely on frame interpolation to synthesize high-speed motion, often introducing artifacts and motion blur. Human visual system inspired sensors, like event cameras, offer high-speed sparse temporal or spatial variation data, partially alleviating these issues. However, existing methods still suffer from RGB blur, temporal aliasing, and loss of event information. To overcome these challenges, we leverage a novel complementary vision sensor, Tianmouc, which outputs high-speed, multi-bit, sparse spatio-temporal difference information with RGB frames. Building on this unique sensing modality, we introduce a Cascaded Bi-directional Recurrent Diffusion Model (CBRDM) that achieves accurate, sharp, color-rich video frames reconstruction. Our method outperforms state-of-the-art RGB interpolation algorithms in quantitative evaluations and surpasses eventbased methods in real-world comparisons.
cover:          /assets/images/covers/tmc_genrec.gif
authors:
- Yapeng Meng*
- Yihan Lin*
- Taoyi Wang
- Yuguo Chen
- Lijian Wang
- Rong Zhao
links:
  Paper: https://openaccess.thecvf.com/content/ICCV2025/html/Meng_Diffusion-Based_Extreme_High-speed_Scenes_Reconstruction_with_the_Complementary_Vision_Sensor_ICCV_2025_paper.html
  Code: https://github.com/Tianmouc/GenRec
---