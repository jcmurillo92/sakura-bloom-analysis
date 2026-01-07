# Cherry Blossom Bloom Timing Analysis (Kyoto, Japan)

## Project Preview
This project analyzes over a century of historical cherry blossom (sakura) bloom data across multiple locations in Japan to identify long-term shifts in seasonal timing.

Key outputs include trend visualizations, comparisons between first and full bloom dates, and summary insights that highlight climate-related patterns observed over time.

---

## Visualization
<img width="857" height="678" alt="first_bloom_trend (2)" src="https://github.com/user-attachments/assets/427354d4-331c-43bb-89b3-3581581483cc" />

---

## Project Overview
This project examines historical cherry blossom (sakura) bloom dates in Japan to understand how bloom timing has changed over time. Sakura bloom dates are highly sensitive to temperature and seasonal conditions, making them a widely recognized natural indicator of climate and environmental change.

The goal of this analysis is to demonstrate foundational data analytics skills, including data organization, cleaning, exploratory analysis, visualization, and clear communication of insights using real-world historical data.

This project is designed as a portfolio-ready, junior-level data analytics case study.

---

## Research Questions
- Have cherry blossom bloom dates shifted earlier or later over time?
- How do first bloom dates compare to full bloom dates?
- Are bloom timing trends consistent across different locations in Japan?
- What long-term patterns can be observed across decades?

---

## Data Sources
This analysis uses publicly available historical datasets:

- `sakura_first_bloom_dates.csv`  
  Records the **first bloom date** by year and location

- `sakura_full_bloom_dates.csv`  
  Records the **full bloom date** by year and location

All raw datasets are stored without modification to preserve data integrity.

---

## Repository Structure
sakura-bloom-analysis/
│
├── README.md
│
├── data/
│ ├── raw/
│ │ ├── sakura_first_bloom_dates.csv
│ │ ├── sakura_full_bloom_dates.csv
│ │ └── README.md
│ │
│ ├── processed/
│ │ └── README.md
│ │
│ └── plots/
│ └── README.md

yaml
Copy code

---

## Data Cleaning & Preparation
The following data preparation steps were performed:

- Verified date formats and standardized year values
- Checked for missing or incomplete records
- Ensured consistent location naming
- Maintained separation between raw and processed data

No raw files were altered during the cleaning process.

---

## Analysis Approach
The analysis focuses on exploratory data analysis techniques, including:

- Comparing first bloom versus full bloom timing
- Evaluating year-over-year trends
- Identifying long-term shifts in bloom dates
- Summarizing patterns across multiple geographic locations

Simple summary statistics and visual trend analysis are used to support findings.

---

## Sample Visualizations
*(Visualizations are stored in the `data/plots/` directory and can be embedded here once available.)*

Example visual outputs include:
- Line charts showing first bloom dates over time
- Line charts showing full bloom dates over time
- Comparative plots between first and full bloom timing
- Trend visualizations highlighting long-term shifts

---

## Summary Statistics
- Dataset spans more than 100 years of historical bloom records
- Includes multiple geographic locations across Japan
- First bloom dates consistently occur earlier than full bloom dates
- Recent decades show increased variability in bloom timing

---

## Key Findings
- Cherry blossom bloom dates demonstrate a clear long-term shift toward earlier seasonal onset, particularly in recent decades
- First bloom dates consistently occur earlier than full bloom dates across locations
- Long-term trends suggest increasing variability in bloom timing
- Observed patterns align with existing research on rising seasonal temperatures

---

## Why This Analysis Matters
Cherry blossom bloom timing is widely used as a natural indicator of climate variability. Analyzing long-term bloom trends helps contextualize broader environmental changes and demonstrates the value of historical datasets in climate-related analysis.

This project highlights how relatively simple datasets can be used to uncover meaningful long-term patterns.

---

## Limitations
- Not all locations have continuous records across all years
- The analysis is descriptive rather than predictive
- Temperature and weather data are not directly included

---

## Future Improvements
Future iterations of this project may:
- Integrate climate and temperature datasets
- Apply predictive modeling techniques to forecast bloom timing
- Create interactive visual dashboards
- Expand analysis to additional regions or countries

---

## Tools Used
- GitHub
- CSV datasets
- Spreadsheet-based analysis
- Data visualization tools
