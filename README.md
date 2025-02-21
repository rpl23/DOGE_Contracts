# DOGE Contracts Analysis

## Overview
This repository contains a Colab notebook analyzing Department of Defense (DoD) Other Transaction Authority (OTA) agreements and DOGE contracts. The analysis provides insights into contract distributions, values, and patterns across different agencies, time periods, and contract types.

## Data Source
- Data extracted from [G2Xchange DOGE Tracker](https://app.g2xchange.com/doge-tracker) as of February 21, 2025
- Preprocessed and cleaned for analysis

## Analysis Components

### Financial Analysis
- Contract ceiling analysis by agency
- Average contract value trends by fiscal quarter
- Contract value distribution by contract type

### Temporal Analysis
- Monthly contract signing trends (May 2015 - Present)
- Fiscal quarter analysis
- Contract lifecycle status analysis

### Categorical Analysis
- Distribution across NAICS codes (Business Types)
- Contract type distribution
- Agency participation metrics
- Contract status breakdown

### Textual Analysis
- Contract description analysis
- Token frequency analysis
- Key terms extraction

## Prerequisites
```python
# Required libraries
pandas
numpy
matplotlib
seaborn
nltk
plotly
```

## Getting Started
1. Clone this repository
2. Install prerequisites
3. Open `DOGE_Contracts_Analysis.ipynb` in Jupyter Notebook/Lab
4. Run all cells to reproduce the analysis

---
*Note: This analysis is based on publicly available data and is intended for informational purposes only.*
