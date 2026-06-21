# 🤖 Agent Skill Evaluation and Evolution: Frameworks and Benchmarks

📄 Paper link: [arXiv](https://arxiv.org/abs/2606.11435)

The growth of agent skills has transformed how agentic systems are built, evaluated, and deployed. As skill libraries continue to scale, rigorous evaluation becomes critical to ensuring their utility, quality, and safety in real-world applications. Consequently, the field is undergoing an emerging paradigm shift from isolated skill creation to automated, evaluation-driven skill evolution. In this survey, we systematically examine the landscape of skill evolution and evaluation beyond foundational skill creation. We categorize evolution into four distinct paradigms, spanning execution feedback, trajectory distillation, compression, and reinforcement learning, showing how each element contributes to improving skill utility and reliability. We also provide an analysis of six skill-centric benchmark categories, identifying structural gaps in benchmark coverage, trade-offs, and metric richness to advance skill research. Finally, we identify open directions for building skill ecosystems that are generalizable, efficient, and verifiably safe.

This repository accompanies our survey on the lifecycle of **agent skills** for LLM agents — spanning skill **creation & usage**, **evolution**, and **evaluation**. Below, we provide an overview figure and curated reference tables for the works discussed in the survey.

<p align="center">
  <img src="https://github.com/Cassie07/AgentSkill_Survey/blob/main/Figure/Fig1_overview.png" alt="Overview of agent skill creation/usage, evolution, and evaluation" width="100%">
</p>

> We map the landscape of agent skill evolution strategies (§3) through comparative analysis and design recommendations. We offer evaluation insights (§4) through structural gaps and benchmark limitations, and open challenges (§5) for robust real-world skill deployment.

## 📋 Table of Contents
- [🛠️ Skill Creation, Usage & Evolution](#️-skill-creation-usage--evolution)
- [📊 Skill-Centric Evaluation & Benchmarks](#-skill-centric-evaluation--benchmarks)
- [🌐 General-Domain Evaluation Benchmarks](#-table-3--general-domain-evaluation-benchmarks)
- [📝 Citation](#-citation)

---

## 🛠️ Skill Creation, Usage & Evolution

This table covers the works discussed in the *skill definition & creation*, *skill usage* (retrieval, routing, management), and *skill evolution* sections.

| Work | Reference | Category | Year |
|------|-----------|----------|------|
| Anthropic Skill Creator | [Link](https://github.com/anthropics/skills) | 🤖 Creation — Automatic Creation | 2025 |
| Voyager | [Link](https://arxiv.org/abs/2305.16291) | 🤖 Creation — Automatic Creation | 2023 |
| SAGE | [Link](https://arxiv.org/abs/2512.17102) | 🎯 Creation — RL-based Creation | 2025 |
| ARISE | [Link](https://arxiv.org/abs/2603.16060) | 🎯 Creation — RL-based Creation | 2026 |
| SkillRouter | [Link](https://arxiv.org/abs/2603.22455) | 🔍 Usage — Retrieval / Routing | 2026 |
| SkillFlow | [Link](https://arxiv.org/abs/2504.06188) | 🔍 Usage — Retrieval | 2025 |
| SkillOrchestra | [Link](https://arxiv.org/abs/2602.19672) | 🔍 Usage — Routing | 2026 |
| AgentSkillOS | [Link](https://arxiv.org/abs/2603.02176) | 🗂️ Usage — Management / Orchestration | 2026 |
| SSL | [Link](https://arxiv.org/abs/2604.24026) | 🗂️ Usage — Management | 2026 |
| SkillForge | [Link](https://arxiv.org/abs/2604.08618) | 🔄 Evolution — Execution Feedback | 2026 |
| CoEvoSkills | [Link](https://arxiv.org/abs/2604.01687) | 🔄 Evolution — Execution Feedback | 2026 |
| EmbodiSkill | [Link](https://arxiv.org/abs/2605.10332) | 🔄 Evolution — Execution Feedback | 2026 |
| Skills-Coach | [Link](https://arxiv.org/abs/2604.27488) | 🔄 Evolution — Execution Feedback | 2026 |
| Ctx2Skill | [Link](https://arxiv.org/abs/2604.27660) | 🔄 Evolution — Execution Feedback | 2026 |
| AutoSkill | [Link](https://arxiv.org/abs/2603.01145) | 🔄 Evolution — Execution Feedback | 2026 |
| SkillClaw | [Link](https://arxiv.org/abs/2604.08377) | 🔄 Evolution — Execution Feedback | 2026 |
| SPARK | [Link](https://arxiv.org/abs/2605.09192) | 🧪 Evolution — Trajectory Distillation | 2026 |
| Trace2Skill | [Link](https://arxiv.org/abs/2603.25158) | 🧪 Evolution — Trajectory Distillation | 2026 |
| Memento-Skills | [Link](https://arxiv.org/abs/2603.18743) | 🧪 Evolution — Trajectory Distillation | 2026 |
| XSkill | [Link](https://arxiv.org/abs/2603.12056) | 🧪 Evolution — Trajectory Distillation | 2026 |
| SkillNet | [Link](https://arxiv.org/abs/2603.04448) | 🗜️ Evolution — Compression & Augmentation | 2026 |
| SkillX | [Link](https://arxiv.org/abs/2604.04804) | 🗜️ Evolution — Compression & Augmentation | 2026 |
| SkillFoundry | [Link](https://arxiv.org/abs/2604.03964) | 🗜️ Evolution — Compression & Augmentation | 2026 |
| SkillReducer | [Link](https://arxiv.org/abs/2603.29919) | 🗜️ Evolution — Compression & Augmentation | 2026 |
| D2Skill | [Link](https://arxiv.org/abs/2603.28716) | 🏋️ Evolution — Reinforcement Learning | 2026 |
| SkillRL | [Link](https://arxiv.org/abs/2602.08234) | 🏋️ Evolution — Reinforcement Learning | 2026 |
| Skill1 | [Link](https://arxiv.org/abs/2605.06130) | 🏋️ Evolution — Reinforcement Learning | 2026 |

---

## 📊 Skill-Centric Evaluation & Benchmarks

This table covers the benchmarks discussed in the *skill-centric evaluation and benchmarks* section.

| Work | Reference | Category | Year |
|------|-----------|----------|------|
| SkillsBench | [Link](https://arxiv.org/abs/2602.12670) | ⚡ Skill Utility | 2026 |
| SkillCraft | [Link](https://arxiv.org/abs/2603.00718) | ⚡ Skill Utility | 2026 |
| SkillLearnBench | [Link](https://arxiv.org/abs/2604.20087) | ✨ Skill Generation | 2026 |
| SkillRouter | [Link](https://arxiv.org/abs/2603.22455) | 🔍 Retrieval & Routing | 2026 |
| SRA-Bench | [Link](https://arxiv.org/abs/2604.24594) | 🔍 Retrieval & Routing | 2026 |
| AgentSkillOS Benchmark | [Link](https://arxiv.org/abs/2603.02176) | 🔍 Retrieval & Routing | 2026 |
| SkillTester | [Link](https://arxiv.org/abs/2603.28815) | 🛡️ Safety & Security | 2026 |
| SkillGuardBench | [Link](https://arxiv.org/abs/2604.25109) | 🛡️ Safety & Security | 2026 |
| SKILL-INJECT | [Link](https://arxiv.org/abs/2602.20156) | 🛡️ Safety & Security | 2026 |
| SWE-Skills-Bench | [Link](https://arxiv.org/abs/2603.15401) | 💻 Software Engineering | 2026 |
| WildClawBench | [Link](https://arxiv.org/abs/2605.10912) | 🌍 Real-world Environment | 2026 |
| SkillForge | [Link](https://arxiv.org/abs/2604.08618) | 🌍 Real-world Environment | 2026 |

---

## 🌐 Table 3 — General-Domain Evaluation Benchmarks

General-domain benchmarks that were not designed for skill evaluation but are still applicable to assessing agent skills, grouped by task category.

| Work | Reference | Category | Year |
|------|-----------|----------|------|
| ALFWorld | [Link](https://arxiv.org/abs/2010.03768) | 🕹️ Interactive Agent Environments | 2020 |
| WebShop | [Link](https://arxiv.org/abs/2207.01206) | 🕹️ Interactive Agent Environments | 2022 |
| ScienceWorld | [Link](https://arxiv.org/abs/2203.07540) | 🕹️ Interactive Agent Environments | 2022 |
| WebArena | [Link](https://arxiv.org/abs/2307.13854) | 🕹️ Interactive Agent Environments | 2024 |
| AgentBench | [Link](https://arxiv.org/abs/2308.03688) | 🕹️ Interactive Agent Environments | 2024 |
| AppWorld | [Link](https://arxiv.org/abs/2407.18901) | 🕹️ Interactive Agent Environments | 2024 |
| Terminal-Bench | [Link](https://arxiv.org/abs/2601.11868) | 💻 Code Generation & Software Engineering | 2026 |
| HumanEval | [Link](https://arxiv.org/abs/2107.03374) | 💻 Code Generation & Software Engineering | 2021 |
| MBPP | [Link](https://arxiv.org/abs/2108.07732) | 💻 Code Generation & Software Engineering | 2021 |
| EffiBench-X | [Link](https://arxiv.org/abs/2505.13004) | 💻 Code Generation & Software Engineering | 2026 |
| PIE dataset | [Link](https://arxiv.org/abs/2302.07867) | 💻 Code Generation & Software Engineering | 2023 |
| AMC / AIME | [Link](https://artofproblemsolving.com/wiki/index.php/AIME_Problems_and_Solutions) | 🔢 Mathematical Reasoning | 2026 |
| Omni-MATH | [Link](https://arxiv.org/abs/2410.07985) | 🔢 Mathematical Reasoning | 2025 |
| DeepScaleR | [Link](https://github.com/agentica-project/rllm) | 🔢 Mathematical Reasoning | 2025 |
| Natural Questions (NQ) | [Link](https://aclanthology.org/Q19-1026/) | 💡 Question Answering & Knowledge-Intensive | 2019 |
| TriviaQA | [Link](https://arxiv.org/abs/1705.03551) | 💡 Question Answering & Knowledge-Intensive | 2017 |
| PopQA | [Link](https://arxiv.org/abs/2212.10511) | 💡 Question Answering & Knowledge-Intensive | 2023 |
| HotpotQA | [Link](https://arxiv.org/abs/1809.09600) | 💡 Question Answering & Knowledge-Intensive | 2018 |
| 2WikiMultiHopQA | [Link](https://arxiv.org/abs/2011.01060) | 💡 Question Answering & Knowledge-Intensive | 2020 |
| MuSiQue | [Link](https://arxiv.org/abs/2108.00573) | 💡 Question Answering & Knowledge-Intensive | 2022 |
| Bamboogle | [Link](https://arxiv.org/abs/2210.03350) | 💡 Question Answering & Knowledge-Intensive | 2023 |
| WikiTableQuestions | [Link](https://arxiv.org/abs/1508.00305) | 💡 Question Answering & Knowledge-Intensive | 2015 |
| GAIA | [Link](https://arxiv.org/abs/2311.12983) | 💡 Question Answering & Knowledge-Intensive | 2024 |
| HLE (Humanity's Last Exam) | [Link](https://arxiv.org/abs/2501.14249) | 💡 Question Answering & Knowledge-Intensive | 2025 |
| MMLU | [Link](https://arxiv.org/abs/2009.03300) | 📚 Knowledge, Language & Instruction-Following | 2020 |
| AlpacaEval | [Link](https://github.com/tatsu-lab/alpaca_eval) | 📚 Knowledge, Language & Instruction-Following | 2023 |
| MT-Bench | [Link](https://arxiv.org/abs/2306.05685) | 📚 Knowledge, Language & Instruction-Following | 2023 |
| WildBench | [Link](https://arxiv.org/abs/2406.04770) | 📚 Knowledge, Language & Instruction-Following | 2025 |
| LoCoMo | [Link](https://arxiv.org/abs/2402.17753) | 💬 Memory & Conversational | 2024 |
| LongMemEval | [Link](https://arxiv.org/abs/2410.10813) | 💬 Memory & Conversational | 2024 |
| StuLife | [Link](https://arxiv.org/abs/2508.19005) | 💬 Memory & Conversational | 2025 |
| VisualToolBench | [Link](https://arxiv.org/abs/2510.12712) | 🖼️ Multimodal & Tool-Use | 2025 |
| TIR-Bench | [Link](https://arxiv.org/abs/2511.01833) | 🖼️ Multimodal & Tool-Use | 2025 |
| MMSearch-Plus | [Link](https://arxiv.org/abs/2508.21475) | 🖼️ Multimodal & Tool-Use | 2025 |
| MMBrowseComp | [Link](https://arxiv.org/abs/2508.13186) | 🖼️ Multimodal & Tool-Use | 2025 |
| AgentVista | [Link](https://arxiv.org/abs/2602.23166) | 🖼️ Multimodal & Tool-Use | 2026 |
| SpreadsheetBench | [Link](https://arxiv.org/abs/2406.14991) | 🖼️ Multimodal & Tool-Use | 2024 |
| BFCL-v3 | [Link](https://arxiv.org/abs/2305.15334) | 🖼️ Multimodal & Tool-Use | 2024 |
| τ²-Bench | [Link](https://arxiv.org/abs/2506.07982) | 🖼️ Multimodal & Tool-Use | 2025 |
| M³-Bench | [Link](https://arxiv.org/abs/2511.17729) | 🖼️ Multimodal & Tool-Use | 2025 |
| MineDojo / Minecraft | [Link](https://arxiv.org/abs/2206.08853) | 🤸 Embodied / Open-Ended | 2022 |

---

## 📝 Citation
```
@misc{ding2026skillsurvey,
  title         = {Agent Skill Evaluation and Evolution: Frameworks and Benchmarks},
  author        = {Ding, Kexin and Zhou, Yang and Jin, Can and Tong, Feng and
                   Zhou, Mu and Metaxas, Dimitris N.},
  year          = {2026},
  eprint        = {2606.11435},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2606.11435}
}
```
