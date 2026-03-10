# 🏢 Remote Work & Commercial Real Estate

> Analyzing how the shift to remote work is reshaping office vacancy rates and pricing across 25 major U.S. cities — using data from CBRE, JLL, CoStar, and federal transit agencies.

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## Hypothesis

The shift towards remote work is accelerating the decline of traditional office buildings in major U.S. cities — driving up vacancy rates and suppressing commercial real estate prices. However, the impact is uneven: local economies, transit dependency, and market dynamics mean some cities feel the pressure far more than others.

---

## Key Findings

- **Prices haven't followed vacancies down.** Despite rising vacancy rates across most markets, office prices have remained relatively stagnant — a phenomenon tied to the banking industry's "extend and pretend" policy, which has propped up the CRE market by deferring loan defaults.
- **Transit ridership tells the story.** Commuter data from NYC MTA and SF BART shows dramatically low ridership into major metro areas post-COVID — painting a stark picture for the CRE industry and the local businesses that depend on daily commuters.
- **City-by-city variation is significant.** Markets like Manhattan and San Francisco face severe pressure, while Sun Belt cities show more resilience due to population growth and economic diversification.

---

## Markets Analyzed

25 major U.S. cities: Boston · Dallas · Miami · Atlanta · Tampa · Detroit · Philadelphia · Chicago · Manhattan · New Jersey · Austin · Denver · Orlando · Phoenix · Bay Area · Nashville · Charlotte · Washington DC · Houston · Los Angeles · Portland · Seattle · San Francisco · San Diego · New York

---

## Data Sources

| Source | Data |
|--------|------|
| CBRE, JLL, CoStar | Office vacancy rates & pricing across 25 cities (2015–2024) |
| NYC MTA | Daily ridership (March 2020 – July 2024) |
| NYC MTA | Monthly ridership (2008–2024) |
| SF BART | Daily ridership (March 2020 – July 2024) |
| Yardi Matrix | Commercial real estate vacancy & pricing |
| U.S. Census Bureau | Commute pattern trends |
| Federal Transit Administration | National transit usage data |

---

## Methodology

1. **Commercial Real Estate Trends** — Collected office vacancy rates and pricing from CBRE, JLL, and CoStar across 25 major U.S. cities spanning 2015–2024.
2. **Remote Work Adoption Signals** — Analyzed U.S. Census commuting data and Federal Transit Administration ridership figures to quantify the shift away from in-office work.
3. **Cross-city Comparison** — Controlled for confounding factors including local economic conditions, population shifts, building supply, and pandemic timing to isolate the remote work signal.

---

## Project Structure

```
remote-work-office-market-analysis/
├── BLS Dataset/                        # Bureau of Labor Statistics data
├── Remote Work Impact.ipynb            # Main analysis notebook
├── Project 1 - Group 2 Presentation.pdf  # Slide deck
└── README.md
```

---

## Team

This was a collaborative group project. View the original repo at [Salsonmez/Project-1-Group-2](https://github.com/Salsonmez/Project-1-Group-2).
