# CHIPS Act — Semiconductor Industry Analysis

**Course:** Financial Data Analytics  
**Institution:** Clark University School of Business  
**Team:** Kubra Banu, Joash Kawal

---

## Overview

This project analyzes the economic and market impact of the **CHIPS and Science Act** (enacted August 9, 2022) on two U.S. industries:

- **SIC 3674** — Semiconductors and Related Devices (Joash) — Focus company: **Intel Corp**
- **SIC 3679** — Electronic Components, Not Elsewhere Classified (Kubra) — Focus company: **Advanced Energy Industries, Inc**

The act authorized ~$280 billion in funding for domestic semiconductor research and manufacturing to strengthen U.S. supply chain resilience.

---

## Research Hypotheses

**Kubra:** The production efficiency of companies in the electronics components industry (SIC 3679) has been positively affected by the CHIPS Act, in turn leading to a positive stock market reaction.

**Joash:** The CHIPS and Science Act will positively impact the Semiconductor and Related Devices industry (SIC 3674) in the U.S., improving financial return on revenues.

---

## Tools & Data Sources

| Tool / Source | Purpose |
|---------------|---------|
| **Python** | Data processing, event study, statistical analysis |
| **Tableau** | Industry trend and stock market visualizations |
| **Compustat** | Financial statement data (via WRDS) |
| **CRSP** | Stock return and market data (via WRDS) |
| **WRDS** | Wharton Research Data Services platform |
| **SEC EDGAR** | Company filings (Intel, Advanced Energy Industries) |

---

## Methodology

1. **Event Study Design** — CHIPS Act enactment (Aug 9, 2022) as the event date
2. **Industry Selection** — SIC 3674 (Semiconductors) and SIC 3679 (Electronic Components)
3. **Data Collection** — Compustat financials + CRSP stock returns via WRDS
4. **Analysis** — Abnormal returns, production efficiency metrics, stock market reactions pre/post-event
5. **Visualization** — Tableau dashboards showing industry trends and financial indicators

---

## Key Findings

- Electronics components industry (SIC 3679) saw positive production efficiency impact from CHIPS Act
- Increased semiconductor manufacturing demand drove higher need for components (resistors, capacitors, etc.)
- Semiconductor industry (SIC 3674) positioned for long-term domestic manufacturing growth
- Intel received $8.5 billion in direct CHIPS Act funding, signaling strong domestic investment
- Stock market reacted positively to CHIPS Act enactment across both industries

---

## Files

| File | Description |
|------|-------------|
| `Kubra.html` | Python analysis notebook (HTML export) |
| `Kubra_chips-act.pptx` | Presentation slides |
| `Kubra_Project1-3.pdf` | Full project report |

---

## References

- [CHIPS and Science Act — Wikipedia](https://en.wikipedia.org/wiki/CHIPS_and_Science_Act)
- [Intel CHIPS Act Funding](https://www.intel.com/content/www/us/en/newsroom/news/us-chips-act-intel-direct-funding.html)
- [McKinsey — What's in the CHIPS Act](https://www.mckinsey.com/industries/public-sector/our-insights/the-chips-andscience-act-heres-whats-in-it)
- [PwC CHIPS Act Analysis](https://www.pwc.com/us/en/library/chips-act.html)
- [Congressional Research Service Report R47523](https://crsreports.congress.gov/product/pdf/R/R47523)
