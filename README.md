# Hi, I'm Budhaditya Mukhopadhyay 👋

**Senior AI Engineer | AI Systems Architect | Healthcare AI | Edge & Cloud AI | GenAI | Autonomous Systems**

📍 Munich, Germany · 🇩🇪 German Permanent Resident
🌐 [Portfolio](https://www.budhadityamukhopadhyay.com/) · 💼 [LinkedIn](https://www.linkedin.com/in/budhadityamukhopadhyay/) · 🎓 [Google Scholar](https://scholar.google.com/citations?hl=en&user=UyFDbHAAAAAJ) · 📧 [Email](mailto:budha2011@gmail.com)

---

## About Me

I am a Senior AI Engineer with experience designing and delivering end-to-end AI systems across healthcare, edge and cloud inference, audio and video ML, computer vision, medical imaging, GenAI, agentic automation, and autonomous UAV systems.

My work spans the complete AI lifecycle:

* Data strategy, collection, preprocessing, and validation
* Model development, evaluation, optimization, and deployment
* Mobile and on-device inference
* Containerized cloud model serving
* AI architecture and production system design
* Technical leadership, mentoring, and stakeholder communication

I enjoy turning research ideas into reliable, usable products—especially where AI must operate under real-world constraints such as latency, model size, privacy, noisy data, hardware limitations, or safety-critical workflows.

---

## Selected Impact

* Built healthcare AI models achieving approximately **97% accuracy**
* Optimized a mobile inference model to approximately **16 MB** with approximately **200 ms prediction time**
* Supported AI functionality used by an application with approximately **2,300 users**
* Contributed to AI workflows supporting **two clinical trials**
* Built training datasets containing approximately **3,000 audio files** and **2,000+ images**
* Designed a hybrid AI architecture combining **offline TensorFlow.js inference** with **Azure-hosted inference**
* Mentored **3 master's students** in healthcare AI and **7 students/interns** in UAV systems
* Delivered a webinar on agentic AI to approximately **60 students**
* Published research in medical AI, explainability, computer vision, and tumour segmentation

---

## What I Work On

### Production AI and Healthcare ML

* Audio event detection and temporal modelling
* Healthcare audio and video processing
* Mobile-first and on-device AI
* Clinical validation and human-in-the-loop evaluation
* Medical computer vision and imaging
* Privacy-aware clinical documentation systems

### GenAI and Agentic Systems

* LLM-powered applications
* Retrieval-Augmented Generation
* Local and privacy-aware LLM deployment
* LangGraph and LangChain workflows
* Structured information extraction
* Long-running human-in-the-loop automation
* AI-assisted document and business-process workflows

### Edge, Cloud and Autonomous Systems

* Hybrid edge/cloud inference
* Azure Container Apps model serving
* Real-time distributed systems
* UAV intelligence and autonomous control
* Embedded and sensor-connected systems
* Secure device communication and telemetry

---

## Current Roles

### Senior AI Engineer — VisionHealth GmbH

I lead end-to-end AI development for audio- and video-based healthcare applications, including data strategy, model development, validation, mobile integration, edge inference, and cloud deployment.

Selected work includes:

* Designing TensorFlow.js models for inhalation, spray, exhalation, and manoeuvre-quality detection
* Implementing local AI inference in a React Native mobile application
* Building a configurable online/offline inference architecture
* Deploying Dockerized inference services using Azure Container Apps and Azure Container Registry
* Implementing secure HTTPS audio inference, health probes, revisions, autoscaling, Managed Identity, monitoring, and logging
* Building LangGraph/LangChain workflows for email processing, structured extraction, PDF generation, human review, signature handling, and document storage
* Mentoring master's students and teaching colleagues about AI and AI ethics

### Strategic Advisor — UAV and AI Systems

I advise on the architecture and development of AI-powered UAV and counter-UAV systems, connecting hardware, sensors, real-time software, autonomy, and product strategy.

My work includes:

* Distributed drone-control architecture
* Detection, tracking, localization, threat scoring, and path planning
* MAVLink-based autonomous drone workflows
* MQTT and ZeroMQ distributed communication
* Embedded C++ development on ESP32
* LoRa-based authenticated telemetry
* HMAC-SHA256 authentication and replay protection
* Student mentoring and technical strategy

---

## Featured Projects

### [MedScribe — Clinical Voice Note Assistant](https://github.com/BudhaTronix/medscribe)

A local-first clinical documentation engineering demo for German and English medical dictation.

**Highlights**

* Local speech recognition with faster-whisper
* Pydantic-validated structured clinical-note extraction
* Local Ollama-compatible LLM integration
* BGE-M3 multilingual embeddings
* Qdrant vector search and grounded RAG
* Evidence-threshold refusal to reduce unsupported answers
* FastAPI, Gradio, Prometheus, Docker Compose, nginx, and Kubernetes examples
* Evaluation tooling for WER, CER, hit@k, MRR, and refusal correctness

> Uses synthetic data and is presented as an engineering demo, not a medical device.

---

### [AI Repo Analyzer](https://github.com/BudhaTronix/ai-repo-analyzer)

An AI-assisted developer tool that analyzes public GitHub repositories and generates:

* Architecture and dependency insights
* Framework and entry-point detection
* Risk and improvement suggestions
* Architecture diagrams
* Downloadable Markdown reports
* Optional LLM-assisted analysis with local fallback support

**Stack:** Python, FastAPI, Gradio, NetworkX, Graphviz, Docker, GitHub Actions

---

### [RemoteLlama / OllaBridge](https://github.com/BudhaTronix/RemoteLlama)

A local-first web interface for interacting with models hosted on a remote Ollama server.

**Highlights**

* Streaming chat responses
* Remote Ollama connectivity
* Next.js API proxying
* Document upload and extraction
* Local chat and configuration persistence
* Multimodal model support

**Stack:** Next.js, TypeScript, Tailwind CSS, IndexedDB, Vitest

---

### [JarvisFlow](https://github.com/BudhaTronix/JarvisFlow)

A gesture-controlled brainstorming and learning application using browser-based hand tracking.

**Highlights**

* MediaPipe hand tracking
* Gesture-based topic navigation
* Accessible keyboard and mouse alternatives
* FastAPI backend
* React, Vite, and TypeScript frontend
* Service abstraction for future LLM-powered topic expansion

---

### [Weakly-Supervised Tumour Detection](https://github.com/BudhaTronix/Weakly-Supervised-Tumour-Detection)

A productionized medical-imaging research pipeline for registration-assisted liver tumour localization and segmentation.

**Stack:** PyTorch, 3D U-Net, MSCGUNet, Streamlit, Docker, CLI tooling, pytest

---

### [BlurDetection](https://github.com/BudhaTronix/BlurDetection)

A production-oriented MRI and CT blur-detection application with training, testing, inference, configuration management, a Streamlit interface, tests, and Docker support.

---

## Open-Source Contribution

### [PyTorch-OOD](https://github.com/kkirchheim/pytorch-ood)

Contributor to **PyTorch-OOD**, an open-source PyTorch library for:

* Out-of-distribution detection
* Open-set recognition
* Novelty and anomaly detection
* Confidence estimation
* Reusable datasets, models, losses, metrics, and benchmarks

This work reflects my interest in trustworthy machine learning, model robustness, reproducible research tooling, and detecting unknown inputs in deployed AI systems.

---

## Research and Publications

### Towards Segmenting the Invisible

**First author** — AIBIO 2025 / Springer, published online in 2026

Research on registration-assisted and weakly supervised tumour segmentation across medical-imaging modalities.

[View publication](https://doi.org/10.1007/978-3-032-17216-7_18)

### An Automated Tongue Tracker for Quantifying Bulbar Function in ALS

**Equal first author / co-first author** — Frontiers in Neurology, 2022

Developed computer-vision and deep-learning methods for tongue tracking and bulbar-function analysis in ALS research.

[View publication](https://doi.org/10.3389/fneur.2022.838191)

### TorchEsegeta

**Co-author** — Applied Sciences, 2022

Contributed to the development of an interpretability and explainability framework for image-based deep-learning models.

[View publication](https://doi.org/10.3390/app12041834)

---

## Technical Skills

### AI and Machine Learning

`PyTorch` · `TensorFlow` · `TensorFlow.js` · `Scikit-learn` · `OpenCV` · `YOLO` · `MobileNetV2` · `Time-Series ML` · `Audio ML` · `Computer Vision` · `Medical Imaging` · `XAI` · `OOD Detection`

### GenAI and Data Systems

`LangGraph` · `LangChain` · `Ollama` · `faster-whisper` · `Qdrant` · `BGE-M3` · `Sentence Transformers` · `Pydantic` · `RAG` · `Local LLMs`

### Backend, Cloud and MLOps

`FastAPI` · `Flask` · `Docker` · `Docker Compose` · `GitHub Actions` · `Azure Container Apps` · `Azure Container Registry` · `Azure Monitor` · `Prometheus` · `nginx` · `Kubernetes`

### Edge, Embedded and Distributed Systems

`React Native` · `MAVLink` · `MQTT` · `ZeroMQ` · `ESP32` · `LoRa` · `Raspberry Pi` · `HMAC-SHA256` · `Real-Time Control Systems`

### Languages

`Python` · `TypeScript` · `JavaScript` · `C++` · `C#`

---

## Leadership and Knowledge Sharing

* Mentored master's students working on applied AI projects
* Mentored students and interns working on UAV and autonomous-system technologies
* Taught AI and AI ethics to colleagues
* Main speaker for **“Agents in Action: The Dawn of Action-Oriented AI”**
* Comfortable working as both a hands-on senior engineer and a technical AI lead

---

## Professional Interests

I am particularly interested in opportunities involving:

* Senior AI engineering and AI technical leadership
* Healthcare and medical AI
* GenAI and agentic workflows
* Edge and on-device inference
* Cloud AI and production model serving
* Computer vision and medical imaging
* Trustworthy ML and out-of-distribution detection
* Robotics, autonomous systems, and UAV intelligence

---

## Beyond Engineering

Outside work, I enjoy:

* FPV drone flying
* Photography
* Playing guitar
* Swimming

---

## Let's Connect

I am open to senior AI engineering and AI leadership opportunities across Germany.

* [LinkedIn](https://www.linkedin.com/in/budhadityamukhopadhyay/)
* [Portfolio](https://www.budhadityamukhopadhyay.com/)
* [GitHub](https://github.com/BudhaTronix)
* [Google Scholar](https://scholar.google.com/citations?hl=en&user=UyFDbHAAAAAJ)
* [Email](mailto:budha2011@gmail.com)
