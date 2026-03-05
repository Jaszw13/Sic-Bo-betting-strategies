# Sic-Bo Betting Strategies
A Python-based simulation tool to analyze and compare classic Sic Bo betting strategies (Martingale, fixed-bet), quantify risk-reward profiles, and deliver data-driven recommendations for achieving target capital while balancing risk.

## 📌 Project Inspiration
This project was inspired by the need to move beyond anecdotal claims about Sic Bo betting strategies and objectively quantify their real-world performance. It aims to demystify the risk/reward trade-offs of Martingale and fixed-bet approaches through reproducible simulations, and highlight the inherent house edge in Sic Bo that impacts all betting strategies.

## 🌍 Target Users
- Hobbyists curious about Sic Bo game mechanics and the mathematical viability of betting strategies
- Data enthusiasts learning to build financial strategy simulations and analyze statistical outcomes
- Python beginners practicing hands-on data analysis, simulation logic, and visualization
- Individuals seeking evidence-based insights into gambling strategy risks (not for gambling guidance)

## ✨ Core Features
- Accurate modeling of Sic Bo "Big/Small" bet mechanics (48.61% win probability, 1:1 payout, excluding triples)
- Implementation of two core betting strategies:
  - Martingale (progressive bet doubling after losses)
  - Fixed-bet (consistent minimum bet per round)
- Configurable comprehensive simulations (500 experiments per strategy):
  - Initial capital: 3000
  - Target capital: 10000
  - Maximum bet limit: 99000
  - Minimum bet options: 30, 50
- Quantification of key performance metrics:
  - Probability of reaching target capital
  - Bankruptcy rate (total capital loss)
  - Expected net revenue (gain/loss)
- Visualization of capital trajectories (volatility and trend analysis)
- Plain-language recommendations on strategy/minimum bet selection (balancing risk and target achievement)

## 🛠️ Tech Stack
- Python (core simulation and calculation logic)
- Pandas & NumPy (data processing and statistical analysis)
- Matplotlib & Seaborn (capital trajectory visualization and probability plotting)
- No backend required (fully local execution with standard Python libraries)

## 🤖 AI Contribution (Important Note)
This project was **largely created with the assistance of AI** (including but not limited to):
- Design of Sic Bo game mechanics and betting strategy logic
- Python implementation of simulation loops, parameter configuration, and experiment execution
- Statistical analysis of simulation results (probability calculation, expected revenue)
- Visualization of capital trajectories and performance metrics
- Git/GitHub setup guidance

Manual adjustments were minimal – the core structure, logic, and code implementation are AI-generated.

## 🚀 How to Use
### Option 1: Local Use (Script Execution)
1. Clone this repo:
   ```bash
   git clone https://github.com/[your-username]/sic-bo-betting-strategies.git
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the main simulation script:
   ```bash
   python sic_bo_simulation.py
   ```
4. Review the generated report (quantitative metrics + visual charts) in your local directory

### Option 2: Interactive Analysis (Jupyter Notebook)
1. Follow Step 1 & 2 from "Local Use" above
2. Open the interactive notebook in Jupyter Lab/Notebook:
   ```bash
   jupyter notebook sic_bo_analysis.ipynb
   ```
3. Run all cells to execute simulations and explore results interactively

## ⚠️ Disclaimer
- This tool is for **educational/reference purposes only** – it does NOT constitute gambling, financial, or investment advice
- Simulations are based on theoretical Sic Bo mechanics and do not reflect real-world variables (e.g., casino table limits, rule variations, human behavior)
- Gambling involves significant financial risk and can lead to addiction; always gamble responsibly (or avoid it entirely)
- This project does NOT endorse, promote, or encourage gambling activities
- All simulated strategies show negative expected revenue, confirming the inherent house edge in Sic Bo

## 📄 License
This project is open-source under the MIT License (free for personal/non-commercial use).

---
*Last updated: March 2026*  
*Created with AI assistance | Focused on Sic Bo betting strategy simulation & risk analysis*

### 总结
1. 严格匹配示例README的结构（emoji标题+分层级内容+代码块+加粗强调），适配Sic Bo项目的Python仿真属性；
2. 完整保留核心业务逻辑（500次实验、两种策略、关键参数、风险指标），并转化为用户易读的功能描述；
3. 补充了实用的使用指引（依赖安装、交互式Notebook运行方式），同时强化了免责声明的合规性（明确非赌博建议）。
