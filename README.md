# awesome-3d-detector-2021
3d-detector papers within year 2021, including CVPR, ICRA, ICLR, AAAI, ICCV, ACM MM, arXiv, etc.

## Paper List (before 2021.9)

| Pub.     | Org.   | Title | Remark |
| :-----   | :----: | :----: | :---- |
| ICCV2021 | CUHK, HUAWEI Noah | Pyramid R-CNN:Towards Better Performance and Adaptability for 3D Object Detection | det:kitti,Waymo |
| ICCV2021 | QCraft | Exploring Simple 3D Multi-Object Tracking for Autonomous Driving | tracking |
| ICCV2021(oral) |Tsinghua | PoinTr: Diverse Point Cloud Completion with Geometry-Aware Transformers | point completion |
| ICCV2021 |CUHK, HUAWEI Noah | VoTr: Voxel Transformer for 3D Object Detection | det:kitti,Waymo |
| ICCV2021 |USC, Waymo | SPG: Unsupervised Domain Adaptation for 3D Object Detection via Semantic Point Generation |  det:kitti,Waymo |
| ICCV2021 | Zhejiang University, DAMO Academy | Improving 3D Object Detection with Channel-wise Transformer |  det:kitti, Waymo |
| ICCV2021 | FAIR | An End-to-End Transformer Model for 3D Object Detection |  det:ScanNet |
| CVPR2021 | Southeast University, NUST | SIENet: Spatial Information Enhancement Network for 3D Object Detection from Point Cloud |  det:kitti |
| CVPR2021 | Yonsei University | HVPR: Hybrid Voxel-Point Representation for Single-stage 3D Object Detection |  det:kitti |
| CVPR2021 | CUHK | SE-SSD: Self-Ensembling Single-Stage Object Detector From Point Cloud) |  det:kitti |
| CVPR2021 | Waymo, Google brain | To the Point: Efficient 3D Object Detection in the Range Image with Graph Convolution Kernels |  det:Waymo |
| CVPR2021 | TuSimple | LiDAR R-CNN: An Efficient and Universal 3D Object Detector |  det:kitti,Waymo |
| CVPR2021 | beihang | Back-tracing Representative Points for Voting-based 3D Object Detection in Point Clouds |  indoor det |
| CVPR2021 | University of Hong Kong | ST3D: Self-training for Unsupervised Domain Adaptation on 3D Object Detection |  domain adaptation:kitti,waymo,nuScenes |
| CVPR2021 | Stanford University | 3DIoUMatch: Leveraging IoU Prediction for Semi-Supervised 3D Object Detection |  semi supervised det:kitti |
| CVPR2021 | CUHK | Bidirectional Projection Network for Cross Dimension Scene Understanding |  2D,3D seg |
| CVPR2021 |  Tsinghua University | PV-RAFT: Point-Voxel Correlation Fields for Scene Flow Estimation of Point Clouds | estimate scene flow from point clouds |
| CVPR2021 | HKUST | FFB6D：A Full Flow Bidirectional Fusion Network for 6D Pose Estimation |  RGBD:fuse RGB & D |
| CVPR2021 | CUHK | Point Cloud Upsampling via Disentangled Refinement | generative model & upsample |
| CVPR2021 | Peking University | Diffusion Probabilistic Models for 3D Point Cloud Generation | generative model & upsample(best paper finalist) |
| CVPR2021 | Stanford University | Rethinking Sampling in 3D Point Cloud GANs | generative model & upsample |
| CVPR2021WAD | Horizon Robotics | 1st Place Solution for Waymo Open Dataset Challenge  |  det: Waymo |
| CVPR2021 | ReLER | Point 4D Transformer Networks for Spatio-Temporal Modeling in Point Cloud Videos. | Point Cloud Videos |
| ICLR2021 | National University of Singapore | PSTNet: Point Spatio-Temporal Convolution on Point Cloud Sequences |  point cloud sequences/vedio |
| ICRA2021 | BNRist, Tsinghua | FGR: Frustum-Aware Geometric Reasoning for Weakly Supervised 3D Vehicle Detection | det:kitti |
| AAAI2021 | CUHK | CIA-SSD: Confident IoU-Aware Single-Stage Object Detector From Point Cloud |  det:kitti |
| AAAI2021 | USTC | Voxel R-CNN: Towards High Performance Voxel-based 3D Object Detection |  det:kitti |
| arXiv 2021.3 | CUHK, Google, Waymo | 3D-MAN: 3D Multi-frame Attention Network for Object Detection |  det:Waymo |
| arXiv 2021.4 | USTC,MSRA | Group-Free 3D Object Detection via Transformers |  indoor det |
| arXiv 2021.4 | University of Maryland, Fudan | M3DETR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers | det:kitti,Waymo |
| arXiv 2021.5 | Renmin University of China | Boundary-Aware 3D Object Detection from Point Clouds |  det:kitti |
| arXiv 2021.5 | Zhejiang University | X-view: Non-egocentric Multi-View 3D Object Detector |  det:kitti, nuScenes |
| arXiv 2021.6 | Baidu | FusionPainting: Multimodal Fusion with Adaptive Attention for 3D Object  Detection |  det:nuScenes |
| arXiv 2021.6 | Google, Waymo | RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection |  det:Waymo |
| arXiv 2021.7 | Google, Waymo | Lidar Light Scattering Augmentation (LISA): Physics-based Simulation of AdverseWeather Conditions for 3D Object Detection | 3D augmentation|
| arXiv 2021.7 | HUKST | DV-Det: Efficient 3D Point Cloud Object Detection with Dynamic Voxelization | det:kitti|
| arXiv 2021.8 | Horizon | Real-Time Anchor-Free Single-Stage 3D Detection with IoU-Awareness | det:Waymo|
| arXiv 2021.8 | Xi'an Jiaotong University | MBDF-Net: Multi-Branch Deep Fusion Network for 3D Object Detection | det:kitti|
| arXiv 2021.8 | Baidu | AutoShape: Real-Time Shape-Aware Monocular 3D Object Detection | det:kitti|
| ACM MM21 | Zhejiang University | From Voxel to Point: IoU-guided 3D Object Detection for Point Cloud with Voxel-to-Point Decoder| det:kitti|
| ACM MM21 | Zhejiang University | Anchor-free 3D Single Stage Detector with Mask-Guided Attention for Point Cloud| det:kitti|

