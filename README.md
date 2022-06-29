<!--A curated list of resources for deep segmentation for thermal image-->
<!-- PROJECT LOGO -->

<p align="center">
  <h1 align="center">Awesome-Thermal-Segmentation</h1>
  <p align="center">A curated list of resources for deep semantic/instance/panoptic segmentation for thermal image
  </p>
</p>

<h2>Table of contents</h2>

- [1. Dataset for RGB-Thermal Segmentation](#1-dataset-for-rgb-thermal-segmentation)
- [2. Deep RGB-Thermal Segmentation](#2-deep-rgb-thermal-segmentation)
- [2-1. RGB-Thermal Semantic Segmentation](#21-rgb-thermal-semantic-segmentation)
- [3. Dataset for Thermal Segmentation](#3-dataset-for-thermal-segmentation)
- [4. Deep Thermal Segmentation](#4-deep-thermal-segmentation)
- [4-1. Thermal Semantic Segmentation](#41-thermal-semantic-segmentation)

# 1. Dataset for RGB-Thermal Segmentation

<h2>Dataset List</h2>

|Publication|Title|Sensor|Scene Types|Label Type|Highlight|Dataset Link|
|-|-|-|-|-|-|-|
IROS 17 | [Mfnet: Towards real-time semantic segmentation for autonomous vehicles with multispectral scenes](https://ieeexplore.ieee.org/abstract/document/8206396) | TBA | Outdoor | Semantic Seg | Aligned 820 day, 749 nighttime RGB-T images, 8 classes | [Here](https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/) |
ICRA 20 | [Pst900: Rgbthermal calibration, dataset and segmentation network](https://ieeexplore.ieee.org/abstract/document/9196831) | TBA | TBA | Semantic Seg | Aligned 894 RGB-T images, 4 classes | [Here](https://github.com/ShreyasSkandanS/pst900_thermal_rgb/blob/master/README.md) |
IROS 20 | [Heatnet: Bridging the day-night domain gap in semantic segmentation with thermal images](https://ieeexplore.ieee.org/abstract/document/9341192) | TBA | TBA | Semantic Seg | 32 day, 32 nighttime RGB-T images, 13 classes | [Here](http://thermal.cs.uni-freiburg.de/) |
RA-L 21 | [MS-UDA: Multi-Spectral Unsupervised Domain Adaptation for Thermal Image Semantic Segmentation](https://ieeexplore.ieee.org/document/9468936) | TBA | Outdoor | Semantic Seg | Aligned 950 Day-Night RGb-T images, 19 classes | [Here](https://github.com/yeong5366/MS-UDA) |

---


# 2. Deep RGB-Thermal Segmentation

## 2.1 RGB-Thermal Semantic Segmentation

<h2>Paper List</h2>

|Publication|Title|Code|Highlight|
|-|-|-|-|
IROS 17 | [Mfnet: Towards real-time semantic segmentation for autonomous vehicles with multispectral scenes](https://ieeexplore.ieee.org/abstract/document/8206396) | [Here](https://github.com/haqishen/MFNet-pytorch) | TBA |
RA-L 19 | [Rtfnet: Rgbthermal fusion network for semantic segmentation of urban scenes](https://ieeexplore.ieee.org/abstract/document/8666745) | [Here](https://github.com/yuxiangsun/RTFNet) | TBA | 
ICRA 20 | [Pst900: Rgbthermal calibration, dataset and segmentation network](https://ieeexplore.ieee.org/abstract/document/9196831) | [Here](https://github.com/ShreyasSkandanS/pst900_thermal_rgb) | TBA | 
T-ASE 20 | [Fuseseg: semantic segmentation of urban scenes based on rgb and thermal data fusion](https://ieeexplore.ieee.org/abstract/document/9108585) | Here | TBA | 
IROS 20 | [Heatnet: Bridging the day-night domain gap in semantic segmentation with thermal images](https://ieeexplore.ieee.org/abstract/document/9341192) | [Here](http://thermal.cs.uni-freiburg.de) | TBA |
IROS 21 | [FEANet: Feature-Enhanced Attention Network for RGB-Thermal Real-time Semantic Segmentation](https://ieeexplore.ieee.org/abstract/document/9636084) | Here | TBA | 
TIP 21 | [Gmnet: graded-feature multilabel-learning network for rgb-thermal urban scene semantic segmentation](https://ieeexplore.ieee.org/abstract/document/9531449/) | [Here](https://github.com/Jinfu0913/GMNet) | TBA | 
Applied Intelligence 21 | [Mmnet: Multimodal multi-stage network for rgb-t image semantic segmentation](https://link.springer.com/article/10.1007/s10489-021-02687-7) | Here | TBA | 
CVPR 21 | [Abmdrnet: Adaptive-weighted bi-directional modality difference reduction network for rgb-t semantic segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhang_ABMDRNet_Adaptive-Weighted_Bi-Directional_Modality_Difference_Reduction_Network_for_RGB-T_Semantic_CVPR_2021_paper.html) | Here | TBA | 
PRL 21 | [Attention fusion network for multi-spectral semantic segmentation](https://www.sciencedirect.com/science/article/pii/S0167865521001021) | Here | TBA | 
AAAI 22 | [Edge-aware Guidance Fusion Network for RGB–Thermal SceneParsing](https://www.aaai.org/AAAI22Papers/AAAI-2853.ZhouW.pdf) | [Here](https://github.com/ShaohuaDong2021/EGFNet) | TBA |
Neurocomputing 22 | [CCAFFMNet: Dual-spectral semantic segmentation network with channel-coordinate attention feature fusion module](https://www.sciencedirect.com/science/article/pii/S0925231221017331) | Here | TBA |
TIV 22 | [MTANet: Multitask-Aware Network with Hierarchical Multimodal Fusion for RGB-T Urban Scene Understanding](https://ieeexplore.ieee.org/abstract/document/9749834/) | [Here](https://github.com/ShaohuaDong2021/MTANet) | TBA | 
ACPR 22 | [ARTSeg: Employing Attention for Thermal Images Semantic Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-02375-0_27) | Here | TBA 
Arxiv 22 | [CMX: Cross-Modal Fusion for RGB-X Semantic Segmentation with Transformers](https://arxiv.org/pdf/2203.04838v2.pdf) | [Here](https://github.com/huaaaliu/rgbx_semantic_segmentation) | TBA | 


# 3. Dataset for Thermal Segmentation

<h2>Dataset List</h2>

|Publication|Title|Sensor|Scene Types|Label Type|Highlight|Dataset Link|
|-|-|-|-|-|-|-|
TNNLS 20 | [Segmenting objects in day and night: Edge-conditioned cnn for thermal image semantic segmentation](https://ieeexplore.ieee.org/abstract/document/9152142) | TBA | TBA | Semantic Seg | 2168 Real, 5000 synthetic images| [Here](https://github.com/ahucv/Homepage/blob/master/public/source/dataset.md) |
Infrared Physics & Technology 21 | [Mcnet: Multilevel correction network for thermal image semantic segmentation of nighttime driving scene](https://www.sciencedirect.com/science/article/pii/S1350449520306769) |  TBA | Outdoor | TBA | Semantic Seg | [Here](https://github.com/SCUT-CV/SCUT_FIR_Pedestrian_Dataset) |


---

# 4. Deep Thermal Segmentation

## 4.1 Thermal Semantic Segmentation

<h2>Paper List</h2>

|Publication|Title|Code|Highlight|
|-|-|-|-|
TNNLS 20 | [Segmenting objects in day and night: Edge-conditioned cnn for thermal image semantic segmentation](https://ieeexplore.ieee.org/abstract/document/9152142) | Here | TBA | 
Infrared Physics & Technology 21 | [Mcnet: Multilevel correction network for thermal image semantic segmentation of nighttime driving scene](https://www.sciencedirect.com/science/article/pii/S1350449520306769) | [Here](https://github.com/haitaobiyao/MCNet) | TBA | 
IEEE Access 21 | [Ftnet: Feature transverse network for thermal image semantic segmentation](https://ieeexplore.ieee.org/abstract/document/9585453) | [Here](https://github.com/shreyaskamathkm/FTNet)| TBA | 

---
