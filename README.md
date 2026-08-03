<div align="center">

<!-- BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:1a202c&height=200&section=header&text=Faber%20David%20Sanchez%20Martinez&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Quantitative%20Developer%20%7C%20Systems%20Engineer&descAlignY=55&descSize=20&descColor=a0aec0" width="100%" alt="Faber David Sanchez Martinez Header" />

<br>

<!-- TYPEWRITER SUBTITLE -->
<a href="https://github.com/Fabersanchez">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=500&size=16&duration=4000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Architecting+High-Performance+Trading+Systems;Engineering+Multi-Agent+AI+Architectures;Building+Robust+Data+Pipelines+in+Python" alt="Typing SVG" />
</a>

<br>

<!-- PROFESSIONAL BADGES -->
<a href="https://linkedin.com/in/fabersanchez">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/Fabersanchez">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="mailto:your.email@domain.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="#">
  <img src="https://img.shields.io/badge/Curriculum_Vitae-25292E?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="CV" />
</a>

<br><br>

</div>

---

## 🔬 Executive Summary

I am a **Systems Engineer and Quantitative Developer** specializing in the intersection of **Artificial Intelligence** and **Algorithmic Trading**. 

My engineering focus is on architecting high-frequency data pipelines, multi-threaded execution engines, and institutional-grade decision models. I build systems capable of solving complex, real-world financial problems through deterministic execution, rigorous statistical validation, and scalable backend infrastructure. 

---

## ⚙️ Core Architecture & Tech Stack

<div align="center">

| Focus Area | Core Technologies |
| :--- | :--- |
| **Language Ecosystem** | `Python (CPython/PyPy)` • `MQL5` • `SQL` • `Bash` |
| **Quantitative & AI** | `NumPy` • `Pandas` • `PyTorch` • `Scikit-Learn` • `SciPy` |
| **Distributed Backend** | `FastAPI` • `Asyncio` • `PostgreSQL` • `REST/WebSockets` |
| **DevOps & Infrastructure**| `Docker` • `Git / GitHub Actions` • `Linux (RHEL/Ubuntu)` |

<br>

<!-- TECH STACK BADGES (FLAT-SQUARE HIGH-CONTRAST) -->
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## 🚀 Featured Engineering

<table bordercolor="#30363d">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ Sentinel V19</h3>
      <p align="center"><i>Autonomous AI Trading Engine</i></p>
      <hr>
      <p>A multi-threaded algorithmic trading platform engineered for institutional market analysis, autonomous execution, and dynamic risk control.</p>
      <ul>
        <li><b>Hybrid Architecture:</b> Python core orchestration bridged with MQL5 for highly efficient, low-latency market execution.</li>
        <li><b>Multi-Agent Engine:</b> Specialized concurrent agents handling regime detection, signal generation, and risk validation.</li>
        <li><b>XAI Integration:</b> Explainable AI components ensuring full auditability of decision logic and margin adjustments.</li>
      </ul>
      <p><b>Stack:</b> <code>Python</code> • <code>MQL5</code> • <code>Asyncio</code> • <code>PostgreSQL</code></p>
      <p align="center"><a href="https://github.com/Fabersanchez/Sentinel"><b>[ View Architecture ]</b></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📊 QuantLab</h3>
      <p align="center"><i>Quantitative Research Framework</i></p>
      <hr>
      <p>An end-to-end quantitative research environment built to design, backtest, and statistically validate predictive models.</p>
      <ul>
        <li><b>Vectorized Engine:</b> High-performance backtesting handling tick and bar data with absolute zero look-ahead bias.</li>
        <li><b>Advanced Analytics:</b> Automated calculation of Sharpe ratios, Maximum Drawdown, VaR, and Monte Carlo stress testing.</li>
        <li><b>Custom Indicators:</b> Proprietary mathematical implementations of complex quantitative metrics.</li>
      </ul>
      <p><b>Stack:</b> <code>Python</code> • <code>Pandas</code> • <code>SciPy</code> • <code>FastAPI</code></p>
      <p align="center"><a href="https://github.com/Fabersanchez/QuantLab"><b>[ View Framework ]</b></a></p>
    </td>
  </tr>
</table>

---

## 📐 System Blueprint: Sentinel V19

```mermaid
graph TD
    classDef market fill:#0d1117,stroke:#30363d,stroke-width:1px,color:#c9d1d9
    classDef engine fill:#161b22,stroke:#58a6ff,stroke-width:1.5px,color:#f0f6fc
    classDef exec fill:#092e20,stroke:#2ea043,stroke-width:1.5px,color:#f0f6fc
    classDef db fill:#21262d,stroke:#8b949e,stroke-width:1px,color:#c9d1d9

    A[Live Market Feed] -->|Tick Data| B(Ingestion Pipeline)
    B --> C{Async Event Bus}
    
    C -->|Stream| D[Feature Engineering]
    C -->|Stream| E[AI Regime Agent]
    
    D --> F[Multi-Agent Signal Matrix]
    E --> F
    
    F -->|Raw Alpha| G[Risk Management & Position Sizing]
    G -->|Validated Order| H[MQL5 Low-Latency Bridge]
    
    H -->|Execute| I[Exchange API]
    
    G -->|Audit Trail| J[(PostgreSQL Cluster)]
    I -->|Fill Reports| J

    class A,I market;
    class B,C,D,E,F,G engine;
    class H exec;
    class J db;

<p align="center">

⭐ Thanks for visiting my profile!

</p>
