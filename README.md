# Awesome Agent Orals [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A curated list of **agent-related papers** accepted as **Oral presentations or Award winners** at top-tier AI conferences (ICLR, ICML, NeurIPS, ACL, CVPR).

**Why Orals & Awards?**  
The number of AI papers has grown explosively — thousands are submitted to each top conference every year. Reading everything is impossible, and simple keyword search drowns you in noise. **Oral presentations and award papers** are the program committee's own answer to this problem: they represent the top ~2% of submissions that reviewers judged to have the clearest contributions, strongest results, and broadest impact. This list uses that signal as a quality filter, so you can trust that every entry here has already passed the highest bar the field sets.

**Coverage:** ICLR 2024/2025/2026 · ICML 2024/2025 · ACL 2024/2025 · NeurIPS 2024/2025 · CVPR 2024/2025 · ICCV 2025

**Legend:** 🏆 Best Paper · 🥈 Best Paper Runner-up · ⭐ Outstanding Paper · 📖 Oral

---

## Contents

- [Quick Overview](#-quick-overview)
- [ICLR 2026](#-iclr-2026-oral--6-papers)
- [ICLR 2025](#-iclr-2025-oral--22-papers)
- [ICML 2025](#-icml-2025-oral--outstanding-paper--15-papers)
- [NeurIPS 2025](#-neurips-2025-oral--best-papers--6-papers)
- [CVPR 2025](#-cvpr-2025-oral--8-papers)
- [ACL 2025](#-acl-2025--award--representative-papers)
- [ICCV 2025](#-iccv-2025-oral--2-papers)
- [ICML 2024](#-icml-2024-oral--11-papers)
- [ICLR 2024](#-iclr-2024-oral--6-papers)
- [ACL 2024](#-acl-2024-outstanding-papers--3-papers)
- [NeurIPS 2024](#-neurips-2024-oralspotlight--5-representative-papers)
- [CVPR 2024](#-cvpr-2024-oral--5-papers)
- [Topic Index](#-topic-index)
- [Contributing](#contributing)

---

## 📊 Quick Overview

| Venue | Year | Agent Papers | Focus Areas |
|-------|------|-------------|-------------|
| ICLR | 2026 | 6 (Oral confirmed) | Agent Protocol, Security Testing, Inference Speedup |
| ICLR | 2025 | 22 | Agentic Workflow, GUI Agent, Benchmarks, Embodied AI |
| ICML | 2025 | 15 + 1 ⭐ Outstanding | Multi-Agent Search, SWE, IT Automation, Curious Agent |
| NeurIPS | 2025 | 6 + 🏆 Best Paper + 🥈 Runner-up | RL Scaling, VLN, World Simulator, Web Code Benchmark |
| CVPR | 2025 | 8 | Navigation World Models, Generalist Embodied Agent, Robot |
| ACL | 2025 | 2 (SAC Highlights) + representative | AI Agent for Science, Visual Gen Eval |
| ICCV | 2025 | 2 | Robot Manipulation from Video, Embodied AI Reasoning Agent |
| ICML | 2024 | 11 | LLM Agent Frameworks, Code Agent, Multi-Agent Competition |
| ICLR | 2024 | 6 | Web Agent, MetaGPT, SWE-bench, Causal World Model, MARL |
| ACL | 2024 | 3 (award papers) | Interactive Coding Agent, Multi-Agent Safety, Econ Simulation |
| NeurIPS | 2024 | 5 (representative) | Agent Eval, Social Agent, GUI Agent, Code Agent |
| CVPR | 2024 | 5 | Embodied AI Perception, Autonomous Driving, Embodied Navigation |

---

## 📌 ICLR 2026 Oral — 6 Papers

> Papers confirmed on OpenReview; conference to be held in 2026

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Agent Data Protocol: Unifying Datasets for Diverse, Effective Fine-tuning of LLM Agents** | [OpenReview](https://openreview.net/forum?id=tG6301ORHd) | Lightweight "interlingua" schema (ADP) that standardizes 13 heterogeneous agent datasets; SFT on unified data yields ~20% avg gain across coding/browsing/tool-use benchmarks |
| 📖 **MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science** | [OpenReview](https://openreview.net/forum?id=jHDZEUgS4r) | Scalable agentic training environment for code-centric reasoning in biomedical data science |
| 📖 **AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite** | [OpenReview](https://openreview.net/forum?id=M7TNf5J26u) | Rigorous evaluation of AI agents across a full scientific research workflow |
| 📖 **Speculative Actions: A Lossless Framework for Faster AI Agents** | [arXiv](https://arxiv.org/abs/2510.04371) · [OpenReview](https://openreview.net/forum?id=P0GOk5wslg) | Speculative execution framework that significantly accelerates AI agent inference without accuracy loss |
| 📖 **RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments** | [OpenReview](https://openreview.net/forum?id=yWwrgcBoK3) | Red-teaming framework for adversarial testing of computer-use agents in realistic Web-OS environments |
| 📖 **Compositional Diffusion with Guided Search for Long-Horizon Planning** | [arXiv](https://arxiv.org/abs/2601.00126) | CDGS embeds search in diffusion denoising to compose local models for long-horizon planning; matches oracle on 7 robot manipulation tasks |

---

## 📌 ICLR 2025 Oral — 22 Papers

> 213 Orals total out of 11,672 submissions (1.82% acceptance rate)

### 🔧 Agentic Workflow & Automation

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **AFlow: Automating Agentic Workflow Generation** | [arXiv](https://arxiv.org/abs/2410.10762) · [OpenReview](https://iclr.cc/virtual/2025/oral/31731) | Frames workflow optimization as a code search problem; uses MCTS to auto-generate workflows, averaging +5.7% over SOTA |

### 🖥️ GUI / Web / Code Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents (UGround)** | [arXiv](https://arxiv.org/abs/2410.05243) · [OpenReview](https://iclr.cc/virtual/2025/oral/32124) | Pixel-level GUI agent trained without HTML/Accessibility Tree; universal visual grounding model |
| 📖 **Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows** | [arXiv](https://arxiv.org/abs/2411.07763) · [OpenReview](https://iclr.cc/virtual/2025/oral/31826) | Enterprise-grade Text-to-SQL benchmark requiring multi-step planning, tool use, and multi-dialect handling |

### 🔩 Tool Use & LLM-Tool Interaction

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **From Exploration to Mastery: Enabling LLMs to Master Tools via Self-Driven Interactions (DRAFT)** | [OpenReview](https://iclr.cc/virtual/2025/oral/31850) | Self-driven tool exploration dynamically refines tool documentation; no human annotation needed |
| 📖 **LLM-SR: Scientific Equation Discovery via Programming with Large Language Models** | [arXiv](https://arxiv.org/abs/2404.18400) · [OpenReview](https://iclr.cc/virtual/2025/oral/31782) | LLM agent iteratively writes and executes code to discover scientific equations; significantly outperforms symbolic regression |

### 📊 Agent Benchmarks

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering** | [arXiv](https://arxiv.org/abs/2410.07095) · [OpenReview](https://iclr.cc/virtual/2025/oral/31914) | 75 Kaggle competitions as ML engineering benchmark; o1+AIDE achieves bronze on 16.9% |
| 📖 **Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models** | [arXiv](https://arxiv.org/abs/2408.08926) · [OpenReview](https://iclr.cc/virtual/2025/oral/31753) | 40 professional-grade CTF challenges to evaluate autonomous LLM cybersecurity agents |
| 📖 **BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions** | [arXiv](https://arxiv.org/abs/2406.15877) · [OpenReview](https://iclr.cc/virtual/2025/oral/31821) | Code generation benchmark covering real-world library function calls and complex multi-step instructions |

### 🤝 Multi-Agent Systems

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Do as We Do, Not as You Think: the Conformity of Large Language Models** | [arXiv](https://arxiv.org/abs/2501.13381) · [OpenReview](https://iclr.cc/virtual/2025/oral/31760) | Studies conformity bias in LLM multi-agent systems; introduces reasoning-intensive benchmark BenchForm |
| 📖 **Advantage Alignment Algorithms** | [arXiv](https://arxiv.org/abs/2406.14662) · [OpenReview](https://iclr.cc/virtual/2025/oral/31851) | Algorithm family for opponent shaping that aligns advantage functions across interacting agents to reach cooperative equilibria |
| 📖 **PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation through Multi-agent Collaboration** | [arXiv](https://arxiv.org/abs/2407.00203) · [OpenReview](https://iclr.cc/virtual/2025/oral/31765) | Multi-agent pipeline for scalable generation of 1.6M pathology image-text pairs |

### 🧠 Planning, Reasoning & Self-Improvement

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **REGENT: A Retrieval-Augmented Generalist Agent That Can Act In-Context in New Environments** | [arXiv](https://arxiv.org/abs/2412.04759) · [OpenReview](https://iclr.cc/virtual/2025/oral/31863) | Retrieval-augmented in-context learning; adapts to new environments (robotics/games) without fine-tuning |
| 📖 **OptionZero: Planning with Learned Options** | [arXiv](https://arxiv.org/abs/2502.16634) · [OpenReview](https://iclr.cc/virtual/2025/oral/31926) | Integrates option networks into MuZero; discovers high-level options via self-play; +131.58% on 26 Atari games |
| 📖 **Interpreting Emergent Planning in Model-Free Reinforcement Learning** | [OpenReview](https://iclr.cc/virtual/2025/oral/31895) | First mechanistic interpretability evidence that model-free RL agents (Sokoban) form internal planning representations |
| 📖 **MaestroMotif: Skill Design from Artificial Intelligence Feedback** | [arXiv](https://arxiv.org/abs/2412.08542) · [OpenReview](https://iclr.cc/virtual/2025/oral/31770) | LLM auto-designs reward functions from natural language skill descriptions; surpasses prior methods on NetHack |
| 📖 **Training Language Models to Self-Correct via Reinforcement Learning (SCoRe)** | [arXiv](https://arxiv.org/abs/2409.12917) · [OpenReview](https://iclr.cc/virtual/2025/oral/31899) | Multi-turn online RL trains LLMs to genuinely self-correct, without external models or extra supervision |

### 🤖 Embodied Agent & Robotics

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Kinetix: Investigating the Training of General Agents through Open-Ended Physics-Based Control Tasks** | [arXiv](https://arxiv.org/abs/2410.23208) · [OpenReview](https://iclr.cc/virtual/2025/oral/31729) | Procedurally generates tens of millions of 2D physics control tasks for training generalist RL agents |
| 📖 **Instant Policy: In-Context Imitation Learning via Graph Diffusion** | [arXiv](https://arxiv.org/abs/2411.12633) · [OpenReview](https://iclr.cc/virtual/2025/oral/31789) | Robot in-context imitation learning; learns new tasks from just 1–2 demonstrations |
| 📖 **Open-World Reinforcement Learning over Long Short-Term Imagination (LS-Imagine)** | [arXiv](https://arxiv.org/abs/2410.03618) · [OpenReview](https://iclr.cc/virtual/2025/oral/31740) | Long-short-term world model; substantially outperforms SOTA on MineDojo and other open-world environments |
| 📖 **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation (Seer)** | [arXiv](https://arxiv.org/abs/2412.15109) · [OpenReview](https://iclr.cc/virtual/2025/oral/31780) | Pre-trained inverse dynamics model on large-scale robot dataset DROID |

### 🌐 Extended Scope (Vision / Test-Time Compute)

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **PhysBench: Benchmarking and Enhancing Vision-Language Models for Physical World Understanding** | [arXiv](https://arxiv.org/abs/2501.16411) · [OpenReview](https://iclr.cc/virtual/2025/oral/32125) | Physical world understanding benchmark; introduces PhysAgent fusing VLM with vision-specialized models |
| 📖 **Scaling LLM Test-Time Compute Optimally Can be More Effective than Scaling Parameters for Reasoning** | [OpenReview](https://iclr.cc/virtual/2025/oral/31924) | Optimal allocation of test-time compute enables small models to outperform models 14× larger |

---

## 📌 ICML 2025 Oral + Outstanding Paper — 15 Papers

> ~120 Orals total; CollabLLM also received the **Outstanding Paper** award

### 🏆 Outstanding Paper

| Paper | Links | TL;DR |
|-------|-------|-------|
| ⭐ **CollabLLM: From Passive Responders to Active Collaborators** | [ICML](https://icml.cc/virtual/2025/oral/47250) | Transforms LLMs from passive responders to proactive collaborators; identifies implicit user needs and initiates interaction |

### 🤖 Multi-Agent Architecture & Coordination

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Multi-agent Architecture Search via Agentic Supernet (MaAS)** | [ICML](https://icml.cc/virtual/2025/oral/47201) | Agentic Supernet automatically searches for the optimal multi-agent architecture; supports task-adaptive composition |
| 📖 **Cross-environment Cooperation Enables Zero-shot Multi-agent Coordination (CEC)** | [ICML](https://icml.cc/virtual/2025/oral/47165) | Cross-environment cooperative training enables zero-shot multi-agent coordination without shared environment priors |

### 🌍 Generalist / Embodied Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Training a Generally Curious Agent (Paprika)** | [ICML](https://icml.cc/virtual/2025/oral/47218) | Trains an intrinsically curious agent that explores diverse environments without task-specific rewards |
| 📖 **EmbodiedBench: Comprehensive Benchmarking Multi-modal LLMs for Vision-Driven Embodied Agents** | [ICML](https://icml.cc/virtual/2025/oral/47252) | Comprehensive multi-modal LLM benchmark for vision-driven embodied agents |

### 📊 Agent Benchmarks

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **What Limits Virtual Agent Application? OmniBench** | [ICML](https://icml.cc/virtual/2025/oral/47259) | Comprehensive benchmark identifying bottlenecks in virtual agent applications |
| 📖 **SWE-Lancer: Can Frontier LLMs Earn $1 Million from Real-World Freelance Software Engineering?** | [ICML](https://icml.cc/virtual/2025/oral/47172) | Evaluates frontier LLMs on real freelance software engineering tasks with $1M prize pool |
| 📖 **ITBench: Evaluating AI Agents across Diverse Real-World IT Automation Tasks** | [ICML](https://icml.cc/virtual/2025/oral/47199) | Evaluates AI agents across a wide range of real-world IT automation tasks |
| 📖 **AutoAdvExBench: Benchmarking Autonomous Exploitation of Adversarial Example Defenses** | [ICML](https://icml.cc/virtual/2025/oral/47244) | Benchmark for security agents autonomously exploiting adversarial example defenses |
| 📖 **LLM-SRBench: A New Benchmark for Scientific Equation Discovery with LLMs** | [ICML](https://icml.cc/virtual/2025/oral/47220) | New benchmark for LLM-driven scientific equation discovery |

### 🧠 Reasoning & Planning Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking** | [ICML](https://icml.cc/virtual/2025/oral/47258) | Small LLMs master math reasoning via self-evolved deep thinking (MCTS); matches o1-level performance |
| 📖 **CodeIO: Condensing Reasoning Patterns via Code Input-Output Prediction** | [ICML](https://icml.cc/virtual/2025/oral/47203) | Condenses reasoning patterns via code I/O prediction to enhance code agent capabilities |
| 📖 **STAIR: Improving Safety Alignment with Introspective Reasoning (SI-MCTS)** | [ICML](https://icml.cc/virtual/2025/oral/47210) | Introspective reasoning + MCTS improves safety alignment for reasoning agents |

### 🤝 Governance & RL Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Position: AI Agents Need Authenticated Delegation** | [ICML](https://icml.cc/virtual/2025/oral/40173) | Position paper: AI agents require authenticated delegation mechanisms to ensure legal and trustworthy action |
| 📖 **Network Sparsity Unlocks the Scaling Potential of Deep Reinforcement Learning** | [ICML](https://icml.cc/virtual/2025/oral/47193) | Network sparsity unlocks scaling potential for deep RL agents |

---

## 📌 NeurIPS 2025 Oral + Best Papers — 6 Papers

> 87 Orals total; held in San Diego, USA, December 2025

### 🏆 Award Papers

| Paper | Links | Award | TL;DR |
|-------|-------|-------|-------|
| 🏆 **1000 Layer Networks for Self-Supervised RL: Scaling Depth Can Enable New Goal-Reaching Capabilities** | [NeurIPS](https://neurips.cc/virtual/2025/oral/115732) | **Best Paper** | Demonstrates that scaling network depth (1000 layers) in self-supervised RL unlocks new goal-reaching capabilities |
| 🥈 **Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?** | [NeurIPS](https://neurips.cc/virtual/2025/oral/119945) | **Best Paper Runner-up** | Systematically examines whether RL truly enhances LLM reasoning or merely reactivates pre-trained knowledge |

### 🤖 Embodied / Navigation Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Dynam3D: Dynamic Layered 3D Tokens Empower VLM for Vision-and-Language Navigation** | [NeurIPS](https://neurips.cc/virtual/2025/oral/115716) | Dynamic layered 3D tokens enhance VLM for vision-and-language navigation (VLN) |
| 📖 **PRIMT: Preference-based RL with Multimodal Feedback and Trajectory Synthesis from Foundation Models** | [NeurIPS](https://neurips.cc/virtual/2025/oral/119904) | Preference-based RL with multimodal feedback and trajectory synthesis for robot skill learning |
| 📖 **PlayerOne: Egocentric World Simulator** | [NeurIPS](https://neurips.cc/virtual/2025/oral/118938) | Egocentric world simulator providing interactive training environments for embodied agents |

### 📊 Agent Benchmark

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **WebGen-Bench: Evaluating LLMs on Generating Interactive and Functional Websites from Scratch** | [NeurIPS](https://neurips.cc/virtual/2025/oral/121452) | Evaluates LLMs (Bolt.diy, OpenHands, Aider, etc.) on generating interactive, functional websites from scratch |

---

## 📌 CVPR 2025 Oral — 8 Papers

> ~95 Orals total; held in Seattle, USA, June 2025

### 🌐 Navigation / World Model Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Navigation World Models (NWM)** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35338) | Controllable video-generative world model for navigation agents; plans without explicit maps (LeCun group) |
| 📖 **From Multimodal LLMs to Generalist Embodied Agents: Methods and Lessons (GEA)** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35327) | Systematic study of building generalist embodied agents from MLLMs; covers Embodied AI, games, UI control, planning, RL training |

### 🦾 Embodied AI / Robotics

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **TokenHSI: Unified Synthesis of Physical Human-Scene Interactions through Task Tokenization** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35302) | Unified Transformer policy with task tokenization for multi-skill physical human-scene interaction synthesis |
| 📖 **PDFactor: Learning Tri-Perspective View Policy Diffusion Field for Multi-Task Robotic Manipulation** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35335) | Tri-perspective policy diffusion field for multi-task robotic manipulation |
| 📖 **RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35336) | Dataset and methods for spatial understanding; improves 2D/3D spatial reasoning in robot VLMs |
| 📖 **EgoLM: Multi-Modal Language Model of Egocentric Motions** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35299) | Multi-modal language model of egocentric motions for first-person agents |

### 🚗 Autonomous Driving Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Closed-Loop Supervised Fine-Tuning of Tokenized Traffic Models** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35307) | Closed-loop SFT of tokenized traffic models with CAT-K rollouts; top-ranked on Waymo Sim Agent Challenge |

### 🏆 RL + LLM/VLM Reward

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **GROVE: A Generalized Reward for Learning Open-Vocabulary Physical Skill** | [CVPR](https://cvpr.thecvf.com/virtual/2025/oral/35337) | LLM generates constraints, VLM evaluates rewards for open-vocabulary physical skill learning; +22.2% naturalness |

---

## 📌 ACL 2025 — Award & Representative Papers

> Held in Vienna, Austria, July 2025

### 🏅 SAC Highlights (Area Chair Award — Agent-Related)

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Completing A Systematic Review in Hours instead of Months with Interactive AI Agents** | [arXiv](https://arxiv.org/abs/2504.14822) | AI agent pipeline automating systematic review (screening, extraction, synthesis); reduces months-long human effort to hours |
| 📖 **Evaluation Agent: Efficient and Promptable Evaluation Framework for Visual Generative Models** | [arXiv](https://arxiv.org/abs/2412.09645) | Agent-based evaluation framework that dynamically adapts evaluation strategies and metrics for visual generative models based on user prompts |

### 📖 Representative Agent Papers (Main Conference)

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System** | [ACL Anthology](https://aclanthology.org/2025.acl-long.103) | Tool-integrated LLM agent system that automates real-world repository-level compilation |

---

## 📌 ICCV 2025 Oral — 2 Papers

> 64 Orals total; held in Honolulu, Hawaii, USA, October 2025  
> *Note: ICCV is a biennial conference held only on odd years (2021 · 2023 · **2025** · 2027…). ICCV 2024 does not exist.*

### 🤖 Robot Manipulation Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Moto: Latent Motion Token as the Bridging Language for Learning Robot Manipulation from Videos** | [arXiv](https://arxiv.org/abs/2412.04445) · [ICCV](https://iccv.thecvf.com/virtual/2025/oral/2928) | Converts video into latent Motion Token sequences; pre-trains Moto-GPT on large video corpora then co-finetunes for real robot control — bridges cheap video supervision with hardware-agnostic robot action |

### 🧠 Embodied AI Reasoning Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Online Reasoning Video Segmentation with Just-in-Time Digital Twins** | [arXiv](https://arxiv.org/abs/2503.21056) · [ICCV](https://iccv.thecvf.com/virtual/2025/oral/2940) | Agent framework that decouples perception and reasoning for online video segmentation; LLM planner dynamically constructs a "just-in-time" digital twin scene representation, enabling embodied AI to handle complex spatial/temporal queries without LLM fine-tuning |

---

## 📌 ICML 2024 Oral — 11 Papers

> 144 Orals total

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **GPTSwarm: Language Agents as Optimizable Graphs** | [ICML](https://icml.cc/virtual/2024/oral/35447) | Represents LLM agents as optimizable computation graphs; auto-optimizes node prompts and edge connectivity |
| 📖 **SceneCraft: An LLM Agent for Synthesizing 3D Scenes as Blender Code** | [ICML](https://icml.cc/virtual/2024/oral/35488) | LLM agent converts text descriptions to executable Blender Python scripts with scene graph planning |
| 📖 **CompeteAI: Understanding the Competition Dynamics of Large Language Model-based Agents** | [ICML](https://icml.cc/virtual/2024/oral/35443) | Studies competition dynamics between LLM agents; virtual town simulation with restaurant/customer agents |
| 📖 **Chain of Code: Reasoning with a Language Model-Augmented Code Emulator** | [ICML](https://icml.cc/virtual/2024/oral/35444) | CoC framework: LM improves reasoning by writing code and using an LMulator to simulate execution; +12% on BIG-Bench Hard |
| 📖 **Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model (EoH)** | [ICML](https://icml.cc/virtual/2024/oral/35555) | LLM + evolutionary computation for automatic heuristic design; surpasses FunSearch on combinatorial optimization |
| 📖 **Learning to Model the World With Language (Dynalang)** | [ICML](https://icml.cc/virtual/2024/oral/35565) | Agent builds a multimodal world model from diverse language signals for game and indoor navigation |
| 📖 **PRISE: LLM-Style Sequence Compression for Learning Temporal Action Abstractions in Control** | [ICML](https://icml.cc/virtual/2024/oral/35464) | Frames action abstraction as sequence compression (BPE-style) to learn high-level robot manipulation skills |
| 📖 **Genie: Generative Interactive Environments** | [ICML](https://icml.cc/virtual/2024/oral/35508) | First 11B generative interactive environment trained unsupervised from unlabeled Internet videos; enables generalist agent training |
| 📖 **Offline Actor-Critic Reinforcement Learning Scales to Large Models** | [ICML](https://icml.cc/virtual/2024/oral/35451) | Offline Actor-Critic RL scales to Transformer-based large models; surpasses behavioral cloning on 132 continuous control tasks |
| 📖 **AI Control: Improving Safety Despite Intentional Subversion** | [ICML](https://icml.cc/virtual/2024/oral/35539) | AI control protocol that prevents malicious code submission even with a powerful but untrustworthy LLM (GPT-4) |
| 📖 **Debating with More Persuasive LLMs Leads to More Truthful Answers** | [ICML](https://icml.cc/virtual/2024/oral/35483) | LLM debate mechanism: two expert LLMs debate while a weak judge determines truth; accuracy 48% → 76% |

---

## 📌 ICLR 2024 Oral — 6 Papers

> 86 Orals total out of ~7,262 submissions

### 🌐 Web / Code Agent

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis** | [arXiv](https://arxiv.org/abs/2307.12856) · [ICLR](https://iclr.cc/virtual/2024/oral/19785) | LLM-driven web agent (Flan-U-PaLM + HTML-T5) that decomposes instructions, summarizes long HTML, and executes via Python programs; 50%+ improvement on real websites, SoTA on Mind2Web |
| 📖 **SWE-bench: Can Language Models Resolve Real-world Github Issues?** | [arXiv](https://arxiv.org/abs/2310.06770) · [ICLR](https://iclr.cc/virtual/2024/oral/19757) | 2,294 software engineering problems from real GitHub issues across 12 Python repos; tests multi-file, multi-function code editing; the de facto benchmark for coding agents |

### 🤝 Multi-Agent Systems

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** | [arXiv](https://arxiv.org/abs/2308.00352) · [ICLR](https://iclr.cc/virtual/2024/oral/19756) | Encodes SOPs into LLM multi-agent workflows with role-assignment (PM/architect/engineer); reduces cascading hallucinations; SoTA on collaborative software engineering benchmarks |
| 📖 **Efficient Episodic Memory Utilization of Cooperative Multi-Agent Reinforcement Learning** | [ICLR](https://iclr.cc/virtual/2024/oral/19766) | EMU: semantically coherent episodic memory recall + episodic incentive reward for MARL; SoTA on StarCraft II and Google Research Football |

### 🧠 Agent Theory & RL

| Paper | Links | TL;DR |
|-------|-------|-------|
| 📖 **Robust agents learn causal world models** | [ICLR](https://iclr.cc/virtual/2024/oral/19724) | Proves any agent satisfying a regret bound across large distribution shifts must learn an approximate causal world model; theoretical foundation for robust generalization |
| 📖 **METRA: Scalable Unsupervised RL with Metric-Aware Abstraction** | [ICLR](https://iclr.cc/virtual/2024/oral/19745) | Metric-aware latent abstraction for unsupervised RL skill discovery; first to discover diverse locomotion behaviors in pixel-based Humanoid/Quadruped |

---

## 📌 ACL 2024 Outstanding Papers — 3 Papers

> ACL does not have oral presentations; Outstanding / Best Papers are the equivalent top-tier distinction

| Paper | Links | Award | TL;DR |
|-------|-------|-------|-------|
| 🏆 **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** | [ACL Anthology](https://aclanthology.org/2024.acl-long.0/) | Best Resource Paper | Controllable world of apps and virtual people for benchmarking interactive coding agents with multi-step code execution |
| 🏆 **PsySafe: A Comprehensive Framework for Psychological-based Attack, Defense, and Evaluation of Multi-agent System Safety** | ACL 2024 | Outstanding Paper | Examines multi-agent system safety from a psychological perspective; covers attack, defense, and evaluation |
| 🏆 **EconAgent: Large Language Model-Empowered Agents for Simulating Macroeconomic Activities** | ACL 2024 | Outstanding Paper | LLM-driven macroeconomic simulation agents modeling consumer, enterprise, and market behaviors |

---

## 📌 NeurIPS 2024 Oral/Spotlight — 5 Representative Papers

| Paper | arXiv | TL;DR |
|-------|-------|-------|
| 📖 **AgentBench: Evaluating LLMs as Agents** | [2308.03688](https://arxiv.org/abs/2308.03688) | Systematic evaluation of LLMs as agents across 8 real-world interactive environments |
| 📖 **SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents** | [2310.11667](https://arxiv.org/abs/2310.11667) | Interactive evaluation of social intelligence in language agents via dynamic conversation simulation |
| 📖 **CogAgent: A Visual Language Model for GUI Agents** | [2312.08914](https://arxiv.org/abs/2312.08914) | 18B VLM specifically optimized for GUI control and agent interactions |
| 📖 **SWE-bench: Can Language Models Resolve Real-World GitHub Issues?** | [2310.06770](https://arxiv.org/abs/2310.06770) | Benchmark for code agents resolving real GitHub issues; the de facto standard for code agent evaluation |
| 📖 **OpenAgents: An Open Platform for Language Agents in the Wild** | [2310.10634](https://arxiv.org/abs/2310.10634) | Open language agent platform with three agents: data analysis, plugin use, and web browsing |

---

## 📌 CVPR 2024 Oral — 5 Papers

| Paper | arXiv | TL;DR |
|-------|-------|-------|
| 📖 **EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI** | [2312.16170](https://arxiv.org/abs/2312.16170) | Holistic 3D multi-modal perception suite for embodied AI; covers detection, localization, and QA |
| 📖 **Generalized Predictive Model for Autonomous Driving (GenAD)** | [2403.09630](https://arxiv.org/abs/2403.09630) | Unified driving agent model for motion prediction and scene understanding |
| 📖 **Towards Learning a Generalist Model for Embodied Navigation** | [2312.02010](https://arxiv.org/abs/2312.02010) | Generalist model for embodied navigation unifying diverse navigation tasks and instruction types |
| 📖 **GROOT: Learning to Follow Instructions by Watching Gameplay Videos** | [2310.08235](https://arxiv.org/abs/2310.08235) | Learns instruction following from gameplay videos for agents in open-world environments like Minecraft |
| 📖 **HiMap: Learning Topology-Aware Representations for Aerial View Point-of-Interest Mapping** | CVPR 2024 Oral | Topology-aware representations for aerial-view POI mapping in navigation agents |

---

## 🔑 Topic Index

### Agentic Workflow / Automation
- AFlow (ICLR 2025) `2410.10762`
- GPTSwarm (ICML 2024)
- EoH (ICML 2024)
- MaAS (ICML 2025)
- Speculative Actions (ICLR 2026)
- Completing Systematic Review Agents (ACL 2025) `2504.14822`

### GUI / Web / Computer-Use Agent
- UGround (ICLR 2025) `2410.05243`
- Spider 2.0 (ICLR 2025) `2411.07763`
- WebAgent (ICLR 2024) `2307.12856`
- CogAgent (NeurIPS 2024) `2312.08914`
- RedTeamCUA (ICLR 2026)

### Code / Software Engineering Agent
- BigCodeBench (ICLR 2025) `2406.15877`
- MLE-bench (ICLR 2025) `2410.07095`
- AppWorld 🏆 (ACL 2024)
- SWE-bench (ICLR 2024) `2310.06770`
- SWE-Lancer (ICML 2025)
- Chain of Code (ICML 2024)
- CompileAgent (ACL 2025)
- WebGen-Bench (NeurIPS 2025)
- SceneCraft (ICML 2024)

### Multi-Agent Systems
- MetaGPT (ICLR 2024) `2308.00352`
- Efficient Episodic Memory MARL (ICLR 2024)
- CompeteAI (ICML 2024)
- Advantage Alignment (ICLR 2025) `2406.14662`
- PsySafe 🏆 (ACL 2024)
- CEC (ICML 2025)
- CollabLLM ⭐ (ICML 2025 Outstanding)
- Agent Data Protocol (ICLR 2026)

### Embodied Agent / Robotics
- Kinetix (ICLR 2025) `2410.23208`
- Instant Policy (ICLR 2025) `2411.12633`
- Seer (ICLR 2025) `2412.15109`
- LS-Imagine (ICLR 2025) `2410.03618`
- EmbodiedScan (CVPR 2024) `2312.16170`
- GROOT (CVPR 2024) `2310.08235`
- EmbodiedBench (ICML 2025)
- NWM (CVPR 2025)
- GEA (CVPR 2025)
- TokenHSI (CVPR 2025)
- PDFactor (CVPR 2025)
- RoboSpatial (CVPR 2025)
- PRIMT (NeurIPS 2025)
- Dynam3D (NeurIPS 2025)
- Moto (ICCV 2025) `2412.04445`
- Online Reasoning Video Segmentation (ICCV 2025) `2503.21056`
- MedAgentGym (ICLR 2026)

### RL Agent / Reasoning Agent
- Robust agents learn causal world models (ICLR 2024)
- METRA (ICLR 2024)
- PRISE (ICML 2024)
- Offline AC RL Scales (ICML 2024)
- 1000 Layer RL Networks 🏆 (NeurIPS 2025 Best Paper)
- Does RL Incentivize Reasoning 🥈 (NeurIPS 2025 Runner-up)
- Network Sparsity + Deep RL (ICML 2025)
- rStar-Math (ICML 2025)
- Compositional Diffusion Planning (ICLR 2026)

### Agent Safety / Alignment / Governance
- AI Control (ICML 2024)
- Cybench (ICLR 2025) `2408.08926`
- SCoRe (ICLR 2025) `2409.12917`
- AutoAdvExBench (ICML 2025)
- STAIR (ICML 2025)
- RedTeamCUA (ICLR 2026)
- Authenticated Delegation (ICML 2025 Position)

### Agent Benchmarks (General)
- AgentBench (NeurIPS 2024) `2308.03688`
- SOTOPIA (NeurIPS 2024) `2310.11667`
- REGENT (ICLR 2025) `2412.04759`
- PhysBench (ICLR 2025) `2501.16411`
- EconAgent 🏆 (ACL 2024)
- OmniBench (ICML 2025)
- ITBench (ICML 2025)
- LLM-SRBench (ICML 2025)
- AstaBench (ICLR 2026)
- Evaluation Agent (ACL 2025) `2412.09645`

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

**Criteria for inclusion:**
1. The paper must be accepted as an **Oral**, **Spotlight** (for NeurIPS), or **Award paper** (Best Paper / Outstanding Paper / Best Resource Paper) at a CCF-A conference (ICLR, ICML, NeurIPS, ACL, CVPR).
2. The paper must be clearly related to **AI agents**: LLM/VLM agents, multi-agent systems, embodied agents, agentic workflows, tool use, agent safety, or agent benchmarks.

---

*Sources: ICLR 2024/2025/2026 virtual site & OpenReview · ICML 2024/2025 virtual site & awards_detail · ACL Anthology 2024/2025 · NeurIPS 2024/2025 virtual site & awards_detail · CVPR 2024/2025 virtual site · ICCV 2025 virtual site (thecvf.com)*  
*Last updated: March 2026*
