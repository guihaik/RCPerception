# RCPerception 
**This repository is the paperlist on Perception Algorithms for Radar and Camera Fusion.**


## 1. 3D Object Detection 
**The NDS and mAP are given in the NuScenes Val.**
| Paper                                                        | 发表地方 | 融合方法         | 代码链接                                                | Backbone | Image Size | NDS   | mAP   |
| :----------------------------------------------------------: | :------: | :--------------: | :-----------------------------------------------------: | :------: | :---: | :---: | :---: |
| [CenterFusion](https://openaccess.thecvf.com/content/WACV2021/papers/Nabati_CenterFusion_Center-Based_Radar_and_Camera_Fusion_for_3D_Object_Detection_WACV_2021_paper.pdf) | WACV2021 | 3D框与雷达点关联 | [pytorch](https://github.com/mrnabati/CenterFusion) | DAL34 | 450 $\times$ 800 | 0.453 | 0.332 |
| [ClusterFusion](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10302296)|IEEE Access| - | - | DLA34 | 448 $\times$ 800 | 0.490 | 0.347 |
| [CRAFT](https://arxiv.org/pdf/2209.06535.pdf)                | AAAI2023 | 3D框与雷达点关联 | - | DLA34 | 448 $\times$ 800 | 0.517 | 0.411 |
| [RADIANT](http://cvlab.cse.msu.edu/pdfs/Long_Kumar_Morris_Liu_Castro_Chakravarty_AAAI2023.pdf) | AAAI2023 | 3D框与雷达点关联 | [pytorch](https://github.com/longyunf/radiant) | R101 | 448 $\times$ 800 | - | 0.384 |
| [TransCAR](https://arxiv.org/pdf/2305.00397.pdf)|IROS2023 | - | - | R101 | - | 0.464 | 0.355 |
| [RCBEV4d](https://arxiv.org/pdf/2208.12079.pdf)|TIV2023| 特征级融合 |  -| Swin-T | 256 $\times$ 704 | 0.497 | 0.381 |
| [RC-BEVFusion](https://arxiv.org/pdf/2305.15883.pdf)|GCPR2023| - | - | swin-T | 256 $\times$ 704 |0.525 | 0.434 |
| [MVFusion](https://arxiv.org/pdf/2302.10511.pdf)|ICRA2023 |特征级融合 |  -|R50| 256 $\times$ 704 | 0.402 | 0.330 |
| [CRN](https://openaccess.thecvf.com/content/ICCV2023/papers/Kim_CRN_Camera_Radar_Net_for_Accurate_Robust_Efficient_3D_Perception_ICCV_2023_paper.pdf)| ICCV2023 | 特征级融合 |  [pytorch](https://github.com/youngskkim/CRN)| R50 | 256 $\times$ 704 | 0.560 | 0.490 |
| [X3DK](https://openaccess.thecvf.com/content/CVPR2023/papers/Klingner_X3KD_Knowledge_Distillation_Across_Modalities_Tasks_and_Stages_for_Multi-Camera_CVPR_2023_paper.pdf)| CVPR2023 | 知识蒸馏 | - | R50 | 256 $\times$ 704 | 0.538 | 0.423 |
| [RCM-Fusion](https://ieeexplore.ieee.org/abstract/document/10611449)| ICRA2024 | - | - | R50 | 450 $\times$ 800 | 0.529 | 0.443 |
| [HVDetFusion](https://arxiv.org/pdf/2307.11323.pdf)| arxiv | - | [pytorch](https://github.com/HVXLab/HVDetFusion) | R50 | 256 $\times$ 704 | 0.451 | 0.557 |
| [RCBEVDet](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_RCBEVDet_Radar-camera_Fusion_in_Birds_Eye_View_for_3D_Object_CVPR_2024_paper.html) | CVPR2024 | - | [pytorch](https://github.com/VDIGPKU/RCBEVDet) | R50 | 256 $\times$ 704 | 0.568 | 0.453 |
| [CRKD](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_CRKD_Enhanced_Camera-Radar_Object_Detection_with_Cross-modality_Knowledge_Distillation_CVPR_2024_paper.html) | CVPR2024 | 知识蒸馏 | [pytorch](https://github.com/Song-Jingyu/CRKD) | R50 | 256 $\times$ 704 | 0.549  | 0.432 |
| [CR3DT](https://arxiv.org/pdf/2403.15313) | IROS2024 | - | [pytorch](https://github.com/ETH-PBL/CR3DT) | R50 | 256 $\times$ 704 | 0.456  | 0.351 |
| [HyDRa](https://arxiv.org/pdf/2403.07746) | arxiv2403 | - | - | R50 | 256 $\times$ 704 | 0.585  | 0.494 |
| [SpaRC](https://arxiv.org/pdf/2411.19860) | arxiv2411 | - | - | R50 | 256 $\times$ 704 | 0.620  | 0.545 |

## 2. Depth  Estimation