## KITTI paper
| Pub.     | Title. |  car moderate AP(test) |  Remark |
| :-----   | :----: | :----: | :----: |
| ICCV2021 | Pyramid R-CNN:Towards Better Performance and Adaptability for 3D Object Detection |  82.08 |   -   |
| ICCV2021 | VoTr: Voxel Transformer for 3D Object Detection |  82.09 |   Voxel-Transformer   |
| ICCV2021 | Improving 3D Object Detection with Channel-wise Transformer |  81.77 |   Transformer   |
| ICCV2021 | SPG: Unsupervised Domain Adaptation for 3D Object Detection via Semantic Point Generation |  82.13 |   Domain adapation   |
| CVPR2021 | SIENet: Spatial Information Enhancement Network for 3D Object Detection from Point Cloud |  81.71 |   -   |
| CVPR2021 | HVPR: Hybrid Voxel-Point Representation for Single-stage 3D Object Detection |  77.92 |   36.1Hz    |
| CVPR2021 | SE-SSD: Self-Ensembling Single-Stage Object Detector From Point Cloud) |  82.57 |   30.56ms    |
| CVPR2021 | LiDAR R-CNN: An Efficient and Universal 3D Object Detector |  74.21 |   based on pointpillar(increase 1.4mAP)    |
| ICRA2021 | FGR: Frustum-Aware Geometric Reasoning for Weakly Supervised 3D Vehicle Detection |  68.47 |   without 3D label    |
| AAAI2021 | CIA-SSD: Confident IoU-Aware Single-Stage Object Detector From Point Cloud |  80.28 |   32FPS    |
| AAAI2021 | Voxel R-CNN: Towards High Performance Voxel-based 3D Object Detection |  81.62 |   25FPS    |
| arXiv 2021.4 | M3DETR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers |  81.73 |  Transformers based   |
| arXiv 2021.5 | Boundary-Aware 3D Object Detection from Point Clouds |  81.61 |   car bev rank 1st    |
| arXiv 2021.5 | X-view: Non-egocentric Multi-View 3D Object Detector |  81.35 |   Non-egocentric Multi-View    |
| arXiv 2021.7 | DV-Det: Efficient 3D Point Cloud Object Detection with Dynamic Voxelization |  76.74 |  75FPS    |
| arXiv 2021.8 | MBDF-Net: Multi-Branch Deep Fusion Network for 3D Object Detection |  80.00 |  multi-modal    |
| arXiv 2021.8 | AutoShape: Real-Time Shape-Aware Monocular 3D Object Detection |  14.17 |  mono    |
| ACM MM21 | From Voxel to Point: IoU-guided 3D Object Detection for Point Cloud with Voxel-to-Point Decoder |  81.58 |  -    |
| ACM MM21 | Anchor-free 3D Single Stage Detector with Mask-Guided Attention for Point Cloud |  79.68 |  -    |

## nuScenes paper
| Pub.     | Title. |  mAP(val) |  NDS(val) |
| :-----   | :----: | :----: | :----: |
| arXiv 2021.5 | X-view: Non-egocentric Multi-View 3D Object Detector |  51.69 |  63.76     |
| arXiv 2021.6 | FusionPainting: Multimodal Fusion with Adaptive Attention for 3D Object  Detection |  66.53 |  70.68     |


## Waymo paper
| Pub.     | Title. | vehicle 3D APH L2(val) |  Pedestrian 3D APH L2(val) |
| :-----   | :----: | :----: | :----: |
| ICCV2021 | Pyramid R-CNN:Towards Better Performance and Adaptability for 3D Object Detection |  66.68 |  -   |
| ICCV2021 | VoTr: Voxel Transformer for 3D Object Detection |  65.29 |  -   |
| ICCV2021 | Improving 3D Object Detection with Channel-wise Transformer |  69.04 |   -   | 
| ICCV2021 | SPG: Unsupervised Domain Adaptation for 3D Object Detection via Semantic Point Generation |  65.98 |   57.68   |
| CVPR2021 | To the Point: Efficient 3D Object Detection in the Range Image with Graph Convolution Kernels |  56.7 |  61.5  |
| CVPR2021 | LiDAR R-CNN: An Efficient and Universal 3D Object Detector |  64.2 |  51.7  |
| CVPR2021WAD | 1st Place Solution for Waymo Open Dataset Challenge |  77.83 |  76.6  |
| arXiv 2021.3 | 3D-MAN: 3D Multi-frame Attention Network for Object Detection |  67.14 |  59.04  |
| arXiv 2021.4 | M3DETR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers |  66.02 | -  |
| arXiv 2021.6 | RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection |  69.5 |  69.9  |
| arXiv 2021.8 | Real-Time Anchor-Free Single-Stage 3D Detection with IoU-Awareness |  73.89 | 72.41  |