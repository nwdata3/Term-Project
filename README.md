# Term-Project
# Introduction
This project represents an investment fund for a financial engineering class incorporating Monte Carlo simulation, a portfolio 34 energy stocks, and advanced modeling techniques.

# Literature Review 

Several foundational and contemporary authors have contributed significantly to the field of technical analysis. These include Robert Edwards & John Magee, W.H.C. Bassetti, Thomas Meyers, Barbara Rockefeller, and Trivedi & Kyal.
All authors and researchers provide unique perspectives and recommendations:
Edwards & Magee develops the groundwork for pattern recognition and Dow Theory.
Meyers focuses on technical indicators and step-by-step analysis methods.
Barbara Rockefeller provides a modern, risk-conscious approach focused on entry/exit planning and accessibility.
Trivedi & Kyal blends traditional techniques with algorithmic trading and intermarket analysis.
A common theme across these works is the importance of diversification across sectors and asset classes, which is a consistent concept with financial theory taught in academia. Each research provides both practical tools and theoretical backing for my strategy.

# Methods
This research is based on technical analysis and emphasizes diversification across ETFs, individual stocks, and sector-based funds.
Data collection was sourced Yahoo Finance via Python incorporating the past 25 years of history.
This dataset captures key market shocks, including the 2008 recession and the COVID-19 inflation window, to ensure resilience.
While initially launched as a long-only strategy, we evaluated shorting and hedging and determined they were more effective for a growth-focused mandate during periods of volatility. 
Our Momentum Trading Strategy is to incorporate long and short positions rebalanced monthly to assess returns. 
Stocks are ranked against each other using this cross-sectional momentum to rebalance on a more consistent basis given its long and short position strategy. Assumes longing the best performers and shorting the worst performers.
A key challenge is the risk of misinterpretation due to market manipulation (e.g., short squeezes, insider activity). However, these same distortions can also highlight market inefficiencies, creating opportunities for short-term gains that may not be apparent through fundamental analysis.

# Results

What I’ve discovered so far from my research is the following: 
1. Cross Sectional Momentum Trading Strategy is less volatile during downturns of XLE benchmark, but overall less cumulative return.
2. Energy Sector is highly complex and more research would be necessary to apply new features and stocks for a more robust portfolio.
   
My plan is for high-growth potential with some risk management across my portfolio given having a more risk-averse mentality.

# Conclusion
Overall, I would not recommend starting this fund.

# Disclosures
ChatGPT was utilized to refine errors in my analysis and provide guidance on applying momentum trading strategies within the energy sector.
