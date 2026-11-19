# Christophe Abelem Pinho

Computer Engineering student building data-intensive tools for DeFi and tokenized real-world assets

Computer Engineering at CESUPA (Belém, Brazil). I build quantitative finance projects on DeFi, stablecoins and tokenized real-world assets (RWA): stochastic models, simulation engines and on-chain data, written as reproducible Python code. I also work as a real estate data analyst, doing ROI and data analysis in Python and SQL.

## Featured projects

**[Uniswap v3 LP Backtesting Engine](https://github.com/ChristopheAbelem/uniswap-lp-backtest)**

A Python package that replays every swap of the Uniswap v3 USDC/WETH pool since 2021, collected directly from on-chain event logs, to test liquidity provision strategies. Simulates concentrated liquidity positions swap by swap, with fee accrual, impermanent loss and real gas costs, and compares range and rebalancing rules across market regimes. Includes a resumable collector with retry and checkpointing, and unit tests against the official Uniswap v3 math.
`Python` `SQLite` `Etherscan API` `pytest` `matplotlib`

**[Adaptive LTV for Tokenized Real Estate](https://github.com/ChristopheAbelem/adaptive-ltv-rwa)**

A closed-loop simulation of RealT's lending market, where tokenized Detroit houses served as collateral under a fixed 60% loan-to-value limit. A 27-rule Mamdani fuzzy controller adjusts the maximum LTV every month from collateral volatility, pool utilization and rent coverage, and is tested on RealT's 2024–2026 collapse, a historical housing shock and Merton jump-diffusion scenarios. Includes a live Streamlit app that shows each step of the controller's inference.
`Python` `fuzzy logic` `Monte Carlo` `Streamlit` `pytest`

**[Circle (CRCL) Valuation with Stochastic Interest Rates](https://github.com/ChristopheAbelem/circle-valuation)**

A stochastic DCF of Circle, the issuer of USDC, whose revenue depends on interest rates and stablecoin supply. Models the short rate (Vasicek) and USDC supply (geometric Brownian motion, solved with Itô's lemma) as correlated processes via Cholesky decomposition, values the company on 10,000 Monte Carlo paths, and runs a reverse DCF to extract what the share price implies. Every simulation is validated against closed-form results.
`Python` `NumPy` `SciPy` `pandas` `Monte Carlo` `Jupyter`

**[M&A Post-Mortem: Agnico Eagle & Kirkland Lake Gold](https://github.com/ChristopheAbelem/agnico-kirkland-ma-analysis)**

An evaluation of a C$13.5B all-stock gold mining merger against its peers (Newmont and Barrick). Reconstructs the deal terms from filings and tests the promised synergies through announcement returns, margins, all-in sustaining costs, asset-level results and valuation multiples. Published as an interactive dashboard.
`Python` `SQL` `SQLite` `Streamlit` `Plotly` `pandas`

## Stack

| Area | Technologies |
|---|---|
| Quantitative finance | DCF and reverse DCF, comparables, Monte Carlo simulation, stochastic differential equations, Vasicek, GBM, Itô's lemma, fuzzy control |
| Data and engineering | Python, pandas, NumPy, SciPy, SQLAlchemy, pytest, Git |
| Databases | SQL, SQLite, PostgreSQL |
| Visualization | Streamlit, Plotly, matplotlib |
| Blockchain data | Ethereum event logs, ABI decoding, Etherscan API, DefiLlama |
| Languages | Portuguese (native), English (fluent), Spanish (intermediate) |

## Contact

[LinkedIn](https://linkedin.com/in/christophe-abelem-686681346) · abelemchristophe@gmail.com
