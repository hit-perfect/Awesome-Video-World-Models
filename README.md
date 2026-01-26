<div align="center">

<!-- <img src="figs/survey_logo.png" style="width: 70%;"/> -->

## A Mechanistic View on Video Generation as World Models: State and Dynamics

[![Awesome](https://img.shields.io/badge/Awesome-0066CC?style=for-the-badge&logo=awesome-lists&logoColor=white)](https://github.com/sindresorhus/awesome)
[![Github](https://img.shields.io/badge/Awesome--State--In--World--Models-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hit-perfect/Awesome-State-In-World-Models)
![Visitors](https://komarev.com/ghpvc/?username=hit-perfect&repo=Awesome-State-In-World-Models&label=Visitors&color=0e75b6&style=for-the-badge)

<!-- 
[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/XXXX.XXXXX)
[![HF Papers](https://img.shields.io/badge/HF--Paper-%23FFD14D?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/papers/XXXX.XXXXX)
-->

</div>

> 💡 **We encourage contributions!** If you come across relevant research that we haven't covered, please open an issue to let us know, and we'll do our best to include it in future updates.

## 🤩 Overview

Our survey proposes a **State-and-Dynamic-scentric taxonomy** for video generative “world models” (state construction and dynamics modeling) and argues for shifting evaluation from visual realism to functional tests of persistence and causality to advance toward robust, general-purpose simulators.

<p align="center">
   <img src="figs/Overview.png" alt="Overview of our Survey" style="width: 100%;">
</p>

We organize the survey into several key sections:

1. <u>Preliminary:</u> formalizes world models and, using open-loop video generation, maps progress in memory and causality toward robust world simulation.
2. <u>State Categorization:</u> Implicit State and Explicit State.
3. <u>Dynamics Categorization:</u> Causal Architecture Reformulation and Causal Knowledge Integration.
4. <u>Evaluation:</u> World-simulation evaluation centers on three axes: Quality, Persistence, and Causality.
5. <u>Future Directions:</u> World simulation is a paradigm shift that hinges on Persistence and Causality.

## 📈 Citation

If you find this survey helpful, please cite our work:

```bibtex
@article{wang2026mechanistic,
  title={A Mechanistic View on Video Generation as World Models: State and Dynamics},
  author={Wang, Luozhou and Chen, Zhifei and Du, Yihua and Yan, Dongyu and Ge, Wenhang and Shen, Guibao and Xu, Xinli and Wu, Leyi and Chen, Man and Xu, Tianshuo and Ren, Peiran and Tao, Xin and Wan, Pengfei and Chen, Ying-Cong},
  year={2026},
}
```

## 🎉 News
- **[2026-01-26]** 🔥 We are excited to introduce a comprehensive collection of papers and projects on video generation as world models with a mechanistic view on state and dynamics!

## 📖 Contents
- [A Mechanistic View on Video Generation as World Models: State and Dynamics](#a-mechanistic-view-on-video-generation-as-world-models-state-and-dynamics)
- [🤩 Overview](#-overview)
- [📈 Citation](#-citation)
- [🎉 News](#-news)
- [📖 Contents](#-contents)
- [📚 Paper List](#-paper-list)
  - [State](#state)
    - [Implicit State - Memory Mechanism](#implicit-state---memory-mechanism)
      - [Compression](#compression)
      - [Retrieval](#retrieval)
        - [External](#external)
        - [Internal](#internal)
      - [Consolidation](#consolidation)
    - [Explicit State](#explicit-state)
      - [Coupled States](#coupled-states)
        - [Hidden-Variable](#hidden-variable)
        - [Parametric](#parametric)
      - [Decoupled States](#decoupled-states)
        - [Semantics-oriented](#semantics-oriented)
        - [Geometry-oriented](#geometry-oriented)
  - [Dynamics](#dynamics)
    - [Causal Architecture Reformulation](#causal-architecture-reformulation)
    - [Causal Knowledge Integration](#causal-knowledge-integration)
  - [Evaluation](#evaluation)
    - [Quality](#quality)
    - [Persistence](#persistence)
    - [Causality](#causality)
- [🌟 Acknowledgment](#-acknowledgment)
- [✨ Star History](#-star-history)


## 📚 Paper List

### State

#### Implicit State - Memory Mechanism

<p align="center">
   <img src="figs/Implicit_State.png" alt="Overview of our Survey" style="width: 100%;">
</p>

##### Compression

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-12 | `VidToMe` | VidToMe: Video Token Merging for Zero-Shot Video Editing | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2312.10656) | - |
| 2024-10 | `Pyramidal Flow` | Pyramidal Flow Matching for Efficient Video Generative Modeling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.05954) | - |
| 2025-02 | `SVG` | Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.01776) | - |
| 2025-04 | `FramePack` | Packing Input Frame Context in Next-Frame Prediction Models for Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.12626) | - |
| 2025-07 | `LoViC` | LoViC: Efficient Long Video Generation with Context Compression | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.12952) | - |
| 2025-11 | `TempoMaster` | TempoMaster: Efficient Long Video Generation via Next-Frame-Rate Prediction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.12578) | - |
| 2025-12 | `RELIC` | RELIC: Interactive Video World Model with Long-Horizon Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.04040) | - |

##### Retrieval

###### External

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2025-04 | `RAGME` | RAGME: Retrieval Augmented Video Generation for Enhanced Motion Realism | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.06672) | - |
| 2025-04 | `WorldMem` | WorldMem: Long-term Consistent World Simulation with Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.12369) | - |
| 2025-05 | `VRAG` | Learning World Models for Interactive Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.21996) | - |
| 2025-06 | `Context-as-Memory` | Context as Memory: Scene-consistent Interactive Long Video Generation with Memory Retrieval | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.03141) | - |
| 2025-08 | `Corgi` | Corgi: Cached Memory Guided Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.16078) | - |
| 2025-09 | `MotionRAG` | MotionRAG: Motion Retrieval-Augmented Image-to-Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.26391) | - |
| 2025-10 | `Pack and Force` | Pack and Force Your Memory: Long-form and Consistent Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01784) | - |
| 2025-10 | `Ctrl-World` | Ctrl-World: A Controllable Generative World Model for Robot Manipulation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.10125) | - |
| 2025-11 | `MagicWorld` | MagicWorld: Interactive Geometry-driven Video World Exploration | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.18886) | - |
| 2025-11 | `DiT-Mem` | Learning Plug-and-play Memory for Guiding Video Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.19229) | - |
| 2025-12 | `WorldPack` | WorldPack: Compressed Memory Improves Spatial Consistency in Video World Modeling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.02473) | - |
| 2025-12 | `OneStory` | OneStory: Coherent Multi-Shot Video Generation with Adaptive Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.07802) | - |

###### Internal

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-12 | `VSA` | Faster Video Diffusion with Trainable Sparse Attention | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.04512) | - |
| 2025-02 | `MoBA` | MoBA: Mixture of Block Attention for Long-Context LLMs | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.13189) | - |
| 2025-02 | `AdaSpa` | Training-free and Adaptive Sparse Attention for Efficient Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.21079) | - |
| 2025-05 | `SVG2` | Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.18875) | - |
| 2025-06 | `ReSA` | Rectified Sparse Attention | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.04108) | - |
| 2025-06 | `Video-XL-2` | Video-XL-2: Towards Very Long-Video Understanding Through Task-Aware KV Sparsification | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.19225) | - |
| 2025-06 | `Radial Attention` | Radial Attention: Sparse Attention with Energy Decay for Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.19852) | - |
| 2025-06 | `VMOBA` | VMoBA: Mixture-of-Block Attention for Video Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.23858) | - |
| 2025-08 | `MoC` | Mixture of Contexts for Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.21058) | - |
| 2025-09 | `BSA` | Bidirectional Sparse Attention for Faster Video Diffusion Training | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.01085) | - |
| 2025-10 | `MoGA` | MoGA: Mixture-of-Groups Attention for End-to-End Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.18692) | - |

##### Consolidation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-12 | `FreeLong` | FreeLong: Training-free Long Video Generation with SpectralBlend Temporal Attention | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2312.06263) | - |
| 2024-03 | `StreamingT2V` | StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.14773) | - |
| 2024-10 | `Loong` | Loong: Generating Minute-level Long Videos with Autoregressive Language Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.02757) | - |
| 2025-03 | `FAR` | Long-context Autoregressive Video Modeling with Next-frame Prediction | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.19325) | - |
| 2025-08 | `WorldWeaver` | WorldWeaver: Generating Long-horizon Video Worlds via Rich Perception | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.15720) | - |
| 2025-12 | `EgoLCD` | EgoLCD: Egocentric Video Generation with Long Context Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.04515) | - |

#### Explicit State

<p align="center">
   <img src="figs/Explicit_State.png" alt="Overview of our Survey" style="width: 50%;">
</p>

##### Coupled States

###### Hidden-Variable

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-05 | `Matten` | Matten: Video Generation with Mamba-Attention | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.03025) | - |
| 2024-05 | `DiM` | Scaling Diffusion Mamba with Bidirectional SSMs for Efficient Image and Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2405.15881) | - |
| 2024-09 | `LinGen` | LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.09396) | - |
| 2025-02 | `MALT` | MALT Diffusion: Memory-Augmented Latent Transformers for Any-Length Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.12632) | - |
| 2025-05 | `Po et al.` | Long-context State-space Video World Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.20171) | - |
| 2025-09 | `SANA-Video` | SANA-Video: Efficient Video Generation with Block Linear Diffusion Transformer | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.24695) | - |
| 2025-11 | `RAD` | Recurrent Autoregressive Diffusion: Global Memory Meets Local Attention | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.12940) | - |
| 2025-12 | `VideoSSM` | VideoSSM: Autoregressive Long Video Generation with Hybrid State-Space Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.04519) | - |

