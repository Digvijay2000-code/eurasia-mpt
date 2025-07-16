# Eurasia Investment Portfolio Optimization

## Overview
This project implements a **multi-asset portfolio optimization** and **risk simulation** model using Python. It was developed for the **Eurasia Asset Management Challenge**, where the goal was to create a robust 20-year strategic asset allocation plan across global ETFs using quantitative methods and sustainability-focused constraints.

---

## Features
- Optimizes portfolio weights to meet a 10% annualized return target  
- Applies real-world constraints:  
  - ≥ 65% allocation to favored ETFs  
  - Fixed 5% Gold and 2.5% Cash allocations  
- Uses historical return and volatility assumptions for 18 ETFs  
- Performs **Monte Carlo simulations** (10,000 runs) over a 20-year period  
- Outputs portfolio return, volatility, and drawdown distributions  
- Visualizes results with clear histograms for:
  - End portfolio values  
  - Annualized returns  
  - Annualized volatility  
  - Maximum drawdowns  

---

## Sample Output
Sample portfolio weights:
```
Invesco QQQ Trust: 9.20%
iShares Core MSCI Europe ETF: 7.34%
Vanguard Total International Bond ETF: 4.56%
...
Gold: 5.00%
Cash: 2.50%
```

Example metrics:
- **Expected Annualized Return**: ~10.5%  
- **Volatility**: ~18.2%  
- **Mean Ending Value**: ~$330 million (from initial $100M)  
- **Mean Max Drawdown**: ~25.4%

---

## Files
- `EURASIA_script.ipynb` – Main Python notebook with optimization and simulation logic
- `README.md` – Project overview (you're reading it!)
- `requirements.txt` *(optional)* – Use if you want to specify libraries like:
  ```txt
  numpy
  pandas
  matplotlib
  scipy
  ```

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/eurasia-portfolio-optimizer.git
   cd eurasia-portfolio-optimizer
   ```

2. Install dependencies (if using `requirements.txt`):
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook EURASIA_script.ipynb
   ```

---

## Techniques Used
- Modern Portfolio Theory (MPT)  
- Constrained Optimization (`scipy.optimize.minimize`)  
- t-distribution-based stochastic simulations  
- Risk analytics (volatility, drawdown, return distribution)

---

## 🧑‍💻 Author
Digvijay Morajkar  
Economics & Quantitative Finance, SMU  
📫 [LinkedIn Profile](www.linkedin.com/in/digvijay-morajkar)
📁 [GitHub Portfolio](https://github.com/digivjay2000-code)
