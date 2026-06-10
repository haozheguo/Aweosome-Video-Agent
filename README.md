<div align="center">

<h1>🎬 Awesome-Video-Agent</h1>

<p>🍦Exploring the latest papers in Video Agent & long video understanding.🍦</p>

<p><img width="768px" alt="image" src="assets/logo.png"></p>

<img src='https://awesome.re/badge.svg' alt='Survey'>
<img src='https://img.shields.io/badge/Related Work-10+ Papers-blue' alt='MorePapers'>
<img src='https://img.shields.io/badge/Update 🔥-2026.06.10-red' alt='MorePapers'>

</div>

---

# 1️⃣ Awesome Papers

> ⚠️ 这里整理的所有论文均开源代码，并且已排除代码仓库为空的情况。
> 
> ❗️ 总结部分只针对论文方法总结，不介绍论文其他方面（比如论文提出benchmark构造思路）

<details open>
<summary><strong>2026</strong></summary>
<div>
<table width="100%">
  <colgroup>
    <col width="54%">
    <col width="46%">
  </colgroup>
  <thead>
    <tr>
      <th>📑 论文</th>
      <th>✨ 总结</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tempo：Small Vision-Language Models are Smart Compressors for Long Video Understanding<br><a href="https://arxiv.org/pdf/2604.08120"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2604.08120-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://feielysia.github.io/tempo-page"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2026/2604.08120_Tempo.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 Meta AI、KAUST</td>
      <td><strong>是否Training-Free</strong>：❌<br>论文提出Tempo，用小型视觉语言模型作为局部压缩器生成与查询对齐的视频记忆，再由全局大语言模型完成理解与生成。进一步提出ATA策略，利用零样本相关性先验和语义前置特性，在严格预算下动态分配token，兼顾关键细节保留与全局时间连续性。<br>📊 Eval Benchmark：LongVideoBench、MLVU、Video-MME 和 LVBench（Long）</td>
    </tr>
    <tr>
      <td>Agentic Very Long Video Understanding<br><a href="https://arxiv.org/pdf/2601.18157"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2601.18157-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://facebookresearch.github.io/egagent"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2026/2601.18157_EGAgent.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 Meta、UW-Madison</td>
      <td><strong>是否Training-Free</strong>：✅<br>针对现有方法难以支持跨天的组合式、多跳超长视频推理问题，论文提出EGAgent，通过带时间标注的实体图结合视觉、音频检索与规划智能体，实现超长视频的跨模态、多跳推理。<br>📊 Eval Benchmark：EgoLifeQA、Video-MME（Long）</td>
    </tr>
  </tbody>
</table>


</div>
</details>

