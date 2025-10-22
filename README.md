# Depth Foundation Models
- A collection of papers on monocular depth estimation with depth foundation models, e.g., discriminative model, generativate model, etc.
- A collection of papers on depth completion with different methods, e.g., RGB-Guided method, Unguided, etc. We list the depth completion methods based on **diffusion models** separately to emphasize an important direction for future depth completion research.

- We mainly focus on the work after **2022**.

We will continue to update this list with the latest resources. If you find any missed resources (paper/code) or errors, please **feel free to open an issue**.

## ✨Monocular Depth Estimation
### 🏷️Discriminative Model
- [Wang2025] Jasmine: Harnessing Diffusion Prior for Self-supervised Depth Estimation in *NeurIPS*, 2025. [\[paper\]](https://arxiv.org/abs/2503.15905)[\[code\]](https://github.com/wangjiyuan9/jasmine)
- [Wang2025] VGGT: Visual Geometry Grounded Transformer in *CVPR*, 2025. 👍*CVPR Best Paper*. [\[paper\]](https://arxiv.org/abs/2503.11651)[\[code\]](https://github.com/facebookresearch/vggt)
- [Yang2024] Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2401.10891)[\[code\]](https://github.com/LiheYoung/Depth-Anything)
- [Yang2024] Depth Anything V2 in *NeurIPS*, 2024. [\[paper\]](https://arxiv.org/abs/2406.09414)[\[code\]](https://github.com/DepthAnything/Depth-Anything-V2)
- [Hu2024] Metric3Dv2: A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation in *IEEE TPAMI*, 2024. [\[paper\]](https://arxiv.org/abs/2404.15506)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Yin2023] Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image in *ICCV*, 2023. [\[paper\]](https://arxiv.org/abs/2307.10984)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Zhang2022] Hierarchical Normalization for Robust Monocular Depth Estimation in *NeurIPS*, 2022. [\[paper\]](https://arxiv.org/abs/2210.09670)[\[code\]](https://github.com/icoz69/HDN)
- [Ranftl2021] Vision Transformers for Dense Prediction in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ranftl_Vision_Transformers_for_Dense_Prediction_ICCV_2021_paper.pdf)[\[code\]](https://github.com/isl-org/DPT)
- [Ranftl2020] Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer in *IEEE TPAMI*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/9178977)[\[code\]](https://github.com/isl-org/MiDaS)

### 🏷️Generative Model
- [Gui2025] DepthFM: Fast Monocular Depth Estimation with Flow Matching in *AAAI*, 2025. [\[paper\]](https://arxiv.org/abs/2403.13788)[\[code\]](https://github.com/CompVis/depth-fm)
- [Ke2024] Marigold: Affordable Adaptation of Diffusion-Based Image Generators for Image Analysis in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2505.09358)[\[code\]](https://github.com/prs-eth/Marigold)
- [Fu2024] GeoWizard: Unleashing the Diffusion Priors for 3D Geometry Estimation from a Single Image in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2403.12013)[\[code\]](https://github.com/fuxiao0719/GeoWizard)
- [Liu2024] DepthLab: From Partial to Complete in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2412.18153)[\[code\]](https://github.com/ant-research/DepthLab)
- [Ji2023] DDP: Diffusion Model for Dense Visual Prediction in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_DDP_Diffusion_Model_for_Dense_Visual_Prediction_ICCV_2023_paper.pdf)[\[code\]](https://github.com/JiYuanFeng/DDP)
- [Saxena2023] Monocular Depth Estimation using Diffusion Models in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2302.14816)[\[code\]](https://depth-gen.github.io/)

### 🏷️Combination
- [Pham2025] SharpDepth: Sharpening Metric Depth Predictions Using Diffusion Distillation in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Pham_SharpDepth_Sharpening_Metric_Depth_Predictions_Using_Diffusion_Distillation_CVPR_2025_paper.pdf)[\[code\]](https://github.com/Qualcomm-AI-research/SharpDepth)

## ✨Depth Completion
### 💡Diffusion-Based Method
- [Voila2025][Marigold-DC: Zero-Shot Monocular Depth Completion with Guided Diffusion] in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2412.13389)[\[code\]](https://github.com/prs-eth/Marigold-DC)
- [Liu2024] DepthLab: From Partial to Complete in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2412.18153)[\[code\]](https://github.com/ant-research/DepthLab)
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
[Liang2025] Distilling Monocular Foundation Model for Fine-grained Depth Completion in *CVPR*, 2025. [\[paper\]](https://github.com/Sharpiless/DMD3C)[\[code\]](https://github.com/Sharpiless/DMD3C)
<!-- - [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]()
- [] in **. [\[paper\]]()[\[code\]]() -->
- [Tang2024] Bilateral propagation network for depth completion in *CVPR*, 2024. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_Bilateral_Propagation_Network_for_Depth_Completion_CVPR_2024_paper.pdf)[\[code\]](https://github.com/kakaxi314/BP-Net)

### 🏷️Unguided Method
- [Eldesokey2020] Uncertainty-Aware CNNs for Depth Completion: Uncertainty from Beginning to End in *CVPR*, 2020. [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Eldesokey_Uncertainty-Aware_CNNs_for_Depth_Completion_Uncertainty_from_Beginning_to_End_CVPR_2020_paper.pdf)[\[code\]](https://github.com/abdo-eldesokey/pncnn)
- [Huang2019] HMS-Net: Hierarchical Multi-Scale Sparsity-Invariant Network for Sparse Depth Completion in *IEEE TIP*, 2019. [\[paper\]](https://ieeexplore.ieee.org/document/8946876)

## ✨Datasets
- **VOID**: [Wong2020] Unsupervised depth completion from visual inertial odometry in *IEEE RA-L*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/8972600)[\[download\]](https://github.com/alexklwong/void-dataset)
- **DIODE**: [Vasiljevic2019] DIODE: A Dense Indoor and Outdoor DEpth Dataset in *Arxiv*, 2019. [\[paper\]](https://arxiv.org/abs/1908.00463)[\[download\]](https://diode-dataset.org/)
- **ETH3D**: [Schöps2017] A Multi-view Stereo Benchmark with High-Resolution Images and Multi-camera Videos in *CVPR*, 2017. [\[paper\]](https://ieeexplore.ieee.org/document/8099755)[\[download\]](https://www.eth3d.net/)
- **KITTI**: [Uhrig2017] Sparsity Invariant CNNs in *3DV*, 2017. [\[paper\]](https://arxiv.org/abs/1708.06500)[\[download\]](https://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_completion)
- **ScanNet**: [Dai2017] ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes in *CVPR*, 2017. [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)[\[download\]](http://www.scan-net.org/)
- **NYU-v2**: [Silberman2012] Indoor Segmentation and Support Inference  from RGBD Images in *ECCV*, 2012. [\[paper\]](https://cs.nyu.edu/~fergus/datasets/indoor_seg_support.pdf)[\[download\]](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html)
- **Virtual KITTI**:- [Gaidon2016] Virtual Worlds as Proxy for Multi-Object Tracking Analysis in *CVPR*,2016. [\[paper-v1\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Gaidon_Virtual_Worlds_as_CVPR_2016_paper.pdf)[\[paper-v2\]](https://arxiv.org/abs/2001.10773)[\[download\]](https://synthia-dataset.net/)
- **SYNTHIA**:- [ROS2016] The SYNTHIADataset: A Large Collection of Synthetic Images for Semantic
 Segmentation of Urban Scenes in *CVPR*, 2016. [\[paper\]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf)[\[download\]](https://synthia-dataset.net/)
 
## ✨Related Survey
- [Xu2025] Towards Depth Foundation Model: Recent Trends in Vision-Based Depth Estimation in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2507.11540)
- [Arampatzakis2023] Monocular Depth Estimation: A Thorough Review in *IEEE TPAMI*, 2023. [\[paper\]](https://ieeexplore.ieee.org/document/10313067)
- [Hu2022] Deep Depth Completion From Extremely Sparse Data: A Survey in *IEEE TPAMI*, 2022. [\[paper\]](https://ieeexplore.ieee.org/document/9984942)