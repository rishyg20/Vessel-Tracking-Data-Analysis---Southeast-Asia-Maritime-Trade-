# Vessel Tracking Data Analysis - Southeast Asia Maritime Trade

Analysis of vessel movements and cargo patterns in Southeast Asia over a 5-day period (August 20-24, 2024).

---

## Data Files Required

Place in the same directory as the notebook:

1. **vessel_positions.csv** - 71,635 observations × 54 columns (vessel tracking data)
2. **vessel_characteristics.csv** - 14,757 vessels × 212 columns (vessel specifications)

---

## Running the Notebook

Execute cells sequentially from top to bottom. Total runtime: 5-10 minutes.

---

## Analysis Structure

1. **Data Cleaning** - Remove invalid data, convert timestamps, validate ranges
2. **EDA** - Draft/speed/status relationships
3. **Vessel Classification** - Categorize by DWT (Handymax to Capesize)
4. **Cargo Analysis** - Commodity patterns by vessel class
5. **Geographic Analysis** - Southeast Asia polygon definition and vessel identification
6. **Southeast Asia Deep Dive** - Cargo types, exports by country, destinations, operators, draft analysis
7. **ETA Prediction** - Feature engineering and system architecture design

---

## Key Findings

- Coal dominates at 38.1% of Southeast Asian cargo
- China receives 41.9% of exports
- Indonesian operators lead in vessel ownership
- 62% of vessels operate fully loaded (>90% draft utilization)
- 90.7% of trade stays within Asia

---

## Requirements

Python 3.8+, Jupyter Notebook, pandas, numpy, matplotlib, seaborn

---