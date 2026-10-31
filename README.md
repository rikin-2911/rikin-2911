# Rikin Pithadia
### AI/ML Engineer | Generative AI | Agentic Systems | Scientific Machine Learning

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=180&color=0:0f2027,50:203a43,100:2c5364&text=Rikin%20Pithadia&fontColor=ffffff&fontSize=48&fontAlignY=45&desc=Building%20Intelligent%20Systems%20Through%20AI%20%26%20Engineering&descAlignY=68&descSize=14" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/rikin2911">
    <img src="https://img.shields.io/badge/GitHub-rikin2911-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://rikin2911-portfolio-ai-ml.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

## `$ whoami`

I'm an **AI/ML Engineer** interested in building intelligent, scalable and production-ready systems.

My work spans Machine Learning, Deep Learning, Generative AI, Agentic AI, Computer Vision and Scientific Machine Learning. I enjoy working at the intersection of research and engineering — taking ideas from experimentation to implementation and deployment.

- Building agentic AI systems using LLMs, RAG and MCP.
- Developing and optimizing deep learning models for real-world applications.
- Exploring Scientific ML, Neural ODEs and Physics-Informed Learning.
- Working with ML infrastructure, model optimization and deployment.
- Exploring Robotics, Edge AI and intelligent automation.

**Current interests:** MLOps Systems, Agentic AI, AI Research, Model Optimization and Scientific ML.

---

## `$ tech_stack --list`

### Programming Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,bash,sql" />
</p>

### Machine Learning & Deep Learning
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" />
  <img src="https://img.shields.io/badge/JAX-000000?style=flat&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Computer%20Vision-00599C?style=flat" />
</p>

### Generative AI & Agentic Systems
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=flat" />
  <img src="https://img.shields.io/badge/MCP-412991?style=flat" />
  <img src="https://img.shields.io/badge/LLM%20Evaluation-00897B?style=flat" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=googlegemini&logoColor=white" />
</p>

### Backend, Databases & MLOps
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,docker,git,github,linux,postgres,mongodb" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat" />
</p>

### Robotics & Scientific Machine Learning
<p>
  <img src="https://skillicons.dev/icons?i=opencv,ros" />
  <img src="https://img.shields.io/badge/YOLO-111F68?style=flat" />
  <img src="https://img.shields.io/badge/Neural%20ODEs-6A5ACD?style=flat" />
  <img src="https://img.shields.io/badge/PINNs-00897B?style=flat" />
  <img src="https://img.shields.io/badge/Diffrax-333333?style=flat" />
  <img src="https://img.shields.io/badge/Equinox-333333?style=flat" />
</p>

---

## `$ ls ./featured_projects`

### 01. Agentic CAD System
**Natural Language to 3D CAD Generation**

An agentic CAD platform that translates natural-language instructions into parametric 3D models using LLM-powered tool orchestration.

- Designed an agentic workflow using LangGraph and LangChain.
- Developed an MCP server using FastMCP for CAD operations.
- Integrated CadQuery for programmatic 3D geometry generation.
- Built a FastAPI backend and integrated LLM-based reasoning.
- Implemented geometry validation, measurement and STEP/STL export.
- Integrated LangSmith for tracing and LLM evaluation.

**Tech:** Python · LangGraph · LangChain · FastMCP · FastAPI · CadQuery · Pinecone · Gemini

**Evaluation:** ~52.46 seconds average end-to-end latency across 10 experiments.

[Repository](https://github.com/rikin2911) · [Portfolio](https://rikin2911-portfolio-ai-ml.vercel.app/)

---

### 02. Physics-Informed Neural ODE Autoencoder
**Scientific Machine Learning for Stiff Chemical Kinetics**

Developed a Neural ODE-based surrogate modeling approach for stiff chemical kinetic systems, with characteristic time scales ranging from 10⁻⁹ to 10⁻³ seconds.

- Implemented an autoencoder architecture using JAX and Equinox.
- Integrated Diffrax with adaptive Dopri5 ODE solving.
- Designed a composite physics-informed loss framework.
- Incorporated species reconstruction, temperature prediction, elemental conservation, enthalpy consistency and non-negativity constraints.
- Migrated the training pipeline from PyTorch to JAX to leverage JIT compilation and XLA.

**Tech:** Python · JAX · Equinox · Diffrax · Optax · PyTorch · Neural ODEs · PINNs

**Research focus:** Physics-informed learning, numerical integration, stiff ODEs and computational efficiency.

---

### 03. Edge AI Weed Detection
**YOLO-Based Segmentation on NVIDIA Jetson Nano**

Developed a computer vision pipeline for detecting and segmenting weeds in real-world agricultural environments.

- Trained YOLOv11n-seg on 800+ self-captured and annotated field images.
- Achieved 0.80 Box mAP@50 and 0.78 Mask mAP@50.
- Implemented on-device inference on NVIDIA Jetson Nano.
- Achieved approximately 8 FPS (125 ms/frame).
- Implemented OpenCV checkerboard calibration and ground-plane homography.

**Tech:** Python · PyTorch · YOLOv11 · OpenCV · Roboflow · NVIDIA Jetson Nano

---

### 04. Multimodal Agentic RAG System
**Intelligent Document Understanding and Retrieval**

Built a multimodal document intelligence application for processing and querying complex PDF documents.

- Designed an agentic retrieval workflow using LangGraph.
- Integrated multimodal document processing and retrieval.
- Implemented vector similarity search using Pinecone.
- Developed backend APIs using FastAPI.
- Integrated Google Gemini for LLM-powered question answering.

**Tech:** Python · LangChain · LangGraph · FastAPI · FastMCP · Pinecone · Google Gemini

---

## `$ experience --show`

| Organization | Role | Period |
|---|---|---|
| IIT Gandhinagar | SRIP Research Intern – Scientific ML | May–July 2026 |
| Vajra Software & Robotics | Robotics & AI Intern | Feb–May 2026 |
| CognifyEV | AI Engineer Intern | Aug–Nov 2025 |

**Research – IIT Gandhinagar**

Project: *A Priori Assessment of LES–PCA Modeling for Hydrogen-Enriched Jet-in-Crossflow Flames Using DNS Data.*

Research interests include Scientific ML, combustion modeling and data-driven surrogate modeling.

---

## `$ education --show`

**Indian Institute of Technology Guwahati**
- B.S. (Honours) in Data Science and Artificial Intelligence
- CPI: 7.75/10

**Government Engineering College, Gandhinagar**
- B.Tech in Mechanical Engineering
- CPI: 7.97/10
- Minor in Internet of Things (IoT) — CPI: 10.00/10

---

## `$ github --analytics`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rikin2911&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&rank_icon=github" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rikin2911&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=rikin2911&theme=github-dark-blue&hide_border=true" width="75%" />
</p>

### Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rikin2911&theme=github-compact&hide_border=true&area=true" width="100%" />
</p>

### Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/rikin2911/rikin2911/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation" width="100%" />
</p>

---

## `$ connect --with-me`

I'm interested in collaborating on AI/ML projects, research initiatives, Agentic AI applications and open-source engineering.

<p align="center">
  <a href="https://github.com/rikin2911">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://rikin2911-portfolio-ai-ml.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Explore-0A66C2?style=for-the-badge&logo=vercel" />
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
</p>

<p align="center">
  <i>"Turning research ideas into intelligent systems, one experiment at a time."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=100&section=footer" width="100%" />
</p>