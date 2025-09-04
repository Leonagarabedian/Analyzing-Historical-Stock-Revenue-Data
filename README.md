# Analyzing Historical Stock & Revenue Data (TSLA vs. GME)

**Goal**  
Reproduce an end-to-end analysis exploring how **company revenue** relates to **stock price** for **Tesla (TSLA)** and **GameStop (GME)**.  
All data is **fetched at runtime** (no CSVs stored in the repo).

## Live Data Flow
- **Prices:** via `yfinance`
- **Revenue:** via `pandas.read_html()` from public investor/financial pages

## Quickstart
```bash
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/Final_Assignment.ipynb
```
## Results 
- **TSLA:** Revenue inflection (2019–2021+) broadly coincides with sustained price strength.
- **GME:** Event-driven price spikes decouple from revenue fundamentals.
- **Takeaway:** Fundamentals matter over medium horizons; short-term moves can be sentiment/catalyst‑dominated.

