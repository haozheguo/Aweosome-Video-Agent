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

#### Agentic Very Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2601.18157-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2601.18157) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://longvideoagent.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2026/2601.18157_EGAgent.md)

- **🏅 出处**：Arxiv
- **🏫 单位**：Reality Labs Research at Meta；University of Wisconsin-Madison
- **✨ 总结**：针对现有方法难以支持跨天的组合式、多跳超长视频推理问题，论文提出EGAgent，通过带时间标注的实体图结合视觉、音频检索与规划智能体，实现超长视频的跨模态、多跳推理。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：EgoLifeQA、Video-MME（Long）

</div>
</details>


<details open>
<summary><strong>2025</strong></summary>
<div>

#### LongVideoAgent: Multi-Agent Reasoning with Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2512.20618-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.20618) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://facebookresearch.github.io/egagent) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.20618_LongVideoAgent.md)

- **🏅 出处**：Arxiv
- **🏫 单位**：Hong Kong University of Science and Technology；Monash University
- **✨ 总结**：LongVideoAgent通过主控智能体协调定位与视觉子智能体，在多轮迭代中定位相关片段并按需读取视觉细节，在累积证据后完成长视频问答。
- **🚀 是否Training-Free**：❌（包括GRPO训练过程）
- **📊 评测数据集**：LongTVQA、LongTVQA+（均为论文提出）

#### A Benchmark and Agentic Framework for Omni-Modal Reasoning and Tool Use in Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2512.16978-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.16978) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/longshot) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.16978_LongShOT.md)

- **🏅 出处**：Arxiv
- **🏫 单位**：MBZUAI；American University of Beirut；Linkoping University
- **✨ 总结**：论文提出LongShOT，通过训练模块化智能体，将长视频理解转化为跨视觉、语音和音频的检索、工具调用与迭代优化过程，实现全模态长视频推理。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：LongShOTBench（论文提出）

#### Active Video Perception: Iterative Evidence Seeking for Agentic Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2512.05774-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2512.05774) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://activevideoperception.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2512.05774_Active_Video_Perception.md)

- **🏅 出处**：Arxiv
- **🏫 单位**：Salesforce AI Research；University of North Carolina at Chapel Hill
- **✨ 总结**：Active Video Perception将长视频视为可交互环境，通过“规划—观察—反思”迭代主动搜寻与问题相关的时间戳证据，从而高效完成长视频理解。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：MINERVA、LVBench、MLVU、Video-MME、LongVideoBench

#### LongVT: Incentivizing "Thinking with Long Videos" via Native Tool Calling [![arXiv](https://img.shields.io/badge/arXiv-2511.20785-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2511.20785) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://evolvinglmms-lab.github.io/LongVT/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2511.20785_LongVT.md)

- **🏅 出处**：CVPR 2026
- **🏫 单位**：MiroMind AI；NTU；HKUST(GZ)；THU；LMMs-Lab Team
- **✨ 总结**：LongVT 引入原生视频工具调用，并采用分阶段训练流程（包含SFT与RL阶段）使模型能够直接“基于长视频进行思考”。
- **🚀 是否Training-Free**：❌，包含SFT、RL、RFT等训练方式（n*NVIDIA A800-SXM4-80GB）
- **📊 评测数据集**：VideoMME , VideoMMMU, LVBench, and our self-curated VideoSIAH-Eval

#### Video-CoM: Interactive Video Reasoning via Chain of Manipulations [![arXiv](https://img.shields.io/badge/arXiv-2511.23477-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2511.23477) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/Video-CoM) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2511.23477_Video_CoM.md)

- **🏅 出处**：Arxiv
- **🏫 单位**：Mohamed bin Zayed University of AI；University of California Merced；Google Research；Linkoping University；Australian National University
- **✨ 总结**：Video-CoM 将长视频推理建模为“操作链”的交互过程，模型通过迭代操作不断细化时空证据。论文还引入配套训练数据与基于强化学习的优化策略，以增强分步骤推理质量。
- **🚀 是否Training-Free**：❌，包含SFT、GRPO等训练过程
- **📊 评测数据集**：Video-MMMU、MMVU-Val、Minerva、ScienceVideoBench、VideoMathQA、TempoCompass、Video-MME、MLVU、Video-CoM-Bench（论文提出）