###### Parametric

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-10 | `Nested Learning` | Nested Learning: The Illusion of Deep Learning Architectures | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.08735) | - |
| 2024-12 | `Titans` | Titans: Learning to Memorize at Test Time | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.00663) | - |
| 2025-01 | `TTT-DiT` | One-minute Video Generation with Test-time Training | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.06716) | - |

##### Decoupled States

###### Semantics-oriented

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-12 | `Owl-1` | Owl-1: Omni World Model for Consistent Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.09600) | - |
| 2025-10 | `Pack and Force` | Pack and Force Your Memory: Long-form and Consistent Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01784) | - |

###### Geometry-oriented

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2024-09 | `ViewCrafter` | ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.02048) | - |
| 2024-09 | `GenFusion` | GenFusion: Closing the Loop Between Reconstruction and Generation via Videos | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.01761) | - |
| 2024-12 | `Scene Splatter` | Scene Splatter: Momentum 3D Scene Generation from Single Image with Video Diffusion Model | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.16156) | - |
| 2025-01 | `Gen3C` | Gen3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.04740) | - |
| 2025-01 | `StarGen` | StarGen: A Spatiotemporal Autoregression Framework with Video Diffusion Model for Scalable and Controllable Scene Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.09095) | - |
| 2025-03 | `FlexWorld` | FlexWorld: Progressively Expanding 3D Scenes for Flexible-view Synthesis | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.13265) | - |
| 2025-04 | `Uni3C` | Uni3C: Unifying Precisely 3D-Enhanced Camera and Human Motion Controls for Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.14899) | - |
| 2025-06 | `Voyager` | Voyager: Long-Range and World-Consistent Video Diffusion for Explorable 3D Scene Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.04225) | - |
| 2025-06 | `VMem` | VMem: Consistent Interactive Video Scene Generation with Surfel-Indexed View Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.18903) | - |
| 2025-08 | `Matrix-3D` | Matrix-3D: Omnidirectional Explorable 3D World Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.08086) | - |
| 2025-10 | `EvoWorld` | EvoWorld: Evolving Panoramic World Generation with Explicit 3D Memory | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.01183) | - |