<details open>
<summary><strong>2025</strong></summary>
<div>
<table width="100%">
  <colgroup>
    <col width="54%">
    <col width="46%">
  </colgroup>
  <thead>
    <tr>
      <th>📑 论文</th>
      <th>✨ 总结</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>LongVideoAgent: Multi-Agent Reasoning with Long Videos<br><a href="https://arxiv.org/pdf/2512.20618"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2512.20618-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://longvideoagent.github.io/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2512.20618_LongVideoAgent.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 HKUST、Monash</td>
      <td><strong>是否Training-Free</strong>：❌（包括GRPO训练过程）<br>LongVideoAgent通过主控智能体协调定位与视觉子智能体，在多轮迭代中定位相关片段并按需读取视觉细节，在累积证据后完成长视频问答。<br>📊 Eval Benchmark：LongTVQA、LongTVQA+（均为论文提出）</td>
    </tr>
    <tr>
      <td>A Benchmark and Agentic Framework for Omni-Modal Reasoning and Tool Use in Long Videos<br><a href="https://arxiv.org/pdf/2512.16978"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2512.16978-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://github.com/mbzuai-oryx/longshot"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2512.16978_LongShOT.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 MBZUAI、AUB</td>
      <td><strong>是否Training-Free</strong>：✅<br>论文提出LongShOT，通过训练模块化智能体，将长视频理解转化为跨视觉、语音和音频的检索、工具调用与迭代优化过程，实现全模态长视频推理。<br>📊 Eval Benchmark：LongShOTBench（论文提出）</td>
    </tr>
    <tr>
      <td>Active Video Perception: Iterative Evidence Seeking for Agentic Long Video Understanding<br><a href="https://arxiv.org/pdf/2512.05774"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2512.05774-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://activevideoperception.github.io/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2512.05774_Active_Video_Perception.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 Salesforce、UNC</td>
      <td><strong>是否Training-Free</strong>：✅<br>Active Video Perception将长视频视为可交互环境，通过“规划—观察—反思”迭代主动搜寻与问题相关的时间戳证据，从而高效完成长视频理解。<br>📊 Eval Benchmark：MINERVA、LVBench、MLVU、Video-MME、LongVideoBench</td>
    </tr>
    <tr>
      <td><strong>🏅CVPR 2026</strong><br>LongVT: Incentivizing "Thinking with Long Videos" via Native Tool Calling<br><a href="https://arxiv.org/pdf/2511.20785"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2511.20785-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://evolvinglmms-lab.github.io/LongVT/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2511.20785_LongVT.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 MiroMind、NTU</td>
      <td><strong>是否Training-Free</strong>：❌，包含SFT、RL、RFT等训练方式（n*NVIDIA A800-SXM4-80GB）<br>LongVT 引入原生视频工具调用，并采用分阶段训练流程（包含SFT与RL阶段）使模型能够直接“基于长视频进行思考”。<br>📊 Eval Benchmark：VideoMME , VideoMMMU, LVBench, and our self-curated VideoSIAH-Eval</td>
    </tr>
    <tr>
      <td>Video-CoM: Interactive Video Reasoning via Chain of Manipulations<br><a href="https://arxiv.org/pdf/2511.23477"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2511.23477-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://github.com/mbzuai-oryx/Video-CoM"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2511.23477_Video_CoM.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 MBZUAI、UC Merced</td>
      <td><strong>是否Training-Free</strong>：❌，包含SFT、GRPO等训练过程<br>Video-CoM 将长视频推理建模为“操作链”的交互过程，模型通过迭代操作不断细化时空证据。论文还引入配套训练数据与基于强化学习的优化策略，以增强分步骤推理质量。<br>📊 Eval Benchmark：Video-MMMU、MMVU-Val、Minerva、ScienceVideoBench、VideoMathQA、TempoCompass、Video-MME、MLVU、Video-CoM-Bench（论文提出）</td>
    </tr>
    <tr>
      <td><strong>🏅NeurIPS 2025 Spotlight</strong><br>Vgent: Graph-based Retrieval-Reasoning-Augmented Generation For Long Video Understanding<br><a href="https://arxiv.org/pdf/2510.14032"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2510.14032-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://xiaoqian-shen.github.io/Vgent/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2510.14032_Vgent.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 KAUST、Meta AI</td>
      <td><strong>是否Training-Free</strong>：✅<br>Vgent 提出一种面向长视频理解的图结构检索与推理增强生成框架。该方法将视频片段组织为结构化图，通过“图检索+结构化中间推理”过滤噪声、聚合证据，从而提升长视频问答效果。<br>📊 Eval Benchmark：Video-MME、MLVU、LongVideoBench (LVB)</td>
    </tr>
    <tr>
      <td><strong>🏅NeurIPS 2025</strong><br>VideoLucy: Deep Memory Backtracking for Long Video Understanding<br><a href="https://arxiv.org/pdf/2510.12422"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2510.12422-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://videolucy.github.io/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2510.12422_VideoLucy.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 HUST、NUS</td>
      <td><strong>是否Training-Free</strong>：✅<br>VideoLucy通过由粗到细的分层记忆和智能体迭代回溯机制，逐步挖掘与问题相关的深层视频记忆，从而兼顾长时序理解与关键细节保留。<br>📊 Eval Benchmark：MLVU、Video-MME、LVBench、EgoMem（论文提出）</td>
    </tr>
    <tr>
      <td><strong>🏅NeurIPS 2025</strong><br>Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding<br><a href="https://arxiv.org/pdf/2505.18079"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.18079-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://github.com/microsoft/DeepVideoDiscovery"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2025/2505.18079_Deep_Video_Discovery.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 MSRA、USTC</td>
      <td><strong>是否Training-Free</strong>：✅<br>Deep Video Discovery先将长视频构造成多粒度可搜索数据库，再由LLM自主调用全局浏览、片段搜索和帧级检查工具，迭代检索证据并完成长视频问答。<br>📊 Eval Benchmark：LVBench、LongVideoBench、Video MME、EgoSchema</td>
    </tr>
  </tbody>
</table>

</div>
</details>

