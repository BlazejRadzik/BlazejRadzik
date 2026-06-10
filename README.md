### **Aspiring Quant**

---

## Project: QuantRisk**
**A Management Platform designed for multi-asset portfolio modeling.**

> [**[View Repository]**](https://github.com/BlazejRadzik/QuantRiskEngine)

### **Implementations:**

* **HPC Monte Carlo Engine (C++17):** Developed a custom simulation module integrated via **Pybind11**. Utilizing **OpenMP** for full CPU core parallelization and **SIMD Optimization**, achieving **400x+ speedup** over standard Python loops for 50,000+ path Geometric Brownian Motion (GBM) simulations.
* **Hybrid Volatility Forecasting:** Implemented a unique pipeline where **GARCH(1,1)** econometric models are corrected by **LSTM Neural Networks (PyTorch)** to capture non-linear market anomalies and volatility clustering.
* **Dynamic Correlation (EWMA):** Real-time covariance matrix updates to detect **"correlation breakdown"** during market stress events.
* **Statistical Backtesting:** Automated validation layer using **Kupiec (POF)** and **Christoffersen independence tests** to ensure VaR model integrity.
* **Optimized Data Layer:** Custom **SQL caching layer** and **memory-aligned data structures** to minimize cache misses and reduce data retrieval latency by **95%**.

---

## **🛠 Tech Stack**

### **Core Programming & HPC**
* **Languages:** `C++17/20` (Templates, Metaprogramming), `Python 3.x` (AsyncIO).
* **Optimization:** `OpenMP` (Multi-threading), `SIMD` (Vectorization), `Pybind11` (Zero-copy memory transfer).
* **Backend & Dev:** `FastAPI`, `Docker & Compose`, `PostgreSQL/SQLite`.

### **Quant & Data Science**
* **Libraries:** `PyTorch` (LSTMs), `NumPy`, `Pandas`, `SciPy`, `Plotly`.
* **Focus Areas:** **Tail Risk Estimation** (Parametric, Historical, Monte Carlo VaR/ES), **Portfolio Optimization** (Mean-Variance), **Spectral Dynamics**.

---

## **📈 Activity & Stats**

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=BlazejRadzik&show_icons=true&theme=tokyonight&hide_border=true&cache_bust=1" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=BlazejRadzik&layout=compact&theme=tokyonight&hide_border=true&cache_bust=1" width="45%" alt="Top Languages" />
</p>

---

## **🎯 Current Focus**
* Developing **Real-time pricing engines** for derivative instruments.
* Researching **Spectral Dynamics** in high-frequency financial time series.
* Refining **Institutional Dynamic Weight Bounds** in portfolio rebalancing.

---
