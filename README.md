<h1 align="center">Hi 👋, I'm Saksham Bisen</h1>
<h3 align="center">Applied AI & Systems Engineer — sandboxed execution infrastructure, agent orchestration, eval frameworks</h3>
<p align="center">
Robotics & Automation engineer who moved into AI systems. I build the layer between LLMs and reliable production behavior: execution sandboxes, orchestration graphs, and evaluation harnesses that make agents debuggable instead of magical.
</p>
<br>

### 🚀 Featured — [agent-sandbox-architectures](https://github.com/sb-saksham/agent-sandbox-architectures)
Benchmarked the **cold-boot cost of three isolation backends** for multi-tenant execution — Docker (runc, shared kernel), self-hosted Firecracker via **kata-fc on Kubernetes** (k3s · devmapper · RuntimeClass), and managed Firecracker via **E2B** — with measured p50/p95/p99 across two layers, per-backend security analysis, and a decision matrix.
**Finding:** the microVM isolation boundary itself costs only **~0.8–1.0s over a container** — most of the visible 2.5–4.3s spawn gap is JupyterHub startup and orchestration, *not* the kernel boundary. Measured, not guessed.

### 🔭 Currently building
- **Agent execution infrastructure** @ LastLab AI: hybrid sandboxed runtime with conditional routing between Kata Containers (GPU) and Firecracker microVMs (CPU-only isolation) — the isolation stack I benchmarked publicly above
- **LangGraph orchestration**: stateful multi-step agent reasoning with typed tool contracts and recoverable execution graphs
- **Eval frameworks**: component-level golden-response testing for agent reliability

### 📌 Also pinned
- **Research paper implementations** (PyTorch): BitNet 1-bit LLMs · Byte Latent Transformer · Multi-Query Attention · Milvus vector DB
- **LangGraph multi-agent systems**: self-correcting net-zero planner · real-time drone pest-detection (RT-DETR + SegFormer)

### 🧠 What I care about
Agent reliability • Sandboxed execution • Specification-first systems design • Eval-driven development • The intersection of AI infrastructure and the physical world

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
B.Tech, Robotics & Automation (9.1 GPA) · Gemini/Llama training & evaluation pipelines @ Turing · Layer-1 protocol engineering in Go @ Cubane · robotics & UAV systems background

### 💬 Ask me about
**Firecracker microVMs** • **kata-containers / gVisor** • **LangGraph** • **Agent evaluation** • **Sandbox isolation tradeoffs** • **FastAPI** • **UAV systems**

### 📫 Reach me
**Email:** [sakshambisen123@gmail.com](mailto:sakshambisen123@gmail.com)  
**LinkedIn:** [linkedin.com/in/sbsaksham](https://linkedin.com/in/sbsaksham)

<br>

---
<details>
<summary>📈 My GitHub Stats</summary>
<p align="center"> 
<img src="https://github-readme-stats.vercel.app/api?username=sb-saksham&show_icons=true&theme=radical" alt="Saksham Bisen" />
</p>
</details>
<br>