#### Vgent: Graph-based Retrieval-Reasoning-Augmented Generation For Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2510.14032-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2510.14032) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://xiaoqian-shen.github.io/Vgent/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2510.14032_Vgent.md)

- **🏅 出处**：NeurIPS 2025 Spotlight
- **🏫 单位**：King Abdullah University of Science and Technology；Meta AI
- **✨ 总结**：Vgent 提出一种面向长视频理解的图结构检索与推理增强生成框架。该方法将视频片段组织为结构化图，通过“图检索+结构化中间推理”过滤噪声、聚合证据，从而提升长视频问答效果。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：Video-MME、MLVU、LongVideoBench (LVB)

#### VideoLucy: Deep Memory Backtracking for Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2510.12422-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2510.12422) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videolucy.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2510.12422_VideoLucy.md)

- **🏅 出处**：NeurIPS 2025
- **🏫 单位**：Huazhong University of Science and Technology；NUS；NTU S-Lab；Shanghai AI Lab
- **✨ 总结**：VideoLucy通过由粗到细的分层记忆和智能体迭代回溯机制，逐步挖掘与问题相关的深层视频记忆，从而兼顾长时序理解与关键细节保留。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：MLVU、Video-MME、LVBench、EgoMem（论文提出）

#### Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2505.18079-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2505.18079) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/microsoft/DeepVideoDiscovery) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2025/2505.18079_Deep_Video_Discovery.md)

- **🏅 出处**：NeurIPS 2025
- **🏫 单位**：Microsoft Research Asia；University of Science and Technology of China
- **✨ 总结**：Deep Video Discovery先将长视频构造成多粒度可搜索数据库，再由LLM自主调用全局浏览、片段搜索和帧级检查工具，迭代检索证据并完成长视频问答。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：LVBench、LongVideoBench、Video MME、EgoSchema

</div>
</details>


<details open>
<summary><strong>2024</strong></summary>
<div>

#### DrVideo: Document Retrieval Based Long Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2406.12846-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2406.12846) [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/Upper9527/DrVideo) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2406.12846_DrVideo.md)

- **🏅 出处**：CVPR 2025
- **🏫 单位**：Hunan University；Monash University
- **✨ 总结**：DrVideo将长视频转为可检索的长文档，通过关键帧检索、文档增强和多阶段Agent循环逐步补全缺失信息，实现零样本长视频理解。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：EgoSchema、MovieChat-1K、Video-MME

#### VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos [![arXiv](https://img.shields.io/badge/arXiv-2405.19209-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2405.19209) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videotree2024.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2405.19209_VideoTree.md)

- **🏅 出处**：CVPR 2025
- **🏫 单位**：UNC Chapel Hill
- **✨ 总结**：VideoTree 提出一种 Training-free 的自适应树结构视频表示方法。该方法根据查询进行关键帧选择，并执行由粗到细的视频树结构表示扩展，从而支持LLM高效完成长视频推理。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：EgoSchema、NExT-QA、Video-MME

#### VideoAgent: Long-form Video Understanding with Large Language Model as Agent [![arXiv](https://img.shields.io/badge/arXiv-2403.10517-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2403.10517) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://wxh1996.github.io/VideoAgent-Website/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2403.10517_VideoAgent_LongForm.md)

- **🏅 出处**：ECCV 2024
- **🏫 单位**：Stanford University
- **✨ 关键词**：（首个Video Agent）VideoAgent 将长视频理解建模为由 LLM 控制的智能体决策过程。Agent通过迭代规划动作、检索信息帧并针对观察结果推理，实现更高效的视频问答。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：EgoSchema、NExT-QA

#### VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding [![arXiv](https://img.shields.io/badge/arXiv-2403.11481-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.11481) [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videoagent.github.io/) [![Abstract](https://img.shields.io/badge/Abstract-中文翻译-0ea5e9?logo=bookstack&logoColor=white)](paper_abstract/2024/2403.11481_VideoAgent_MemoryAugmented.md)

