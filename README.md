# RCPerception
This repository is the paperlist on Perception Algorithms for Radar and Camera Fusion.


## 3D Object Detection
| paper                                                        | 发表地方 | 融合方法         | 代码链接                                                | backbone | NDS   | mAP   |
| ------------------------------------------------------------ | -------- | ---------------- | ------------------------------------------------------- | -------- | ----- | ----- |
| [CenterFusion](https://openaccess.thecvf.com/content/WACV2021/papers/Nabati_CenterFusion_Center-Based_Radar_and_Camera_Fusion_for_3D_Object_Detection_WACV_2021_paper.pdf) | WACV2021 | 3D框与雷达点关联 | [pytorch代码](https://github.com/mrnabati/CenterFusion) | DAL34    | 0.453 | 0.332 |
| [RADIANT](http://cvlab.cse.msu.edu/pdfs/Long_Kumar_Morris_Liu_Castro_Chakravarty_AAAI2023.pdf) | AAAI2023 | 3D框与雷达点关联 | [pytorch代码](https://github.com/longyunf/radiant)      | R101     | -     | 0.384 |
| [CRAFT](https://arxiv.org/pdf/2209.06535.pdf)                | AAAI2023 | 3D框与雷达点关联 | -                                                       | DLA34    | 0.517 | 0.411 |
| [RCBEV4d](https://arxiv.org/pdf/2208.12079.pdf)|TIV2023| 特征级融合 |  -|Swin-T|0.497|0.381|
| [MVFusion](https://arxiv.org/pdf/2302.10511.pdf)|ICRA2023 |特征级融合 |  -|R101|0.455|0.380|
| [CRN](https://openaccess.thecvf.com/content/ICCV2023/papers/Kim_CRN_Camera_Radar_Net_for_Accurate_Robust_Efficient_3D_Perception_ICCV_2023_paper.pdf)|ICCV2023 | 特征级融合 |  [pytorch](https://github.com/youngskkim/CRN)|R50|0.560|0.490|
| [RCM-Fusion](https://arxiv.org/pdf/2307.10249.pdf)|arxiv | - | R50|0.535(test)|0.452(test)||
| [ClusterFusion](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10302296)|IEEE Access|| - |  DLA34|0.487(test)|0.341(test)|
| [TransCAR](https://arxiv.org/pdf/2305.00397.pdf)|IROS2023 | - |R101|0.522(test)|0.422(test)||
| [HVDetFusion](https://arxiv.org/pdf/2307.11323.pdf)|arxiv| | [pytorch](https://github.com/HVXLab/HVDetFusion) | R50|0.451|0.557|
| [RC-BEVFusion](https://arxiv.org/pdf/2305.15883.pdf)|GCPR2023| | - |  swin-T|0.567(test)|0.476(test)|
| [RCBEVDet](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_RCBEVDet_Radar-camera_Fusion_in_Birds_Eye_View_for_3D_Object_CVPR_2024_paper.html) |CVPR2024| | [pytorch](https://github.com/VDIGPKU/RCBEVDet) |             |             |             |
| [CRKD](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_CRKD_Enhanced_Camera-Radar_Object_Detection_with_Cross-modality_Knowledge_Distillation_CVPR_2024_paper.html) |CVPR2024| | [pytorch](https://github.com/Song-Jingyu/CRKD) |  ||             |
