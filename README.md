# awesome-human-human-interaction
A curated list of awesome human-human interaction (HHI) resources. If you find any errors or problems, please don't hesitate to comment.


#### Table of Contents
* [Datasets](#datasets)
* [Papers](#recent-papers)
    * [HHI Generation](#hhi-generation)
    * [HHI Reconstruction](#hhi-reconstruction)
    * [HHI Detection](#hhi-detection)
    * [Reaction Generation](#reaction-generation)
    * [Group Interaction](#group-interaction)

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
| [InterDance](https://inter-dance.github.io/) | 2025 | - | 3.93hours | No | MoCap | SMPL-X |

## Recent Papers

<!-- ****, __ [[Paper]](), [[Project]](), [[Code]]() -->

### HHI Generation

- **InterAct: A Large-Scale Dataset of Dynamic, Expressive and Interactive Activities between Two People in Daily Scenarios**, _SCA'25_ [[Paper]](https://arxiv.org/abs/2509.05747), [[Project]](https://hku-cg.github.io/interact/)

- **Perceiving and Acting in First-Person: A Dataset and Benchmark for Egocentric Human-Object-Human Interactions**, _ICCV'25_ [[Paper]](https://arxiv.org/abs/2508.04681), [[Project]](https://liangxuy.github.io/InterVLA/)

- **Towards Immersive Human-X Interaction: A Real-Time Framework for Physically Plausible Motion Synthesis**, _ICCV'25_ [[Paper]](https://arxiv.org/abs/2508.02106), [[Project]](https://humanx-interaction.github.io/)

- **DuetGen: Music Driven Two-Person Dance Generation via Hierarchical Masked Modeling**, _SIGGRAPH'25_ [[Paper]](https://arxiv.org/abs/2506.18680), [[Project]](https://anindita127.github.io/DuetGen/), [[Code]](https://github.com/anindita127/DuetGen)

- **PhysiInter: Integrating Physical Mapping for High-Fidelity Human Interaction Generation**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2506.07456)

- **InterMamba: Efficient Human-Human Interaction Generation with Adaptive Spatio-Temporal Mamba**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2506.03084)

- **Dyadic Mamba: Long-term Dyadic Human Motion Synthesis**, CVPRW'25_ [[Paper]](https://arxiv.org/abs/2505.09827)

- **InterMask: 3D Human Interaction Generation via Collaborative Masked Modeling**, _ICLR'25_ [[Paper]](https://arxiv.org/abs/2410.10010), [[Project]](https://gohar-malik.github.io/intermask/), [[Code]](https://github.com/gohar-malik/intermask)

- **TIMotion: Temporal and Interactive Framework for Efficient Human-Human Motion Generation**, _CVPR'25_ [[Paper]](https://arxiv.org/abs/2408.17135), [[Project]](https://aigc-explorer.github.io/TIMotion-page/), [[Code]](https://github.com/AIGC-Explorer/TIMotion)

- **MixerMDM: Learnable Composition of Human Motion Diffusion Models**, _CVPR'25_ [[Paper]](https://arxiv.org/abs/2504.01019), [[Project]](https://pabloruizponce.com/papers/MixerMDM), [[Code]](https://github.com/pabloruizponce/MixerMDM)

- **Invisible Strings: Revealing Latent Dancer-to-Dancer Interactions with Graph Neural Networks**, _ICCC'25_ [[Paper]](https://arxiv.org/abs/2503.04816), [[Code]](https://github.com/humanai-foundation/ChoreoAI/tree/main/ChoreoAI_Duet_ChorAIgraphy_Luis_Zerkowski)

- **Leader and Follower: Interactive Motion Generation under Trajectory Constraints**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2502.11563)

- **InterDance:Reactive 3D Dance Generation with Realistic Duet Interactions**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2412.16982), [[Code]](https://inter-dance.github.io/)

- **Two-in-One: Unified Multi-Person Interactive Motion Generation by Latent Diffusion Transformer**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2412.16670)

- **It Takes Two: Real-time Co-Speech Two-person’s Interaction Generation via Reactive Auto-regressive Diffusion Model**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2412.02419)

- **COLLAGE: Collaborative Human-Agent Interaction Generation using Hierarchical Latent Diffusion and Language Models**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2409.20502)

- **InterControl: Zero-shot Human Interaction Generation by Controlling Every Joint**, _NeurIPS'24_ [[Paper]](https://arxiv.org/abs/2311.15864), [[Code]](https://github.com/zhenzhiwang/intercontrol)

- **Towards Open Domain Text-Driven Synthesis of Multi-Person Motions**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2405.18483), [[Project]](https://shanmy.github.io/Multi-Motion/)

- **in2IN: Leveraging individual Information to Generate Human INteractions**, _CVPRW'24_ [[Paper]](https://arxiv.org/abs/2404.09988), [[Project]](https://pabloruizponce.github.io/in2IN/), [[Code]](https://github.com/pabloruizponce/in2IN)

- **CORE4D: A 4D Human-Object-Human Interaction Dataset for Collaborative Object REarrangement**, _arxiv 2024.06_ [[Paper]](https://arxiv.org/abs/2406.19353), [[Project]](https://core4d.github.io/), [[Code]](https://github.com/leolyliu/CORE4D-Instructions)

- **Inter-X: Towards Versatile Human-Human Interaction Analysis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2312.16051), [[Project]](https://liangxuy.github.io/inter-x/), [[Code&Data]](https://github.com/liangxuy/Inter-X)

- **ContactGen: Contact-Guided Interactive 3D Human Generation for Partners**, _AAAI'24_ [[Paper]](https://arxiv.org/abs/2401.17212), [[Project]](https://dongjunku.github.io/contactgen/), [[Code]](https://github.com/dongjunKu/ContactGen/)

- **InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions**, _IJCV'24_ [[Paper]](https://arxiv.org/abs/2304.05684), [[Project]](https://tr3e.github.io/intergen-page/), [[Code&Data]](https://drive.google.com/drive/folders/1oyozJ4E7Sqgsr7Q747Na35tWo5CjNYk3)

- **ActFormer: A GAN-based Transformer towards General Action-Conditioned 3D Human Motion Generation**, _ICCV'23_ [[Paper]](https://arxiv.org/abs/2203.07706), [[Project]](https://liangxuy.github.io/actformer/), [[Code]](https://github.com/Szy-Young/actformer)

- **PriorMDM: Human Motion Diffusion as a Generative Prior**, _ICLR'24_ [[Paper]](https://arxiv.org/abs/2303.01418), [[Project]](https://priormdm.github.io/priorMDM-page/), [[Code]](https://github.com/priorMDM/priorMDM)

- **Neural Animation Layering for Synthesizing Martial Arts Movements**, _SIGGRAPH 2021_ [[Paper]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2021/Paper.pdf)

- **Local Motion Phases for Learning Multi-Contact Character Movements**, _SIGGRAPH 2020_ [[Paper]](https://github.com/sebastianstarke/AI4Animation/blob/master/Media/SIGGRAPH_2020/Paper.pdf), [[Code]](https://github.com/sebastianstarke/AI4Animation/tree/master/AI4Animation/SIGGRAPH_2020)


### Reaction Generation

- **Real-time and Controllable Reactive Motion Synthesis via Intention Guidance**, _arXiv'25_ [[Paper]](https://www.arxiv.org/abs/2507.09704)

- **MARRS: Masked Autoregressive Unit-based Reaction Synthesis**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2505.11334)

- **E-React: Towards Emotionally Controlled Synthesis of Human Reactions**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2508.06093), [[Project]](https://ereact.github.io/)

- **ReactDance: Progressive-Granular Representation for Long-Term Coherent Reactive Dance Generation**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2505.05589)

- **HERO: Human Reaction Generation from Videos**, _arXiv'25_ [[Paper]](https://arxiv.org/pdf/2503.08270), [[Project]](https://jackyu6.github.io/HERO/)

- **Think Then React: Towards Unconstrained Action-to-Reaction Motion Generation**, _ICLR'25_ [[Paper]](https://www.arxiv.org/abs/2503.16451), [[Project]](https://think-then-react.github.io/)

- **Ready-to-React: Online Reaction Policy for Two-Character Interaction Generation**, _ICLR'25_ [[Paper]](https://arxiv.org/abs/2502.20370), [[Project]](https://zju3dv.github.io/ready_to_react/), [[Code]](https://github.com/zju3dv/ready_to_react)

- **Interactive Humanoid: Online Full-Body Motion Reaction Synthesis with Social Affordance Canonicalization and Forecasting**, _3DV'25_ [[Paper]](https://arxiv.org/abs/2312.08983), [[Project]](https://yunzeliu.github.io/iHuman/)

- **MARRS: Masked Autoregressive Unit-based Reaction Synthesis**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2505.11334)

- **SocialGen: Modeling Multi-Human Social Interaction with Language Models**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2503.22906), [[Project]](https://socialgenx.github.io/)

- **ARFlow: Human Action-Reaction Flow Matching with Physical Guidance**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2503.16973), [[Project]](https://arflow2025.github.io/)

- **PhysReaction: Physically Plausible Real-Time Humanoid Reaction Synthesis via Forward Dynamics Guided 4D Imitation**, _arXiv 2024.04_ [[Paper]](https://arxiv.org/abs/2404.01081), [[Project]](https://yunzeliu.github.io/PhysReaction/)

- **Inter-X: Towards Versatile Human-Human Interaction Analysis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2312.16051), [[Project]](https://liangxuy.github.io/inter-x/), [[Code&Data]](https://github.com/liangxuy/Inter-X)

- **ReGenNet: Towards Human Action-Reaction Synthesis**, _CVPR'24_ [[Paper]](https://arxiv.org/abs/2403.11882), [[Project]](https://liangxuy.github.io/ReGenNet/), [[Code]](https://github.com/liangxuy/ReGenNet)

- **Role-aware Interaction Generation from Textual Description**, _ICCV'23_ [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Tanaka_Role-Aware_Interaction_Generation_from_Textual_Description_ICCV_2023_paper.html), [[Code]](https://github.com/line/Human-Interaction-Generation)

- **ReMoS: 3D Motion-Conditioned Reaction Synthesis for Two-Person Interactions**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2311.17057), [[Project]](https://vcai.mpi-inf.mpg.de/projects/remos/)

- **Interaction transformer for human reaction generation**, _TMM'23_ [[Paper]](https://arxiv.org/abs/2207.01685)


### HHI Reconstruction

- **MAMMA: Markerless & Automatic Multi-Person Motion Action Capture**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2506.13040)

- **Reconstructing Close Human Interaction with Appearance and Proxemics Reasoning**, _CVPR'25_ [[Paper]](https://www.buzhenhuang.com/publications/papers/CVPR2025-CloseApp.pdf)

- **Harmony4D: A Video Dataset for In-The-Wild Close Human Interactions**, _NeurIPS'24_ [[Paper]](https://arxiv.org/abs/2410.20294), [[Project]](https://jyuntins.github.io/harmony4d/), [[Data]](https://huggingface.co/datasets/Jyun-Ting/Harmony4D/tree/main)

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


### Group Interaction


- **Large-Scale Multi-Character Interaction Synthesis**, _SIGGRAPH'25_ [[Paper]](https://arxiv.org/abs/2505.14087), [[Project]](https://hubertshum.com/pbl_siggraph2025interaction.htm)

- **PINO: Person-Interaction Noise Optimization for Long-Duration and Customizable Motion Generation of Arbitrary-Sized Groups**, _ICCV'25_ [[Paper]](https://arxiv.org/abs/2507.19292), [[Project]](https://sinc865.github.io/pino/), [[Code]](https://github.com/sinc865/PINO)

- **Multi-Person Interaction Generation from Two-Person Motion Priors**, _SIGGRAPH'25_ [[Paper]](https://arxiv.org/abs/2505.17860), [[Project]](https://wenningxu.github.io/multicharacter/), [[Code]](https://github.com/wenningxu/multi-person-interaction)

- **SocialGen: Modeling Multi-Human Social Interaction with Language Models**, _arXiv'25_ [[Paper]](https://arxiv.org/abs/2503.22906), [[Project]](https://socialgenx.github.io/)

- **Towards Open Domain Text-Driven Synthesis of  Multi-Person Motions**, _ECCV'24_ [[Paper]](https://arxiv.org/abs/2405.18483), [[Project]](https://shanmy.github.io/Multi-Motion/)

- **Stochastic Multi-Person 3D Motion Forecasting**, _ICLR'23_ [[Paper]](https://arxiv.org/abs/2306.05421), [[Project]](https://sirui-xu.github.io/DuMMF/), [[Code]](https://github.com/Sirui-Xu/DuMMF)

- **Joint-Relation Transformer for Multi-Person Motion Prediction**, _ICCV'23_ [[Paper]](https://arxiv.org/abs/2308.04808), [[Code]](https://github.com/MediaBrain-SJTU/JRTransformer)

- **Music-Driven Group Choreography**, _CVPR'23_ [[Paper]](https://arxiv.org/abs/2303.12337), [[Project]](https://aioz-ai.github.io/AIOZ-GDANCE/)
