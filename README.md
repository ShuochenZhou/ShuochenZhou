# Shuochen (Michael) Zhou

I am a Computer Science undergraduate at NYU Shanghai (B.S., expected May 2027), an undergraduate researcher with the eBRAIN Lab at NYU Abu Dhabi, and an AI Solutions Engineering Intern at Intel.

My research focuses on efficient and reliable continual learning in spiking neural networks. In my projects, I build tool-using agents and retrieval systems with explicit control over context, resource use, and failure recovery.

[Email](mailto:sz4544@nyu.edu)

## Research

### ENCL

**Enabling Efficient Neuromorphic Continual Learning with Local Learning Rule and Sub-Network Freezing Strategy**

Rachmad Vidya Wicaksana Putra, **Shuochen Zhou**, Hassan Raza, and Muhammad Shafique.

*Preprint, 2026. Under review at AAAI 2027.* · [Paper](https://arxiv.org/abs/2610.31927) · [Code](https://github.com/ShuochenZhou/ENCL)

ENCL combines local learning with task-specific subnetwork freezing for efficient continual learning in spiking neural networks. I aligned local supervision with task-specific output classes, retrained task heads on frozen backbone features, and replaced multi-candidate subnetwork selection with one random subnetwork per task and overlap-aware mask completion using unused neurons.

### RobustNCL

**Robustifying Neuromorphic Continual Learning under Transient Faults with Lightweight Detect-and-Cure Strategy**

Rachmad Vidya Wicaksana Putra, **Shuochen Zhou**, and Muhammad Shafique.

*Preprint, 2026. Under review at ICLR 2027.* · [Paper](https://arxiv.org/abs/2610.31954) · [Code](https://github.com/ShuochenZhou/RobustNCL)

RobustNCL protects neuromorphic continual learning against transient memory faults. I simulated DRAM bit flips after each task, traced accuracy collapse to outlying weights, and developed repairs for ENCL and memory replay using clean per-layer min/max/mode statistics, including protection of later tasks' initialization.

## Selected Projects

### AskVideo

A full-stack platform where users submit a video file or link and request answers, summaries, study guides, critiques, or voiceover scripts with timestamp citations. I built a bounded Planner–Executor–Critic workflow with conversation memory, plus a Qwen3-1.7B pipeline for distillation from DeepSeek-V3.2, full/LoRA/QLoRA fine-tuning, FFN pruning, NNCF mixed INT4/INT8 compression, OpenVINO Model Server deployment with continuous batching and chunked prefill, and VTune profiling.

[Code](https://github.com/ShuochenZhou/AskVideo)

### Isolated Areas Help Hub

A pickup and delivery platform where underserved Shanghai residents request free supplies, couriers deliver them, and administrators manage stock. I independently built the WeChat app and backend, then wrote a compiler to port the app to the web. The system combines idempotent writes, inventory locking, a transactional outbox, capacity-aware dispatch with 2-opt routing, and an LLM assistant that uses live data with ownership checks, confirmation tokens, and a rule-based fallback.

I received the [2024 Millennium Fellowship](https://www.millenniumfellows.org/fellow/2024/shanghainyu/shuochen-zhou) for this project.

[Code](https://github.com/ShuochenZhou/Isolated-Areas-Help-Hub) · [Live site](https://qingpu-help-hub.vercel.app)

### GrowAgent

A general-purpose agent runtime with **self-evolving skills**. I built a workflow that extracts durable requirements from user feedback, decides whether to add, merge, or discard skills, and supports replay evaluation, versioned updates, and archival of unused skills. The runtime supports OpenAI- and Anthropic-compatible models, five permission modes, resumable sessions, three-layer context folding, on-demand skill and memory retrieval, MCP, and isolated sub-agents.

[Code](https://github.com/ShuochenZhou/GrowAgent)

### Ne Zha II Review Explorer

An interactive dashboard for exploring Maoyan and Douban reviews of Ne Zha II. I built a rate-limited crawler with transactional checkpoints and idempotent writes, six linked views over a five-dimensional data cube, and cross-lingual BM25 search over Chinese bigrams and English translations with topic and sentiment boosts. Province colors show gaps from national sentiment using an outlier-resistant scale; evaluation tools support blind relevance judging.

[Code](https://github.com/ShuochenZhou/nezha-ii-review-explorer) · [Live dashboard](https://nezha-ii-reception-atlas.vercel.app)
