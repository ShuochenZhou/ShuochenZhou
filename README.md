# Shuochen (Michael) Zhou

I am a Computer Science undergraduate at NYU Shanghai (B.S., expected May 2027), an undergraduate researcher with the eBRAIN Lab at NYU Abu Dhabi, and an AI Software Engineering Intern at Intel.

My research focuses on efficient and reliable continual learning in spiking neural networks. In my projects, I build tool-using agents and retrieval systems with explicit control over context, resource use, and failure recovery.

[Email](mailto:sz4544@nyu.edu)

## Research

### ENCL

**Enabling Efficient Neuromorphic Continual Learning with Local Learning Rule and Sub-Network Freezing Strategy**

Rachmad Vidya Wicaksana Putra, **Shuochen Zhou**, Hassan Raza, and Muhammad Shafique.

*Preprint, 2026. Under review at AAAI 2027.* · [Paper](https://arxiv.org/abs/2610.31927) · [Code](https://github.com/ShuochenZhou/ENCL)

ENCL combines local learning with task-specific subnetwork freezing for continual learning in spiking neural networks. I implemented random subnetwork selection with overlap-aware mask completion, retrained task-specific heads on frozen features, and aligned local supervision with each task's output classes.

### RobustNCL

**Robustifying Neuromorphic Continual Learning under Transient Faults with Lightweight Detect-and-Cure Strategy**

Rachmad Vidya Wicaksana Putra, **Shuochen Zhou**, and Muhammad Shafique.

*Preprint, 2026. Under review at ICLR 2027.* · [Paper](https://arxiv.org/abs/2610.31954) · [Code](https://github.com/ShuochenZhou/RobustNCL)

RobustNCL studies transient memory faults in neuromorphic continual learning. I implemented DRAM bit-flip simulation, analyzed fault-induced weight outliers, and developed lightweight detection and repair policies using clean weight-distribution statistics.

## Selected Projects

### AskVideo

A platform for asking questions about long videos and generating answers with timestamped evidence. I built the multimodal ingestion and retrieval pipeline, a bounded Planner–Executor–Critic workflow, and model-engineering tools for distillation, compression, and OpenVINO serving.

[Code](https://github.com/ShuochenZhou/AskVideo)

### Isolated Areas Help Hub

A pickup and delivery platform developed for the [2024 Millennium Fellowship](https://www.millenniumfellows.org/fellow/2024/shanghainyu/shuochen-zhou). I built the WeChat and web applications, transactional inventory and event processing, capacity-constrained dispatch, and an assistant that checks ownership and requires confirmation before writes.

[Code](https://github.com/ShuochenZhou/Isolated-Areas-Help-Hub) · [Live site](https://qingpu-help-hub.vercel.app)

### Ne Zha II Review Explorer

An interactive dashboard for exploring audience responses across China. I built resumable review collection, six coordinated analytical views over a precomputed data cube, and bilingual BM25 search with tools for blind relevance assessment.

[Code](https://github.com/ShuochenZhou/nezha-ii-review-explorer) · [Live dashboard](https://nezha-ii-reception-atlas.vercel.app)

### GrowAgent

A Python runtime for tool-using agents. I implemented model-provider adapters, permission-controlled tool execution, recoverable sessions, structured context folding, MCP integration, and skill evolution with replay evaluation and versioned updates.

[Code](https://github.com/ShuochenZhou/GrowAgent)
