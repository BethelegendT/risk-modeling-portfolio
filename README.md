# Risk Modeling Portfolio (Excel + Python)

A compact portfolio demonstrating quantitative readiness for ERM:
**credit risk (PD/LGD/EAD + tail loss)** and **market risk (VaR/ES + backtesting + stress testing)**.

**Public artifacts use synthetic data** for reproducibility and confidentiality.

---

## 1) Credit Risk (Excel): Credit Portfolio Loss + VaR/ES
- Outputs: **EL, VaR(99%), ES(99%)**
- Extras: **3 stress scenarios** + basic calibration view (PD buckets)
- Results (1-page memo): **[PDF](PASTE_MEMO_PDF_LINK)**
- Repo (code/template): [credit-portfolio-var-es](PASTE_CREDIT_REPO_LINK)

---

## 2) Market Risk (Python): VaR/ES Backtesting + Stress Testing
- Models: historical / normal / EWMA
- Backtesting: exceptions + **Kupiec test**
- Stress testing: return shock + vol multiplier
- Results (one page): **[docs/report.md](PASTE_REPORT_LINK)**
- Repo: [market-var-backtest-stress](PASTE_MARKET_REPO_LINK)

---

## Reproducibility & confidentiality
- The original loan-level dataset is **not shared**.
- This portfolio uses **synthetic samples** to reproduce the workflow end-to-end.

---

## Suggested resume line
**Risk Modeling Portfolio (Excel + Python)** — Built a credit portfolio loss model (PD/LGD/EAD; EL/VaR/ES; stress + calibration) and a market VaR/ES workflow (rolling backtests + Kupiec; stress testing) with reproducible results and synthetic data. (Link)
