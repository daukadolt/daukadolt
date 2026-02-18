## 🧠 Projects

### 🔥 [Pandora](https://github.com/daukadolt/pandora)
> Ephemeral sandboxed code execution inside Firecracker microVMs with pre-warmed pools and full observability

Boots isolated **Firecracker microVMs** in <5ms via a pre-warmed pool. Session-based REST API lets clients create sandboxes, run commands over SSH, and tear them down — with automatic idle reaping. Every lifecycle phase is instrumented with **Prometheus** metrics and visualized on a **Grafana** dashboard.

**Tech Stack:** `Python (FastAPI)` · `Firecracker` · `KVM` · `Linux Networking (iptables/NAT/TAP)` · `Prometheus` · `Grafana` · `Docker Compose`

<p align="center">
  <img src="https://raw.githubusercontent.com/daukadolt/pandora/main/pandora.gif" width="600" />
</p>

---

### 📄 [PaperRAG](https://github.com/daukadolt/PaperRAG)
> Modular Retrieval-Augmented Generation system for academic papers  

Built with **ChromaDB** + **OpenAI API**, optimized using **H100 GPU** cloud processing.  
Indexes and answers queries over 200+ LLM agent papers.

**Tech Stack:** `Python` · `LangChain` · `ChromaDB` · `OpenAI`

---

### 🤖 [Agent Smith](https://github.com/daukadolt/agent_smith)
> Programmable AI assistant with function-calling capabilities  

Parses natural instructions and executes structured actions via **CLI** or **Telegram**, using OpenAI function calling. Includes **Airtable automation** and a modular tool interface.

**Tech Stack:** `Python` · `OpenAI Functions` · `Airtable API` · `Telegram Bot`

---