- **🏅 出处**：ECCV 2024
- **🏫 单位**：BIGAI；Peking University
- **✨ 总结**：VideoAgent将长视频转化为可检索的时序记忆（物体随时间的变化）与物体记忆（物体自身状态的变化），并由LLM以零样本工具调用方式逐步查询记忆，实现长视频问答与时刻定位。
- **🚀 是否Training-Free**：✅
- **📊 评测数据集**：EgoSchema、WorldQA、NExT-QA

</div>
</details>


---

# 2️⃣ Awesome Benchmarks

<details>
<summary><strong>2026</strong></summary>
<div>

#### VideoSIAH-Eval [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://huggingface.co/datasets/EvolvingLMMs-Lab/VideoSIAH-Eval)

- VideoSIAH-Eval: LongVT paper curated benchmark for long-video temporal reasoning and tool-calling evaluation. (2026)

</div>
</details>


<details open>
<summary><strong>2025</strong></summary>
<div>

#### VideoMMMU [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://github.com/gregor-ge/CinePile/tree/main/videommmu)

- VideoMMMU: A benchmark for expert-level multimodal understanding and reasoning on videos. (2025)

#### MMVU / MMVU-Val [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://mmvu-benchmark.github.io/)

- MMVU: A benchmark for evaluating multimodal video understanding and reasoning. (2025)

#### MINERVA [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva)

- MINERVA: A long-video understanding benchmark in the Neptune suite for memory and retrieval intensive reasoning. (2025)

#### MLVU [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/JUNJIE99/MLVU)

- MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding. (CVPR 2025)

#### LVBench [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://lvbench.github.io/)

- LVBench: An Extreme Long Video Understanding Benchmark. (ICCV 2025)

#### Video-MME [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://video-mme.github.io/)

- Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis

#### Video-CoM-Bench [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/Video-CoM)

- Video-CoM-Bench: A benchmark introduced by Video-CoM for interactive video reasoning with chain-of-manipulations. (2025)

#### ScienceVideoBench [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/Video-CoM)

- ScienceVideoBench: A science-oriented video reasoning benchmark used in Video-CoM evaluation. (2025)

#### VideoMathQA [![GitHub](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/mbzuai-oryx/Video-CoM)

- VideoMathQA: A video mathematical reasoning benchmark used in Video-CoM evaluation. (2025)

#### EgoMem [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://videolucy.github.io/)

- EgoMem: A benchmark introduced by VideoLucy for ultra-long egocentric video memory understanding. (2025)

</div>
</details>


<details open>
<summary><strong>2024</strong></summary>
<div>

#### EgoSchema [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://egoschema.github.io/)

- Egoschema: A diagnostic benchmark for very long-form video language understanding.

#### WorldQA  [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://zhangyuanhan-ai.github.io/WorldQA/)

- WorldQA: Multimodal World Knowledge in Videos through Long-Chain Reasoning.

#### LongVideoBench [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://longvideobench.github.io/)

- LONGVIDEOBENCH: A Benchmark for Long-context Interleaved Video-Language Understanding.（NeurIPS 2024）

#### MovieChat-1K [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://wenhaochai.com/MovieChat/)

- MovieChat: From Dense Token to Sparse Memory in Long Video Understanding.(CVPR 2024)

</div>
</details>


<details>
<summary><strong>更早之前</strong></summary>
<div>

#### NExT-QA [![GitHub](https://img.shields.io/badge/GitHub-Project-181717?logo=github&logoColor=white)](https://doc-doc.github.io/docs/nextqa.html)

- NExT-QA: Next Phase of Question-Answering to Explaining Temporal Actions. (CVPR 2021)

</div>
</details>


## Contribution

Contributions are welcome! Please feel free to create an issue or open a pull request with your contributions.

### ✨You are welcome to provide us your work with a topic related to Video Agent & Long Video Understanding.✨

If you discover any missing work or have any suggestions, please feel free to submit a pull request. We will promptly add the missing papers to this repository.

## About

Exploring the latest papers in Video Agent and long video understanding.
