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

- **[2026-04-29]** Papers are updated with code/project links.

- **[2026-04-28]** Database Access is updated.

- **[2025-09]** Our paper *"A Survey on Emotion-Controllable Face Generation"* is now available on [techrxiv](https://github.com/zylye123/Emotion-Controllable-Face-Generation-Survey), and this repository has been open-sourced!

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
  - [📚 Datasets](#-datasets)
  - [🔄 Updates](#-updates)

---
## Dataset Access Information

The table below provides practical access information for the facial-expression-centric datasets reviewed in this survey. We prioritize official dataset pages, author-maintained project pages, and stable institutional repositories. Since access policies may change over time, readers should always check the corresponding license, data-use agreement, and redistribution restrictions before downloading or using a dataset.

**Access tags**
- *Open* — direct public download, no registration required.
- *EULA* — sign an end-user licence agreement and submit (often by email) to obtain the data.
- *Request* — fill in a request form / contact authors; approval typically required.
- *Restricted* — access currently unavailable, ended, or limited; check the official page for current status.

| Dataset | Year | Homepage / Project Page | Access |
|---|---:|---|---|
| BU-3DFE | 2006 | [Official BU-3DFE page](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html) | *Request* — agreement via official page |
| Oulu-CASIA | 2010 | [University of Oulu CMVS](https://www.oulu.fi/en/university/faculties-and-units/faculty-information-technology-and-electrical-engineering/center-for-machine-vision-and-signal-analysis) | *Request* — by email to maintainer |
| FER-2013 | 2013 | [Kaggle FER-2013 challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) | *Open* — Kaggle login + terms |
| CK+ | 2010 | [Jeffrey Cohn resources page](https://www.jeffcohn.net/resources/) | *Restricted* — distribution ended May 1, 2025 |
| EmotioNet | 2016 | [EmotioNet challenge page](http://cbcsl.ece.ohio-state.edu/EmotionNetChallenge/) | *Restricted* — limited availability, check page |
| RaFD | 2010 | [RaFD official page](https://rafd.nl/) | *Restricted* — downloads currently unavailable |
| AffectNet | 2017 | [AffectNet official page](https://mohammadmahoor.com/pages/databases/affectnet/) | *Request* — agreement via official page |
| BP4D | 2013 | [BP4D technology page](https://binghamton.technologypublisher.com/tech?title=BP4D%3A_4D_Spontaneous_Facial_Expression_Database) | *Request* — institutional agreement |
| BP4D+ | 2014 | [AffCom resources](https://affcom.ku.edu/resources.html) | *Request* — institutional agreement |
| DISFA | 2013 | [DISFA official page](https://www.mohammadmahoor.com/pages/databases/disfa/) | *Request* — signed form |
| CelebA | 2015 | [CelebA official page](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) | *Open* — Google Drive / Baidu, non-commercial |
| CelebA-HQ | 2018 | [Progressive GAN repository](https://github.com/tkarras/progressive_growing_of_gans) | *Open* — generated via released script |
| MM-CelebA-HQ | 2021 | [MM-CelebA-HQ GitHub](https://github.com/IIGROUP/MM-CelebA-HQ-Dataset) | *Restricted* — repo redirects to original sources |
| CelebA-Dialog | 2021 | [CelebA-Dialog GitHub](https://github.com/ziqihuangg/CelebA-Dialog) | *Open* — direct Google Drive links |
| FFHQ | 2019 | [FFHQ official GitHub](https://github.com/NVlabs/ffhq-dataset) | *Open* — metadata + download scripts |
| FaceForensics++ | 2019 | [FaceForensics++ GitHub](https://github.com/ondyari/FaceForensics) | *EULA* — Google Form linked from repo |
| CASME II | 2014 | [CASME II official page](https://casme.psych.ac.cn/casme/e2) | *EULA* — application + licence agreement |
| CAS(ME)^3 | 2022 | [CAS(ME)^3 official page](https://casme.psych.ac.cn/casme/e4) · [ME-Lab mirror](https://melabipcas.github.io/melab/en/databases.html) | *EULA* — application + licence agreement |
| SAMM | 2016 | [SAMM release agreement](https://megc2022.github.io/files/SAMM_ReleaseAgreementV2.pdf) | *EULA* — signed release agreement |
| SMIC | 2013 | [University of Oulu CMVS](https://www.oulu.fi/en/university/faculties-and-units/faculty-information-technology-and-electrical-engineering/center-for-machine-vision-and-signal-analysis) | *Request* — by email, indicate subset |
| NaME | 2025 | [NaME GitHub](https://github.com/real-ljt/NAMEdataset) | *EULA* — sign agreement + email author |
| IMPA-FACE3D | 2008 | [IMPA FacesDB](https://app.visgraf.impa.br/database/faces/) | *Open* — project page download tab |
| VoxCeleb1 | 2017 | [VoxCeleb official page](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | *Open* — form for full set; URLs + timestamps |
| VoxCeleb2 | 2018 | [VoxCeleb official page](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | *Open* — same access route as VoxCeleb1 |
| Aff-Wild2 | 2019 | [Aff-Wild2 official page](https://sites.google.com/view/dimitrioskollias/databases/aff-wild2) | *EULA* — academic email + signed form |
| MEAD | 2020 | [MEAD project page](https://wywu.github.io/projects/MEAD/MEAD.html) | *Open* — Google Drive / Baidu links |
| GRID | 2006 | [GRID corpus on Zenodo](https://zenodo.org/records/3625687) | *Open* — CC-BY 4.0, per-talker archives |
| ViCo | 2022 | [ViCo project page](https://project.mhzhou.com/vico/) | *Request* — research-use access |
| RealTalk | 2023 | [RealTalk project page](https://realtalk.cs.columbia.edu/) | *Request* — via Google Form on project page |

> 🔄 **Note on availability.** Access policies are set by the dataset owners and may change over time. Some EULA-gated datasets require an *institutional* email and a signed form before download links are provided. Where a dataset has multiple mirrors, we list the most authoritative one. Last verified: 2026-04. Please open an issue or PR if a link breaks or an access policy changes.

---

## Papers

The tables below organize representative works on **Emotion-Controllable Face Generation** by task. To support reproducibility and follow-up research, we additionally provide project/code access information where reliable official or author-maintained resources could be verified.

**Project / Code access tags**

- ![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github) official or author-maintained implementation is publicly available.
- ![Project](https://img.shields.io/badge/Project-Page-blue) official project/demo page exists, but no full implementation code was verified.
- ![Partial](https://img.shields.io/badge/Partial-Code-orange) partial/demo code or incomplete core components are publicly available.
- ![Related](https://img.shields.io/badge/Related-Code-lightgrey) related code exists, but the exact method/version was not verified as fully released.
- ![Unofficial](https://img.shields.io/badge/Unofficial-Code-lightgrey) third-party implementation; useful for reference, but not official.
- `--` no reliable public project/code link was verified.

> **Note on availability.** We prioritize official project pages, author-maintained GitHub repositories, institutional pages, and paper pages. Since repositories may be moved, archived, or updated over time, please check the license and release status before using any code. Last verified: 2026-04.

---

### Categorical Conditioned Generation

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2021-06 | GANmut: Learning Interpretable Conditional Space for Gamut of Emotions | CVPR 2021 | V/A Model | GAN | [![CVPR](https://img.shields.io/badge/CVPR-Paper-blue.svg)](https://openaccess.thecvf.com/content/CVPR2021/papers/dApolito_GANmut_Learning_Interpretable_Conditional_Space_for_Gamut_of_Emotions_CVPR_2021_paper.pdf) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/stefanodapolito/GANmut) |
| 2024-04-01 | A Unified and Interpretable Emotion Representation and Expression Generation | CVPR 2024 | AU Vector + V/A Model | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2404.01243-b31b1b.svg)](https://arxiv.org/abs/2404.01243) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://emotion-diffusion.github.io/) |
| 2022-11-23 | CGOF++: Controllable 3D Face Synthesis with Conditional Generative Occupancy Fields | TPAMI 2023 | 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2211.13251-b31b1b.svg)](https://arxiv.org/abs/2211.13251) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/KeqiangSun/cGOF) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://kpufighting.github.io/cgof.github.io/) |
| 2020-04-02 | Learning Formation of Physically-Based Face Attributes | CVPR 2020 | 3DMM + UV Map | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2004.03458-b31b1b.svg)](https://arxiv.org/abs/2004.03458) | -- |
| 2023-04-20 | Collaborative Diffusion for Multi-Modal Face Generation and Editing | CVPR 2023 | Text + Semantic Map | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2304.10530-b31b1b.svg)](https://arxiv.org/abs/2304.10530) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/ziqihuangg/Collaborative-Diffusion) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://ziqihuangg.github.io/projects/collaborative-diffusion.html) |
| 2023-12-21 | Controllable 3D Face Generation with Conditional Style Code Diffusion | AAAI 2024 | Text + 3DMM | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2312.13941-b31b1b.svg)](https://arxiv.org/abs/2312.13941) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/sxl142/TEx-Face) |

---

### Identity-preserving Expression Editing

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2017-09-12 | ExprGAN: Facial Expression Editing with Controllable Expression Intensity | AAAI 2018 | Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-1709.03842-b31b1b.svg)](https://arxiv.org/abs/1709.03842) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/HuiDingUMD/ExprGAN) |
| 2017-11-24 | StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018 | Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-1711.09020-b31b1b.svg)](https://arxiv.org/abs/1711.09020) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/yunjey/stargan) |
| 2018-06 | Joint Pose and Expression Modeling for Facial Expression Recognition | CVPR 2018 | Emotion Vector | GAN | [![CVPR](https://img.shields.io/badge/CVPR-Paper-blue.svg)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Joint_Pose_and_CVPR_2018_paper.pdf) | -- |
| 2018-11-12 | Deep Neural Network Augmentation: Generating Faces for Affect Analysis | IJCV 2020 | V/A Model | Regression | [![arXiv](https://img.shields.io/badge/arXiv-1811.05027-b31b1b.svg)](https://arxiv.org/abs/1811.05027) | -- |
| 2020-03-12 | Cascade EF-GAN: Progressive Facial Expression Editing with Local Focuses | CVPR 2020 | AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2003.05905-b31b1b.svg)](https://arxiv.org/abs/2003.05905) | -- |
| 2020-04-07 | Toward Fine-Grained Facial Expression Manipulation | ECCV 2020 | AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2004.03132-b31b1b.svg)](https://arxiv.org/abs/2004.03132) | -- |
| 2024-01 | EmoStyle: One-Shot Facial Expression Editing Using Continuous Emotion Parameters | WACV 2024 | V/A Model | GAN | [![WACV](https://img.shields.io/badge/WACV-Paper-blue.svg)](https://openaccess.thecvf.com/content/WACV2024/papers/Azari_EmoStyle_One-Shot_Facial_Expression_Editing_Using_Continuous_Emotion_Parameters_WACV_2024_paper.pdf) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/bihamta/emostyle) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://bihamta.github.io/emostyle/) |
| 2021-12-03 | How to Synthesize a Large-Scale and Trainable Micro-Expression Dataset? | ECCV 2022 | Emotion Vector + AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2112.01730-b31b1b.svg)](https://arxiv.org/abs/2112.01730) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/liuyvchi/MiE-X) |
| 2024-04-07 | AUEditNet: Dual-Branch Facial Action Unit Intensity Manipulation with Implicit Disentanglement | CVPR 2024 | AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2404.05063-b31b1b.svg)](https://arxiv.org/abs/2404.05063) | -- |
| 2024-07-25 | Towards Localized Fine-Grained Control for Facial Expression Generation | arXiv 2024 | AU Vector | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2407.20175-b31b1b.svg)](https://arxiv.org/abs/2407.20175) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/tvaranka/fineface) |
| 2019-07-23 | Dynamic Facial Expression Generation on Hilbert Hypersphere with Conditional Wasserstein Generative Adversarial Nets | TPAMI 2019 | Emotion Vector + 2D Landmarks | GAN | [![arXiv](https://img.shields.io/badge/arXiv-1907.10087-b31b1b.svg)](https://arxiv.org/abs/1907.10087) | -- |
| 2021-12-11 | AvatarMe++: Facial Shape and BRDF Inference with Photorealistic Rendering-Aware GANs | TPAMI 2021 | 3DMM + UV Map | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2112.05957-b31b1b.svg)](https://arxiv.org/abs/2112.05957) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/lattas/AvatarMe) |
| 2023-04-18 | POCE: Pose-Controllable Expression Editing | TIP 2023 | UV Map + AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2304.08938-b31b1b.svg)](https://arxiv.org/abs/2304.08938) | -- |
| 2022-10-20 | Diffusion Models Already Have a Semantic Latent Space | ICLR 2023 | Text | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2210.10960-b31b1b.svg)](https://arxiv.org/abs/2210.10960) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/kwonminki/Asyrp_official) |
| 2024-05-09 | MasterWeaver: Taming Editability and Face Identity for Personalized Text-to-Image Generation | ECCV 2024 | Text | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2405.05806-b31b1b.svg)](https://arxiv.org/abs/2405.05806) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/csyxwei/MasterWeaver) |
| 2023-12-07 | PhotoMaker: Customizing Realistic Human Photos via Stacked ID Embedding | CVPR 2024 | Text | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2312.04461-b31b1b.svg)](https://arxiv.org/abs/2312.04461) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/TencentARC/PhotoMaker) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://photo-maker.github.io/) |
| 2024-01-02 | Towards a Simultaneous and Granular Identity-Expression Control in Personalized Face Generation | CVPR 2024 | Text | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2401.01207-b31b1b.svg)](https://arxiv.org/abs/2401.01207) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://diffsfsr.github.io/) |

---

### Face Swapping

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2019-10 | FSGAN: Subject Agnostic Face Swapping and Reenactment | ICCV 2019 | Landmarks | GAN | [![ICCV](https://img.shields.io/badge/ICCV-Paper-blue.svg)](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nirkin_FSGAN_Subject_Agnostic_Face_Swapping_and_Reenactment_ICCV_2019_paper.pdf) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/YuvalNirkin/fsgan) |
| 2022-02-25 | FSGANv2: Improved Subject Agnostic Face Swapping and Reenactment | arXiv 2022 | Landmarks | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2202.12972-b31b1b.svg)](https://arxiv.org/abs/2202.12972) | [![Related](https://img.shields.io/badge/Related-Code-lightgrey)](https://github.com/YuvalNirkin/fsgan) |
| 2021-06-18 | HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping | IJCAI 2021 | 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2106.09965-b31b1b.svg)](https://arxiv.org/abs/2106.09965) | [![Unofficial](https://img.shields.io/badge/Unofficial-Code-lightgrey)](https://github.com/maum-ai/hififace) |
| 2021-08-18 | A Unified Framework for High Fidelity Face Swap and Expression Reenactment | TCSVT 2021 | 3DMM | VAE | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-00629B.svg?logo=ieee)](https://ieeexplore.ieee.org/abstract/document/9517088/) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/xc-csc101/UniFace) |
| 2025-03-11 | UniFace++: Revisiting a Unified Framework for Face Reenactment and Swapping via 3D Priors | IJCV 2025 | 3DMM | Diffusion | [![IJCV](https://img.shields.io/badge/IJCV-Springer-darkgreen.svg)](https://link.springer.com/article/10.1007/s11263-025-02395-6) | [![Related](https://img.shields.io/badge/Related-Code-lightgrey)](https://github.com/xc-csc101/UniFace) |

---

### Face Image Animation

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2019-08-24 | GANimation: One-Shot Anatomically Consistent Facial Animation | IJCV 2020 | AU Vector | GAN | [![IJCV](https://img.shields.io/badge/IJCV-Springer-darkgreen.svg)](https://link.springer.com/article/10.1007/s11263-019-01210-3) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/albertpumarola/GANimation) |
| 2019-04-03 | ICFace: Interpretable and Controllable Face Reenactment Using GANs | WACV 2020 | AU Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-1904.01909-b31b1b.svg)](https://arxiv.org/abs/1904.01909) | [![Partial](https://img.shields.io/badge/Partial-Code-orange)](https://github.com/Blade6570/icface) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://tutvision.github.io/icface/) |
| 2023-04-06 | Face Animation with an Attribute-Guided Diffusion Model | CVPR 2023 | 3DMM | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2304.03199-b31b1b.svg)](https://arxiv.org/abs/2304.03199) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/zengbohan0217/FADM) |
| 2024-10-10 | Generalizable and Animatable Gaussian Head Avatar | NeurIPS 2024 | 3DMM | 3DGS | [![arXiv](https://img.shields.io/badge/arXiv-2410.07971-b31b1b.svg)](https://arxiv.org/abs/2410.07971) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/xg-chu/GAGAvatar) |
| 2020-02-29 | First Order Motion Model for Image Animation | NeurIPS 2019 | Motion Field | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2003.00196-b31b1b.svg)](https://arxiv.org/abs/2003.00196) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Aliaksandrsiarohin/first-order-model) |
| 2022-03-27 | Thin-Plate Spline Motion Model for Image Animation | CVPR 2022 | Motion Field | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2203.14367-b31b1b.svg)](https://arxiv.org/abs/2203.14367) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model) |
| 2022-03-17 | Latent Image Animator: Learning to Animate Images via Latent Space Navigation | TPAMI 2024 | Motion Field | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2203.09043-b31b1b.svg)](https://arxiv.org/abs/2203.09043) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/wyhsirius/LIA) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://wyhsirius.github.io/LIA-project/) |
| 2025-04-30 | Instruction-Driven 3D Facial Expression Generation and Transition | TMM 2025 | Text | VAE | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-00629B.svg?logo=ieee)](https://ieeexplore.ieee.org/abstract/document/10980355) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://vohoanganh.github.io/tg3dfet/) |

---

### Talking Face Generation

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2021-12-01 | Neural Emotion Director: Speech-Preserving Semantic Control of Facial Expressions in In-the-Wild Videos | CVPR 2022 | 3DMM + Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2112.00585-b31b1b.svg)](https://arxiv.org/abs/2112.00585) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/foivospar/NED) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://foivospar.github.io/NED/) |
| 2022-09-17 | Continuously Controllable Facial Expression Editing in Talking Face Videos | TAFFC 2024 | UV Map + 3DMM + Emotion Vector | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2209.08289-b31b1b.svg)](https://arxiv.org/abs/2209.08289) | -- |
| 2024-03-24 | FG-EmoTalk: Talking Head Video Generation with Fine-Grained Controllable Facial Expressions | AAAI 2024 | 3DMM + AU Vector | GAN | [![AAAI](https://img.shields.io/badge/AAAI-Paper-blue.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/28309) | -- |
| 2023-05-10 | DaGAN++: Depth-Aware Generative Adversarial Network for Talking Head Video Generation | TPAMI 2023 | Motion Field | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2305.06225-b31b1b.svg)](https://arxiv.org/abs/2305.06225) | [![Related](https://img.shields.io/badge/Related-Code-lightgrey)](https://github.com/harlanhong/CVPR2022-DaGAN) |
| 2025-04-14 | Keypoints and Action Units Jointly Drive Talking Head Generation for Video Conferencing | TCSVT 2025 | Motion Field + AU Vector | GAN | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-00629B.svg?logo=ieee)](https://ieeexplore.ieee.org/abstract/document/10964316) | -- |
| 2020-02-24 | Audio-Driven Talking Face Video Generation with Learning-Based Personalized Head Pose | TMM 2020 | Audio + 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2002.10137-b31b1b.svg)](https://arxiv.org/abs/2002.10137) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/yiranran/Audio-driven-TalkingFace-HeadPose) |
| 2020-04-27 | MakeItTalk: Speaker-Aware Talking-Head Animation | TOG 2020 | Audio | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2004.12992-b31b1b.svg)](https://arxiv.org/abs/2004.12992) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/yzhou359/MakeItTalk) |
| 2021-08-18 | FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning | ICCV 2021 | Audio + AU Vector + 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2108.07938-b31b1b.svg)](https://arxiv.org/abs/2108.07938) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/zhangchenxu528/FACIAL) |
| 2021-06 | Flow-Guided One-Shot Talking Face Generation with a High-Resolution Audio-Visual Dataset | CVPR 2021 | Audio + 3DMM + Motion Field | GAN | [![CVPR](https://img.shields.io/badge/CVPR-Paper-blue.svg)](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Flow-Guided_One-Shot_Talking_Face_Generation_With_a_High-Resolution_Audio-Visual_Dataset_CVPR_2021_paper.pdf) | [![Code/Data](https://img.shields.io/badge/Code%2FData-GitHub-181717?logo=github)](https://github.com/MRzzm/HDTF) |
| 2021-04-15 | Audio-Driven Emotional Video Portraits | CVPR 2021 | Audio + 2D Landmarks + 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2104.07452-b31b1b.svg)](https://arxiv.org/abs/2104.07452) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/jixinya/EVP) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://jixinya.github.io/projects/evp/) |
| 2022-05-30 | EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model | SIGGRAPH 2022 | Audio + 2D Landmarks | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2205.15278-b31b1b.svg)](https://arxiv.org/abs/2205.15278) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/jixinya/EAMM) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://jixinya.github.io/projects/EAMM/) |
| 2023-05-04 | High-Fidelity Generalized Emotional Talking Face Generation with Multi-Modal Emotion Space Learning | CVPR 2023 | Text + Audio + 3DMM | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2305.02572-b31b1b.svg)](https://arxiv.org/abs/2305.02572) | -- |
| 2024-12-26 | Multimodal Emotional Talking Face Generation Based on Action Units | TCSVT 2024 | Audio + AU Vector + Emotion Vector | GAN | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-00629B.svg?logo=ieee)](https://ieeexplore.ieee.org/abstract/document/10816597) | -- |
| 2024-03-11 | Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style | AAAI 2024 | Text + Audio + 3DMM | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2403.06365-b31b1b.svg)](https://arxiv.org/abs/2403.06365) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/tanshuai0219/style2talker) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://tanshuai0219.github.io/Style2Talker/) |
| 2024-04-23 | TalkingGaussian: Structure-Persistent 3D Talking Head Synthesis via Gaussian Splatting | ECCV 2024 | Audio + AU Vector | 3DGS | [![arXiv](https://img.shields.io/badge/arXiv-2404.15264-b31b1b.svg)](https://arxiv.org/abs/2404.15264) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Fictionarry/TalkingGaussian) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://fictionarry.github.io/TalkingGaussian/) |
| 2024-04-16 | VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time | NeurIPS 2024 | Audio | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2404.10667-b31b1b.svg)](https://arxiv.org/abs/2404.10667) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://www.microsoft.com/en-us/research/project/vasa-1/) |
| 2024-03-11 | FlowVQTalker: High-Quality Emotional Talking Face Generation Through Normalizing Flow and Quantization | CVPR 2024 | Audio + 3DMM | N-Flow + VAE | [![arXiv](https://img.shields.io/badge/arXiv-2403.06375-b31b1b.svg)](https://arxiv.org/abs/2403.06375) | -- |
| 2024-11-23 | EmotiveTalk: Expressive Talking Head Generation Through Audio Information Decoupling and Emotional Video Diffusion | CVPR 2024 | Audio | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2411.16726-b31b1b.svg)](https://arxiv.org/abs/2411.16726) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://nju-3dv.github.io/projects/EmotiveTalk/) |
| 2023-09-30 | DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models | TOG 2024 | Audio | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2310.00434-b31b1b.svg)](https://arxiv.org/abs/2310.00434) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/DiffPoseTalk/DiffPoseTalk) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://diffposetalk.github.io/) |
| 2022-12-09 | Memories Are One-to-Many Mapping Alleviators in Talking Face Generation | TPAMI 2024 | Audio | GAN | [![arXiv](https://img.shields.io/badge/arXiv-2212.05005-b31b1b.svg)](https://arxiv.org/abs/2212.05005) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://memoryface.github.io/) |
| 2024-08-12 | DEEPTalk: Dynamic Emotion Embedding for Probabilistic Speech-Driven 3D Face Animation | AAAI 2025 | Audio | VAE | [![arXiv](https://img.shields.io/badge/arXiv-2408.06010-b31b1b.svg)](https://arxiv.org/abs/2408.06010) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/whwjdqls/DEEPTalk) |
| 2025-03-03 | KeyFace: Expressive Audio-Driven Facial Animation for Long Sequences via KeyFrame Interpolation | CVPR 2025 | Audio + V/A Model | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2503.01715-b31b1b.svg)](https://arxiv.org/abs/2503.01715) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/antonibigata/keyface_cvpr) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://antonibigata.github.io/KeyFace/) |

---

### Listener Response Synthesis

| **Date** | **Title** | **Venue** | **Representation** | **Model** | **Paper** | **Project / Code** |
|:---:|:---|:---:|:---:|:---:|:---:|:---:|
| 2022-04-18 | Learning to Listen: Modeling Non-Deterministic Dyadic Facial Motion | CVPR 2022 | Audio | VAE | [![arXiv](https://img.shields.io/badge/arXiv-2204.08451-b31b1b.svg)](https://arxiv.org/abs/2204.08451) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/evonneng/learning2listen) [![Project](https://img.shields.io/badge/Project-Page-blue)](https://evonneng.github.io/learning2listen/) |
| 2024-01-15 | Emotional Listener Portrait: Realistic Listener Motion Simulation in Conversation | ICCV 2023 | Audio + Emotion Vector + 3DMM | VAE | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-00629B.svg?logo=ieee)](https://ieeexplore.ieee.org/abstract/document/10377831) | -- |
| 2024-03-14 | Dyadic Interaction Modeling for Social Behavior Generation | ECCV 2024 | Audio | VAE | [![arXiv](https://img.shields.io/badge/arXiv-2403.09069-b31b1b.svg)](https://arxiv.org/abs/2403.09069) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Boese0601/Dyadic-Interaction-Modeling) |
| 2024-03-01 | CustomListener: Text-Guided Responsive Interaction for User-Friendly Listening Head Generation | CVPR 2024 | Text + Audio | Diffusion | [![arXiv](https://img.shields.io/badge/arXiv-2403.00274-b31b1b.svg)](https://arxiv.org/abs/2403.00274) | [![Project](https://img.shields.io/badge/Project-Page-blue)](https://customlistener.github.io/) |

> **Note**: We prioritize linking to **arXiv** for paper access when available. If a paper is not on arXiv, we provide the earliest official conference/journal link. For project/code access, we prioritize official or author-maintained resources and mark unverified or unofficial resources conservatively.

---

## 🔄 Updates 

This survey is a **living document** and will be continuously updated.  
We regularly track newly published papers, datasets, and projects related to **Emotion-Controllable Face Generation**, and integrate them into this repository.  

- 📌 **Update frequency**: We aim to update every 1–2 months.  
- 🔍 **Sources monitored**: arXiv, major conferences/journals, and open-source projects.  
- 🙌 **Community help**: If you notice new works that are not yet included, feel free to open an issue or a pull request.  

Stay tuned for the latest progress!


## Cite The Survey
If you find our survey and repository useful for your research project, please consider citing our paper:
