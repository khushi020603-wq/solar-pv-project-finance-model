# Solar PV Project Finance Model

A quarterly project finance model for a 10 MW solar PV plant in India, built in Excel.

## What it does

The model tracks the full financial life of the project — from construction through 30 years of operation — and calculates whether the project is bankable (i.e. worth investing in).

## Key inputs
- Plant capacity: 10 MW
- Capacity factor: 20%
- Cost: ₹45,000 per kW (Total CapEx: ₹45 crore)
- Debt: 60% of CapEx, 9% interest, 15-year tenor
- Price sold at: ₹3,000 per MWh

## What it calculates
- **Debt schedule** — interest and principal repayment each quarter
- **Depreciation & tax** — using loss carry-forward rules
- **Cash flow waterfall** — revenue → OpEx → debt service → equity returns
- **DSCR** (Debt Service Coverage Ratio) — how safely the project can repay debt
- **Project IRR** and **Equity IRR** — investor return metrics
- **LCOE** (Levelized Cost of Energy) — cost per unit of electricity produced
- **NPV** — using XNPV for both project and equity cash flows

## Key results

| Metric | Value |
|---|---|
| Project IRR (Unlevered) | 6.3% |
| Equity IRR (Levered) | 6.2% |
| Average DSCR | 1.28x |
| Minimum DSCR | 0.93x |
| LCOE (Ungeared) | ₹2,661 / MWh |
| LCOE (Geared) | ₹3,036 / MWh |
| Equity NPV | ₹70.9 lakh |
| Project NPV | ₹9.52 crore |

## Why this project

Built to practice project finance modeling skills relevant to renewable energy investment analysis. This structure is also a foundation for a future model assessing investment feasibility of natural hydrogen exploration sites.

## Tools used
Excel — dynamic debt scheduling, tax-loss carry-forward logic, cash flow waterfall, XNPV/XIRR functions
