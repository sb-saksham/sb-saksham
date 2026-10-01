<h1 align="center">Hi 👋, I'm Saksham Bisen</h1>
<h3 align="center">Applied AI & Systems Engineer — AI infrastructure, agent systems, ML research</h3>

<p align="center">
Robotics & Automation engineer working on AI systems and infrastructure. I build systems around
LLMs and ML models that make them reliable, testable, and useful in real-world environments.
</p>

<br>

### 🔭 Currently building

- **Agent execution infrastructure** @ [LastLab AI](https://lastlabai.com): multi-tenant sandboxed execution on GKE,
  FastAPI, JupyterHub, gVisor, Terraform, GCS, and resource/quota management.
- **HingNoul — Calibrated Hinglish Decisions**: a benchmark and modeling project studying
  decision-making across English, Devanagari, and Hinglish, with a focus on accuracy and
  calibration.

### 🧪 Featured — [HingNoul](https://github.com/sb-saksham/hinglish-jev-noul)

A benchmark and modeling project for evaluating AI decision-making across English, Devanagari,
and Hinglish.

- Built a **1,110+ item benchmark** across 6 business domains
- Found up to **20-point accuracy gaps** and **15–24% confident-wrong answer rates** across
  4 open baselines
- Fine-tuned a **307M mmBERT cross-encoder** on 45.6k synthetic examples using PyTorch,
  Hugging Face, BCE and Brier loss
- Achieved **5–12 point accuracy gains** over the strongest open baseline and reduced
  Devanagari calibration error by **30%+** on 353 human-labeled samples
- Validated generalization with **4-fold cross-validation**
- Shipped an installable Python package with **52 tests, CLI/library APIs, and a
  crash-resilient training pipeline**

### 🏗️ Selected — [agent-sandbox-architectures](https://github.com/sb-saksham/agent-sandbox-architectures)

Benchmarked the **cold-boot cost of three isolation backends** for multi-tenant execution —
Docker (runc, shared kernel), self-hosted Firecracker via **kata-fc on Kubernetes**
(k3s · devmapper · RuntimeClass), and managed Firecracker via **E2B** — with measured
p50/p95/p99 across two layers, per-backend security analysis, and a decision matrix.

**Finding:** the microVM isolation boundary itself costs only **~0.8–1.0s over a container** —
most of the visible spawn gap comes from JupyterHub startup and orchestration, not the
kernel boundary. Measured, not guessed.

### 📌 Research & AI Systems

- **Research paper implementations** (PyTorch): BitNet 1-bit LLMs · Byte Latent Transformer ·
  Multi-Query Attention · Milvus vector DB
- **Net-Zero House Planner**: self-correcting and self-validating multi-agent LangGraph system
  for energy, water and food planning
- **Selective Pesticide Spraying**: RT-DETR + SegFormer computer-vision pipeline with a
  LangGraph spray-decision workflow, designed for deployment on NVIDIA Jetson Orin
- **Dermit**: Django backend with Redis-backed WebSockets, AWS S3, multimodal CV + LLM pipeline,
  and conversational RAG

### 🧠 What I care about

AI reliability • ML evaluation • Sandboxed execution • Agent systems •
Research implementation • Computer vision • AI infrastructure •
The intersection of AI and the physical world

### 🛠️ Languages and Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,go,rust,fastapi,docker,kubernetes,linux,redis,postgres,aws,pytorch" />
</p>

<p align="left">
  <img height="48" src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/langchain.svg" />
  <img height="48" src="https://raw.githubusercontent.com/github/explore/master/topics/raspberry-pi/raspberry-pi.png" />
  <img height="48" src="https://raw.githubusercontent.com/github/explore/master/topics/arduino/arduino.png" />
  <img height="48" src="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/ethereum.svg" />
</p>

### 📍 Background

B.Tech, Robotics & Automation (9.1 GPA) </br>
· Gemini/Llama training & evaluation pipelines @ [Turing](https://turing.com) </br>
· Layer-1 protocol engineering in Go @ [Cubane](https://cubane.space) </br>
· Robotics & UAV systems background

### 💬 Ask me about

**Python / FastAPI** • **Firecracker / gVisor / Kata Containers** • **Agent execution**
• **ML evaluation** • **LangGraph** • **Computer Vision** • **UAV systems**

### 📫 Reach me

**Email:** [sakshambisen123@gmail.com](mailto:sakshambisen123@gmail.com)  
**LinkedIn:** [linkedin.com/in/sbsaksham](https://linkedin.com/in/sbsaksham)

<br>
