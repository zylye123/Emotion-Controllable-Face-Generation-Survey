# A Survey on Emotion-Controllable Face Generation

<p align="center">
  <img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/> 
  <a href="https://github.com/zylye123/Emotion-Controllable-Face-Generation-Survey">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
  </a>
  <br>
  <a href="https://github.com/zylye123/Emotion-Controllable-Face-Generation-Survey">
    <img src="https://img.shields.io/badge/arXiv-b31b1b.svg" alt="Arxiv PDF">
  </a>
  <img src="https://img.shields.io/badge/Update 🔥-2025.09.xx-red" alt="MorePapers">
</p>


## 📖 Introduction

This repository is related to **Emotion-Controllable Face Generation**. It organizes research works in this area and categorizes them by **different tasks** for easier navigation. Our goal is to maintain a **living resource** that helps researchers and practitioners track the latest progress in the field.

## 📢 News

- **[2025-09-xx]** Our paper *"A Survey on Emotion-Controllable Face Generation"* is now available on [arXiv](https://github.com/zylye123/Emotion-Controllable-Face-Generation-Survey), and this repository has been open-sourced!


## 🔖 Table of Contents

- [A Survey on Emotion-Controllable Face Generation](#a-survey-on-emotion-controllable-face-generation)
  - [📖 Introduction](#-introduction)
  - [📢 News](#-news)
  - [📚 Papers](#-papers)
    - [Identity-preserving Expression Editing](#identity-preserving-expression-editing)
    - [Categorical Conditioned Generation](#categorical-conditioned-generation)
    - [Face Swapping](#face-swapping)
    - [Talking Face Generation](#talking-face-generation)
    - [Face Image Animation](#face-image-animation)
    - [Listener Response Synthesis](#listener-response-synthesis)
  - [🔄 Updates](#-updates)


## 📚 Papers

### Identity-preserving Expression Editing

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:---------:|:----------|:--------:|:------------------:|:---------:|:---------:|
| 2017-09-12 | ExprGAN: Facial Expression Editing With Controllable Expression Intensity | AAAI 2018 | Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1709.03842) |
| 2017-11-24 | StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018 | Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1711.09020) |
| 2018-06 | Joint Pose and Expression Modeling for Facial Expression Recognition | CVPR 2018 | Emotion Vector | GAN | [![CVPR](https://img.shields.io/badge/CVPR-blue)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Joint_Pose_and_CVPR_2018_paper.pdf) |
| 2018-11-12 | Deep Neural Network Augmentation: Generating Faces for Affect Analysis | IJCV 2020 | V/A model | Regression | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1811.05027) |
| 2020-03-12 | Cascade EF-GAN: Progressive Facial Expression Editing with Local Focuses | CVPR 2020 | V/A model | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2003.05905) |
| 2020-04-07 | Toward Fine-grained Facial Expression Manipulation |ECCV 2020| V/A model | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2004.03132) |
| 2024-01 | EmoStyle: One-shot Facial Expression Editing Using Continuous Emotion Parameters | WACV 2024 | V/A model | GAN | [![WACV](https://img.shields.io/badge/WACV-blue)](https://openaccess.thecvf.com/content/WACV2024/papers/Azari_EmoStyle_One-Shot_Facial_Expression_Editing_Using_Continuous_Emotion_Parameters_WACV_2024_paper.pdf)  |
| 2021-12-03 |            How to Synthesize a Large-Scale and Trainable Micro-Expression Dataset?| ECCV 2022	| Emotion Vector + AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.01730)  |
| 2024-04-07 |            AUEditNet: Dual-Branch Facial Action Unit Intensity Manipulation with Implicit Disentanglement| CVPR 2024 |           AU Vector            	| GAN	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05063)            	|
| 2024-07-25 |            Towards Localized Fine-Grained Control for Facial Expression Generation| arXiv 2024  	|  AU Vector  | Diffusion	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.20175)      	|
| 2019-07-23 |            Dynamic Facial Expression Generation on Hilbert Hypersphere with Conditional Wasserstein Generative Adversarial Nets| TPAMI 2019 |           Emotion Vector + 2D Landmarks            	| GAN	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1907.10087) |
| 2021-12-01 |             Neural emotion director: Speech-preserving semantic control of facial expressions in" in-the-wild" videos| CVPR 2022 | 3DMM + Emotion Vector | GAN	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.00585) 	|
| 2021-12-11 |             AvatarMe++: Facial Shape and BRDF Inference with Photorealistic Rendering-Aware GANs| TPAMI 2021	|   3DMM + UV map	| GAN	|     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2112.05957)|
| 2023-04-18 |             POCE: Pose-Controllable Expression Editing| TIP 2023 |           UV map + AU Vector             	| GAN	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08938)                 	|
| 2022-09-17 |             Continuously Controllable Facial Expression Editing in Talking Face Videos| TAFFC 2024   	| UV map + 3DMM + Emotion Vector | GAN |    [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.08289)              	|
| 2022-10-20 |             Diffusion Models already have a Semantic Latent Space|  ICLR 2023 | Text | Diffusion	|      [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.10960)                 	|
| 2024-05-09 |             MasterWeaver: Taming Editability and Face Identity for Personalized Text-to-Image Generation| ECCV 2024 | Text | Diffusion	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05806)                 	|
| 2023-12-07 |             PhotoMaker: Customizing Realistic Human Photos via Stacked ID Embedding|  CVPR 2024 | Text | Diffusion	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04461)             	|
| 2024-01-02 |             Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation| CVPR 2024	| Text | Diffusion	|                             [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01207)         	|
| 2025-04-30 |             Instruction-Driven 3D Facial Expression Generation and Transition| TMM 2025 | Text | VAE	|       [![TMM](https://img.shields.io/badge/TMM-blue)](https://ieeexplore.ieee.org/abstract/document/10980355)                   	|

### Categorical Conditioned Generation

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:---------:|:---------:|:---------------:|:-----------------:|:---------:|:---------:|
| 2021-06   | GANmut: Learning interpretable conditional space for gamut of emotions | CVPR 2021  | V/A model | GAN | [![CVPR](https://img.shields.io/badge/CVPR-blue)](https://openaccess.thecvf.com/content/CVPR2021/papers/dApolito_GANmut_Learning_Interpretable_Conditional_Space_for_Gamut_of_Emotions_CVPR_2021_paper.pdf)|
| 2024-04-01| A Unified and Interpretable Emotion Representation and Expression Generation | CVPR 2024  | AU Vector + V/A Model | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01243) |
| 2022-11-23| CGOF++: Controllable 3D Face Synthesis with Conditional Generative Occupancy Fields | TPAMI 2023 | 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.13251) |
| 2020-04-02| Learning formation of physically-based face attributes | CVPR 2020 | 3DMM + UV map | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2004.03458) |
| 2023-04-20| Collaborative Diffusion for Multi-Modal Face Generation and Editing | CVPR 2023 | Text + Semantic Map | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10530) |
| 2023-12-21| Controllable 3D Face Generation with Conditional Style Code Diffusion | AAAI 2024 | Text + 3DMM | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.13941)  |



### Face Swapping

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:----------:|:----------|:--------:|:------------------:|:---------:|:---------:|
| 2019-10 | FSGAN: Subject Agnostic Face Swapping and Reenactment | ICCV 2019  | Landmarks | GAN | [![ICCV](https://img.shields.io/badge/IJCV-blue)](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nirkin_FSGAN_Subject_Agnostic_Face_Swapping_and_Reenactment_ICCV_2019_paper.pdf)|
| 2022-02-25 | FSGANv2: Improved Subject Agnostic Face Swapping and Reenactment | Arxiv 2022  |Landmarks | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2202.12972)|
| 2021-06-18 | HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping | IJCAI 2021 | 3DMM | GAN |  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2106.09965) |
| 2021-08-18 | A Unified Framework for High Fidelity Face Swap and Expression Reenactment | TCSVT 2021 | 3DMM | VAE |  [![TCSVT](https://img.shields.io/badge/TCSVT-blue)](https://ieeexplore.ieee.org/abstract/document/9517088/)|
| 2025-03-11 | UniFace++: Revisiting a Unified Framework for Face Reenactment and Swapping via 3D Priors | IJCV 2025  | 3DMM | Diffusion |[![IJCV](https://img.shields.io/badge/IJCV-blue)](https://link.springer.com/article/10.1007/s11263-025-02395-6)|



### Talking Face Generation

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:----------:|:----------|:--------:|:------------------:|:---------:|:---------:|
| 2024-03-24 | FG-EmoTalk: Talking Head Video Generation with Fine-Grained Controllable Facial Expressions | AAAI 2024 | 3DMM + AU Vector | GAN | [![AAAI](https://img.shields.io/badge/AAAI-blue)](https://ojs.aaai.org/index.php/AAAI/article/view/28309)|
| 2023-05-10 | DaGAN++: Depth-Aware Generative Adversarial Network for Talking Head Video Generation | TPAMI 2023 | Motion Field | GAN | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.06225)  |
| 2025-04-14	|              DaGAN++: Depth-Aware Generative Adversarial Network for Talking Head Video Generation            	| TCSVT 2025    	|          Motion Field + AU Vector           	| GAN 	|                 [![TSCVT](https://img.shields.io/badge/TSCVT-blue)](https://ieeexplore.ieee.org/abstract/document/10964316)       	|
| 2020-02-24	|              DaGAN++: Depth-Aware Generative Adversarial Network for Talking Head Video Generation            	| TMM 2020 	|          Audio + 3DMM            	| GAN 	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2002.10137)       	|
| 2020-04-27	|              MakeItTalk: Speaker-Aware Talking-Head Animation            	|  TOG 2020 	|          Audio            	| GAN 	|     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2004.12992)              	|
| 2021-08-18	|              FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning            	|  ICCV 2021   	|          Audio + AU Vector + 3DMM             	| GAN 	|      [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.07938)           	|
| 2021-06	|  Flow-guided One-shot Talking Face Generation with a High-resolution Audio-visual Dataset  | CVPR 2021	| Audio + 3DMM + Motion Field | GAN | [![CVPR](https://img.shields.io/badge/CVPR-blue)](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Flow-Guided_One-Shot_Talking_Face_Generation_With_a_High-Resolution_Audio-Visual_Dataset_CVPR_2021_paper.pdf)  |
| 2021-04-15	|            Audio-Driven Emotional Video Portraits            	| CVPR 2021  	|          Audio + 2D Landmarks + 3DMM              	| GAN 	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.07452)          	|
| 2022-05-30	|         EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model            	|  SIGGRAPH 2022   	|          Audio + 2D Landmarks              	| GAN 	|     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.15278)        	|
| 2023-05-04	|         High-fidelity Generalized Emotional Talking Face Generation with Multi-modal Emotion Space Learning            	| CVPR 2023  	|         Text + Audio + 3DMM              	| Diffusion 	|      [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.02572)           	|
| 2024-12-26	|          Multimodal Emotional Talking Face Generation Based on Action Units           	|	TCSVT 2024 |         Audio + AU Vector + Emotion Vector              	| GAN 	|   [![TCSVT](https://img.shields.io/badge/TCSVT-blue)](https://ieeexplore.ieee.org/abstract/document/10816597)             	|
| 2024-03-11	|          Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style           	| AAAI 2024  |         Text + Audio + 3DMM              	| GAN 	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06365) 	        	|
| 2024-04-23	|          TalkingGaussian: Structure-Persistent 3D Talking Head Synthesis via Gaussian Splatting|             ECCV 2024  	|         Audio + AU Vector              	| 3DGS 	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15264)             	|
| 2024-04-16	|          VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time|	    NeurIPS 2024   |         Audio             	| Diffusion  	|   [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10667)             	|
| 2024-03-11	|          FlowVQTalker: High-Quality Emotional Talking Face Generation through Normalizing Flow and Quantization| CVPR 2024   	|         Audio + 3DMM             	| N-Flow + VAE  	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06375)          	|
| 2024-11-23	|          EmotiveTalk: Expressive Talking Head Generation through Audio Information Decoupling and Emotional Video Diffusion| CVPR 2024    	|         Audio            	| Diffusion  	|   [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16726)          	|
| 2023-09-30	|          DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models| TOG 2024  |         Audio            	| Diffusion  	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00434) 	        	|
| 2022-12-09	|           Memories are One-to-Many Mapping Alleviators in Talking Face Generation|  TPAMI 2024	|         Audio            	| GAN  	|        [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.05005)             	|
| 2024-08-12	|           DEEPTalk: Dynamic Emotion Embedding for Probabilistic Speech-Driven 3D Face Animatio| AAAI 2025 	|         Audio            	| VAE  	|    [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06010)             	|
| 2025-03-03	|          KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation | CVPR 2025 	|         Audio + V/A Model             	| Diffusion 	|   [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.01715)              	|

### Face Image Animation

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:----------:|:----------|:--------:|:------------------:|:---------:|:---------:|
| 2019-08-24	|             GANimation: One-Shot Anatomically Consistent Facial Animation            	|  IJCV 2020 	|          AU Vector          	| GAN 	|   [![IJCV](https://img.shields.io/badge/IJCV-blue)](https://link.springer.com/article/10.1007/s11263-019-01210-3)             	|
| 2019-04-03	|             Icface: Interpretable and controllable face reenactment using gans.            	|       WACV 2020 	|          AU Vector          	| GAN 	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1904.01909)            	|
| 2023-04-06	|             Face Animation with an Attribute-Guided Diffusion Model          	| CVPR 2023 	|          3DMM          	| Diffusion 	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.03199)             	|
| 2024-10-10	|             Generalizable and Animatable Gaussian Head Avatar          	| NeurIPS 2024 	|          3DMM          	| 3DGS  	|    [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07971)            	|
| 2020-02-29	|             First Order Motion Model for Image Animation          	| NeurlPS 2019	|          GAN          	| Motion Field	|  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2003.00196)             	|
| 2022-03-27	|             Thin-Plate Spline Motion Model for Image Animation          	| CVPR 2022 |          GAN          	| Motion Field	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.14367) 	             	|
| 2022-03-17	|             Latent Image Animator: Learning to Animate Images via Latent Space Navigation          	|  TPAMI 2024  	|          GAN          	| Motion Field	| [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.09043)            	|


### Listener Response Synthesis

| **Date**  | **Title** | **Venue** | **Representation** | **Model** | **Link** |
|:----------:|:----------|:--------:|:------------------:|:---------:|:---------:|
| 2022-04-18	|  Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion |CVPR 2022 |Audio  | VAE 	|   [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.08451)  |
| 2024-01-15	|             Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation|      ICCV 2023  	|          Audio + Emotion Vector + 3DMM          	| VAE 	|        [![ICCV](https://img.shields.io/badge/ICCV-blue)](https://ieeexplore.ieee.org/abstract/document/10377831)          	|
| 2024-03-14	|             Dyadic Interaction Modeling for Social Behavior Generation            	|  ECCV 2024  	|          Audio       	| VAE 	|     [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.09069)            	|
| 2024-03-01	|             CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation            	| CVPR 2024 	|          Text + Audio       	| Diffusion  	|       [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.00274)        	|

> 🔗 **Note**: We prioritize linking to **arXiv** (earliest version).  
> If a paper is not on arXiv, we provide the earliest official conference/journal link.


## 🔄 Updates 

This survey is a **living document** and will be continuously updated.  
We regularly track newly published papers, datasets, and projects related to **Emotion-Controllable Face Generation**, and integrate them into this repository.  

- 📌 **Update frequency**: We aim to update every 1–2 months.  
- 🔍 **Sources monitored**: arXiv, major conferences/journals, and open-source projects.  
- 🙌 **Community help**: If you notice new works that are not yet included, feel free to open an issue or a pull request.  

Stay tuned for the latest progress!


## Cite The Survey
If you find our survey and repository useful for your research project, please consider citing our paper:
