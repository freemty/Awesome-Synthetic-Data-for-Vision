# Synthetic Data for Vision: Insights, Progress and Applications
A personal survey of Synthetic Data for Computer Vision

## Overview

This repository collects the studies on 3D generation currunt progress of Synthetic Datta for computer vision research.
<!-- including both [3D shape generation](#3d-shape-generation) and [3D-aware image generation](#3d-aware-image-generation).  -->
<!-- Different from 3D reconstruction, which focuses on per-instance recovery (*i.e.*, the data already exists in the real world), 3D generation targets learning the real distribution and hence allows sampling new data. -->

Overall, the paper collection is organized as follows. *If you find some work/repo/blog/talk is missing, feel free to raise an issue or create a pull request. We appreciate contributions in any form.*

<!-- - [Insights of Synthetic Data for Vision](#Insights-of-Synthetic-Data-for-Vision)
  - [Talk](#voxel-1)

- [Synthetic Data Generation](#Synthetic-Data-Generation)
- [Insights of Synthetic for Vision](#3d-control-of-2d-generative-models)
  - [Released Datasets](#Released-Datasets)
  - [Codebase](#Codebase)

- [Synthetic Data Applicatuon](#Synthetic-Data-Application) -->


## 1. Insights

- **[Talk]** **Toward an ImageNet Moment for Synthetic Data**  *[Prof.Jia Deng](https://www.cs.princeton.edu/~jiadeng/)* 2024 [Toutube](https://youtu.be/XuqqZEVinwk?si=AfeUknyEZ707xrPp)


<!-- - **[Talk]** **Scaling Laws of Synthetic Images for Model Training ... for Now**  *[Prof.Jia Deng](https://www.cs.princeton.edu/~jiadeng/)* 2024 [Toutube](https://youtu.be/XuqqZEVinwk?si=AfeUknyEZ707xrPp)


CVPR 2024 Workshop on
Representation Learning with Very Limited Images -->

<!-- https://www.youtube.com/watch?v=lqbZdTLMyQw&t=103s -->

<!-- https://www.youtube.com/watch?v=1AvY_iS6xQA -->

<!-- - **[Talk]** **Generating synthetic data for deep learning**  *[Prof.Jia Deng](https://www.cs.princeton.edu/~jiadeng/)* 2024 [Toutube](https://youtu.be/XuqqZEVinwk?si=AfeUknyEZ707xrPp)

Synthetic Data for Perception in Autonomous Driving https://www.youtube.com/watch?v=WbOfEz5MKpU -->


## 2. Datasets
<!-- CLEVR, FlyingThings, MPISintle, CARLA, MegaSynth, LRM-Zero, Hypersim, Kubric, PointOdessy, ParallelDomain, VirtualKITTI -->



<!-- - [**Kubric: a scalable dataset generator**]() [Paper]() [Code]() 

- [**BlenderProc: A Procedural Pipeline for Photorealistic Rendering**](https://arxiv.org/abs/2402.10379) [Paper](https://arxiv.org/abs/1911.01911) [Code](https://github.com/DLR-RM/BlenderProc)  -->


<!-- - [**PointOdessy: A Large-Scale Synthetic Dataset for Long-Term Point Tracking**]() [Paper]() [Code](https://github.com/y-zheng18/point_odyssey) 

- [**Zeroverse**]() [Paper]() [Code](https://github.com/hwjiang1510/MegaSynth) [Dataset](https://github.com/hwjiang1510/MegaSynth)

- [**MegaSynth: Scaling Up 3D Scene Renstruction with Synthesized Data**]() [Paper]() [Code](https://github.com/hwjiang1510/MegaSynth) 

- [**EgoGen: An Egocentric Synthetic Data Generator**]() [Paper]() [Code]()

- [**Behivor Suite: XX**]() [Paper]() [Code]()

- [**Flying Things: XX**]() [Paper]() [Code]()

- [**Virtial KITTI: XX**]() [Paper]() [Code]()

- [**SyncCam: XX**]() [Paper]() [Code]() [Dataset](https://huggingface.co/datasets/KwaiVGI/SynCamVideo-Dataset) 

- [**Virtial KITTI: XX**]() [Paper]() [Code]() 

- [**Hypersim: XX**]() [Paper]() [Code]() 

- [**CarlaSC: XX**]() [Paper]() [Code]() 

- [**MatrixCity: XX**]() [Paper]() [Code]() 

- [**TartianAir: XX**]() [Paper]() [Code]()  -->


## 3. Applacations

### Visual Representation Lrarning

<!-- StableRep -->
<!-- 

Learning Video Representations without Natural Videos

How Transferable are Video Representations Based on Synthetic Data?

Task2Sim : Towards Effective Pre-training and Transfer from Synthetic Data


StableRep: Synthetic Images from Text-to-Image
Models Make Strong Visual Representation Learners

Learning Vision from Models Rivals Learning Vision from Data



-  Scaling Laws of Synthetic Images for Model Training ... for Now <br>
  [CVPR 2024](https://arxiv.org/abs/2312.02145) / [Project Page](https://marigoldmonodepth.github.io/) / [Code](https://github.com/prs-eth/Marigold)



-  Visual Representation Learning from Synthetic Data <br>
  [Phd Thesis](https://arxiv.org/abs/2312.02145) -->


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
  [arxiv2024](https://arxiv.org/abs/2406.01493) / [Project Page](https://xdimlab.github.io/ChronoDepth/) / [Code](https://github.com/jiahao-shao1/ChronoDepth)

-  **DepthCrafter**: Generating Consistent Long Depth Sequences for Open-world Videos<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)


### Motion Estimation

<!-- TAPIR, cotracker, Spatracker -->

#### Optical&Scene Flow

<!-- RAFT -->

-  **SEA-RAFT**: Simple, Efficient, Accurate RAFT for Optical Flow<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/princeton-vl/SEA-RAFT)

-  **SEA-RAFT**: Simple, Efficient, Accurate RAFT for Optical Flow<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/princeton-vl/SEA-RAFT)

  
-  **SEA-RAFT**: Simple, Efficient, Accurate RAFT for Optical Flow<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/princeton-vl/SEA-RAFT)


#### Tracking Any Points

<!-- TAPIR, Cotracker, SpaTracker -->
-  **Particle Video Revisited**: Tracking Through Occlusions Using Point Trajectories<br>
  [ECCV 2022](https://arxiv.org/abs/2204.04153) / [Project Page](hhttps://particle-video-revisited.github.io/) / [Code](https://github.com/aharley/pips)

-  **TAPIR**: Tracking Any Point with per-frame Initialization and temporal Refinement<br>
[ICCV 2023](https://arxiv.org/abs/2306.08637) / [Project Page](https://deepmind-tapir.github.io/) / [Code](https://github.com/google-deepmind/tapnet)

-  **CoTracker**: It is Better to Track Together<br>
  [V2@ECCV 2024](https://arxiv.org/abs/2307.07635) / [V3@arxiv 2024](https://arxiv.org/abs/2410.11831) / [Project Page](https://github.com/facebookresearch/co-tracker) / [Code](https://github.com/facebookresearch/co-tracker)

-  **SpatialTracker**: Tracking Any 2D Pixels in 3D Space<br>
  [CVPR 2024](https://arxiv.org/abs/2404.04319) / [Project Page](https://henry123-boy.github.io/SpaTracker/) / [Code](https://github.com/henry123-boy/SpaTracker)

-  **LocoTrack**: Local All-Pair Correspondence for Point Tracking<br>
  [ECCV 2024](https://arxiv.org/abs/2407.15420) /[Project Page](https://ku-cvlab.github.io/locotrack/) / [Code](https://github.com/cvlab-kaist/locotrack)



### 3D Reconstruction

<!-- LRM Zero, MegaSynth -->
-  **DROID-SLAM**: Deep Visual SLAM for Monocular,
Stereo, and RGB-D Cameras<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)
  
<!-- 
-  **LRM Zero**: Generating Consistent Long Depth Sequences for Open-world Videos<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)

-  **MegaSynth**: Generating Consistent Long Depth Sequences for Open-world Videos<br>
  [arxiv 2024](https://arxiv.org/abs/2406.09414) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2) -->



### Visual Content Genereation

### Video Generation
<!-- SyncCamMaster, TrajCamMaster, GCD, simgen-->

-  Generative Camera Dolly:<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://metadriverse.github.io/simgen/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)


-  TrajCamMaster<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)

-  SyncCamMaster: Deep Visual SLAM for Monocular,
Stereo, and RGB-D Cameras<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://depth-anything-v2.github.io/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)

-  **DROID-SLAM**: Deep Visual SLAM for Monocular,
Stereo, and RGB-D Cameras<br>
  [arxiv 2024](https://arxiv.org/pdf/2108.10869) / [Project Page](https://metadriverse.github.io/simgen/) / [Code](https://github.com/DepthAnything/Depth-Anything-V2)




### Driving

### Robotic

<!-- https://lucidsim.github.io/ -->

