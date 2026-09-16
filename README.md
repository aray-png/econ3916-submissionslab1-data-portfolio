# The Data Portfolio — Big Mac Index Analysis

## Objective
This project evaluates global currency valuation using The Economist's Big Mac Index, applying purchasing power parity theory to identify systematically over- and undervalued currencies across a 24-year panel of international pricing data.

## Methodology
- Sourced the Big Mac Index dataset directly from The Economist's public GitHub repository, spanning 57 countries and 45 time periods (April 2000 – July 2026), with 54 countries represented in the July 2024 cross-section
- Computed implied Purchasing Power Parity (PPP) exchange rates from local Big Mac prices and derived valuation percentages relative to actual market exchange rates
- Classified the dataset's structural dimensions, distinguishing cross-sectional, time-series, and panel components to guide appropriate analytical treatment
- Conducted a missing data audit, diagnosing Russia's exit from the panel as Missing Not At Random (MNAR) given its association with geopolitical sanctions rather than random data collection gaps
- Built visualizations, including a bar chart of currency valuations by country and a multi-country time-series comparison tracking valuation trends from 2000 to 2026

## Key Findings
- The Swiss franc emerged as the most persistently overvalued currency in the dataset, trading **+41.8% above PPP-implied fair value** in the July 2024 cross-section, and has held that position in every period since January 2015
- The Japanese yen showed a consistent pattern of undervaluation, remaining below PPP-implied fair value in every decade covered by the series — and has been the most dramatically repriced currency since 2010, moving from near-parity to roughly **50 percentage points undervalued** by 2026
- Together, these results illustrate how the Big Mac Index, despite its informal framing, surfaces durable and economically meaningful deviations from currency parity across both space and time
