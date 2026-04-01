<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,50:3BBFCE,100:F7931E&height=220&section=header&text=Tahiana+Andriambahoaka&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=MLOps+Engineer+·+Telecom+Paris+IP+Paris&descSize=18&descAlignY=60&animation=fadeIn" width="100%"/>
</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=MLOps+Engineer;NLP+%26+Deep+Learning;Big+Data+Pipelines;From+notebooks+to+production+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:tahiana.hajanirina@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/tahiana-andriambahoaka"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/tahianahajanirina"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

```python
tahiana = {
    "role"      : "MLOps Engineer · NLP & Deep Learning",
    "formation" : "MS® IA Expert Data & MLops — Télécom Paris (IP Paris)",
    "location"  : "Paris, France 🇫🇷",
    "languages" : ["Français 🇫🇷", "Malgache 🇲🇬", "Anglais 🇬🇧"],
    "focus"     : ["MLOps en production", "NLP & Transformers", "Big Data Pipelines"],
    "looking"   : "Stage / CDI MLOps & ML Engineering — Île-de-France",
    "motto"     : "Je ne livre pas des modèles. Je livre des systèmes qui tiennent en prod. 🚀",
}
```

---

## 🚀 Projets phares

<div align="center">
  <img src="projects-carousel.gif" alt="Projets phares — carousel animé" width="100%"/>
</div>

<!-- Détail des projets (pour référencement) -->
<details>
<summary><b>Voir le détail des projets</b></summary>

<table>
<tr>
<td width="50%" valign="top">

### 🔍 FraudGuard
> **Détecter la fraude bancaire avant qu'elle arrive.**

Pipeline MLOps complet de bout en bout : ingestion, entraînement automatisé, API de prédiction temps réel, monitoring production — le tout orchestré avec Airflow et containerisé avec Docker.

- 🧠 Modèle LightGBM · F1 = 0.711 · ROC-AUC = 0.887
- ⚙️ Retraining automatique déclenché par Airflow
- 📊 Dashboard Grafana + alertes Prometheus en temps réel
- 🚀 API FastAPI · 63 tests · déployable sur Kubernetes

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

[![Voir le repo](https://img.shields.io/badge/→_Voir_le_repo-black?style=for-the-badge&logo=github)](https://github.com/tahianahajanirina/Fraudguard)

</td>
<td width="50%" valign="top">

### 🏷️ HieraCat &nbsp; ![](https://img.shields.io/badge/EN_COURS-brightgreen?style=flat-square)
> **Classer des millions de produits, automatiquement et avec précision.**

Système de classification hiérarchique profonde pour catégoriser des produits e-commerce à grande échelle — sur deux niveaux : catégorie principale et sous-catégorie fine.

- 🗂️ 157 catégories · 6 059 sous-catégories
- 🤖 CamemBERT fine-tuné · 3 variantes (Local, Global, Nested)
- ⚡ Entraînement distribué multi-GPU sur cluster SLURM
- 📈 Tracking MLflow · explicabilité Gradient × Input · 77 tests

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![SLURM](https://img.shields.io/badge/SLURM-HPC-green?style=for-the-badge)
![CamemBERT](https://img.shields.io/badge/CamemBERT-NLP-orange?style=for-the-badge)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✈️ SkySafe Datalake
> **Surveiller le trafic aérien français en temps réel avec le Big Data.**

Pipeline Big Data qui ingère toutes les minutes les positions GPS des avions, les croise avec la météo, et calcule un score de risque aéronautique affiché sur un dashboard interactif.

- 📡 Ingestion temps réel · OpenSky API · proxy Serverless Scaleway
- 🌊 Architecture Data Lake 4 couches sur Amazon S3
- 🤖 Classification phases de vol K-Means (Spark MLlib) + anomalies
- 📊 Dashboard Kibana · Score de risque FAA 0–100 · 29 tests

![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)

[![Voir le repo](https://img.shields.io/badge/→_Voir_le_repo-black?style=for-the-badge&logo=github)](https://github.com/tahianahajanirina/skysafe-datalake)

</td>
<td width="50%" valign="top">

### 🍽️ MangetaMain
> **Recommander des recettes personnalisées grâce au Machine Learning.**

Plateforme ML complète d'analyse et de recommandation de recettes : clustering utilisateurs, analyse nutritionnelle, analyse de sentiment et recommandation collaborative.

- 👤 Clustering utilisateurs & recettes (K-Means)
- 🥗 Tagger nutritionnel automatique
- 💬 Analyse de sentiment fine-tunée sur les avis culinaires
- 🤖 Chatbot Gemini · Recommandation SVD · 124 tests

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

[![Voir le repo](https://img.shields.io/badge/→_Voir_le_repo-black?style=for-the-badge&logo=github)](https://github.com/tahianahajanirina/mangetamain)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 DocRAG-MD
> **Répondre à des questions médicales complexes avec des agents LLM spécialisés.**

Plateforme RAG multi-agents production-grade pour la Q&A clinique : 4 agents LangGraph spécialisés (diagnostic, pharmacologie, général, évaluateur), GraphRAG sur PrimeKG (100k+ nœuds, 4M+ arêtes), Self-RAG et CRAG pour la fidélité des réponses.

- 🧠 4 LLMs au choix : Gemini 2.5 Flash/Pro, BioMistral 7B local, GPT-4o
- 📚 301k chunks StatPearls + 36M+ articles PubMed (API live)
- 🔍 GraphRAG · Self-RAG · CRAG · Deep Search multi-step
- 📊 Observabilité Langfuse v3 · 62%+ accuracy MedMCQA · 11 services Docker

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge&logo=qdrant&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

[![Voir le repo](https://img.shields.io/badge/→_Voir_le_repo-black?style=for-the-badge&logo=github)](https://github.com/tahianahajanirina/DocRAG-MD)

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>
</details>

---

## 🛠️ Stack technique

**ML & NLP**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white)

**MLOps & Infrastructure**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Observabilité**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**Big Data**

![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**HPC**

![SLURM](https://img.shields.io/badge/SLURM-Multi--GPU-4CAF50?style=for-the-badge)

---

## 📊 Stats GitHub

<p align="center">
  <img src="https://raw.githubusercontent.com/tahianahajanirina/tahianahajanirina/main/profile-summary-card-output/tokyonight/0-profile-details.svg" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/tahianahajanirina/tahianahajanirina/main/profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="32%"/>
  <img src="https://raw.githubusercontent.com/tahianahajanirina/tahianahajanirina/main/profile-summary-card-output/tokyonight/2-most-commit-language.svg" width="32%"/>
  <img src="https://raw.githubusercontent.com/tahianahajanirina/tahianahajanirina/main/profile-summary-card-output/tokyonight/3-stats.svg" width="32%"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/tahianahajanirina/tahianahajanirina/main/profile-summary-card-output/tokyonight/4-productive-time.svg" width="50%"/>
</p>

---

[![footer](https://capsule-render.vercel.app/api?type=waving&color=0:F7931E,50:3BBFCE,100:6C63FF&height=120&section=footer)](https://github.com/tahianahajanirina)
