---
title:          "Text-guided 3D face synthesis-from generation to editing"
date:           2024-06-05 00:01:00 +0800
selected:       true
pub:            "Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)"
pub_date:       "2024"
abstract: >-
  Text-guided 3D face synthesis has achieved remarkable results by leveraging text-to-image (T2I) diffusion models. However most existing works focus solely on the direct generation ignoring the editing restricting them from synthesizing customized 3D faces through iterative adjustments. In this paper we propose a unified text-guided framework from face generation to editing. In the generation stage we propose a geometry-texture decoupled generation to mitigate the loss of geometric details caused by coupling. Besides decoupling enables us to utilize the generated geometry as a condition for texture generation yielding highly geometry-texture aligned results. We further employ a fine-tuned texture diffusion model to enhance texture quality in both RGB and YUV space. In the editing stage we first employ a pre-trained diffusion model to update facial geometry or texture based on the texts. To enable sequential editing we introduce a UV domain consistency preservation regularization preventing unintentional changes to irrelevant facial attributes. Besides we propose a self-guided consistency weight strategy to improve editing efficacy while preserving consistency. Through comprehensive experiments we showcase our method's superiority in face synthesis.
cover:          https://faceg2e.github.io/figs/overview.png
authors:
- Yunjie Wu*
- Yapeng Meng*
- Zhipeng Hu*
- Lincheng Li
- Haoqian Wu
- Kun Zhou
- Weiwei Xu
- Xin Yu
links:
  Paper: https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Text-Guided_3D_Face_Synthesis_-_From_Generation_to_Editing_CVPR_2024_paper.html
  Project Page: https://faceg2e.github.io/
  Code: https://github.com/JiejiangWu/FaceG2E/
---