<details open>
<summary><strong>2024</strong></summary>
<div>
<table width="100%">
  <colgroup>
    <col width="54%">
    <col width="46%">
  </colgroup>
  <thead>
    <tr>
      <th>📑 论文</th>
      <th>✨ 总结</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>🏅CVPR 2025</strong><br>DrVideo: Document Retrieval Based Long Video Understanding<br><a href="https://arxiv.org/pdf/2406.12846"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.12846-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://github.com/Upper9527/DrVideo"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Code-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2024/2406.12846_DrVideo.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 HNU、Monash</td>
      <td><strong>是否Training-Free</strong>：✅<br>DrVideo将长视频转为可检索的长文档，通过关键帧检索、文档增强和多阶段Agent循环逐步补全缺失信息，实现零样本长视频理解。<br>📊 Eval Benchmark：EgoSchema、MovieChat-1K、Video-MME</td>
    </tr>
    <tr>
      <td><strong>🏅CVPR 2025</strong><br>VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos<br><a href="https://arxiv.org/pdf/2405.19209"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2405.19209-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://videotree2024.github.io/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2024/2405.19209_VideoTree.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 UNC</td>
      <td><strong>是否Training-Free</strong>：✅<br>VideoTree 提出一种 Training-free 的自适应树结构视频表示方法。该方法根据查询进行关键帧选择，并执行由粗到细的视频树结构表示扩展，从而支持LLM高效完成长视频推理。<br>📊 Eval Benchmark：EgoSchema、NExT-QA、Video-MME</td>
    </tr>
    <tr>
      <td><strong>🏅ECCV 2024</strong><br>VideoAgent: Long-form Video Understanding with Large Language Model as Agent<br><a href="https://arxiv.org/pdf/2403.10517"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.10517-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://wxh1996.github.io/VideoAgent-Website/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2024/2403.10517_VideoAgent_LongForm.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 Stanford</td>
      <td><strong>是否Training-Free</strong>：✅<br>（首个Video Agent）VideoAgent 将长视频理解建模为由 LLM 控制的智能体决策过程。Agent通过迭代规划动作、检索信息帧并针对观察结果推理，实现更高效的视频问答。<br>📊 Eval Benchmark：EgoSchema、NExT-QA</td>
    </tr>
    <tr>
      <td><strong>🏅ECCV 2024</strong><br>VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding<br><a href="https://arxiv.org/abs/2403.11481"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.11481-b31b1b?logo=arxiv&amp;logoColor=white"></a> <a href="https://videoagent.github.io/"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Project-181717?logo=github&amp;logoColor=white"></a> <a href="paper_abstract/2024/2403.11481_VideoAgent_MemoryAugmented.md"><img alt="Abstract" src="https://img.shields.io/badge/Abstract-%E4%B8%AD%E6%96%87%E7%BF%BB%E8%AF%91-0ea5e9?logo=bookstack&amp;logoColor=white"></a><br>🏫 BIGAI、PKU</td>
      <td><strong>是否Training-Free</strong>：✅<br>VideoAgent将长视频转化为可检索的时序记忆（物体随时间的变化）与物体记忆（物体自身状态的变化），并由LLM以零样本工具调用方式逐步查询记忆，实现长视频问答与时刻定位。<br>📊 Eval Benchmark：EgoSchema、WorldQA、NExT-QA</td>
    </tr>
  </tbody>
</table>



</div>
</details>

---

# 2️⃣ Awesome Benchmarks

<details>
<summary><strong>2026</strong></summary>
<div>

<table width="100%">
  <colgroup>
    <col width="24%">
    <col width="18%">
    <col width="42%">
    <col width="16%">
  </colgroup>
  <thead>
    <tr>
      <th>📊Benchmark</th>
      <th>🐱 GitHub</th>
      <th>✨ 简介</th>
      <th>🏅 出处</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VideoSIAH-Eval</td>
      <td><a href="https://huggingface.co/datasets/EvolvingLMMs-Lab/VideoSIAH-Eval">Project</a></td>
      <td>LongVT paper curated benchmark for long-video temporal reasoning and tool-calling evaluation.</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

</div>
</details>

<details open>
<summary><strong>2025</strong></summary>
<div>

