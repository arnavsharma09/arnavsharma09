<div align="left">

# Arnav Sharma
**Data Science & ML Engineer building `Multi-Agent LLMs` & `Statistical Systems`**  
*B.Tech in Mechanical Engineering '28 · Indian Institute of Technology (IIT), Jodhpur*

[![Portfolio](https://img.shields.io/badge/Portfolio-arnavsharma09.github.io-38BDF8?style=flat-square&logo=googlechrome&logoColor=white)](https://arnavsharma09.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arnav--sharma09-818CF8?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/arnav-sharma09)
[![Email](https://img.shields.io/badge/Email-arnavsharma090406%40gmail.com-34D399?style=flat-square&logo=gmail&logoColor=white)](mailto:arnavsharma090406@gmail.com)

</div>

---

### About Me

- 🎓 Undergraduate at **IIT Jodhpur** focused on building reliable machine learning pipelines and production-grade AI systems.
- 🧠 Working across **classical ML**, **multi-agent LLM workflows**, **statistical inference**, and **adversarial AI security**.
- 🔬 Currently exploring **LLM guardrails & red-teaming** and **deep learning architectures**, while contributing to **open-source Python data tools**.
- ⚡ I build from first principles—stress-testing models under edge cases, pre-committing statistical tests, and designing systems that stay interpretable.

---

### Featured Systems & Projects

| System | Architecture & Stack | Key Engineering & Statistical Results | Links |
| :--- | :--- | :--- | :---: |
| **[Agent Red-Team](https://github.com/arnavsharma09/agent-redteam)**<br>*Adaptive LLM Red-Team Harness* | `Python` `Ollama (Qwen2.5-7B)` `UCB1 Bandit` `Wilson CIs` `pytest` | • UCB1 bandit searches **144 prompt-injection recipes** (17.4% exfiltration & 37.0% destructive undefended over 350 episodes)<br>• Argument-provenance taint guardrail cut exfiltration from **61/350 → 0/250** with **0/36** benign task blocks (Wilson 95% UB: 9.6%)<br>• Closed file-trust & base64 self-decoding bypasses (**0/100** executions after); **191 passing unit tests** | [Repo ↗](https://github.com/arnavsharma09/agent-redteam) |
| **[AutoInsight](https://github.com/arnavsharma09/AutoInsight)**<br>*7-Node Multi-Agent Statistical Pipeline* | `LangGraph` `Polars` `ChromaDB` `Claude API` `FastAPI` `Streamlit` `Docker` | • Autonomous `Profiler → Router → Planner → [Human Gate] → Sandbox → Critic → Reporter` workflow<br>• Hybrid rule + semantic router indexes **60+ statistical tests**; Critic loop auto-switches methodology when normality fails (e.g., ANOVA → Kruskal-Wallis)<br>• AST-scanned sandbox + **18/18 passing DeepEval faithfulness tests** | [Repo ↗](https://github.com/arnavsharma09/AutoInsight) |
| **[RetainIQ](https://github.com/arnavsharma09/RetainIQ)**<br>*Customer Retention & RFM Pipeline* | `PostgreSQL` `SQL` `scipy` `statsmodels` `Power BI` `Docker` | • Modeled **99,441 orders** across 9 relational tables into a PostgreSQL star schema with quintile RFM segmentation across **~95K customers**<br>• Pre-committed **Mann-Whitney U test** (after Shapiro-Wilk rejection) isolated delivery delay impact (**4.31 vs 3.75 rating, p < 0.001**)<br>• Uncovered **3.04% repeat rate** and **62.5% revenue concentration** in 3/27 states | [Repo ↗](https://github.com/arnavsharma09/RetainIQ) |
| **[Credit Risk Prediction](https://github.com/arnavsharma09/credit-risk-prediction)**<br>*Explainable Default Scoring System* | `Python` `Scikit-learn` `XGBoost` `SHAP` `SMOTE` `Streamlit` | • Trained on **150K+ borrower records** with severe class imbalance (93.7%), applying fold-isolated SMOTE during cross-validation<br>• Benchmarked Random Forest (**0.8588 AUC-ROC**), XGBoost (**0.8492**), and Logistic Regression (**0.8234**)<br>• Deployed real-time **SHAP explainability** scoring dashboard | [Live App ↗](https://arnavsharma-credit-risk.streamlit.app)<br>[Repo ↗](https://github.com/arnavsharma09/credit-risk-prediction) |

---

### Technical Arsenal

**LLM & Multi-Agent Systems**  
![LangGraph](https://img.shields.io/badge/LangGraph-111622?style=flat-square&logo=langchain&logoColor=38BDF8)
![LangChain](https://img.shields.io/badge/LangChain-111622?style=flat-square&logo=langchain&logoColor=818CF8)
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude_API-111622?style=flat-square&logo=anthropic&logoColor=F8FAFC)
![ChromaDB](https://img.shields.io/badge/ChromaDB-111622?style=flat-square&logoColor=38BDF8)
![Ollama](https://img.shields.io/badge/Ollama-111622?style=flat-square&logo=ollama&logoColor=F8FAFC)
![DeepEval](https://img.shields.io/badge/DeepEval-111622?style=flat-square&logoColor=34D399)
![AI Security](https://img.shields.io/badge/LLM_Red--Teaming_%26_Guardrails-111622?style=flat-square&logoColor=38BDF8)
![MCP](https://img.shields.io/badge/Model_Context_Protocol_(MCP)-111622?style=flat-square&logoColor=818CF8)

**Machine Learning & Deep Learning**  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-111622?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![XGBoost](https://img.shields.io/badge/XGBoost-111622?style=flat-square&logoColor=38BDF8)
![PyTorch](https://img.shields.io/badge/PyTorch-111622?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/TensorFlow-111622?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![Optuna](https://img.shields.io/badge/Optuna-111622?style=flat-square&logoColor=818CF8)
![SHAP](https://img.shields.io/badge/SHAP_%26_SMOTE-111622?style=flat-square&logoColor=34D399)
![UCB1 Bandits](https://img.shields.io/badge/Multi--Armed_Bandits_(UCB1)-111622?style=flat-square&logoColor=38BDF8)

**Data Engineering, Statistics & MLOps**  
![Python](https://img.shields.io/badge/Python-111622?style=flat-square&logo=python&logoColor=38BDF8)
![SQL](https://img.shields.io/badge/PostgreSQL_%26_SQL-111622?style=flat-square&logo=postgresql&logoColor=818CF8)
![C++](https://img.shields.io/badge/C_%2F_C++-111622?style=flat-square&logo=cplusplus&logoColor=00599C)
![Polars](https://img.shields.io/badge/Polars-111622?style=flat-square&logo=polars&logoColor=CD792C)
![Pandas](https://img.shields.io/badge/Pandas_%26_NumPy-111622?style=flat-square&logo=pandas&logoColor=F8FAFC)
![SciPy](https://img.shields.io/badge/scipy_%26_statsmodels-111622?style=flat-square&logo=scipy&logoColor=38BDF8)
![FastAPI](https://img.shields.io/badge/FastAPI-111622?style=flat-square&logo=fastapi&logoColor=009688)
![Streamlit](https://img.shields.io/badge/Streamlit-111622?style=flat-square&logo=streamlit&logoColor=FF4B4B)
![Docker](https://img.shields.io/badge/Docker-111622?style=flat-square&logo=docker&logoColor=2496ED)
![MLflow](https://img.shields.io/badge/MLflow-111622?style=flat-square&logo=mlflow&logoColor=0194E2)
![Power BI](https://img.shields.io/badge/Power_BI-111622?style=flat-square&logo=powerbi&logoColor=F2C811)
![pytest](https://img.shields.io/badge/pytest-111622?style=flat-square&logo=pytest&logoColor=0A9EDC)
