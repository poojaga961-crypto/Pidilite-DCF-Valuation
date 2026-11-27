# Pidilite Industries – DCF Valuation (FCFF)

An Excel-based Discounted Cash Flow (DCF) model valuing **Pidilite Industries Ltd** (NSE: PIDILITIND), built as a valuation portfolio project.

**Prepared by:** Pooja G A, CA Finalist
**Valuation date:** 27 Nov 2026 | **Base year:** FY2025-26 (consolidated) | **Figures:** ₹ crore

## Objective
Estimate the intrinsic value per share of Pidilite using a 5-year Free Cash Flow to Firm (FCFF) model, and compare it with the market price.

## Model structure
| Sheet | Contents |
|---|---|
| Cover | Purpose, method, key outputs, takeaway |
| Historical | FY22–FY26 P&L, balance sheet items, cash flows, derived capex, ratios |
| WACC | Cost of equity (CAPM), cost of debt, capital structure, WACC |
| DCF | Assumptions, FCFF build (FY27–FY31), terminal value, equity bridge |
| Sensitivity | Value per share across WACC and terminal growth rates |

## Methodology
- **FCFF** = EBIT × (1 – tax) + D&A – Capex – Increase in NWC
- **Cost of equity** = Risk-free rate + Beta × Equity risk premium
- **Terminal value** = Gordon growth model
- **Equity value** = Enterprise value + Investments – Borrowings
- All projections are formula-driven and linked to the assumption cells

## Key assumptions
- Revenue growth tapering from 11% to 9%
- EBITDA margin around 24–24.5%
- Capex about 4.5% of revenue; D&A about 2.7% of revenue
- Tax rate 25.17% (Section 115BAA)
- WACC about 11.7%; terminal growth 5.5%

## Key findings
- DCF value: about **₹456 per share**, vs market price of about **₹1,605**
- Implied EV/EBITDA of about 12x, vs the market's about 45x
- The gap suggests the market is pricing in a much longer high-growth period and/or a lower discount rate, which reflects Pidilite's strong brands (Fevicol, Dr. Fixit) and high return on capital
- Terminal value is about 77% of EV, so the result is sensitive to WACC and growth (see Sensitivity sheet)

## Colour code
Blue = hard-coded inputs | Black = formulas | Green = links from other sheets | Yellow = key assumptions

## Data sources
- Screener.in, Pidilite consolidated financials
- Pidilite Industries Annual Report FY2025-26

## Limitations and next steps
- Beta and risk-free rate are assumptions; update with current market data
- Capex is derived from the balance sheet; verify against the cash flow statement
- Next: add a comparable companies analysis (Asian Paints, Berger Paints, Astral) and a 10-year DCF

*This project is for learning purposes only and is not investment advice.*
