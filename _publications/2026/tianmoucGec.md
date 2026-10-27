---
title:          "Spatio-Temporal Difference Guided Motion Deblurring with the Complementary Vision Sensor"
date:           2026-06-01 00:01:00 +0800
selected:       true
pub:            "Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)"
pub_date:       "2026"
abstract: >-
  Motion blur arises when rapid scene changes occur during the exposure period, collapsing rich intra-exposure motion into a single RGB frame. Without explicit structural or temporal cues, RGB-only deblurring is highly ill-posed and often fails under extreme motion. Inspired by the human visual system, neuromorphic sensors introduce temporally dense information to alleviate this problem; however, event cameras still suffer from event rate saturation under rapid motion, while the event modality entangles edge features and motion cues, which limits their effectiveness. As a recent breakthrough, the complementary vision sensor (CVS) captures synchronized RGB frames together with high-frame-rate, multi-bit spatial difference (SD, encoding structural edges) and temporal difference (TD, encoding motion cues) data within a single RGB exposure, offering a promising solution for RGB deblurring under extreme dynamic scenes. To fully leverage these complementary modalities, we propose Spatio-Temporal Difference Guided Deblur Net (STGDNet), which adopts a recurrent multi-branch architecture that iteratively encodes and fuses SD and TD sequences to restore structure and color details lost in blurry RGB inputs. Our method outperforms current RGB or event-based approaches in both synthetic CVS dataset and real-world evaluations. Moreover, STGDNet exhibits strong generalization capability across over 100 extreme real-world scenarios.
cover:          /assets/images/covers/tmc_deblur.gif
authors:
- Yapeng Meng*
- Lin Yang*
- Yuguo Chen
- Xiangru Chen
- Taoyi Wang
- Lijian Wang
- Zheyu Yang
- Yihan Lin#
- Rong Zhao#
links:
  Paper: https://openaccess.thecvf.com/content/CVPR2026/html/Meng_Spatio-Temporal_Difference_Guided_Motion_Deblurring_with_the_Complementary_Vision_Sensor_CVPR_2026_paper.html
  Project Page: https://tmcdeblur.github.io/
  Code: https://github.com/Tianmouc/tmcDeblur
---