# Climate Shock Europe
### Part 3 of the *Europe Under Pressure* Series

Analyzing CBAM (Carbon Border Adjustment Mechanism) exposure across 16 EU economies using Python.



## Research Question
Are countries with higher carbon-industrial exposure experiencing higher unemployment in Europe?

## Key Finding
Higher CBAM exposure is **negatively and significantly associated** with unemployment 
(coefficient: -5.65, p=0.009, R²=0.394).

This is the **statistically strongestest significant result** in the series:
- Part 1 China Shock p: 0.3 
- Part 2 AI Shock  p: 0.518 
- Part 3 Climate Shock  p: 0.009 

Interpretation: High-carbon industrial economies (Czech Republic, Germany, Netherlands) 
already have low unemployment — suggesting they are adapting to green transition pressures 
rather than being hurt by them.

## Methodology
**Original analysis** inspired by CBAM literature and the Europe Under Pressure series.

## Results
| Metric | Value |
|--------|-------|
| Coefficient on CBAM exposure | -5.65 |
| R-squared | 0.394 |
| p-value | 0.009  |
| Most exposed country | Czech Republic |
| Least exposed country | Romania |

## Tools
`Python` `pandas` `wbgapi` `Our World in Data` `plotly` `statsmodels` `Google Colab`

[🗺️ View Interactive Map](https://poonum-malhi.github.io/climate-shock-europe/climate_shock_map.html)

## Europe Under Pressure — Full Series
| Project | Question | p-value | Finding |
|---------|----------|---------|---------|
| [Part 1 — China Shock](https://github.com/Poonum-Malhi/china-shock-europe) | Did Chinese imports raise EU unemployment? | 0.3 | No — industrial upgrading offset the shock |
| [Part 2 — AI Shock](https://github.com/Poonum-Malhi/Europe-under-pressure-first-China-now-AI) | Does AI exposure raise EU unemployment? | 0.518 | No — not yet significant |
| Part 3 — Climate Shock (this repo) | Does CBAM exposure raise EU unemployment? | 0.009  | Significant — but direction is surprising |

## Data Sources
- World Bank API (wbgapi) — Manufacturing & Unemployment
- Our World in Data — CO2 per capita (2019)
- Frey & Osborne (2017) — Automation risk scores

---
*Built as part of an Economics × AI research*

📖 [Read the full series on Medium](https://medium.com/@poonummalhi04/europe-under-pressure-first-china-now-b5db88ea4d68)
