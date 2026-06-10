<div align="center">

<h1>🎬 Awesome-Video-Agent</h1>

<p>🍦Exploring the latest papers in Video Agent & long video understanding.🍦</p>

<p><img width="768px" alt="image" src="assets/logo.png"></p>

<img src='https://awesome.re/badge.svg' alt='Survey'>
<img src='https://img.shields.io/badge/Related Work-10+ Papers-blue' alt='MorePapers'>
<img src='https://img.shields.io/badge/Update 🔥-2026.03.15-red' alt='MorePapers'>

</div>

---

# 1️⃣ Awesome Papers

> ⚠️ 这里整理的所有论文均开源代码，并且已排除代码仓库为空的情况。
> 
> ❗️ 总结部分只针对论文方法总结，不介绍论文其他方面（比如论文提出benchmark构造思路）

<details open>
<summary><strong>2026</strong></summary>
<div>

| 📑 论文 | 🏅出处 | 🏫 单位 | ✨ 总结 | 🚀 是否Training-Free | 📊 评测数据集 |
| --- | --- | --- | --- | --- | --- |
| Tempo：Small Vision-Language Models are Smart Compressors for Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2604.08120-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2604.08120) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://feielysia.github.io/tempo-page) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2026/2604.08120_Tempo.md) | Arxiv | Meta AI；King Abdullah University of Science and Technology (KAUST) | 论文提出Tempo，用小型视觉语言模型作为局部压缩器生成与查询对齐的视频记忆，再由全局大语言模型完成理解与生成。进一步提出ATA策略，利用零样本相关性先验和语义前置特性，在严格预算下动态分配token，兼顾关键细节保留与全局时间连续性。 | ❌ | LongVideoBench、MLVU、Video-MME 和 LVBench（Long） |
| Agentic Very Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2601.18157-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2601.18157) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://facebookresearch.github.io/egagent) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2026/2601.18157_EGAgent.md) | Arxiv | Reality Labs Research at Meta；University of Wisconsin-Madison | 针对现有方法难以支持跨天的组合式、多跳超长视频推理问题，论文提出EGAgent，通过带时间标注的实体图结合视觉、音频检索与规划智能体，实现超长视频的跨模态、多跳推理。 | ✅ | EgoLifeQA、Video-MME（Long） |

</div>
</details>

<details open>
<summary><strong>2025</strong></summary>
<div>

