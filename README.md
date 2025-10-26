# Depth Foundation Models
- A collection of papers on depth estimation with depth foundation models, e.g., discriminative model, generativate model, etc.
- A collection of papers on depth completion with different methods, e.g., RGB-Guided method, Unguided, etc. We list the depth completion methods based on **diffusion models** separately to emphasize an important direction for future depth completion research.

- We mainly focus on the work after **2022**.

We will continue to update this list with the latest resources. If you find any missed resources (paper/code) or errors, please **feel free to open an issue**.

## ✨Monocular Depth Estimation
### 🏷️Discriminative Model
- [Wang2025] Jasmine: Harnessing Diffusion Prior for Self-supervised Depth Estimation in *NeurIPS*, 2025. [\[paper\]](https://arxiv.org/abs/2503.15905)[\[code\]](https://github.com/wangjiyuan9/jasmine)
- [Wang2025] VGGT: Visual Geometry Grounded Transformer in *CVPR*, 2025. 👍*CVPR Best Paper*. [\[paper\]](https://arxiv.org/abs/2503.11651)[\[code\]](https://github.com/facebookresearch/vggt)
- [Fang2025] Dens3R: A Foundation Model for 3D Geometry Prediction in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/pdf/2507.16290v1)[\[code\]](https://github.com/G-1nOnly/Dens3R)
- [Wang2024] DUSt3R: Geometric 3D Vision Made Easy in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2312.14132)[\[code\]](https://github.com/naver/dust3r)
- [Yang2024] Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2401.10891)[\[code\]](https://github.com/LiheYoung/Depth-Anything)
- [Yang2024] Depth Anything V2 in *NeurIPS*, 2024. [\[paper\]](https://arxiv.org/abs/2406.09414)[\[code\]](https://github.com/DepthAnything/Depth-Anything-V2)
- [Hu2024] Metric3Dv2: A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation in *IEEE TPAMI*, 2024. [\[paper\]](https://arxiv.org/abs/2404.15506)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Liu2024] Mono-ViFI: A Unified Learning Framework for Self-supervised Single and Multi-frame Monocular Depth Estimation in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2407.14126)[\[code\]](https://github.com/LiuJF1226/Mono-ViFI)
- [Han2024] High-Precision Self-Supervised Monocular Depth Estimation with Rich-Resource Prior in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2408.00361)[\[code\]](https://github.com/wencheng256/RPrDepth)
- [Yin2023] Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image in *ICCV*, 2023. [\[paper\]](https://arxiv.org/abs/2307.10984)[\[code\]](https://github.com/YvanYin/Metric3D)
- [Zhang2022] Hierarchical Normalization for Robust Monocular Depth Estimation in *NeurIPS*, 2022. [\[paper\]](https://arxiv.org/abs/2210.09670)[\[code\]](https://github.com/icoz69/HDN)
- [Ranftl2021] Vision Transformers for Dense Prediction in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ranftl_Vision_Transformers_for_Dense_Prediction_ICCV_2021_paper.pdf)[\[code\]](https://github.com/isl-org/DPT)
- [Ranftl2020] Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer in *IEEE TPAMI*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/9178977)[\[code\]](https://github.com/isl-org/MiDaS)

### 🏷️Generative Model
- [Pham] GeoDiff: Geometry-Guided Diffusion for Metric Depth Estimation in *ICCV Findings*, 2025. [\[paper\]](https://arxiv.org/pdf/2510.18291)[\[code\]]()
- [Gui2025] DepthFM: Fast Monocular Depth Estimation with Flow Matching in *AAAI*, 2025. [\[paper\]](https://arxiv.org/abs/2403.13788)[\[code\]](https://github.com/CompVis/depth-fm)
- [Hu2025] DepthCrafter: Generating Consistent Long Depth Sequences for Open-world Videos in **. [\[paper\]](https://arxiv.org/abs/2409.02095)[\[code\]](https://github.com/Tencent/DepthCrafter)
- [Garcia2025] Fine-Tuning Image-Conditional Diffusion Models is Easier than You Think in *WACV*, 2025. [\[paper\]](https://arxiv.org/pdf/2409.11355)[\[code\]](https://github.com/VisualComputingInstitute/diffusion-e2e-ft)
- [He2025] Lotus: Diffusion-based Visual Foundation Model for High-quality Dense Prediction in *ICLR*, 2025. [\[paper\]](https://arxiv.org/abs/2409.18124)[\[code\]](https://github.com/EnVision-Research/Lotus)
- [Shao2025] Learning Temporally Consistent Video Depth from Video Diffusion Priors in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2406.01493)[\[code\]](https://github.com/jiahao-shao1/ChronoDepth)
- [Wang2023] Neural Video Depth Stabilizer in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Neural_Video_Depth_Stabilizer_ICCV_2023_paper.pdf)[\[code\]](https://github.com/RaymondWang987/NVDS)
- [Ke2024] Marigold: Affordable Adaptation of Diffusion-Based Image Generators for Image Analysis in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2505.09358)[\[code\]](https://github.com/prs-eth/Marigold)
- [Fu2024] GeoWizard: Unleashing the Diffusion Priors for 3D Geometry Estimation from a Single Image in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2403.12013)[\[code\]](https://github.com/fuxiao0719/GeoWizard)
- [Liu2024] DepthLab: From Partial to Complete in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2412.18153)[\[code\]](https://github.com/ant-research/DepthLab)
- [Shao2024] MonoDiffusion: Self-Supervised Monocular Depth Estimation Using Diffusion Model in *TCSVT*, 2024. [\[paper\]](https://arxiv.org/abs/2311.07198)[\[code\]](https://github.com/ShuweiShao/MonoDiffusion)
- [Wang2024] Digging into contrastive learning for robust depth estimation with diffusion models in *MM*, 2024. [\[paper\]](https://arxiv.org/abs/2404.09831)[\[code\]](https://github.com/wangjiyuan9/D4RD)
- [Ji2023] DDP: Diffusion Model for Dense Visual Prediction in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_DDP_Diffusion_Model_for_Dense_Visual_Prediction_ICCV_2023_paper.pdf)[\[code\]](https://github.com/JiYuanFeng/DDP)
- [Saxena2023] Monocular Depth Estimation using Diffusion Models in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2302.14816)[\[code\]](https://depth-gen.github.io/)
- [Saxena2023] The Surprising Effectiveness of Diffusion Models for Optical Flow and Monocular Depth Estimation in *NeurIPS*, 2023. [\[paper\]](https://arxiv.org/pdf/2306.01923)[\[code\]](https://diffusion-vision.github.io/)

### 🏷️Combination
- [Pham2025] SharpDepth: Sharpening Metric Depth Predictions Using Diffusion Distillation in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Pham_SharpDepth_Sharpening_Metric_Depth_Predictions_Using_Diffusion_Distillation_CVPR_2025_paper.pdf)[\[code\]](https://github.com/Qualcomm-AI-research/SharpDepth)

## ✨Depth Completion
### 💡Diffusion-Based Method
- [Voila2025] Marigold-DC: Zero-Shot Monocular Depth Completion with Guided Diffusion in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2412.13389)[\[code\]](https://github.com/prs-eth/Marigold-DC)
- [Liu2024] DepthLab: From Partial to Complete in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2412.18153)[\[code\]](https://github.com/ant-research/DepthLab)
<!-- - [] in **. [\[paper\]]()[\[code\]]() -->

### 🏷️RGB-Guided Method
- [Liang2025] Distilling Monocular Foundation Model for Fine-grained Depth Completion in *CVPR*, 2025. [\[paper\]](https://github.com/Sharpiless/DMD3C)[\[code\]](https://github.com/Sharpiless/DMD3C)
- [Tang2024] Bilateral propagation network for depth completion in *CVPR*, 2024. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_Bilateral_Propagation_Network_for_Depth_Completion_CVPR_2024_paper.pdf)[\[code\]](https://github.com/kakaxi314/BP-Net)
- [Wang2024] Improving Depth Completion via Depth Feature Upsampling in *CVPR*, 2024. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Improving_Depth_Completion_via_Depth_Feature_Upsampling_CVPR_2024_paper.pdf)[\[code\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Improving_Depth_Completion_via_Depth_Feature_Upsampling_CVPR_2024_paper.pdf)

### 🏷️Unguided Method
- [Eldesokey2020] Uncertainty-Aware CNNs for Depth Completion: Uncertainty from Beginning to End in *CVPR*, 2020. [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Eldesokey_Uncertainty-Aware_CNNs_for_Depth_Completion_Uncertainty_from_Beginning_to_End_CVPR_2020_paper.pdf)[\[code\]](https://github.com/abdo-eldesokey/pncnn)
- [Huang2019] HMS-Net: Hierarchical Multi-Scale Sparsity-Invariant Network for Sparse Depth Completion in *IEEE TIP*, 2019. [\[paper\]](https://ieeexplore.ieee.org/document/8946876)

## ✨Datasets
- **Hypersim**: [Roberts2021] Hypersim: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Roberts_Hypersim_A_Photorealistic_Synthetic_Dataset_for_Holistic_Indoor_Scene_Understanding_ICCV_2021_paper.pdf)[\[download\]](https://github.com/apple/ml-hypersim)
- **VOID**: [Wong2020] Unsupervised depth completion from visual inertial odometry in *IEEE RA-L*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/8972600)[\[download\]](https://github.com/alexklwong/void-dataset)
- **DDAD**: [Guizilini2020] 3D Packing for Self-Supervised Monocular Depth Estimation in *CVPR*, 2020. [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guizilini_3D_Packing_for_Self-Supervised_Monocular_Depth_Estimation_CVPR_2020_paper.pdf)[\[download\]](https://github.com/TRI-ML/DDAD)
- **DIODE**: [Vasiljevic2019] DIODE: A Dense Indoor and Outdoor DEpth Dataset in *Arxiv*, 2019. [\[paper\]](https://arxiv.org/abs/1908.00463)[\[download\]](https://diode-dataset.org/)
- **ETH3D**: [Schöps2017] A Multi-view Stereo Benchmark with High-Resolution Images and Multi-camera Videos in *CVPR*, 2017. [\[paper\]](https://ieeexplore.ieee.org/document/8099755)[\[download\]](https://www.eth3d.net/)
- **KITTI**: [Uhrig2017] Sparsity Invariant CNNs in *3DV*, 2017. [\[paper\]](https://arxiv.org/abs/1708.06500)[\[download\]](https://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_completion)
- **ScanNet**: [Dai2017] ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes in *CVPR*, 2017. [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)[\[download\]](http://www.scan-net.org/)
- **Virtual KITTI**: [Gaidon2016] Virtual Worlds as Proxy for Multi-Object Tracking Analysis in *CVPR*, 2016. [\[paper-v1\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Gaidon_Virtual_Worlds_as_CVPR_2016_paper.pdf)[\[paper-v2\]](https://arxiv.org/abs/2001.10773)[\[download\]](https://synthia-dataset.net/)
- **SYNTHIA**: [ROS2016] The SYNTHIADataset: A Large Collection of Synthetic Images for Semantic
 Segmentation of Urban Scenes in *CVPR*, 2016. [\[paper\]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf)[\[download\]](https://synthia-dataset.net/)
 - **NYU-v2**: [Silberman2012] Indoor Segmentation and Support Inference  from RGBD Images in *ECCV*, 2012. [\[paper\]](https://cs.nyu.edu/~fergus/datasets/indoor_seg_support.pdf)[\[download\]](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html)
 
## ✨Related Survey
- [Xu2025] Towards Depth Foundation Model: Recent Trends in Vision-Based Depth Estimation in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2507.11540)
- [Arampatzakis2023] Monocular Depth Estimation: A Thorough Review in *IEEE TPAMI*, 2023. [\[paper\]](https://ieeexplore.ieee.org/document/10313067)
- [Hu2022] Deep Depth Completion From Extremely Sparse Data: A Survey in *IEEE TPAMI*, 2022. [\[paper\]](https://ieeexplore.ieee.org/document/9984942)