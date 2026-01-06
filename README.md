# Sakura Bloom Timing Analysis (Japan)

## Project Overview
This project analyzes historical cherry blossom (sakura) bloom dates in Japan to examine how bloom timing has changed over time. Sakura bloom dates are highly sensitive to temperature and seasonal conditions, making them a widely used natural indicator of climate and environmental change.

The goal of this project is to demonstrate foundational data analysis skills, including data organization, cleaning, exploratory analysis, visualization, and clear communication of insights using real-world historical data.

This project is structured as a portfolio-ready, junior-level data analytics case study.

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

The raw datasets are stored without modification to preserve data integrity.

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
- Separated raw and processed data to preserve originals

No raw files were altered during the cleaning process.

---

## Analysis Approach
The analysis focuses on exploratory techniques, including:

- Comparing first bloom vs. full bloom timing
- Evaluating year-over-year trends
- Identifying long-term shifts in bloom dates
- Summarizing patterns across multiple locations

Simple summary statistics and visual trend analysis are used to support findings.

---

## Visualizations
Visualizations were created to better understand long-term patterns and trends, including:

- Line charts showing first bloom dates over time
- Line charts showing full bloom dates over time
- Comparative plots between first and full bloom timing
- Trend visualizations highlighting long-term shifts

All visual outputs are stored in the `data/plots/` directory.

---

## Key Findings
- Cherry blossom bloom dates show a gradual shift toward earlier bloom timing in recent decades
- First bloom dates consistently occur earlier than full bloom dates
- Long-term trends suggest increasing variability in bloom timing
- Observed patterns align with existing research on rising seasonal temperatures

---

## Limitations
- Not all locations have continuous records across all years
- The analysis is descriptive rather than predictive
- Temperature and weather data are not directly included

---

## Future Improvements
- Integrate climate and temperature datasets
- Build predictive models for bloom timing
- Create interactive visual dashboards
- Expand analysis to additional regions

---

## Tools Used
- GitHub
- CSV datasets
- Spreadsheet-based analysis
- Data visualization tools
