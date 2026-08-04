<h1 align="center">Muhammad Huzaifa bin Salman</h1>

<p align="center">
  <b>Junior AI Engineer</b> &nbsp;·&nbsp; Speech &amp; Applied Machine Learning
</p>

<p align="center">
  BS Computer Science (Data Science) — NED University of Engineering &amp; Technology
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/huzaifa-salman-0539602a8">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.kaggle.com/huzaifanvm">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle">
  </a>
</p>

---

I build machine learning systems that run in production, not only in notebooks.

My current work is in **speech and audio ML** — self-supervised representations, metric learning, and getting models to answer real requests inside a real latency budget. Before that I completed an internship in **AI &amp; Data Analytics**, and a run of data-science projects covering EDA, dimensional modelling, and classical ML.

### Focus areas

**Speech &amp; audio ML** — wav2vec2 / XLSR-53 representations, contrastive fine-tuning, DTW alignment, phoneme-level scoring

**ML engineering** — FastAPI services, serverless GPU inference, latency profiling, deployment and evaluation pipelines

**Data science &amp; BI** — ETL pipelines, star-schema warehouses, Power BI dashboards, classical ML

---

### Selected work

<table>
<tr><td width="34%"><b>Arabic Qaida Pronunciation Scorer</b><br><sub><i>private</i></sub></td>
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

<tr><td><b><a href="https://github.com/HUZAIFANVM/Customer-Segmentation">Customer Segmentation</a></b></td>
<td>K-means clustering over customer behaviour features, with the fitted model persisted for serving.<br><br>
<sub><code>scikit-learn</code> <code>pandas</code> <code>Streamlit</code></sub></td></tr>
</table>

---

### Tools

**ML / DL** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Data** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Serving / deploy** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-7FEE64?style=flat-square&logo=modal&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=HUZAIFANVM&show_icons=true&hide_border=true&hide_title=true&include_all_commits=true&count_private=true" alt="stats">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HUZAIFANVM&layout=compact&hide_border=true&langs_count=7" alt="top languages">
</div>

<p align="center"><sub>Open to collaborating on applied ML and speech projects.</sub></p>