| 📑 论文                                                       | 🏅出处                  | 🏫 单位                                                       | ✨ 总结                                                       | 🚀 是否Training-Free                                      | 📊 评测数据集                                                 |
| --- | --- | --- | --- | --- | --- |
| LongVideoAgent: Multi-Agent Reasoning with Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2512.20618-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.20618) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://longvideoagent.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.20618_LongVideoAgent.md) | Arxiv | Hong Kong University of Science and Technology；Monash University | LongVideoAgent通过主控智能体协调定位与视觉子智能体，在多轮迭代中定位相关片段并按需读取视觉细节，在累积证据后完成长视频问答。 | ❌（包括GRPO训练过程） | LongTVQA、LongTVQA+（均为论文提出） |
| A Benchmark and Agentic Framework for Omni-Modal Reasoning and Tool Use in Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2512.16978-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.16978) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/longshot) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.16978_LongShOT.md) | Arxiv | MBZUAI；American University of Beirut；Linkoping University | 论文提出LongShOT，通过训练模块化智能体，将长视频理解转化为跨视觉、语音和音频的检索、工具调用与迭代优化过程，实现全模态长视频推理。 | ✅ | LongShOTBench（论文提出） |
| Active Video Perception: Iterative Evidence Seeking for Agentic Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2512.05774-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.05774) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://activevideoperception.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.05774_Active_Video_Perception.md) | Arxiv | Salesforce AI Research；University of North Carolina at Chapel Hill | Active Video Perception将长视频视为可交互环境，通过“规划—观察—反思”迭代主动搜寻与问题相关的时间戳证据，从而高效完成长视频理解。 | ✅ | MINERVA、LVBench、MLVU、Video-MME、LongVideoBench |
| LongVT: Incentivizing "Thinking with Long Videos" via Native Tool Calling [![arXiv](https://img.shields.io/badge/arXiv-2511.20785-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2511.20785) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://evolvinglmms-lab.github.io/LongVT/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2511.20785_LongVT.md) | CVPR 2026 | MiroMind AI；NTU；HKUST(GZ)；THU；LMMs-Lab Team | LongVT 引入原生视频工具调用，并采用分阶段训练流程（包含SFT与RL阶段）使模型能够直接“基于长视频进行思考”。 | ❌，包含SFT、RL、RFT等训练方式（n*NVIDIA A800-SXM4-80GB） | VideoMME , VideoMMMU, LVBench, and our self-curated VideoSIAH-Eval |
| Video-CoM: Interactive Video Reasoning via Chain of Manipulations [![arXiv](https://img.shields.io/badge/arXiv-2511.23477-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2511.23477) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/Video-CoM) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2511.23477_Video_CoM.md) | Arxiv | Mohamed bin Zayed University of AI；University of California Merced；Google Research；Linkoping University；Australian National University | Video-CoM 将长视频推理建模为“操作链”的交互过程，模型通过迭代操作不断细化时空证据。论文还引入配套训练数据与基于强化学习的优化策略，以增强分步骤推理质量。 | ❌，包含SFT、GRPO等训练过程 | Video-MMMU、MMVU-Val、Minerva、ScienceVideoBench、VideoMathQA、TempoCompass、Video-MME、MLVU、Video-CoM-Bench（论文提出） |
| Vgent: Graph-based Retrieval-Reasoning-Augmented Generation For Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2510.14032-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2510.14032) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://xiaoqian-shen.github.io/Vgent/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2510.14032_Vgent.md) | NeurIPS 2025 Spotlight | King Abdullah University of Science and Technology；Meta AI | Vgent 提出一种面向长视频理解的图结构检索与推理增强生成框架。该方法将视频片段组织为结构化图，通过“图检索+结构化中间推理”过滤噪声、聚合证据，从而提升长视频问答效果。 | ✅ | Video-MME、MLVU、LongVideoBench (LVB) |
| VideoLucy: Deep Memory Backtracking for Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2510.12422-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2510.12422) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videolucy.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2510.12422_VideoLucy.md) | NeurIPS 2025 | Huazhong University of Science and Technology；NUS；NTU S-Lab；Shanghai AI Lab | VideoLucy通过由粗到细的分层记忆和智能体迭代回溯机制，逐步挖掘与问题相关的深层视频记忆，从而兼顾长时序理解与关键细节保留。 | ✅ | MLVU、Video-MME、LVBench、EgoMem（论文提出） |
| Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2505.18079-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2505.18079) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/microsoft/DeepVideoDiscovery) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2505.18079_Deep_Video_Discovery.md) | NeurIPS 2025 | Microsoft Research Asia；University of Science and Technology of China | Deep Video Discovery先将长视频构造成多粒度可搜索数据库，再由LLM自主调用全局浏览、片段搜索和帧级检查工具，迭代检索证据并完成长视频问答。 | ✅ | LVBench、LongVideoBench、Video MME、EgoSchema |

</div>
</details>

<details open>
<summary><strong>2024</strong></summary>
<div>

| 📑 论文                                                       | 🏅出处     | 🏫 单位                              | ✨ 总结                                                       | 🚀 是否Training-Free | 📊 评测数据集                       |
| --- | --- | --- | --- | --- | --- |
| DrVideo: Document Retrieval Based Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2406.12846-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2406.12846) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/Upper9527/DrVideo) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2406.12846_DrVideo.md) | CVPR 2025 | Hunan University；Monash University | DrVideo将长视频转为可检索的长文档，通过关键帧检索、文档增强和多阶段Agent循环逐步补全缺失信息，实现零样本长视频理解。 | ✅ | EgoSchema、MovieChat-1K、Video-MME |
| VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2405.19209-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2405.19209) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videotree2024.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2405.19209_VideoTree.md) | CVPR 2025 | UNC Chapel Hill | VideoTree 提出一种 Training-free 的自适应树结构视频表示方法。该方法根据查询进行关键帧选择，并执行由粗到细的视频树结构表示扩展，从而支持LLM高效完成长视频推理。 | ✅ | EgoSchema、NExT-QA、Video-MME |
| VideoAgent: Long-form Video Understanding with Large Language Model as Agent [![arXiv](https://img.shields.io/badge/arXiv-2403.10517-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2403.10517) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://wxh1996.github.io/VideoAgent-Website/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2403.10517_VideoAgent_LongForm.md) | ECCV 2024 | Stanford University | （首个Video Agent）VideoAgent 将长视频理解建模为由 LLM 控制的智能体决策过程。Agent通过迭代规划动作、检索信息帧并针对观察结果推理，实现更高效的视频问答。 | ✅ | EgoSchema、NExT-QA |
| VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2403.11481-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.11481) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videoagent.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2403.11481_VideoAgent_MemoryAugmented.md) | ECCV 2024 | BIGAI；Peking University | VideoAgent将长视频转化为可检索的时序记忆（物体随时间的变化）与物体记忆（物体自身状态的变化），并由LLM以零样本工具调用方式逐步查询记忆，实现长视频问答与时刻定位。 | ✅ | EgoSchema、WorldQA、NExT-QA |

