# Synthetic Data for Vision: Insights, Progress and Applications
A personal survey of Synthetic Data for Computer Vision

## Overview

This repository collects the studies on currunt progress of Synthetic Data for computer vision research.
<!-- including both [3D shape generation](#3d-shape-generation) and [3D-aware image generation](#3d-aware-image-generation).  -->
<!-- Different from 3D reconstruction, which focuses on per-instance recovery (*i.e.*, the data already exists in the real world), 3D generation targets learning the real distribution and hence allows sampling new data. -->

Overall, the paper collection is organized as follows. *If you find some work/repo/blog/talk is missing, feel free to raise an issue or create a pull request. We appreciate contributions in any form.*

- [Insightsn](#Insights)
- [Datasets]()
- [Application]()

## 1. Insights

- **[Talk]** **Toward an ImageNet Moment for Synthetic Data** by [Prof.Jia Deng](https://www.cs.princeton.edu/~jiadeng/)
| [Recording](https://youtu.be/XuqqZEVinwk?si=AfeUknyEZ707xrPp)

- **[Talk]** **N=0: Learning Vision Without Visual Data** by [Prof.Phillip Isola](https://web.mit.edu/phillipi/) | [Slides](https://www.dropbox.com/scl/fi/oc35cb8q8l3tfzyyvgybw/limit_workshop_cvpr2024.pdf?rlkey=mg4zp6etzm087yf2c58ypxexg&dl=0)

- **[Tutorial]** **Blender pipeline to generate images for deep learning**  | [Youtube](https://youtu.be/1AvY_iS6xQA?si=bi_V8bb3AGiFIE4_)

- **[Tutorial]** **Generating synthetic data for deep learning**  | [Youtube](https://youtu.be/lqbZdTLMyQw?si=DUjdBTtUGZrb_z-Y)

-  How Far is Video Generation from World Model?
— A Physical Law Perspective <br>
  [arxiv](https://arxiv.org/abs/2411.02385) / [Project Page](https://phyworld.github.io/) / [Code](https://github.com/phyworld/phyworld)

-  Scaling Laws of Synthetic Images for Model Training ... for Now <br>
  [CVPR 2024](https://arxiv.org/abs/2410.24213) / [Project Page](https://unicorn53547.github.io/video_syn_rep/) / [Code](https://github.com/google-research/syn-rep-learn) / [Youtube](https://www.youtube.com/watch?v=iiXQTR8dXcc)
<!-- CVPR 2024 Workshop on
Representation Learning with Very Limited Images 

Synthetic Data for Perception in Autonomous Driving https://www.youtube.com/watch?v=WbOfEz5MKpU -->

## 2. Datasets
<!-- CLEVR, FlyingThings, MPISintle, CARLA, MegaSynth, LRM-Zero, Hypersim, Kubric, PointOdessy, ParallelDomain, VirtualKITTI -->

<!-- - [**BlenderProc: A Procedural Pipeline for Photorealistic Rendering**](https://arxiv.org/abs/2402.10379) [Paper](https://arxiv.org/abs/1911.01911) [Code](https://github.com/DLR-RM/BlenderProc)   

- [**Zeroverse**]() [Paper]() [Code](https://github.com/hwjiang1510/MegaSynth) [Dataset](https://github.com/hwjiang1510/MegaSynth)

- [**MegaSynth: Scaling Up 3D Scene Renstruction with Synthesized Data**]() [Paper]() [Code](https://github.com/hwjiang1510/MegaSynth) 


FlyingThings3D FlyingChair

- [**Virtial KITTI: XX**]() [Paper]() [Code]()

- [**SyncCam: XX**]() [Paper]() [Code]() [Dataset](https://huggingface.co/datasets/KwaiVGI/SynCamVideo-Dataset) 

sintel 
 -->

 -  **FlyingThings3D**: A Large Dataset to Train Convolutional Networks for Disparity, Optical Flow, and Scene Flow Estimation <br>
  [CVPR 2016](https://arxiv.org/abs/1512.02134) / [Project Page](https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html)


 -  **Hypersim**: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding <br>
  [ICCV 2021](https://arxiv.org/abs/2011.02523)  / [Project Page](https://github.com/apple/ml-hypersim) / [Code](https://github.com/apple/ml-hypersim)

 -  **CLEVR**: A Diagnostic Dataset for
Compositional Language and Elementary Visual Reasoning <br>
  [CVPR2017](https://arxiv.org/abs/1612.06890) / [Project Page](https://cs.stanford.edu/people/jcjohns/clevr/) / [Code](https://github.com/facebookresearch/clevr-dataset-gen)

 -  **BEHAVIOR Vision Suite**: Customizable Dataset Generation via Simulation <br>
  [CVPR2024](https://arxiv.org/abs/2405.09546) / [Project Page](https://behavior-vision-suite.github.io/) / [Code](https://github.com/behavior-vision-suite/behavior-vision-suite.github.io)

-  **Kubric**: A scalable dataset generator <br>
  [CVPR2022](https://arxiv.org/abs/2203.03570) / [Project Page](https://kubric.readthedocs.io/en/latest/) / [Code](https://github.com/google-research/kubric)

-  **PointOdyssey** A Large-Scale Synthetic Dataset for Long-Term Point Tracking <br>
  [ICCV 2023](https://arxiv.org/abs/2307.15055) / [Project Page](https://pointodyssey.com/) / [Code](https://github.com/y-zheng18/point_odyssey)

-  **EgoGen**: An Egocentric Synthetic Data Generator <br>
  [CVPR 2024](https://arxiv.org/abs/2401.08739) / [Project Page](https://ego-gen.github.io/) / [Code](https://github.com/ligengen/EgoGen)

-  **MatrixCity**: A Large-scale City Dataset for City-scale Neural Rendering and Beyond <br>
  [ICCV 2023](https://arxiv.org/abs/2309.16553) / [Project Page](https://city-super.github.io/matrixcity/) / [Code](https://github.com/city-super/MatrixCity)

-  **TartanAir**: A Dataset to Push the Limits of Visual SLAM  <br>
  [IROS 2020](https://arxiv.org/abs/2003.14338) / [Project Page](https://theairlab.org/tartanair-dataset/)

-  **MotionSC**: Data Set and Network for Real-Time Semantic Mapping in Dynamic Environments <br>
  [arxiv 2022](https://arxiv.org/abs/2203.07060) / [Project Page](https://umich-curly.github.io/CarlaSC.github.io/) / [Code](https://github.com/UMich-CURLY/3DMapping)


## 3. Applications

### Visual Representation Learning

<!-- StableRep -->

 -  Learning to See by Looking at Noise <br>
  [NeurIPS 2021](https://arxiv.org/abs/2106.05963) / [Project Page](https://mbaradad.github.io/learning_with_noise/) / [Code](https://github.com/mbaradad/learning_with_noise)

 -  Procedural Image Programs for Representation Learning <br>
  [NeurIPS 2022](https://arxiv.org/abs/2211.16412) / [Project Page](https://mbaradad.github.io/learning_with_noise/) / [Code](https://github.com/mbaradad/shaders21k)

-  **StableRep**: Synthetic Images from Text-to-Image Models Make Strong Visual Representation Learners <br>
  [arxiv 2024](https://arxiv.org/abs/2410.24213) / [Code](https://github.com/google-research/)

-  Learning Vision from Models Rivals Learning Vision from Data <br>
  [CVPR 2024](https://arxiv.org/abs/2410.24213) / [Code](https://github.com/google-research/syn-rep-learn)

-  Visual Representation Learning from Synthetic Data <br>
  [Dr.Lijie Fan's Phd Thesis](https://dspace.mit.edu/handle/1721.1/156315)

-  Learning Video Representations without Natural Videos <br>
  [arxiv 2024](https://arxiv.org/abs/2410.24213) / [Project Page](https://unicorn53547.github.io/video_syn_rep/)

-  How Transferable are Video Representations Based on
Synthetic Data?<br>
  [NeurIPS 2022](https://arxiv.org/abs/2112.00054) / [Code](https://github.com/mintjohnkim/SynAPT)

-  Task2Sim : Towards Effective Pre-training and Transfer from Synthetic Data<br>
  [CVPR 2022](https://arxiv.org/abs/2112.00054)
  

### Depth Estimation

<!-- Marigold, DA-V2, ChronoDepth, DepthAnyVideo, DepthCrafter -->

-  **Marigold**: Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation <br>
  [CVPR 2024](https://arxiv.org/abs/2312.02145) / [Project Page](https://marigoldmonodepth.github.io/) / [Code](https://github.com/prs-eth/Marigold)

-  **Depth Anything V2** <br>
  [NeurIPS 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)

-  **GeoWizard**:  Unleashing the Diffusion Priors for 3D Geometry Estimation from a Single Image<br>
  [ECCV 2024](https://arxiv.org/abs/2403.12013) / [Project Page](https://fuxiao0719.github.io/projects/geowizard/) / [Code](https://github.com/fuxiao0719/GeoWizard)

-  **ChronoDepth**:  Learning Temporally Consistent Video Depth from Video Diffusion Priors<br>
  [arxiv 2024](https://arxiv.org/abs/2403.12013) / [Project Page](https://fuxiao0719.github.io/projects/geowizard/) / [Code](https://github.com/fuxiao0719/GeoWizard)

-  **Depth Any Video** with Scalable Synthetic Data <br>
  [arxiv 2024](https://arxiv.org/abs/2406.01493) / [Project Page](https://xdimlab.github.io/ChronoDepth/) / [Code](https://github.com/jiahao-shao1/ChronoDepth)

-  **DepthCrafter**: Generating Consistent Long Depth Sequences for Open-world Videos<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)


### Motion Estimation

<!-- TAPIR, cotracker, Spatracker -->

#### Optical&Scene Flow

<!-- RAFT -->

-  **FlowNet**: Learning Optical Flow with Convolutional Networks<br>
  [FlowNet ECCV 2020](https://arxiv.org/abs/1504.06852) / [FlowNet2 CVPR 2017](https://arxiv.org/pdf/1612.01925) / [FlowNet2 Official Code](https://github.com/lmb-freiburg/flownet2) / [FlowNet2 Pytorch Code](https://github.com/NVIDIA/flownet2-pytorch)

-  **PWC-Net**: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume<br>
  [CVPR 2018](https://arxiv.org/abs/1709.02371) / [Code](https://github.com/NVlabs/PWC-Net)

-  **RAFT**: Recurrent All Pairs Field Transforms for Optical Flow<br>
  [ECCV 2020](https://arxiv.org/abs/2003.12039) / [Code](https://github.com/princeton-vl/RAFT)

-  **RAFT-3D**: Scene Flow using Rigid-Motion Embeddings<br>
  [CVPR 2021](https://arxiv.org/abs/2012.00726) / [Code](https://github.com/princeton-vl/RAFT-3D)

-  **GMFlow**: Learning Optical Flow via Global Matching<br>
  [CVPR 2022](https://arxiv.org/abs/2111.13680) / [Code](https://github.com/haofeixu/gmflow)

-  **SEA-RAFT**: Simple, Efficient, Accurate RAFT for Optical Flow<br>
  [ECCV 2024](https://arxiv.org/abs/2406.09414) / [Code](https://github.com/princeton-vl/SEA-RAFT)


#### Tracking Any Points

<!-- TAPIR, Cotracker, SpaTracker -->
-  **Particle Video Revisited**: Tracking Through Occlusions Using Point Trajectories<br>
  [ECCV 2022](https://arxiv.org/abs/2204.04153) / [Project Page](hhttps://particle-video-revisited.github.io/) / [Code](https://github.com/aharley/pips)

-  **TAPIR**: Tracking Any Point with per-frame Initialization and temporal Refinement<br>
[ICCV 2023](https://arxiv.org/abs/2306.08637) / [Project Page](https://deepmind-tapir.github.io/) / [Code](https://github.com/google-deepmind/tapnet)

-  **CoTracker**: It is Better to Track Together<br>
  [CoTracker ECCV 2024](https://arxiv.org/abs/2307.07635) / [CoTrackerV3 arxiv 2024](https://arxiv.org/abs/2410.11831) / [Project Page](https://github.com/facebookresearch/co-tracker) / [Code](https://github.com/facebookresearch/co-tracker)

-  **SpatialTracker**: Tracking Any 2D Pixels in 3D Space<br>
  [CVPR 2024](https://arxiv.org/abs/2404.04319) / [Project Page](https://henry123-boy.github.io/SpaTracker/) / [Code](https://github.com/henry123-boy/SpaTracker)

-  **LocoTrack**: Local All-Pair Correspondence for Point Tracking<br>
  [ECCV 2024](https://arxiv.org/abs/2407.15420) /[Project Page](https://ku-cvlab.github.io/locotrack/) / [Code](https://github.com/cvlab-kaist/locotrack)


### 3D Reconstruction

<!-- LRM Zero, MegaSynth -->
-  **DROID-SLAM**: Deep Visual SLAM for Monocular,
Stereo, and RGB-D Cameras<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)
  

-  **LRM-Zero**: Training Large Reconstruction Models with Synthesized Data<br>
  [NeurIPS 2024](https://arxiv.org/abs/2406.09371) / [Project Page](https://desaixie.github.io/lrm-zero/) / [Code](https://github.com/desaixie/zeroverse)

-  **MegaSynth**: Scaling Up 3D Scene Reconstruction with Synthesized Data<br>
  [arxiv 2024](https://arxiv.org/abs/2412.14166) / [Project Page](https://hwjiang1510.github.io/MegaSynth/) / [Code](https://github.com/desaixie/zeroverse)


### Visual Content Genereation

<!-- ### Video Generation -->
<!-- SyncCamMaster, TrajCamMaster, GCD, simgen-->


-  **SimGen**: Simulator-conditioned Driving Scene Generation<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09386) / [Project Page](https://metadriverse.github.io/simgen/) / [Code](https://github.com/metadriverse/SimGen)

-  **Generative Camera Dolly**: Extreme Monocular Dynamic Novel View Synthesis<br>
  [arxiv 2024](https://arxiv.org/abs/2412.07759) / [Project Page](https://gcd.cs.columbia.edu/) / [Code](https://github.com/basilevh/gcd)

-  **3DTrajMaster**: Mastering 3D Trajectory for Multi-Entity Motion in Video Generation<br>
  [arxiv 2024](https://arxiv.org/abs/2412.07759) / [Project Page](https://fuxiao0719.github.io/projects/3dtrajmaster/) / [Code](https://github.com/KwaiVGI/3DTrajMaster)

-  **SynCamMaster**: Synchronizing Multi-Camera Video Generation from Diverse Viewpoints<br>
  [arxiv 2024](https://arxiv.org/abs/2412.07760) / [Project Page](https://jianhongbai.github.io/SynCamMaster/) / [Code](https://github.com/KwaiVGI/SynCamMaster)



### Autonomous Driving & Robotic

TODO

<!-- https://lucidsim.github.io/