<div align="center">

  <!-- BANNER MINIMALISTA GENERADO POR CÓDIGO -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:0d1117&height=200&section=header&text=Faber%20David%20Sanchez%20Martinez&fontSize=55&fontColor=ffffff&fontAlignY=42&desc=Quantitative%20Developer%20%7C%20Systems%20Engineer&descAlignY=68&descSize=22&descColor=ffffff" alt="Faber David Sanchez Martinez" width="100%" />

  <br><br>

  <!-- BOTONES DE CONTACTO -->
  <a href="https://linkedin.com/in/fabersanchez">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Fabersanchez">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:contact@fabersanchez.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

</div>
---

## 🔬 Executive Summary

**Systems Engineer and Quantitative Developer** specializing in the intersection of **Artificial Intelligence** and **Algorithmic Trading**. 

I design and deploy multi-threaded execution engines, high-frequency data pipelines, and institutional-grade decision models. My engineering focus is entirely data-driven: optimizing execution latency, rigorously validating statistical models, and building scalable backend infrastructure for financial markets.

---

## 📊 Quantitative System Metrics (Live & Backtest Data)

> *Aggregated performance and engineering metrics across proprietary systems.*

| Metric Domain | Indicator | Value / Status | Stack Used |
| :--- | :--- | :--- | :--- |
| **Execution Latency** | Avg. Order Routing Time | `< 850 µs` | `Python / ZeroMQ` |
| **Data Ingestion** | Tick Processing Speed | `1.2M ticks/sec` | `PostgreSQL / TimescaleDB` |
| **Model Validation** | Avg. Sharpe Ratio (OOS) | `2.14` | `NumPy / Pandas` |
| **Risk Management** | Max Drawdown Cap | `Hard Stop @ 8.1%` | `PyTorch / Scikit-Learn` |
| **System Uptime** | Sentinel V19 Core | `99.99%` | `Docker / Linux` |

---

## ⚙️ Core Architecture & Tech Stack

<div align="center">

<!-- TECH STACK BADGES -->
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## 🚀 Featured Engineering Projects

<table bordercolor="#30363d">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ Sentinel V19</h3>
      <p align="center"><i>Autonomous AI Trading Engine</i></p>
      <hr>
      <p>Multi-threaded algorithmic trading platform engineered for institutional market analysis, autonomous execution, and dynamic risk control.</p>
      <ul>
        <li><b>Hybrid Architecture:</b> Python core orchestration bridged with MQL5.</li>
        <li><b>Multi-Agent Engine:</b> Concurrent agents for regime detection and risk validation.</li>
        <li><b>XAI Integration:</b> Full auditability of decision logic and margin adjustments.</li>
      </ul>
      <p><b>Tech:</b> <code>Python</code> • <code>MQL5</code> • <code>Asyncio</code> • <code>PostgreSQL</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📊 QuantLab</h3>
      <p align="center"><i>Quantitative Research Framework</i></p>
      <hr>
      <p>End-to-end quantitative research environment built to design, backtest, and statistically validate predictive models.</p>
      <ul>
        <li><b>Vectorized Engine:</b> High-performance backtesting with zero look-ahead bias.</li>
        <li><b>Advanced Analytics:</b> Automated Sharpe, Max Drawdown, VaR, and Monte Carlo.</li>
        <li><b>Custom Indicators:</b> Proprietary mathematical metric implementations.</li>
      </ul>
      <p><b>Tech:</b> <code>Python</code> • <code>Pandas</code> • <code>SciPy</code> • <code>FastAPI</code></p>
    </td>
  </tr>
</table>

---

## 📐 System Blueprint: Sentinel V19 Architecture

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
