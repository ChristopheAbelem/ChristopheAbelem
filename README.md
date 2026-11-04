# Christophe Abelem

Computer Engineering student focused on quantitative finance for digital assets

Computer Engineering at CESUPA (Belém, Brazil). I build quantitative finance projects on DeFi, stablecoins and tokenized real-world assets (RWA): stochastic models, simulation engines and on-chain data, written as reproducible Python code. I also work as a real estate investment analyst, doing ROI and data analysis in Python and SQL.

## Featured projects

**Uniswap v3 LP Backtesting Engine** *(in progress)*

A Python package that replays every swap of the Uniswap v3 USDC/WETH pool since 2021, collected directly from on-chain event logs, to test liquidity provision strategies. Simulates concentrated liquidity positions swap by swap, with fee accrual, impermanent loss and real gas costs, and compares range and rebalancing rules across market regimes. Includes a resumable collector with retry and checkpointing, and unit tests against the official Uniswap v3 math.
`Python` `SQLite` `Etherscan API` `pytest` `Streamlit` `Plotly`

**[Circle (CRCL) Valuation with Stochastic Interest Rates](https://github.com/ChristopheAbelem/circle-valuation)**

A stochastic DCF of Circle, the issuer of USDC, whose revenue depends on interest rates and stablecoin supply. Models the short rate (Vasicek) and USDC supply (geometric Brownian motion, solved with Itô's lemma) as correlated processes via Cholesky decomposition, values the company on 10,000 Monte Carlo paths, and runs a reverse DCF to extract what the share price implies. Every simulation is validated against closed-form results.
`Python` `NumPy` `SciPy` `pandas` `Monte Carlo` `Jupyter`

**[M&A Post-Mortem: Agnico Eagle & Kirkland Lake Gold](https://github.com/ChristopheAbelem/agnico-kirkland-ma-analysis)**

An evaluation of a C$13.5B all-stock gold mining merger against its peers (Newmont and Barrick). Reconstructs the deal terms from filings and tests the promised synergies through announcement returns, margins, all-in sustaining costs, asset-level results and valuation multiples. Published as an interactive dashboard.
`Python` `SQL` `SQLite` `Streamlit` `Plotly` `pandas`

**[Valuation Methods by Sector: PLD, SOFI & MTB](https://github.com/ChristopheAbelem/pld-sofi-valuation)**

A comparison of how valuation method must adapt to sector economics, using an industrial REIT, a lending fintech and a regional bank. Applies DCF, comparable multiples (P/FFO, P/E) and net asset value, and diagnoses why standard methods break for each business model.
`Python` `pandas` `SQLAlchemy` `SQLite` `matplotlib`

## Stack

| Area | Technologies |
|---|---|
| Quantitative finance | DCF and reverse DCF, comparables, Monte Carlo simulation, stochastic differential equations, Vasicek, GBM, Itô's lemma |
| Data and engineering | Python, pandas, NumPy, SciPy, SQLAlchemy, pytest, Git |
| Databases | SQL, SQLite, PostgreSQL |
| Visualization | Streamlit, Plotly, matplotlib |
| Blockchain data | Ethereum event logs, ABI decoding, Etherscan API |
| Languages | Portuguese (native), English (fluent), Spanish (intermediate) |

## Contact

[LinkedIn](https://linkedin.com/in/christophe-abelem-686681346) · abelemchristophe@gmail.com
