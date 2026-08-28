<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./light.svg">
  <img alt="Nora Peñaloza Friqui banner" src="./dark.svg" width="100%">
</picture>

[![Portfolio](https://img.shields.io/badge/Portfolio-norapfr.github.io-7C3AED?style=flat-square&logo=googlechrome&logoColor=white)](https://norapfr.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nora-peñaloza-friqui-79879b351)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:npenfriq23@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/norapfr)

</div>

---

## About me

Software Engineer graduated from the Universidad de Sevilla, currently looking for my first junior role. I spent this year interning at NTT DATA, building Angular/TypeScript UI on top of Java/Spring Boot services, and finished a Bachelor's Thesis on depression and suicidal-ideation detection (BERT/SBERT) that got a 10/10.

Outside of coursework I taught myself computer vision from zero by building a volleyball tactical-analysis pipeline (YOLOv8 + ByteTrack), and I've got a few other independent projects below — a reinforcement-learning agent, a generative-art tool driven by live weather data, and some smaller web apps.

I like taking things past the notebook stage: training a model is only half the work, the other half is wrapping it in something that actually runs.

**Looking for:** a junior Software Engineering or ML/NLP role — open to pretty much anything at this point. Full portfolio → **[norapfr.github.io](https://norapfr.github.io/)**

---

## Tech stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Web & Backend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## Projects

### [SocialMindScan](https://github.com/norapfr/SocialMindScan) · Bachelor's Thesis, graded 10/10
NLP system for detecting depression and suicidal ideation in text. Compared six model families (SVM, KNN, Random Forest, CNN, BiGRU, BERT/SBERT) across two Reddit-derived datasets, then shipped the best ones behind a Django + React app paired with a support chatbot. Best results: **F1 0.893** (CNN + SBERT) for depression, **F1 ≈0.909** (SVM + TF-IDF) for suicidal ideation. Companion app: [SocialMind_APP](https://github.com/norapfr/SocialMind_APP).

`Python` `PyTorch` `BERT/SBERT` `Django` `React`

### [VolleyVision AI](https://github.com/norapfr/volleyvision-ai) · computer vision
End-to-end tactical analysis system for volleyball: YOLOv8 for player/ball detection, ByteTrack for multi-object tracking, packaged behind FastAPI + Docker with MLflow for experiment tracking. Models are public on [HuggingFace Hub](https://huggingface.co/norapfr/volleyvision-models). Built with zero prior CV experience going in.

`Python` `YOLOv8` `ByteTrack` `FastAPI` `Docker` `MLflow`

### [LunarEntorno](https://github.com/norapfr/LunarEntorno) · reinforcement learning
A Deep Q-Network agent (experience replay + target networks) trained on OpenAI Gym's LunarLander. Lands successfully in **85%** of evaluation episodes.

`Python` `PyTorch` `OpenAI Gym`

### [atmospherica](https://github.com/norapfr/atmospherica) · generative art
Turns six real-time atmospheric variables (OpenWeatherMap, ERA5) into generative visuals through a parametric grammar. Fully deterministic — reproducible runs via a seeded XORShift RNG.

`Python` `OpenWeatherMap` `ERA5`

---

## Experience

**Software Developer Intern** — NTT DATA · Jan 2026 – Aug 2026
Built and shipped Angular/TypeScript UI components wired into Java/Spring Boot backend services for public-sector client platforms, and wrote reusable Spring Boot + Hibernate business logic backed by SQL. Also touched some Node.js services. Worked sprint-based with Jira, code quality checked through SonarQube.

---

## Education

**B.Sc. Computer Engineering (Software Engineering)** — Universidad de Sevilla, 2022–2026
GPA 8.41/10, with distinction in Infinitesimal & Numerical Calculus, Linear & Numerical Algebra, and Computer Networks. Thesis: *Artificial Intelligence in Mental Health*, graded 10/10.

Also part of the university's Algorithmics Club, competed in Ada Byron Regional 2025.

**Languages:** Spanish (native) · English (B2, Trinity)

---

## GitHub activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=norapfr&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7C3AED&icon_color=22D3EE&text_color=F8FAFC&cache_seconds=86400"/>
<img height="160" src="https://streak-stats.demolab.com?user=norapfr&theme=tokyonight&hide_border=true&background=0D1117&ring=7C3AED&fire=22D3EE&currStreakLabel=F8FAFC"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=norapfr&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7C3AED&text_color=F8FAFC&cache_seconds=86400"/>

<img src="https://raw.githubusercontent.com/norapfr/norapfr/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-norapfr.github.io-7C3AED?style=flat-square&logo=googlechrome&logoColor=white)](https://norapfr.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nora-peñaloza-friqui-79879b351)
[![Email](https://img.shields.io/badge/npenfriq23%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:npenfriq23@gmail.com)

</div>
