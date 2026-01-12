# Fantasy Football ADP Value & Risk Analyzer

## Project Overview

This project analyzes fantasy football Average Draft Position (ADP) data alongside historical performance and risk factors to identify undervalued and overdrafted players.

The goal is to provide data-driven insights that support draft decision-making by quantifying expected value and uncertainty across positions.

## Problem Statement

ADP reflects end-users' collective ranking of NFL players during fantasy football drafts. While the ADP statistic is generally predictive of fantasy players' success, it often fails to account for player volatility, injury, and contextual usage changes. This project evaluates how ADP diverges from data-driven projections, demonstrating limitations to this widely used statistic.

## Data Sources
### Data Availability & Licensing

This project uses publicly available fantasy football datasets from third-party providers
(e.g., ADP, historical player statistics, and injury data).

Due to licensing and terms-of-service restrictions, **raw datasets are not included** in this
repository. The repository provides scripts to ingest, clean, and process the data so results
can be reproduced using user-supplied datasets.

Any outputs included in this repository (tables or figures) are derived summaries and do not
contain redistributed raw data.

### Source Attribution
**Player statistics:** Pro-Football-Reference (Passing, Rushing, Receiving, Defense, and Kicking for the 2023-2025 seasons)

**ADP data:** FantasyPros (ADP averaged from that of ESPN, Sleeper, CBS, NFL, RTSPORTS, and FANTRAX)

**Injury history:** Pro-Football_Reference

## Repository Structure

```
fantasy-adp-analyzer/
├── data/           # Data ingestion and processing
├── notebooks/      # Exploratory analysis
├── src/            # Core pipeline code
├── outputs/        # Tables and figures
├── README.md
└── requirements.txt
```

## Methodology
*(To be completed)*

## Key Results
*(To be completed)*

## Limitations
*(To be completed)*
This analysis is conducted for leagues using **PPR Scoring** (points-per-reception) format. Leagues with different scoring settings will likely have variations on the fantasy points awarded to players over the course of the season. As such, point totals from player to player may vary, resulting in an altered ADP.

Below is the PPR scoring utilized in this analysis (from Pro-Football-Reference):
*1 point per 25 yards passing
*4 points per passing touchdown
*-2 points per interception thrown
*1 point per reception
*1 point per 10 yards rushing/receiving
*6 points per TD
*2 points per two-point conversion
*-2 points per fumble lost (est. prior to 1994)

## Future improvements
*(To be completed)*

## Responsible Use
This project is for educational and analytical purposes and does not constitute betting or financial advice.
