<div align="center">

# Deepak Rathore

**AI/ML Engineer · GenAI · Agentic AI · Edge AI**

*Building systems that understand documents, images, and sensor data —*
*not demos, but things that run on real hardware under real constraints.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepak-rathore-7b3b4718b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlgoDr)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dee365rathore@gmail.com)

<br>

[![Status](https://img.shields.io/badge/Status-Immediate_Joiner_Available-2EA043?style=for-the-badge)](#)

</div>

---

## 👨‍💻 Profile

I transition AI from concept to deployment. With **3+ years at DRDO Bengaluru (ADA division)**, I build defence-grade AI ranging from embedded firmware to real-time field deployments achieving **98% efficacy**. 

My architectural philosophy is shaped by extreme constraints: models must run locally on edge devices (like an 8GB Jetson) without API reliance, ensuring absolute reliability in field conditions. Currently, I am expanding these principles into **GenAI, Agentic AI, and RAG architectures**, focusing on systems that autonomously reason and act.

---

## 🏆 Achievements

- 🥈 **2nd Place, DRDO Young Scientist AI/ML Challenge** — Recognized by the Young Scientist Federation against organization-wide senior scientists.
- 🚀 **Rapid Progression** — Advanced from Trainee Engineer to Software Engineer, earning a Research Fellowship at ADA/DRDO.
- ✅ **98% Field Efficacy** — Successfully shipped and tested real-time models for IAF wearable robotics systems.
- 📄 **Published Research** — Co-authored 2 papers on wearable AI systems in defence R&D; presented to international teams.

---

## 🛠️ Stack

<table>
<tr>
<td valign="top"><b>GenAI / RAG</b></td>
<td>
<img src="https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat&logoColor=white">
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white">
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat&logo=google&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=flat&logoColor=white">
<img src="https://img.shields.io/badge/RAG-Multimodal-blueviolet?style=flat">
</td>
</tr>
<tr>
<td valign="top"><b>AI / ML</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/YOLOv5-00FFFF?style=flat&logoColor=black">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black">
</td>
</tr>
<tr>
<td valign="top"><b>Edge / Embedded</b></td>
<td>
<img src="https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/TensorRT-76B900?style=flat&logo=nvidia&logoColor=white">
<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/Firmware-IMU_Sensors-orange?style=flat">
</td>
</tr>
<tr>
<td valign="top"><b>Backend / API</b></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white">
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white">
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logoColor=white">
</td>
</tr>
<tr>
<td valign="top"><b>Data</b></td>
<td>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/BGE-Embeddings-green?style=flat">
<img src="https://img.shields.io/badge/CLIP-ViT--B/32-412991?style=flat">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white">
</td>
</tr>
</table>

---

## 🚀 Projects

### [Multimodal Identity RAG](https://github.com/AlgoDr/Multimodal-RAG) &nbsp;`V3 — ChromaDB + FastAPI + Gradio GUI +Docker`
Hybrid RAG over personal documents — PDFs and images in a unified ChromaDB index. Text queries route to BGE + Gemini LLM. Visual queries route to CLIP ViT-B/32. Image content searchable via Gemini Vision captions. Diagnosed and bypassed two upstream LlamaIndex retriever bugs. FastAPI REST endpoint (`POST /query`, `POST /ingest`) with incremental document ingestion — ChromaDB HNSW updates in-place.
`LlamaIndex` `ChromaDB` `BGE` `CLIP` `Gemini Vision` `FastAPI` `Python 3.13`

### [AI Newsroom Studio](https://github.com/AlgoDr/AI-Newsroom-Studio) &nbsp;`Tested & Deployed (June-July 2026)`
10-agent LangGraph pipeline: HackerNews trends → published YouTube Short, zero human steps. Conditional state machine with shared `NewsroomState` TypedDict. 4 real data sources (NewsAPI, Reddit PRAW, Google Trends, Serper). Chose LangGraph over CrewAI for explicit state control and 3× lower token usage.
`LangGraph` `Gemini 2.5 Flash` `HeyGen` `YouTube API` `Reddit PRAW`

### [AutoJobApply](https://github.com/AlgoDr/AutoJobapply) &nbsp;`Personal Job Hunting Assistant`
Autonomous job application agent targeting explicit profile matches. Searches Naukri, scores roles locally against a target profile, filters with negative keywords, auto-fills forms. Deployed on GCP Cloud Run with WhatsApp Business API webhook for candidate onboarding. 
`Playwright` `Gemini` `SQLAlchemy` `FastAPI` `GCP Cloud Run`

### [ML LifeCycle Automator](https://github.com/AlgoDr/ML-LifeCycle-Automator-craftai) &nbsp;`Approved By Craftify (Aug 2026)`
9-agent autonomous pipeline that translates Natural Language (NL) requirements directly into trained computer vision models. Orchestrates the complete ML lifecycle for complex vision tasks (Object Detection, Instance Segmentation) with zero human intervention. Specialized agents dynamically handle sequential operations: Requirement Analysis → Architecture Search → Model Ranking → Dataset Generation → Training Execution → Training Log Generation.
`Agentic AI` `Computer Vision` `LLMs` `Object Detection` `Segmentation` `Python`

### [Segmentation](https://github.com/AlgoDr/Segmentation) &nbsp;`Classical ML (Oct 2019)`
Real-time instance segmentation on live webcam/video using Mask-RCNN pretrained on COCO.
`PyTorch` `Mask-RCNN` `OpenCV` `Python`

---

### 📊 GitHub Metrics

<div align="center">

![Deepak's GitHub stats](https://github-readme-stats-fast.vercel.app/api?username=AlgoDr&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF)

</div>
