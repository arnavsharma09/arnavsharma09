<div align="center">

# Arnav Sharma
**Data Science & ML Engineer · Multi-Agent LLMs · Statistical Systems**  
<sub>B.Tech in Mechanical Engineering '28 @ <b>IIT Jodhpur</b> · Delhi, India</sub>

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-arnavsharma09.github.io-38BDF8?style=for-the-badge&labelColor=0D1117)](https://arnavsharma09.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-arnav--sharma09-818CF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://linkedin.com/in/arnav-sharma09)
[![Email](https://img.shields.io/badge/Email-arnavsharma090406%40gmail.com-34D399?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:arnavsharma090406@gmail.com)

</div>

---

```python
class ArnavSharma:
    def __init__(self):
        self.education = "B.Tech @ IIT Jodhpur (2024–2028)"
        self.focus     = ["Multi-Agent LLM Systems", "Adversarial AI Security", "Classical ML & Statistics"]
        self.exploring = ["LLM Guardrail Design", "Deep Learning Architectures", "Open Source (Polars, Streamlit)"]
        self.standard  = "Pre-commit statistical tests, stress-test under edge cases, never hide error bars."
```

---

### ⚡ Featured Systems

> #### 🛡️ [Agent Red-Team](https://github.com/arnavsharma09/agent-redteam) — *Adaptive UCB1 Red-Team Harness for LLM Agents*
> `Python` · `Ollama (Qwen2.5-7B)` · `UCB1 Bandit` · `Wilson CIs` · `pytest`
> - **Adversarial Search & Taint Guardrail:** UCB1 bandit searches **144 prompt-injection recipes** against local Qwen2.5-7B. An argument-provenance taint guardrail cut exfiltration from **61/350 → 0/250 episodes**, with **0/36** benign tasks blocked (Wilson 95% UB: 9.6%) and 35/36 task completion.
> - ** Iterative Defense Hardening:** Exposed a gap in my own defense (file reads were trusted; 15/31 exec episodes got through), patched it, and closed a base64 self-decoding bypass (**0/100 executions after**). Backed by **191 passing unit tests**.

> #### 🧠 [AutoInsight](https://github.com/arnavsharma09/AutoInsight) — *7-Node Multi-Agent Autonomous Statistical Pipeline*
> `LangGraph` · `Polars` · `ChromaDB` · `Anthropic Claude API` · `FastAPI` · `Streamlit` · `Docker`
> - **Self-Correcting Workflow:** `Profiler → Router → Planner → [Human Gate] → Sandbox → Critic → Reporter` pipeline indexing **60+ statistical tests**, where a Critic agent auto-switches tests when assumptions fail (e.g., **ANOVA → Kruskal-Wallis** on Shapiro-Wilk rejection).
> - **Zero-Hallucination Execution:** All LLM-generated code executes inside an **AST-scanned sandbox**, with final report claims verified against computed metrics via **DeepEval (18/18 passing)**.

> #### 📊 [RetainIQ](https://github.com/arnavsharma09/RetainIQ) — *Customer Retention & RFM Star-Schema Pipeline*
> `PostgreSQL` · `SQL` · `Python (scipy, statsmodels)` · `Power BI` · `Docker`
> - **Dimensional Modeling:** Engineered a PostgreSQL star schema over **99,441 e-commerce orders** across 9 relational tables, segmenting **~95K customers** into 7 actionable value tiers via quintile-scored RFM.
> - **Pre-Committed Hypothesis Testing:** Isolated delivery delay's impact on satisfaction independent of distance using **Mann-Whitney U** (**4.31 vs 3.75 rating, p < 0.001**), uncovering a **3.04% repeat rate** and **62.5% revenue concentration** in 3/27 states.

> #### 💳 [Credit Risk Prediction System](https://github.com/arnavsharma09/credit-risk-prediction) — *Explainable Default Scoring Pipeline* · **[Live Streamlit App ↗](https://arnavsharma-credit-risk.streamlit.app)**
> `Python` · `Scikit-learn` · `XGBoost` · `SHAP` · `SMOTE` · `Streamlit`
> - **Imbalanced Learning & Benchmarking:** Trained on **150K+ borrower records** (93.7% class imbalance) using fold-isolated SMOTE inside stratified cross-validation; benchmarked **Random Forest (0.8588 AUC-ROC)**, **XGBoost (0.8492)**, and **Logistic Regression (0.8234)**.
> - **Model Explainability:** Integrated **SHAP tree explainers** to surface per-applicant risk drivers in an interactive real-time scoring web app.

---

### 🛠️ Technical Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,c,postgres,pytorch,tensorflow,sklearn,fastapi,docker,git,linux&theme=dark" alt="Tech Stack Icons" />

<br/><br/>

| Domain | Core Tools & Libraries |
| :--- | :--- |
| **LLM & Multi-Agent** | `LangGraph` · `LangChain` · `Anthropic Claude API` · `ChromaDB` · `Ollama` · `RAG` · `DeepEval` · `MCP` · `Prompt-Injection Defense` |
| **ML & Deep Learning** | `Scikit-learn` · `XGBoost` · `Random Forest` · `PyTorch` · `TensorFlow` · `Optuna` · `SHAP` · `SMOTE` · `UCB1 Bandits` |
| **Data, Stats & MLOps** | `Polars` · `Pandas` · `NumPy` · `PostgreSQL` · `scipy` · `statsmodels` · `Power BI` · `FastAPI` · `Streamlit` · `Docker` · `MLflow` · `pytest` |

</div>
