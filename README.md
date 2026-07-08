# Rameen Shakeel

**Marketing & Customer Analytics | MS Business Analytics, University of Illinois Chicago**

I build analytics that answer specific commercial questions: customer segmentation projected to lift campaign response 15% → 24% on 65% less send volume, churn and lead-scoring models at 0.88–0.90 AUC with plain-English explanations for sales teams, marketing mix models validated against ground truth, and an AI risk-monitoring pipeline built for TransUnion.

📫 [rameensh98@gmail.com](mailto:rameensh98@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rameen-shakeel-16442a221/)

---

## 🚀 Featured Projects

### 🛡️ [Android Risk Agents — AI Risk Intelligence Platform](https://github.com/rameenshakeell/android-risk-agents)
**Graduate capstone, built in partnership with TransUnion.** A production-style, multi-agent AI pipeline that autonomously monitors 10+ Android ecosystem sources (security bulletins, CVEs, Play policy changes), classifies changes into risk categories using embeddings, and generates analyst-ready insights through a two-agent LLM workflow (triage → deep analysis with RAG). Delivered as an executive Streamlit dashboard with a grounded chatbot, risk quadrant charts, and a triage action queue, running on a scheduled CI/CD pipeline.

`Python` `LLM Agents` `RAG` `pgvector / Supabase` `Streamlit` `GitHub Actions`

### 🎯 [Customer Segmentation & Campaign Targeting](https://github.com/rameenshakeell/Marketing-Analytics---Independant-Project)
End-to-end campaign analytics on 2,240 customer records: cleaning and imputation, SQL business analysis, K-Means segmentation into four personas, and a Tableau dashboard. Found that **22% of customers drive ~50% of revenue**, and built a targeting strategy projected to **lift response rate from 15% → 24% while cutting send volume by 65%**.

`Python` `SQL` `K-Means` `Tableau`

### 📊 [Marketing Mix Modeling: Channel Attribution & Its Limits](https://github.com/rameenshakeell/marketing-mix-modeling)
Built an MMM with adstock, saturation, and seasonality controls to attribute weekly sales across TV, search, social, and email, then **validated it against known ground truth** using a synthetic dataset I generated. Achieved **4.8% test MAPE** on holdout weeks, correctly attributed search and email, and diagnosed exactly *why* TV/social attribution fails (channel collinearity) the real-world reason MMM gets paired with incrementality testing.

`Python` `Ridge Regression` `scikit-learn` `SciPy`

### 🔮 [CRM Predictive Scoring: Lead Conversion & Churn](https://github.com/rameenshakeell/CRM_Project)
Two predictive models (lead scoring: **0.88 AUC**; churn: **0.90 AUC**) with disciplined model selection, Logistic Regression chosen over XGBoost when the AUC gap was within cross-validation noise, prioritizing interpretability. Each prediction gets a **SHAP explanation translated into plain English by an LLM**, with a validation guardrail against hallucinated reasoning, surfaced in a two-page Power BI dashboard for sales and customer success teams.

`Python` `XGBoost` `SHAP` `LLM` `Power BI`

### 💰 [Credit Risk & Loan Default Analysis](https://github.com/rameenshakeell/loan-default-analysis)
Predictive modeling of peer-to-peer loan default risk on Lending Club data, evaluated not just on accuracy but on **profit-based simulation** aligning model decisions with actual investment returns.

`R` `Classification` `Profit Curve Analysis`

### 💬 [Sentiment Analysis of Restaurant Reviews](https://github.com/rameenshakeell/sentiment-analysis-restaurant-reviews)
Text mining and sentiment classification of Yelp reviews using lexicon-based and machine learning approaches, extracting behavioral insight from unstructured customer feedback.

`R` `NLP` `Text Mining`

---

## 🛠 Toolkit

| | |
|---|---|
| **Languages** | Python (pandas, NumPy, scikit-learn, XGBoost, SHAP) · R (tidyverse, caret) · SQL |
| **ML & Analytics** | Predictive modeling · Segmentation · Marketing mix modeling · Text mining · Model explainability · Profit-based evaluation |
| **AI Systems** | LLM agent pipelines · RAG · Embeddings & vector search · Prompt guardrails |
| **BI & Storytelling** | Tableau · Power BI · Streamlit · Executive-level presentation |

---

## 💡 How I Work

**Clarity over complexity.** A model is only useful if someone can act on it. Every project above ends in a decision: who to target, which leads to call, which risks to triage, not just a metric. And where a method has real limits (like regression-based attribution), I'd rather find and document them than pretend they don't exist.

---

## 📌 Background

Several years in digital marketing and creative strategy for global FMCG brands, now combined with graduate training in analytics. That mix means I speak both languages: I can build the model *and* explain to a stakeholder why it matters.

Outside work: live music, exploring cities, and creative content projects.
