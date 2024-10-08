# awesome-human-human-interaction
A curated list of awesome human-human interaction (HHI) resources. If you find any errors or problems, please don't hesitate to comment.


#### Table of Contents
* [Datasets](#datasets)
* [Papers](#recent-papers)
    * [HHI Generation](#hhi-generation)
    * [HHI Reconstruction](#hhi-reconstruction)
    * [HHI Detection](#hhi-detection)
    * [Reaction Generation](#reaction-generation)

## Datasets

| Dataset | Year | Motions | Frames | Texts | Scheme | Modality |
| ---------- | :-----------:  | :-----------:  | :-----------: | :-----------: | :-----------: | :-----------: |
| [UMPM](https://www.projects.science.uu.nl/umpm/) | 2011 | 36 | 400K | No | MoCap | Skeleton |
| [SBU Kinect](http://vision.cs.stonybrook.edu/~kiwon/Datasets/SBU_Kinect_Interactions/README.txt) | 2012 | 300 | 7.5K | No | RGB+D | Skeleton |
| [You2Me](https://vision.cs.utexas.edu/projects/you2me/) | 2020 | 42 | 77K | No | RGB+D | Skeleton |
| [NTU RGB+D 120](https://rose1.ntu.edu.sg/dataset/actionRecognition/) | 2019 | 8,276 | 462K | No | RGB+D | Skeleton |
| [Chi3D](https://ci3d.imar.ro/chi3d) | 2020 | 373 | 63K | No | MoCap | SMPL-X | 
| [ExPI](https://team.inria.fr/robotlearn/research/expi-dataset/) | 2022 | 115 | 30K | No | Multi RGB | Skeleton |
| [GTA Combat](https://liangxuy.github.io/actformer/) | 2023 | 6.8K | 2.05M | No | Synthetic | Skeleton | 
| [Hi4D](https://yifeiyin04.github.io/Hi4D/) | 2023 | 100 | 11K | No | Multi RGB | SMPL |
| [InterHuman](https://tr3e.github.io/intergen-page/) | 2023 | 6,022 | 1.7M | Yes | Multi RGB | SMPL |
| [Inter-X](https://liangxuy.github.io/inter-x/) | 2024 | 11,388 | 8.1M | Yes | MoCap | SMPL-X, Skeleton |
| [ReMoCap](https://vcai.mpi-inf.mpg.de/projects/remos/) | 2024 | 87 | 275.7K | No | Multi RGB | Skeleton |


## Recent Papers

<!-- ****, __ [[Paper]](), [[Project]](), [[Code]]() -->

### HHI Generation

- **CORE4D: A 4D Human-Object-Human Interaction Dataset for Collaborative Object REarrangement**, _arxiv 2024.06_ [[Paper]](https://arxiv.org/abs/2406.19353), [[Project]](https://core4d.github.io/), [[Code]](https://github.com/leolyliu/CORE4D-Instructions)

- **Inter-X: Towards Versatile Human-Human Interaction Analysis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2312.16051), [[Project]](https://liangxuy.github.io/inter-x/), [[Code&Data]](https://github.com/liangxuy/Inter-X)

- **ContactGen: Contact-Guided Interactive 3D Human Generation for Partners**, _AAAI'24_ [[Paper]](https://arxiv.org/abs/2401.17212), [[Project]](https://dongjunku.github.io/contactgen/), [[Code]](https://github.com/dongjunKu/ContactGen/)

- **InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions**, _IJCV'24_ [[Paper]](https://arxiv.org/abs/2304.05684), [[Project]](https://tr3e.github.io/intergen-page/), [[Code&Data]](https://drive.google.com/drive/folders/1oyozJ4E7Sqgsr7Q747Na35tWo5CjNYk3)

- **ActFormer: A GAN-based Transformer towards General Action-Conditioned 3D Human Motion Generation**, _ICCV'23_ [[Paper]](https://arxiv.org/abs/2203.07706), [[Project]](https://liangxuy.github.io/actformer/), [[Code]](https://github.com/Szy-Young/actformer)

- **PriorMDM: Human Motion Diffusion as a Generative Prior**, _ICLR'24_ [[Paper]](https://arxiv.org/abs/2303.01418), [[Project]](https://priormdm.github.io/priorMDM-page/), [[Code]](https://github.com/priorMDM/priorMDM)

- **Neural Animation Layering for Synthesizing Martial Arts Movements**, _SIGGRAPH 2021_ [[Paper]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2021/Paper.pdf)

- **Local Motion Phases for Learning Multi-Contact Character Movements**, _SIGGRAPH 2020_ [[Paper]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2020/Paper.pdf), [[Code]](https://github.com/sebastianstarke/AI4Animation/tree/master/AI4Animation/SIGGRAPH_2020)


### HHI Reconstruction

- **AvatarPose: Avatar-guided 3D Pose Estimation of Close Human Interaction from Sparse Multi-view Videos**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2408.02110), [[Project]](https://feichilu.github.io/AvatarPose/)

- **Capturing Closely Interacted Two-Person Motions with Reaction Priors**, _CVPR'24_ [[Paper]](https://netease-gameai.github.io/Dual-Human/static/assets/CVPR2024_DualHuman.pdf), [[Project]](https://netease-gameai.github.io/Dual-Human/)

- **Pose Priors from Language Models**, _arXiV 2024.05_ [[Paper]](https://arxiv.org/abs/2405.03689)

- **MultiPhys: Multi-Person Physics-aware 3D Motion Estimation**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2404.11987), [[Project]](http://www.iri.upc.edu/people/nugrinovic/multiphys/), [[Code]](https://github.com/nicolasugrinovic/multiphys)

- **Closely Interactive Human Reconstruction with Proxemics and Physics-Guided Adaption**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2404.11291), [[Code]](https://github.com/boycehbz/HumanInteraction)

- **MultiPhys: Multi-Person Physics-aware 3D Motion Estimation**, _arXiv 2024.04_ [[Paper]](https://arxiv.org/abs/2404.11987), [[Project]](http://www.iri.upc.edu/people/nugrinovic/multiphys/), [[Code]](https://github.com/nicolasugrinovic/multiphys)

- **Reconstructing Close Human Interactions from Multiple Views**, _SIGGRAPH Asia'23_ [[Paper]](https://arxiv.org/abs/2401.16173), [[Code]](https://github.com/zju3dv/CloseMoCap)

- **Hi4D: 4D Instance Segmentation of Close Human Interaction**, _CVPR'23_ [[Paper]](https://arxiv.org/abs/2303.15380v1), [[Project]](https://yifeiyin04.github.io/Hi4D/), [[Code&Data]](https://github.com/yifeiyin04/Hi4D)

- **Multi-Person Extreme Motion Prediction**, _CVPR'22_ [[Paper]](https://arxiv.org/abs/2105.08825), [[Project]](https://team.inria.fr/robotlearn/multi-person-extreme-motion-prediction/), [[Code]](https://github.com/GUO-W/MultiMotion)


### HHI Detection

- **Nonverbal Interaction Detection**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2407.08133), [[Code]](https://github.com/weijianan1/NVI)

- **SportsHHI: A Dataset for Human-Human Interaction Detection in Sports Videos**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2404.04565), [[Code]](https://github.com/MCG-NJU/SportsHHI)

- **Inter-X: Towards Versatile Human-Human Interaction Analysis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2312.16051), [[Project]](https://liangxuy.github.io/inter-x/), [[Code&Data]](https://github.com/liangxuy/Inter-X)

- **IGFormer: Interaction Graph Transformer for Skeleton-based Human Interaction Recognition**, _ECCV'22_ [[Paper]](https://arxiv.org/abs/2207.12100)

- **Human-to-Human Interaction Detection**, _arXiv 2023.07_ [[Paper]](https://arxiv.org/abs/2307.00464)


### Reaction Generation

- **PhysReaction: Physically Plausible Real-Time Humanoid Reaction Synthesis via Forward Dynamics Guided 4D Imitation**, _arXiv 2024.04_ [[Paper]](https://arxiv.org/abs/2404.01081), [[Project]](https://yunzeliu.github.io/PhysReaction/)

- **Inter-X: Towards Versatile Human-Human Interaction Analysis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2312.16051), [[Project]](https://liangxuy.github.io/inter-x/), [[Code&Data]](https://github.com/liangxuy/Inter-X)

- **ReGenNet: Towards Human Action-Reaction Synthesis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2403.11882), [[Project]](https://liangxuy.github.io/ReGenNet/), [[Code]](https://github.com/liangxuy/ReGenNet)

- **Interactive Humanoid: Online Full-Body Motion Reaction Synthesis with Social Affordance Canonicalization and Forecasting**, _arXiv 2023.12_ [[Paper]](https://arxiv.org/abs/2312.08983), [[Project]](https://yunzeliu.github.io/iHuman/)

- **Role-aware Interaction Generation from Textual Description**, _ICCV'23_ [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Tanaka_Role-Aware_Interaction_Generation_from_Textual_Description_ICCV_2023_paper.html), [[Code]](https://github.com/line/Human-Interaction-Generation)

- **ReMoS: 3D Motion-Conditioned Reaction Synthesis for Two-Person Interactions**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2311.17057), [[Project]](https://vcai.mpi-inf.mpg.de/projects/remos/)

- **Interaction transformer for human reaction generation**, _TMM'23_ [[Paper]](https://arxiv.org/abs/2207.01685)