<table width="100%">
  <colgroup>
    <col width="24%">
    <col width="18%">
    <col width="42%">
    <col width="16%">
  </colgroup>
  <thead>
    <tr>
      <th>📊Benchmark</th>
      <th>🐱 GitHub</th>
      <th>✨ 简介</th>
      <th>🏅 出处</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VideoMMMU</td>
      <td><a href="https://github.com/gregor-ge/CinePile/tree/main/videommmu">Project</a></td>
      <td>A benchmark for expert-level multimodal understanding and reasoning on videos.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>MMVU / MMVU-Val</td>
      <td><a href="https://mmvu-benchmark.github.io/">Project</a></td>
      <td>A benchmark for evaluating multimodal video understanding and reasoning.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>MINERVA</td>
      <td><a href="https://github.com/google-deepmind/neptune?tab=readme-ov-file#minerva">Code</a></td>
      <td>A long-video understanding benchmark in the Neptune suite for memory and retrieval intensive reasoning.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>MLVU</td>
      <td><a href="https://github.com/JUNJIE99/MLVU">Code</a></td>
      <td>A Comprehensive Benchmark for Multi-Task Long Video Understanding.</td>
      <td>CVPR 2025</td>
    </tr>
    <tr>
      <td>LVBench</td>
      <td><a href="https://lvbench.github.io/">Project</a></td>
      <td>An Extreme Long Video Understanding Benchmark.</td>
      <td>ICCV 2025</td>
    </tr>
    <tr>
      <td>Video-MME</td>
      <td><a href="https://video-mme.github.io/">Project</a></td>
      <td>The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Video-CoM-Bench</td>
      <td><a href="https://github.com/mbzuai-oryx/Video-CoM">Code</a></td>
      <td>A benchmark introduced by Video-CoM for interactive video reasoning with chain-of-manipulations.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>ScienceVideoBench</td>
      <td><a href="https://github.com/mbzuai-oryx/Video-CoM">Code</a></td>
      <td>A science-oriented video reasoning benchmark used in Video-CoM evaluation.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>VideoMathQA</td>
      <td><a href="https://github.com/mbzuai-oryx/Video-CoM">Code</a></td>
      <td>A video mathematical reasoning benchmark used in Video-CoM evaluation.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>EgoMem</td>
      <td><a href="https://videolucy.github.io/">Project</a></td>
      <td>A benchmark introduced by VideoLucy for ultra-long egocentric video memory understanding.</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

</div>
</details>

<details open>
<summary><strong>2024</strong></summary>
<div>

<table width="100%">
  <colgroup>
    <col width="24%">
    <col width="18%">
    <col width="42%">
    <col width="16%">
  </colgroup>
  <thead>
    <tr>
      <th>📊Benchmark</th>
      <th>🐱 GitHub</th>
      <th>✨ 简介</th>
      <th>🏅 出处</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EgoSchema</td>
      <td><a href="https://egoschema.github.io/">Project</a></td>
      <td>A diagnostic benchmark for very long-form video language understanding.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>WorldQA</td>
      <td><a href="https://zhangyuanhan-ai.github.io/WorldQA/">Project</a></td>
      <td>Multimodal World Knowledge in Videos through Long-Chain Reasoning.</td>
      <td>-</td>
    </tr>
    <tr>
      <td>LongVideoBench</td>
      <td><a href="https://longvideobench.github.io/">Project</a></td>
      <td>A Benchmark for Long-context Interleaved Video-Language Understanding.</td>
      <td>NeurIPS 2024</td>
    </tr>
    <tr>
      <td>MovieChat-1K</td>
      <td><a href="https://wenhaochai.com/MovieChat/">Project</a></td>
      <td>From Dense Token to Sparse Memory in Long Video Understanding.</td>
      <td>CVPR 2024</td>
    </tr>
  </tbody>
</table>

</div>
</details>

<details>
<summary><strong>更早之前</strong></summary>
<div>

<table width="100%">
  <colgroup>
    <col width="24%">
    <col width="18%">
    <col width="42%">
    <col width="16%">
  </colgroup>
  <thead>
    <tr>
      <th>📊Benchmark</th>
      <th>🐱 GitHub</th>
      <th>✨ 简介</th>
      <th>🏅 出处</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>NExT-QA</td>
      <td><a href="https://doc-doc.github.io/docs/nextqa.html">Project</a></td>
      <td>Next Phase of Question-Answering to Explaining Temporal Actions.</td>
      <td>CVPR 2021</td>
    </tr>
  </tbody>
</table>

</div>
</details>

## Contribution

Contributions are welcome! Please feel free to create an issue or open a pull request with your contributions.

### ✨You are welcome to provide us your work with a topic related to Video Agent & Long Video Understanding.✨

If you discover any missing work or have any suggestions, please feel free to submit a pull request to  `hzguo [at] tju.edu.cn` . we will promptly add the missing papers to this repository.

## About

Exploring the latest papers in Video Agent and long video understanding.