### Dynamics

#### Causal Architecture Reformulation

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-09 | `LVD` | LLM-grounded Video Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.17444) | - |
| 2023-12 | `VideoPoet` | VideoPoet: A Large Language Model for Zero-Shot Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2312.14125) | - |
| 2024 | `ART-V` | ART-V: Auto-regressive Text-to-Video Generation with Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2311.18834) | - |
| 2024 | `Diffusion Forcing` | Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.01392) | - |
| 2024-12 | `NOVA` | Autoregressive Video Generation without Vector Quantization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.14169) | - |
| 2025 | `AR-Diffusion` | AR-Diffusion: Asynchronous Video Generation with Auto-Regressive Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.09000) | - |
| 2025 | `CausVid` | From Slow Bidirectional to Fast Autoregressive Video Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2411.07306) | - |
| 2025-05 | `MAGI-1` | MAGI-1: Autoregressive Video Generation at Scale | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.13211) | - |
| 2025-05 | `Video-GPT` | Video-GPT via Next Clip Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.12489) | - |
| 2025-06 | `VideoMAR` | VideoMAR: Autoregressive Video Generation with Continuous Tokens | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.14168) | - |
| 2025-06 | `Self-Forcing` | Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.08009) | - |
| 2025-07 | `Lumos-1` | Lumos-1: On Autoregressive Video Generation from a Unified Model Perspective | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2507.08801) | - |
| 2025-09 | `LongLive` | LongLive: Real-time Interactive Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.22622) | - |
| 2025-09 | `Rolling Forcing` | Rolling Forcing: Autoregressive Long Video Diffusion in Real Time | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2509.25161) | - |
| 2025-10 | `Self-Forcing++` | Self-Forcing++: Towards Minute-Scale High-Quality Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.02283) | - |
| 2025-12 | `Resampling Forcing` | End-to-End Training for Autoregressive Video Diffusion via Self-Resampling | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.15702) | - |