</div>
</details>

---

# 2️⃣ Awesome Benchmarks

<details>
<summary><strong>2026</strong></summary>
<div>

| 📊Benchmark | 🐱 GitHub | ✨ 简介 | 🏅 出处 |
| --- | --- | --- | --- |
| VideoSIAH-Eval | [Project](https://huggingface.co/datasets/EvolvingLMMs-Lab/VideoSIAH-Eval) | LongVT paper curated benchmark for long-video temporal reasoning and tool-calling evaluation. | - |

</div>
</details>

<details open>
<summary><strong>2025</strong></summary>
<div>

| 📊Benchmark        | 🐱 GitHub                                                     | ✨ 简介                                                       | 🏅 出处    |
| --- | --- | --- | --- |
| VideoMMMU | [Project](https://github.com/gregor-ge/CinePile/tree/main/videommmu) | A benchmark for expert-level multimodal understanding and reasoning on videos. | - |
| MMVU / MMVU-Val | [Project](https://mmvu-benchmark.github.io/) | A benchmark for evaluating multimodal video understanding and reasoning. | - |
| MINERVA | [Code](https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva) | A long-video understanding benchmark in the Neptune suite for memory and retrieval intensive reasoning. | - |
| MLVU | [Code](https://github.com/JUNJIE99/MLVU) | A Comprehensive Benchmark for Multi-Task Long Video Understanding. | CVPR 2025 |
| LVBench | [Project](https://lvbench.github.io/) | An Extreme Long Video Understanding Benchmark. | ICCV 2025 |
| Video-MME | [Project](https://video-mme.github.io/) | The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis | - |
| Video-CoM-Bench | [Code](https://github.com/mbzuai-oryx/Video-CoM) | A benchmark introduced by Video-CoM for interactive video reasoning with chain-of-manipulations. | - |
| ScienceVideoBench | [Code](https://github.com/mbzuai-oryx/Video-CoM) | A science-oriented video reasoning benchmark used in Video-CoM evaluation. | - |
| VideoMathQA | [Code](https://github.com/mbzuai-oryx/Video-CoM) | A video mathematical reasoning benchmark used in Video-CoM evaluation. | - |
| EgoMem | [Project](https://videolucy.github.io/) | A benchmark introduced by VideoLucy for ultra-long egocentric video memory understanding. | - |

</div>
</details>

<details open>
<summary><strong>2024</strong></summary>
<div>

| 📊Benchmark     | 🐱 GitHub                                              | ✨ 简介                                                       | 🏅 出处       |
| --- | --- | --- | --- |
| EgoSchema | [Project](https://egoschema.github.io/) | A diagnostic benchmark for very long-form video language understanding. | - |
| WorldQA | [Project](https://zhangyuanhan-ai.github.io/WorldQA/) | Multimodal World Knowledge in Videos through Long-Chain Reasoning. | - |
| LongVideoBench | [Project](https://longvideobench.github.io/) | A Benchmark for Long-context Interleaved Video-Language Understanding. | NeurIPS 2024 |
| MovieChat-1K | [Project](https://wenhaochai.com/MovieChat/) | From Dense Token to Sparse Memory in Long Video Understanding. | CVPR 2024 |

</div>
</details>

<details>
<summary><strong>更早之前</strong></summary>
<div>

| 📊Benchmark | 🐱 GitHub                                              | ✨ 简介                                                       | 🏅 出处    |
| --- | --- | --- | --- |
| NExT-QA | [Project](https://doc-doc.github.io/docs/nextqa.html) | Next Phase of Question-Answering to Explaining Temporal Actions. | CVPR 2021 |

</div>
</details>

## Contribution

Contributions are welcome! Please feel free to create an issue or open a pull request with your contributions.

### ✨You are welcome to provide us your work with a topic related to Video Agent & Long Video Understanding.✨

If you discover any missing work or have any suggestions, please feel free to submit a pull request to  `hzguo [at] tju.edu.cn` . we will promptly add the missing papers to this repository.

## About

Exploring the latest papers in Video Agent and long video understanding.
