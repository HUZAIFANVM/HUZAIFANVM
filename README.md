<!-- ── Bespoke animated hero (assets/hero.svg, hand-authored SMIL) ────── -->
<img width="100%" src="https://raw.githubusercontent.com/HUZAIFANVM/HUZAIFANVM/main/assets/hero.svg?v=2" alt="Muhammad Huzaifa bin Salman — Junior AI Engineer">

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=800&color=22D3EE&center=true&vCenter=true&width=760&lines=Retrieval+pipelines+that+cite+their+sources;Contrastive+speech+embeddings+for+phoneme+scoring;FastAPI+%2B+serverless+GPU+inference;Production+ML+%E2%80%94+not+just+notebooks" alt="">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/huzaifa-salman-0539602a8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.kaggle.com/huzaifanvm"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"></a>
  <img src="https://komarev.com/ghpvc/?username=HUZAIFANVM&label=Profile%20views&color=22d3ee&style=for-the-badge" alt="views">
</p>

<p align="center"><sub>BS Computer Science (Data Science) — NED University of Engineering &amp; Technology</sub></p>

<br>

## ⚡ About

I build machine learning systems that run in production, not only in notebooks.

My current work spans **RAG and AI orchestration** — retrieval pipelines, LLM applications, multi-step agent workflows — and **applied ML** on speech and audio. Across both, the part I care about is the same: getting models to answer real requests, correctly, inside a real latency budget.

Before that I completed an internship in **AI &amp; Data Analytics**, and a run of data-science projects covering EDA, dimensional modelling, and classical ML.

<br>

## 🔎 How I build

<!-- Bespoke animated capability map (assets/ai-stack.svg) -->
<img width="100%" src="https://raw.githubusercontent.com/HUZAIFANVM/HUZAIFANVM/main/assets/ai-stack.svg" alt="Capability map: classical ML, speech ML and RAG feeding an AI orchestration layer that serves a production API">

<br>

## 🧠 Focus areas

<table>
<tr>
<td width="50%" valign="top">

#### RAG &amp; LLM systems
<sub>Retrieval pipelines · embeddings &amp; vector search · chunking and context design · evaluation of retrieval quality</sub>

</td>
<td width="50%" valign="top">

#### AI orchestration
<sub>Multi-step agent workflows · tool calling · LangChain-based pipelines</sub>

</td>
</tr>
<tr>
<td valign="top">

#### AI / ML engineering
<sub>FastAPI services · serverless GPU inference · latency profiling · deployment and evaluation pipelines</sub>

</td>
<td valign="top">

#### Speech &amp; audio ML
<sub>wav2vec2 / XLSR-53 representations · contrastive fine-tuning · DTW alignment · phoneme-level scoring</sub>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### Data science &amp; BI
<sub>ETL pipelines · star-schema warehouses · Power BI dashboards · classical ML</sub>

</td>
</tr>
</table>

<br>

## 🚀 Selected work

<table>
<tr><td width="34%"><b><a href="https://github.com/HUZAIFANVM/nexuslearn">NexusLearn</a></b></td>
<td>A RAG-powered, AI-native corporate <b>learning management system</b>, built around <b>nine AI-driven features</b> layered over an organisation's own training content.<br><br>
Retrieval-augmented generation grounds every response in the organisation's material rather than relying on free-form model output — the difference between an assistant that cites your handbook and one that invents plausible policy.<br><br>
<sub><code>RAG</code> <code>LLM</code> <code>LangChain</code></sub></td></tr>

<tr><td><b><a href="https://github.com/HUZAIFANVM/qaida-project">Arabic Qaida Pronunciation Scorer</a></b></td>
<td>Scores a learner's recitation against a teacher's reference at phoneme level — including the short vowel marks (<i>harakat</i>) that ordinary speech-to-text discards.<br><br>
Contrastive-fine-tuned <b>XLSR-53</b> embeddings with frame-level cosine <b>DTW</b> alignment and per-lesson decision thresholds, over 692 reference recordings across 16 lessons. An initial Whisper transcription approach was measured, shown to be structurally unable to represent the target distinctions, and replaced with metric learning.<br><br>
Served as serverless GPU inference with automatic CPU fallback. Profiling the CPU path found an <code>fp16</code> cast that x86 emulates rather than accelerates — removing it cut latency <b>4.3s → 0.30s</b> with identical embeddings.<br><br>
<sub><code>PyTorch</code> <code>Transformers</code> <code>librosa</code> <code>FastAPI</code> <code>Modal</code> <code>Next.js</code></sub></td></tr>

<tr><td><b><a href="https://github.com/HUZAIFANVM/Pakistan-Real-Estate-Warehouse-ML-Dashboard">Pakistan Real Estate Warehouse &amp; ML Dashboard</a></b></td>
<td>End-to-end DWBI solution: ETL into a star schema (one fact table, four conformed dimensions), price modelling, and a Power BI dashboard alongside a Python app.<br><br>
<sub><code>pandas</code> <code>scikit-learn</code> <code>Power BI</code> <code>Streamlit</code></sub></td></tr>

<tr><td><b><a href="https://github.com/HUZAIFANVM/Document_Analysis">Document Analysis</a></b></td>
<td>Full-stack document analysis application — TypeScript / Next.js frontend against a Python API backend.<br><br>
<sub><code>Next.js</code> <code>TypeScript</code> <code>Python</code></sub></td></tr>

<tr><td><b><a href="https://github.com/HUZAIFANVM/Pneumonia-Detection">Pneumonia Detection</a></b></td>
<td>Chest X-ray image classification for pneumonia screening, trained on medical imaging data.<br><br>
<sub><code>Python</code> <code>CNN</code> <code>Jupyter</code></sub></td></tr>

<tr><td><b><a href="https://github.com/HUZAIFANVM/Book-Recommendation-System">Book Recommendation System</a></b></td>
<td>Collaborative-filtering recommender with precomputed item-similarity matrices, served through a Python app.<br><br>
<sub><code>pandas</code> <code>scikit-learn</code> <code>Streamlit</code></sub></td></tr>
</table>

<br>

## 🛠 Tools

<table>
<tr><td><b>LLM / RAG</b></td><td>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
</td></tr>
<tr><td><b>ML / DL</b></td><td>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
</td></tr>
<tr><td><b>Data</b></td><td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black">
</td></tr>
<tr><td><b>Serving / deploy</b></td><td>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Modal-7FEE64?style=flat-square&logo=modal&logoColor=black">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
</td></tr>
</table>

<br>

<br>

<p align="center"><sub>Open to collaborating on RAG, LLM and applied ML projects.</sub></p>
