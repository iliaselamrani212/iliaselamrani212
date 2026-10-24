# 👋 Hello, I'm **ILIAS EL AMRANI**

<img src="https://github.com/user-attachments/assets/13e0ff2d-b201-4d67-a4f0-15742c6691e5" width="180" align="left" style="margin-right:20px;" />

&nbsp;&nbsp;&nbsp;&nbsp;🎓 **MSc Intelligent Systems & Computer Vision** — Institut Galilée, Université Sorbonne Paris Nord
&nbsp;&nbsp;&nbsp;&nbsp;🤖 Computer Vision · Deep Learning · LLM & Agentic Systems
&nbsp;&nbsp;&nbsp;&nbsp;🔎 Looking for a 6-month end-of-studies internship — **from March 2027**

<br clear="left"/>

---

## 🚀 About Me

Final-year AI engineering student, in a dual-degree programme between
**Institut Galilée (Université Sorbonne Paris Nord)** and **ENIAD**.

I build systems whose output can be checked — a flagged anomaly that
points back to the documentation justifying it, a medical prediction a
clinician can trace to its source. I care more about whether a system
can prove its answer than whether it sounds right.

---

## 📌 Featured Projects

### 🛰️ AI-Powered Network Configuration Auditor
Built during an internship at **inwi** (telecom operator, Casablanca).
Audits Ericsson 4G/5G Bulk CM exports, flags misconfigured parameters,
and explains each finding against the vendor documentation.

- **Three layers** — XML parsing (lxml) → anomaly detection
  (unsupervised + conformance rules) → grounded explanation (RAG)
- **Fully on-premise**: network data could not leave the operator's
  infrastructure, so the LLM runs locally via Ollama
- **Never guess**: the model is required to answer *"the indexed
  documentation contains no usable information"* rather than improvise
- **FastAPI** backend with background jobs and isolated per-audit
  workspaces

`FastAPI` · `LangChain` · `ChromaDB` · `Ollama / Llama 3.2` ·
`scikit-learn` · `lxml`

🔗 https://github.com/iliaselamrani212/ai-powered-network-configuration-auditor

---

### 🧠 Alzheimer's Disease Detection — MRI & Speech
Bimodal detection combining brain imaging and spontaneous speech.

- **3D ResNet-18** with the *Inflate-1* strategy — 2D ImageNet kernels
  inflated to 3D — on ADNI MRI volumes
- GPU skull-stripping (HD-BET), tight cropping, focal loss, volumetric
  augmentation, test-time augmentation
- **Subject-level splits** to prevent data leakage across patient visits
- **Grad-CAM 3D** across axial, sagittal and coronal planes
- NLP branch on the **DementiaBank Pitt Corpus**: CHAT markup parsing,
  disfluency features, transformer classification

`PyTorch` · `nibabel` · `HD-BET` · `transformers` · `scikit-learn`

🔗 https://github.com/iliaselamrani212/Alzheimer-s-Disease-Detection-using-NLP-and-Deep-Learning-Architectures.

---

### 🔗 RAG Pipeline with LangChain & Ollama
A reference implementation of the retrieval architecture above, fully
local and reproducible.

- PDF loading → chunking → embeddings → ChromaDB → generation
- MMR retrieval, cosine similarity, persistent vector store
- No external API required

`LangChain LCEL` · `Ollama` · `Qwen3-Embedding` · `ChromaDB`

🔗 https://github.com/iliaselamrani212/rag-pipeline-langchain-ollama

---

### 📊 Machine Learning Projects
- **[Diabetes Prediction](https://github.com/iliaselamrani212/Diabetes-Prediction)** — Kaggle Playground Series; XGBoost, CatBoost, LightGBM, ensembling
- **[Electricity Consumption Prediction](https://github.com/iliaselamrani212/electricity-prediction-ml)** — ASHRAE dataset; time series analysis and feature engineering

---

## 🛠️ Tech Stack

### 👨‍💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)

### 🤖 Deep Learning & Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

- **Computer vision** — 2D and 3D CNNs, ResNet, Vision Transformers,
  medical imaging, Grad-CAM
- **NLP** — Transformers implemented from scratch (multi-head
  attention), BERT fine-tuning, sequence-to-sequence
- **Classical ML** — gradient boosting, ensembling, unsupervised
  anomaly detection

### 🔗 LLM & Agentic Stack
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat)

- **RAG** — chunking strategies, embeddings, hybrid and MMR retrieval,
  source attribution
- **LangGraph** — multi-agent orchestration, tool calling,
  human-in-the-loop validation
- **Local inference** — Ollama, Llama 3.2, Qwen3-Embedding,
  nomic-embed-text

### ⚙️ Backend & Tooling
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)

---

## 📈 GitHub Stats

![Ilias's GitHub stats](https://github-readme-stats.vercel.app/api?username=iliaselamrani212&show_icons=true&theme=dark)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=iliaselamrani212&layout=compact&theme=dark)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iliaselamrani)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:iliaselamrani8877@gmail.com)
