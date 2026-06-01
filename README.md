<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:0D1117,50:0F2027,100:1a1a2e&text=Vikas%20Saini&fontSize=72&fontColor=58A6FF&animation=fadeIn&fontAlignY=40&desc=Machine%20Learning%20Engineer%20%E2%80%94%20AI%20Systems%20Architect&descAlignY=60&descSize=20&descColor=8B949E" width="100%" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vikas%20Saini-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-saini1)
[![Email](https://img.shields.io/badge/Email-vikassn44%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vikassn44@gmail.com)
[![GitHub](https://img.shields.io/github/followers/vikassaini77?label=Follow&style=flat-square&logo=github&color=238636)](https://github.com/vikassaini77)
![Profile Views](https://komarev.com/ghpvc/?username=vikassaini77&style=flat-square&color=58A6FF&label=Views)

</div>

---

## About

I'm a **Machine Learning Engineer** who builds AI systems designed to survive production — not just pass benchmarks.

My focus is on the gap between *working in notebooks* and *working at scale*: latency constraints, infrastructure reliability, observability, cost efficiency, and the kind of engineering rigor that lets models actually ship. I work across Computer Vision, NLP, and MLOps, with a bias toward systems that are fast, explainable, and maintainable by teams — not just their authors.

> *Models impress. Systems endure.*

---

## Core Competencies

### Real-Time AI Systems
Multi-stream video inference · PyTorch → ONNX → TensorRT optimization · Sub-200ms latency pipelines · Failure-aware architectures with automatic restart and graceful degradation

### Computer Vision
Object detection and tracking (YOLOv8, RT-DETR) · Semantic & instance segmentation · Pose estimation · OCR pipelines · Video understanding at 30+ FPS

### Natural Language Processing
LLM fine-tuning (LoRA / QLoRA) · Retrieval-Augmented Generation (RAG) · Named Entity Recognition · Semantic search · Multi-turn dialogue systems

### MLOps & Infrastructure
MLflow · Kubeflow · DVC · Triton Inference Server · Docker · FastAPI · Model versioning, A/B testing, drift monitoring, and observability dashboards

---

## Technical Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / DL Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Infrastructure & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NVIDIA Triton](https://img.shields.io/badge/Triton-76B900?style=flat-square&logo=nvidia&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)

**Cloud & Data**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

## Selected Projects

### 🔍 Real-Time Multi-Stream Surveillance Pipeline
End-to-end video intelligence system processing 8+ concurrent streams at 30+ FPS. Custom TensorRT INT8 quantization reduced GPU memory footprint by 40% with <2% accuracy trade-off. Built with failure-aware process management and automatic stream recovery.

`PyTorch` `TensorRT` `ONNX` `OpenCV` `FastAPI` `Redis` `Docker`

---

### 💬 Production RAG System for Enterprise Knowledge Retrieval
Retrieval-Augmented Generation pipeline handling 10K+ daily queries with sub-300ms P95 latency. Fine-tuned embedding model on domain corpus; implemented hybrid dense-sparse retrieval (FAISS + BM25) with query rewriting and multi-hop reasoning.

`LangChain` `FAISS` `HuggingFace` `FastAPI` `PostgreSQL` `MLflow`

---

### 🏷️ Document Intelligence Pipeline (OCR + NER)
End-to-end document parsing system for structured and semi-structured documents. Custom NER model achieving 94.2 F1 on financial documents. Processes 500+ documents per minute via async batching with confidence-based human-in-the-loop escalation.

`PaddleOCR` `spaCy` `Transformers` `Celery` `PostgreSQL` `Docker`

---

### ⚡ Model Serving Infrastructure with A/B Testing
Triton-based serving infrastructure supporting shadow deployments and traffic splitting for safe model rollouts. Integrated drift detection, automated rollback triggers, and Grafana dashboards for real-time monitoring.

`NVIDIA Triton` `Prometheus` `Grafana` `Kubernetes` `MLflow` `DVC`

---

## Engineering Philosophy

```
Production ≠ Jupyter.   Accuracy ≠ Value.   Fast ≠ Fragile.
```

Three principles I return to on every project:

**Observability first.** A model you can't monitor is a model you can't trust. Every system I build includes metrics, logging, alerting, and dashboards before it ships — not after something breaks.

**Design for failure.** Networks partition. GPUs OOM. Upstream APIs timeout. I architect for graceful degradation rather than assuming the happy path holds.

**Optimize what matters.** Latency, throughput, cost, and compute are engineering tradeoffs — not afterthoughts. I profile before I optimize, and I measure before I claim improvement.


---

## Currently

- 🔬 Researching efficient multi-modal architectures for edge deployment
- 📦 Building reusable MLOps primitives for small-to-mid-scale teams
- 🌍 Open to global AI engineering roles — remote or relocation

---

## Let's Connect

I'm interested in roles at the intersection of research and production — where the challenge is making capable models reliable, efficient, and actually useful. If that's what you're working on, I'd like to talk.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-saini1)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vikassn44@gmail.com)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1a1a2e,100:0D1117&section=footer" width="100%" />
</div>
