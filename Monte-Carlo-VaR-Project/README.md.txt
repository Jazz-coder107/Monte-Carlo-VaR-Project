# 🧠 Monte Carlo Simulation for Value at Risk (VaR) & Expected Shortfall

This project simulates possible future price paths of a stock (NVDA) using Monte Carlo methods to compute:

- **Value at Risk (VaR)** — the maximum expected loss with a given confidence level
- **Expected Shortfall (CVaR)** — the average loss in the worst-case scenarios beyond the VaR threshold

📊 Techniques used:
- Historical VaR & CVaR (non-parametric)
- Parametric VaR & CVaR using normal distribution assumptions
- Time-scaled VaR (Square Root of Time rule)
- Monte Carlo Simulations based on log returns & Geometric Brownian Motion

## 📈 Example Output: Monte Carlo Simulations
![Monte Carlo](results/VaR_plot.png)

## 🔧 Technologies
- Python, NumPy, Pandas
- Matplotlib, Seaborn
- SciPy
- yFinance API

## 📁 Project Structure
- `MonteCarlo_VaR.ipynb`: Final Jupyter notebook with step-by-step walkthrough
- `results/`: Optional output folder for saving plots or charts
- `README.md`: You’re reading it
- `requirements.txt`: (Optional) List of required Python packages

## 💡 Key Learning Outcomes
- Understanding the strengths/limits of Historical, Parametric, and Simulated VaR
- Visualizing tail risk and interpreting extreme market outcomes
- Applying Monte Carlo to portfolio-level risk estimation

---

### ✅ Instructions
Clone this repo, install dependencies (if needed), and run the notebook.

```bash
pip install -r requirements.txt
