# Market Expansion Toolkit

A practical toolkit for evaluating new mobility markets using demand, supply, competition, infrastructure and regulatory signals.

## Purpose
This repository helps structure market-entry analysis for mobility, logistics, ride-hailing, delivery, and fleet expansion.

## Core Framework
Each market is assessed across five dimensions:
1. Demand potential
2. Supply availability
3. Competitive pressure
4. Operational feasibility
5. Regulatory friction

## Outputs
- City / area scorecards
- Market priority ranking
- Simple visualizations
- 90-day launch playbook
- Reusable market-entry framework

## Suggested Workflow
1. Select a city or market.
2. Gather public data and qualitative inputs.
3. Score key areas from 1 to 5.
4. Compare opportunities and risks.
5. Convert the analysis into a 90-day launch plan.

## Starter Market
Jakarta is included as a sample structure. Replace sample values with validated data before using the analysis for business decisions.

## Repository Structure
```text
market-expansion-toolkit/
├── README.md
├── data/
├── scorecards/
│   └── jakarta_scorecard.csv
├── notebooks/
│   └── starter_analysis.ipynb
└── launch-playbook/
    └── jakarta_90_day_launch.md
```

## Scoring Logic
Higher scores are better for Demand, Supply and Operational Feasibility.
Higher scores indicate more pressure for Competition and Regulatory Friction.

A simple priority score can be calculated as:

`Priority Score = Demand + Supply + Ops Feasibility - Competition - Regulatory Friction`

Use this only as a first-pass filter. Strategic judgment should remain part of the final decision.

## Example Use Cases
- Ride-hailing market entry
- Driver acquisition strategy
- EV / battery swap expansion
- Fleet and B2B mobility partnerships
- Last-mile logistics expansion
- City-by-city rollout planning

## Next Steps
- Add validated Jakarta market data
- Add POI / mobility infrastructure datasets
- Add competitor tracking
- Add geographic heatmaps
- Clone the framework for Manila, HCMC, Hanoi, Surabaya, Cebu, etc.
