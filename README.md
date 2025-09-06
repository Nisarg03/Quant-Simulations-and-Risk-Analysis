# Stock Price Simulation and Risk Analysis in Python  

---

Hi, I’m **Nisarg**, a Research Assistant at Trent University with a Master’s in **Big Data Analytics**, passionate about applying statistical modeling, simulations, and risk analysis to real-world problems.  

This project documents my exploration into **quantitative finance**, where I combine my academic background in data-driven research with hands-on coding to simulate stock price behavior, assess portfolio risk, and analyze uncertainty.  

The journey starts with **Geometric Brownian Motion (GBM)** to model individual stock dynamics, expands into **Monte Carlo simulations** across thousands of potential scenarios, and culminates in **portfolio-level risk modeling** using correlation structures, **Value at Risk (VaR)**, and probability of loss.  

---

## 📌 What is Geometric Brownian Motion (GBM)?  

GBM is a stochastic process commonly used to model stock price movements over time. It assumes:  

- Constant drift (expected return)  
- Constant volatility  
- Log-normal distribution of prices  

It forms the backbone of many financial models, including the **Black–Scholes option pricing model**, and serves as a natural starting point for Monte Carlo simulations.  

---

## 🧮 How Geometric Brownian Motion Works  

At its core, GBM assumes that stock prices follow a continuous compounding process with both **deterministic growth (drift)** and **stochastic fluctuations (volatility)**.  

Mathematically:  

$$
S_{t+1} = S_t \cdot \exp\left( \left( \mu - \tfrac{1}{2}\sigma^2 \right)\Delta t + \sigma \sqrt{\Delta t} \cdot Z_t \right)
$$  

Where:  

- $S_t$: Price at time $t$  
- $\mu$: Expected return (drift)  
- $\sigma$: Volatility  
- $\Delta t$: Time increment (e.g., 1/252 for daily)  
- $Z_t$: Random variable $\sim N(0,1)$  

This ensures stock prices remain positive and captures realistic randomness in price paths.  

---

## 🚀 What This Project Does  

- Simulates single and multiple GBM stock paths  
- Runs large-scale **Monte Carlo simulations** for portfolio risk assessment  
- Visualizes results with **path plots and histograms**  
- Applies **correlation structures** via matrix decomposition for multi-asset portfolios  
- Quantifies risk with **Value at Risk (VaR)** and **probability of loss**  

---

## Example Output

![Portfolio Simulation Output](https://github.com/Nisarg03/Quant-Simulations-and-Risk-Analysis/blob/main/Portfolio_MonteCarlo_Figure.png)

---

## Visualizing the Results

* **Left plot:** 10,000 simulated portfolio paths over time
* **Right plot:** Histogram of ending portfolio values

  * Red line = 95% Value at Risk (VaR)
  * Orange line = \$100,000 initial value
  * Text box = risk summary (VaR and % chance of loss)

---

## 💡 Why This Matters  

In my work and academic projects, I’ve focused heavily on **modeling uncertainty**, whether in financial, scientific, or operational contexts. This simulation project extends those skills to finance, showing:  

- How stochastic processes drive uncertainty in markets  
- How **Monte Carlo methods** can quantify risks that aren’t obvious from single deterministic models  
- How **portfolio correlation** affects diversification and downside protection  

For someone moving into quantitative research, trading, or risk analytics, these skills — **stochastic modeling, Monte Carlo simulation, risk metrics, and matrix-based correlation modeling** — are directly applicable.  

---

## 🛠 Skills Demonstrated  

- Applied stochastic processes (GBM)  
- Monte Carlo simulation at scale (10,000+ paths)  
- Correlated asset modeling with covariance matrices + Cholesky decomposition  
- Vectorized, production-ready Python code  
- Risk analysis (VaR, downside probability, loss distributions)  
- Data visualization and interpretation  

---

## 👨‍💻 About Me  

- 📊 **Background**: MSc in Big Data Analytics, Research Analyst at Trent University  
- 📈 **Focus**: Applying mathematical and computational techniques to model real-world systems  
- ⚡ **Interests**: Quantitative finance, risk analysis, and algorithmic decision-making  
- 🥇 **Bonus**: Strong communication skills (published, TA experience, and adept at explaining technical concepts simply)  

---

## 📚 Resources  

- [QuantStart: GBM Simulation in Python](https://www.quantstart.com/articles/geometric-brownian-motion-simulation-with-python)  
- [IBM Technology – Monte Carlo in Finance](https://www.youtube.com/watch?v=7TqhmX92P6U)  
- [MarbleScience – Monte Carlo Explained](https://www.youtube.com/watch?v=7ESK5SaP-bc)  

---
