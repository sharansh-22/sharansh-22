<div align="center">

# Sharansh Pandey

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=750&height=70&lines=Leakage-free+credit+risk+on+1.34M+loans+%C2%B7+Hallucination-audited+RAG;Negative+results+are+findings+%E2%80%94+I+publish+them;Hypothesis+%E2%86%92+Experiment+%E2%86%92+Evidence+%E2%86%92+Report)](https://github.com/sharansh-22)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sharansh-pandey)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharanshpandey22@gmail.com)

</div>

<br>

---

<br>

## About

**B.Tech AI & Data Science · GGSIPU · 2027**

I built a [leakage-free credit risk platform](https://github.com/sharansh-22/Credit-Risk) on 1.34M loans, a [hallucination-audited RAG system](https://github.com/sharansh-22/Research-OS) for ML research, and a [quantitative research program](https://github.com/sharansh-22/CRIS) that documented negative results instead of hiding them. I care more about reproducibility, leakage-free evaluation, and explainability than benchmark scores.

<br>

---

<br>

## Featured Projects

<br>

<table>
<tr>
<td width="50%" valign="top">

### [Research-OS](https://github.com/sharansh-22/Research-OS)
**Research-Oriented RAG System for ML Research**

A retrieval-augmented generation system with hallucination auditing, research provenance, and math-aware document ingestion.

| Component | Detail |
|:--|:--|
| Retrieval | FAISS + BM25 hybrid |
| Reranking | FlashRank |
| Verification | DeBERTa NLI |
| Auditing | Chain-of-Thought + Hallucination detection |
| Ingestion | Math-aware document pipeline |
| Stack | React · FastAPI |

<!-- METRICS: Replace these with your real numbers -->
<!-- | Papers indexed | 500+ | -->
<!-- | Hallucination detection rate | XX% | -->
<!-- | Avg. retrieval latency | XXms | -->

</td>
<td width="50%" valign="top">

### [Credit Risk Platform](https://github.com/sharansh-22/Credit-Risk)
**Leakage-Free Consumer Credit Risk Modelling**

A rigorous credit risk platform with systematic leakage auditing, out-of-time validation, and economic impact simulation.

| Component | Detail |
|:--|:--|
| Dataset | 1.34M LendingClub loans |
| Modelling | LightGBM · Borrower-only features |
| Explainability | SHAP · Risk segmentation |
| Validation | Out-of-time · Leakage audit |
| Analysis | Stealth defaulter profiling |
| Output | Interactive dashboards · Economic sim |

<!-- METRICS: Replace these with your real numbers -->
<!-- | AUC-ROC | 0.XX | -->
<!-- | Features removed (leakage) | XX | -->
<!-- | Default rate captured (top decile) | XX% | -->

</td>
</tr>
</table>

<br>

<!-- 
  TODO: Add a screenshot of the Credit Risk dashboard here.
  Save the image to your repo and uncomment the line below.
  
  <div align="center">
  <img src="./assets/credit_risk_dashboard.png" alt="Credit Risk Dashboard" width="700"/>
  </div>
-->

<br>

<div align="center">

### [CRIS — Cascade Risk Intelligence System](https://github.com/sharansh-22/CRIS)
**Does Environmental Intelligence Improve Financial Decision Systems?**

</div>

> A quantitative research program investigating whether macroeconomic and market signals improve default prediction beyond borrower-centric models. Negative findings were documented and published rather than discarded.

<table>
<tr>
<td width="50%" valign="top">

#### Research Design
- Controlled comparison: borrower-only vs. macro-augmented models
- Systematic correlation analysis of macroeconomic features
- Cascade architecture for staged signal integration

</td>
<td width="50%" valign="top">

#### Key Findings
- **Borrower-centric models outperformed** direct macro integration
- Macroeconomic signals exhibited strong correlation but **limited incremental predictive value**
- Negative results documented — future directions derived from evidence

</td>
</tr>
</table>

<!-- 
  TODO: Add specific metric comparison. Example:
  
  | Model | AUC-ROC | Gini |
  |:--|:--|:--|
  | Borrower-only | 0.XX | 0.XX |
  | Macro-augmented | 0.XX | 0.XX |
  | Cascade | 0.XX | 0.XX |
-->

<br>

<details>
<summary><b>Research-OS Architecture</b></summary>
<br>

```mermaid
flowchart LR
    subgraph Ingestion
        A[PDF / LaTeX / Markdown] --> B[Math-Aware Parser]
        B --> C[Chunking + Metadata]
    end

    subgraph Retrieval
        D[User Query] --> E[BM25]
        D --> F[FAISS Dense]
        E --> G[Hybrid Merge]
        F --> G
        G --> H[FlashRank Reranker]
    end

    subgraph Verification
        H --> I[LLM Generation]
        I --> J[DeBERTa NLI Check]
        J --> K{Supported?}
        K -- Yes --> L[Response + Provenance]
        K -- No --> M[Hallucination Flag]
    end

    C -.-> E
    C -.-> F
```

</details>

<br>

---

<br>

## Tech Stack

<div align="center">

**Risk & ML** &nbsp;&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-023020?style=flat-square&logo=lightgbm&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6A37?style=flat-square&logo=xgboost&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Data** &nbsp;&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Systems** &nbsp;&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

**Also** &nbsp;&nbsp;
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</div>

<br>

---

<br>

## Research Interests & Direction

<div align="center">

| Domain | Focus | Evidence |
|:--|:--|:--|
| **Credit Risk** | Temporal dynamics, regime-aware default models, PD/LGD/EAD | Credit Risk Platform, CRIS |
| **Financial ML** | Feature leakage, out-of-time validation, model interpretability | Credit Risk Platform |
| **Quantitative Research** | Hypothesis-driven experimentation, negative result documentation | CRIS |
| **Research Infrastructure** | Retrieval architectures, hallucination auditing, provenance | Research-OS |

</div>

<br>

---

<br>

## Next Research Directions

| Question | Domain |
|:--|:--|
| How do credit risk models degrade across economic regimes? | Stochastic processes · Regime detection |
| Can Basel PD/LGD/EAD models be improved with ML while maintaining regulatory interpretability? | Advanced credit risk · Regulatory ML |
| What is the calibration gap between probabilistic ML models and observed default rates? | Bayesian methods · Uncertainty quantification |
| How does order flow asymmetry predict short-term credit spread movements? | Market microstructure · Fixed income |

<br>

---

<br>

## GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sharansh-22&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&ring_color=58A6FF" alt="GitHub Stats" height="180"/>

</div>

<br>

---

<br>

<div align="center">

Open to research collaborations in quantitative finance and financial ML.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sharansh-pandey)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sharanshpandey22@gmail.com)

</div>
