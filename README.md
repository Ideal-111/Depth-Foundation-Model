# Depth Foundation Models
- A collection of papers on monocular depth estimation with depth foundation models, e.g., discriminative model, generativate model, etc.
- A collection of papers on depth completion with different methods, e.g., RGB-Guided method, Unguided, etc. We list the depth completion methods based on **diffusion models** separately to emphasize an important direction for future depth completion research.

*Range*: We mainly focus on the work after **2022**.

We will continue to update this list with the latest resources. If you find any missed resources (paper/code) or errors, please **feel free to open an issue**.

## ✨Monocular Depth Estimation
### 🏷️Discriminative Model
- [Wang2025] Jasmine: Harnessing Diffusion Prior for Self-supervised Depth Estimation in *NeurIPS*, 2025. [\[paper\]](https://arxiv.org/abs/2503.15905)[\[code\]](https://github.com/wangjiyuan9/jasmine)
- [Wang2025] VGGT: Visual Geometry Grounded Transformer in *CVPR*, 2025. 👍*CVPR Best Paper*. [\[paper\]](https://arxiv.org/abs/2503.11651)[\[code\]](https://github.com/facebookresearch/vggt)
- [Yang2024] Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2401.10891)[\[code\]](https://github.com/LiheYoung/Depth-Anything)
- [Yang2024] Depth Anything V2 in *NeurIPS*, 2024. [\[paper\]](https://arxiv.org/abs/2406.09414)[\[code\]](https://github.com/DepthAnything/Depth-Anything-V2)
- [Hu2024] Metric3Dv2: A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation in *IEEE TPAMI*, 2024. [\[paper\]](https://arxiv.org/abs/2404.15506)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Yin2023] Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image in *ICCV*, 2023. [\[paper\]](https://arxiv.org/abs/2307.10984)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Ranftl2022] Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer in *IEEE TPAMI*, 2022. [\[paper\]](https://ieeexplore.ieee.org/document/9178977)[\[code\]](https://github.com/isl-org/MiDaS)
- [Ranftl2021] Vision Transformers for Dense Prediction in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ranftl_Vision_Transformers_for_Dense_Prediction_ICCV_2021_paper.pdf)[\[code\]](https://github.com/isl-org/DPT)
### 🏷️Generative Model
- [Gui2025] DepthFM: Fast Monocular Depth Estimation with Flow Matching in *AAAI*, 2025. [\[paper\]](https://arxiv.org/abs/2403.13788)[\[code\]](https://github.com/CompVis/depth-fm)
- [Ke2024] Marigold: Affordable Adaptation of Diffusion-Based Image Generators for Image Analysis in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2505.09358)[\[code\]](https://github.com/prs-eth/Marigold)
- [Fu2024] GeoWizard: Unleashing the Diffusion Priors for 3D Geometry Estimation from a Single Image in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2403.12013)[\[code\]](https://github.com/fuxiao0719/GeoWizard)
### 🏷️Combination
- [Pham2025] SharpDepth: Sharpening Metric Depth Predictions Using Diffusion Distillation in *CVPR*, 2025. [\[paper\]](SharpDepth: Sharpening Metric Depth Predictions Using Diffusion Distillation)[\[code\]](https://github.com/Qualcomm-AI-research/SharpDepth)

## ✨Depth Completion
### 💡Diffusion-Based Method
- [Voila2025][Marigold-DC: Zero-Shot Monocular Depth Completion with Guided Diffusion] in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2412.13389)[\[code\]](https://github.com/prs-eth/Marigold-DC)
<!-- - [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]() -->
### 🏷️RGB-Guided Method
- [Liang2025] Distilling Monocular Foundation Model for Fine-grained Depth Completion in *CVPR*, 2025. [\[paper\]](https://github.com/Sharpiless/DMD3C)[\[code\]](https://github.com/Sharpiless/DMD3C)
<!-- - [] in **. [\[paper\]]()[\[code\]]() -->

### 🏷️Unguided Method

## ✨Datasets

## ✨Related Survey
- [Xu2025] Towards Depth Foundation Model: Recent Trends in Vision-Based Depth Estimation in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2507.11540)
- [Hu2022] Deep Depth Completion From Extremely Sparse Data: A Survey in *IEEE TPAMI*, 2022. [\[paper\]](https://ieeexplore.ieee.org/document/9984942)