### Hi, I'm Jun Zhang 👋

**Quantitative Finance @ Boston University**

I build the full stack of a quantitative research idea — pulling and cleaning messy
alternative data, engineering features that respect point-in-time correctness,
fitting the model, and then stress-testing the result hard enough to find out
whether it was ever real.

**Focus:** Quant Research & Trading · Data Engineering · Machine Learning · Credit Risk

---

🔭 **Currently**
- Point-in-time data pipelines for systematic equity research — survivorship correction, as-of joins, look-ahead detection
- Large-scale alternative data pipelines on PySpark (satellite, weather, trade, survey sources)
- LLM-assisted labeling and RAG for financial text classification

---

### 📌 Featured Projects

| Project | What it is |
|---|---|
| [**bu-brdge-portfolio-optimization**](https://github.com/zj092912/bu-brdge-portfolio-optimization-) | Point-in-time equity research pipeline · caught a look-ahead leak that inflated a signal's information coefficient from **0.005 to 0.171 (t 11.6)** · survivorship-corrected universe replay, as-of joins on publication timestamps, permanent-security-ID keying that recovered **1.4% of silently dropped history** |
| [**cocoa-futures-forecasting**](https://github.com/zj092912/cocoa-futures-forecasting) | 7 heterogeneous data sources (**~13.9 GB**) fused on **PySpark/MLlib** · point-in-time-correct ingestion · Model Confidence Set, Diebold-Mariano, bootstrap Sharpe CIs · Docker + 28 test modules |
| [**mutual-fund-style-classification**](https://github.com/zj092912/mutual-fund-style-classification) | Fund style from prospectus text · **RAG cuts 2.27M → 692K tokens** · 92.9% test accuracy · the LLM audit surfaced **26 mislabeled funds** in the provided dataset |
| [**bankruptcy-prediction**](https://github.com/zj092912/bankruptcy-prediction) | Corporate default under **3.12% class imbalance** · LogReg vs. LDA vs. GNB selected on minority-class F1, not accuracy · SMOTE without leakage, tuned decision threshold |

> A note on these: several report **negative results** — the cocoa signal doesn't
> beat a coin flip, and at BRDGE the strongest signal we had turned out to be a
> look-ahead leak, so we killed it. I lead with that rather than bury it. The
> methodology is the deliverable; a backtest that only looks good is worth less
> than one you can trust.

---

### 🛠️ Tech

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/-Apache_Spark-E25A1C?logo=apachespark&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/-pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white)

**Quant:** cointegration · optimal stopping / free-boundary PDEs · walk-forward backtesting · execution-cost modeling · Sharpe CIs (Lo, stationary & moving-block bootstrap) · Model Confidence Set
**Data Engineering:** PySpark · Spark SQL · Parquet partitioning · point-in-time correctness · PDF/OCR & API ingestion · Docker · pytest
**ML:** scikit-learn · imbalanced learning (SMOTE) · NLP & text classification · RAG · OpenAI API
**Risk:** credit default modeling · structural & reduced-form PD · imbalanced classification

---

### 📫 Connect

[![Email](https://img.shields.io/badge/-zj0929@bu.edu-D14836?logo=gmail&logoColor=white)](mailto:zj0929@bu.edu)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/junzhang0929)

📍 Boston, MA
