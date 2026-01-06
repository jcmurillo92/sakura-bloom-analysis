# Cherry Blossom Bloom Analysis (Japan)

## Project Overview
This project analyzes historical cherry blossom (sakura) bloom dates in Japan to explore how bloom timing has changed over time. Cherry blossoms are highly sensitive to temperature, making their bloom dates a useful indicator of seasonal and climate-related patterns.

The goal of this project is to demonstrate foundational data analysis skills, including data cleaning, exploratory analysis, and clear communication of insights.

---

## Research Questions
- Have cherry blossom bloom dates shifted earlier or later over time?
- How do first bloom dates compare to full bloom dates?
- Are trends consistent across different locations in Japan?

---

## Data Sources
This analysis uses publicly available historical datasets:

- **sakura_first_bloom_dates.csv**
  - Records the first bloom date by year and location

- **sakura_full_bloom_dates.csv**
  - Records the full bloom date by year and location

Each dataset includes:
- Year
- Location
- Bloom date

---

## Data Cleaning
The following data preparation steps were performed:

- Standardized bloom dates into a consistent `YYYY-MM-DD` format
- Converted dates into day-of-year values for easier comparison
- Checked for missing or invalid entries
- Removed rows with incomplete records when necessary
- Verified alignment between first bloom and full bloom datasets

Original raw data files were preserved, and cleaned versions were stored separately.

---

## Analysis Approach
- Compared bloom timing across multiple decades
- Examined the relationship between first bloom and full bloom dates
- Grouped data by decade to reduce year-to-year variability
- Calculated the time gap between first bloom and full bloom events

The analysis focuses on identifying clear and interpretable trends using basic exploratory techniques.

---

## Visualizations
The following visualizations were created to support the analysis:

- Line charts showing bloom timing over time
- Bar charts comparing average bloom dates by decade
- Scatter plots comparing first bloom versus full bloom dates
- Line charts illustrating changes in bloom duration

These visuals help highlight long-term seasonal patterns.

---

## Key Findings
- Cherry blossom blooms have generally occurred earlier in recent decades
- First bloom and full bloom dates tend to move together
- The time between first bloom and full bloom has slightly decreased
- Most locations show similar overall trends, with some regional variation

---

## Limitations
- Some historical records contain missing data
- Bloom timing is influenced by local environmental conditions
- Temperature data was not directly included in this analysis
- Findings are specific to Japan and may not generalize globally

---

## Next Steps
- Integrate historical temperature data for deeper analysis
- Create an interactive dashboard to explore trends by location
- Expand the study to include additional flowering species

---

## Tools Used
- Excel / Google Sheets
- Python (pandas, matplotlib)
- GitHub for version control