#### Causal Knowledge Integration

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2023-09 | `VIDEODIRECTORGPT` | VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-guided Planning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2309.15091) | - |
| 2024-12 | `Owl-1` | Owl-1: Omni World Model for Consistent Long Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.09600) | - |
| 2024-12 | `DirectorLLM` | Llama Learns to Direct: DirectorLLM for Human-Centric Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2412.14484) | - |
| 2025-03 | `VLIPP` | VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.23368) | - |
| 2025-05 | `BAGEL` | Emerging Properties in Unified Multimodal Pretraining | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.14683) | - |
| 2025-06 | `CSVC` | Causally Steered Diffusion for Automated Video Counterfactual Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2506.14404) | - |
| 2025-10 | `UniVideo` | UniVideo: Unified Understanding, Generation, and Editing for Videos | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.08377) | - |
| 2025-12 | `SemanticGen` | SemanticGen: Video Generation in Semantic Space | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.20619) | - |


### Evaluation

#### Quality

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2018 | `FVD` | Towards Accurate Generative Models of Video: A New Metric & Challenges | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/1812.01717) | - |
| 2023-11 | `VBench` | VBench: Comprehensive Benchmark Suite for Video Generative Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2311.17982) | - |
| 2024-07 | `FVMD` | Fréchet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.16124) | - |
| 2024-11 | `VBench++` | VBench++: Comprehensive and Versatile Benchmark Suite for Video Generative Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2411.13503) | - |
| 2025-02 | `WorldModelBench` | WorldModelBench: Judging Video Generation Models as World Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.20694) | - |

#### Persistence

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2017 | `FID` | GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/1706.08500) | - |
| 2022-10 | `Memory Maze` | Evaluating Long-Term Memory in 3D Mazes | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2210.13383) | - |
| 2025-08 | `World Consistency Score` | World Consistency Score: A Unified Metric for Video Generation Quality | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.00144) | - |
| 2025-11 | `VR-Bench` | Reasoning via Video: The First Evaluation of Video Models' Reasoning Abilities through Maze-Solving Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2511.15065) | - |

#### Causality

| Date | Name | Title | Paper | Github |
|:-:|:-:|:-|:-:|:-:|
| 2020 | `RLBench` | RLBench: The Robot Learning Benchmark & Learning Environment | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/1909.12271) | - |
| 2022 | `CALVIN` | CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2112.03227) | - |
| 2024-06 | `ChronoMagic-Bench` | ChronoMagic-Bench: A Benchmark for Metamorphic Evaluation of Text-to-Time-lapse Video Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2406.18522) | - |
| 2025 | `VideoWorld` | VideoWorld: Exploring Knowledge Learning from Unlabeled Videos | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.06450) | - |
| 2025-01 | `Physics-IQ` | Do Generative Video Models Understand Physical Principles? | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2501.09038) | - |
| 2025-10 | `World-in-World` | World-in-World: World Models in a Closed-Loop World | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2510.18135) | - |


## 🌟 Acknowledgment

We would like to express our sincere gratitude to the [Awesome-RL-for-LRMs](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs) repository for providing an excellent README template that inspired the structure and organization of this collection. Their well-designed format has been instrumental in helping us present our survey in a clear and accessible manner.

## ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hit-perfect/Awesome-State-In-World-Models&type=Date)](https://www.star-history.com/#hit-perfect/Awesome-State-In-World-Models&Date)