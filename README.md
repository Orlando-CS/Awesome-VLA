<div align="center">
  <h1>Awesome Vision-Language-Action (VLA) Models</h1>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome Badge"/>
  </a>
  <img src="https://img.shields.io/github/stars/Orlando-CS/Awesome-VLA.svg?style=social" alt="GitHub stars"/>
</div>

This is a collection of research papers about Embodied Multimodal Large Language Models (VLA models).

If you would like to include your paper or update any details (e.g., code URLs, conference information), please feel free to submit a pull request. Any advice is also welcome!

# 📑 Table of Contents
- [Awesome VLA Models](#awesome-vla-models)
- [Awesome Papers](#awesome-papers)
- [Awesome Datasets and Benchmarks](#awesome-datasets-and-benchmarks)

# Awesome VLA Models

🔥🔥🔥 **RT-2: Robotics Transformer 2 — End-to-End Vision-Language-Action Model**  


[📖 Paper](https://arxiv.org/abs/2307.15818) | [🌟 Project](https://robotics-transformer2.github.io/)
<img src="./images/rt2.jpg" width="45%" alt="RT-2 Image">

Integrates vision-language models trained on internet-scale data directly into robotic control pipelines. ✨

---

🔥🔥🔥 **Helix: Generalist VLA Model for Full-Body Humanoid Control**  

[🌟 Project](https://www.figure.ai/news/helix)
<img src="./images/helix.jpg" width="45%" alt="Helix Image">

First VLA model achieving full upper-body humanoid control including fingers, wrists, torso, and head. ✨

---

🔥🔥🔥 **π0 (Pi-Zero): Generalist VLA Across Diverse Robots**  

[🌟 Project](https://huggingface.co/blog/pi0)

Generalist control across various robot embodiments, utilizing large-scale pretraining and flow matching action generation. ✨

---

🔥🔥🔥 **OpenVLA: Open-Source Large-Scale Vision-Language-Action Model**  

[📖 Paper](https://arxiv.org/abs/2406.09246) | [🌟 Project](https://openvla.github.io/) | [🤖 Hugging Face](https://huggingface.co/openvla/openvla-7b)

Pretrained on 970k+ robotic episodes, setting a new benchmark for generalist robotic policies. ✨

---

🔥🔥🔥 **Gemini Robotics: Multimodal Generalization to Physical Action**  


[🌟 Project](https://www.theverge.com/news/628021/google-deepmind-gemini-robotics-ai-models)
<img src="./images/gemini_robotics.webp" width="45%" alt="Gemini Robotics Image">

Built on Gemini 2.0, enabling complex real-world manipulation without task-specific training. ✨

---

# Awesome Papers

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378) | Integrates perception, language, and action for embodied AI. | 2023-03-06 | - |
| [EmbodiedGPT](https://arxiv.org/abs/2305.15021) | Vision-language models with embodied CoT reasoning. | 2023-05-24 | [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |
| [Co-LLM-Agents](https://arxiv.org/abs/2307.02485) | Cooperative embodied agents via modular LLMs. | 2023-07-05 | [Github](https://github.com/UMass-Foundation-Model/Co-LLM-Agents) |
| [RT-2](https://arxiv.org/abs/2307.15818) | Transfers VLM internet knowledge to robotic control. | 2023-07-28 | - |
| [LLM as Policies](https://arxiv.org/abs/2310.17722) | Apple: LLMs for embodied tasks as policies. | 2023-10-26 | [Github](https://github.com/apple/ml-llarp) |
| [Embodied Generalist Agent 3D](https://arxiv.org/abs/2311.12871) | Generalist agent in 3D worlds. | 2023-11-18 | [Github](https://github.com/IST-DASLab/sparsegpt) |
| [LL3DA](https://arxiv.org/abs/2311.18651) | Omni-3D understanding via instruction tuning. | 2023-11-30 | [Github](https://github.com/Open3DA/LL3DA) |
| [NaviLLM](https://arxiv.org/abs/2312.02010) | Generalist navigation models. | 2023-12-04 | [Github](https://github.com/zd11024/NaviLLM) |
| [MP5](https://arxiv.org/abs/2312.07472) | Open-ended embodied agent in Minecraft. | 2023-12-12 | [Github](https://github.com/IranQin/MP5) |
| [ManipLLM](https://arxiv.org/abs/2312.16217) | Object-centric robotic manipulation via LLMs. | 2023-12-24 | [Github](https://github.com/clorislili/ManipLLM) |
| [MultiPLY](https://arxiv.org/abs/2401.08577) | Multisensory 3D embodied LLMs. | 2024-01-16 | [Github](https://github.com/UMass-Foundation-Model/MultiPLY) |
| [NaVid](https://arxiv.org/abs/2402.15852) | Next-step planning in navigation. | 2024-02-24 | - |
| [ShapeLLM](https://arxiv.org/abs/2402.17766) | 3D object understanding for embodied agents. | 2024-02-27 | [Github](https://github.com/qizekun/ShapeLLM) |
| [3D-VLA](https://arxiv.org/abs/2403.09631) | Generative 3D world model for VLA learning. | 2024-03-14 | [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |
| [RoboMP²](https://arxiv.org/abs/2404.04929) | Multimodal robotic perception-planning. | 2024-04-07 | - |
| [Helix](https://www.figure.ai/news/helix) | Full-body humanoid control model. | 2024-04 | [Project](https://www.figure.ai/news/helix) |
| [Embodied CoT Distillation](https://openreview.net/pdf?id=M4Htd52HMH) | Distilling embodied CoT into agents. | 2024-05-02 | - |
| [Gemini Robotics](https://www.theverge.com/news/628021/google-deepmind-gemini-robotics-ai-models) | Real-world manipulation by Gemini. | 2024-05 | [Project](https://www.theverge.com/news/628021/google-deepmind-gemini-robotics-ai-models) |
| [A3VLM](https://arxiv.org/abs/2406.07549) | Actionable articulation-aware VLMs. | 2024-06-11 | [Github](https://github.com/changhaonan/A3VLM) |
| [OpenVLA](https://arxiv.org/abs/2406.09246) | Open-sourced 7B vision-language-action model. | 2024-06-13 | [Github](https://github.com/openvla/openvla) |
| [TinyVLA](https://arxiv.org/abs/2409.12514) | Compact and efficient VLA models. | 2024-09 | [Paper](https://arxiv.org/abs/2409.12514) |
| [VLA Expert Collaboration](https://arxiv.org/abs/2503.04163) | Improves VLA via expert actions. | 2025-03 | [Paper](https://arxiv.org/abs/2503.04163) |

---

# Awesome Datasets and Benchmarks

## 🏗️ Scene / Environment Generation

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [Holodeck](https://arxiv.org/abs/2312.09067) | LLMs generate interactive 3D simulation environments. | 2023-12-14 | [Github](https://github.com/allenai/Holodeck) |
| [PhyScene](https://arxiv.org/pdf/2404.09465) | Physically interactive 3D scenes for embodied training. | 2024-04-15 | [Github](https://github.com/PhyScene/PhyScene/tree/main) |

## 🧠 Question Answering / Language Interaction Benchmarks

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [OpenEQA](https://openaccess.thecvf.com/content/CVPR2024/papers/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.pdf) | Visual QA benchmark for real-world scenes. | 2024-06-17 | [Github](https://github.com/facebookresearch/open-eqa) |
| [EQA-REAL](https://arxiv.org/abs/2404.13083) | Real-world EmbodiedQA for indoor settings. | 2024-04 | [Github](https://github.com/facebookresearch/eqa-real) |
| [TEACh](https://arxiv.org/abs/2109.00582) | Human-human embodied task dialogues. | 2023 update (original 2021) | [Github](https://github.com/alexa/teach) |

## 👀 Multi-Modal Perception Datasets

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [EmbodiedScan](https://arxiv.org/abs/2312.16170) | Real-world RGB-D + language 3D scans. | 2023-12-26 | [Github](https://github.com/OpenRobotLab/EmbodiedScan) |

## 🕹️ End-to-End Embodied Decision Making / Simulators

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [PCA-EVAL](https://arxiv.org/abs/2310.02071) | Decision-making via GPT-4V evaluation. | 2023-10-03 | [Github](https://github.com/pkunlp-icler/PCA-EVAL) |
| [UniSim](https://arxiv.org/abs/2310.06114) | Interactive real-world simulator learning. | 2023-10-09 | - |

## 🏡 Household Activities / Task Benchmarks

| Title | Introduction | Date | Code |
|:---|:---|:---|:---|
| [BEHAVIOR-1K](https://arxiv.org/abs/2307.07263) | 1,000 household activity programs and scenes. | 2023-07-11 | [Project](https://behavior.stanford.edu/) |
