<div align="center">

# Deepak Rathore

**AI/ML Engineer · GenAI · Agentic AI · Edge AI**

*Building systems that understand documents, images, and sensor data —*
*not demos, but things that run on real hardware under real constraints.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Deepak_Rathore-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepak-rathore-7b3b4718b/)
[![GitHub](https://img.shields.io/badge/GitHub-AlgoDr-181717?style=flat&logo=github&logoColor=white)](https://github.com/AlgoDr)
[![Email](https://img.shields.io/badge/Email-dee365rathore@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:dee365rathore@gmail.com)

</div>

---

## About

**3+ years at DRDO Bengaluru** across DRDO and ADA divisions — building defence-grade AI from embedded firmware to real-time field deployment. My work has shipped to actual IAF systems and achieved **98% model efficacy** in real-world field testing.

The constraint shapes the architecture: your model must run in 8GB RAM on a Jetson, can't call an API, and must work reliably in field conditions. That thinking carries into everything I build — local where it counts, cloud where it adds value.

Currently focused on **GenAI, Agentic AI, and RAG** — building systems that reason over documents and act autonomously.

---

## 🏆 Achievements

- 🥈 **DRDO Young Scientist AI/ML Challenge — 2nd Place** — competed organisation-wide against senior scientists, recognised by Young Scientist Federation
- 📄 **2 Research Papers** — co-authored on wearable AI systems in defence R&D; presented to international teams
- ✅ **98% model efficacy** — real-time field testing of defence-grade wearable robotics system
- 🚀 **Promoted** — Trainee Engineer → Software Engineer → Research Fellowship at ADA/DRDO

---

## 🛠️ Stack

<table>
<tr>
<td valign="top"><b>GenAI / RAG</b></td>
<td>

![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Multimodal-blueviolet?style=flat)

</td>
</tr>
<tr>
<td valign="top"><b>AI / ML</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-00FFFF?style=flat&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

</td>
</tr>
<tr>
<td valign="top"><b>Edge / Embedded</b></td>
<td>

![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Embedded](https://img.shields.io/badge/Firmware-IMU_Sensors-orange?style=flat)

</td>
</tr>
<tr>
<td valign="top"><b>Backend / API</b></td>
<td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logoColor=white)

</td>
</tr>
<tr>
<td valign="top"><b>Data</b></td>
<td>

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![BGE](https://img.shields.io/badge/BGE-Embeddings-green?style=flat)
![CLIP](https://img.shields.io/badge/CLIP-ViT--B/32-412991?style=flat)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

</td>
</tr>
</table>

---

## 🚀 Projects

### [Multimodal Identity RAG](https://github.com/AlgoDr/Multimodal-RAG) &nbsp;`V2 — ChromaDB + FastAPI`
Hybrid RAG over personal documents — PDFs and images in a unified ChromaDB index. Text queries route to BGE + Gemini LLM. Visual queries route to CLIP ViT-B/32. Image content searchable via Gemini Vision captions. Diagnosed and bypassed two upstream LlamaIndex retriever bugs. FastAPI REST endpoint (`POST /query`, `POST /ingest`) with incremental document ingestion — ChromaDB HNSW updates in-place, no rebuild, no restart.

`LlamaIndex` `ChromaDB` `BGE` `CLIP` `Gemini Vision` `FastAPI` `PyMuPDF` `Tesseract` `Python 3.13`

---

### [AI Newsroom Studio](https://github.com/AlgoDr/AI-Newsroom-Studio) &nbsp;`In Development(75% Completed)`
10-agent LangGraph pipeline: HackerNews trends → published YouTube Short, zero human steps. Agents: Trend Scout → Researcher → Fact Checker → Editorial → Script Writer → Video Prompt → Video Generator → Publisher. Conditional state machine with shared `NewsroomState` TypedDict. 4 real data sources (NewsAPI, Reddit PRAW, Google Trends, Serper). Chose LangGraph over CrewAI for explicit state control and 3× lower token usage.

`LangGraph` `Gemini 2.5 Flash` `HeyGen` `YouTube API` `Reddit PRAW` `APScheduler` `SQLite`

---

### [AutoJobApply](https://github.com/AlgoDr/AutoJobapply)
Autonomous job application agent. Searches Naukri, scores roles locally against a target profile, filters with negative keywords, auto-fills forms. 6 confirmed applications on first run. Deployed on GCP Cloud Run with WhatsApp Business API webhook for candidate onboarding.

`Playwright` `Gemini` `SQLAlchemy` `FastAPI` `Docker` `GCP Cloud Run` `WhatsApp API`

---

### [Segmentation](https://github.com/AlgoDr/Segmentation)
Real-time instance segmentation on live webcam/video using Mask-RCNN pretrained on COCO.

`PyTorch` `Mask-RCNN` `OpenCV` `Python`

---

## 📊 GitHub Activity

<div align="center">

![Deepak's GitHub stats](https://github-readme-stats.vercel.app/api?username=AlgoDr&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF)

</div>

---

<div align="center">

**3 years building defence-grade AI at DRDO Bengaluru**
*Actively looking for Data / AI-ML Engineer roles*

</div>
