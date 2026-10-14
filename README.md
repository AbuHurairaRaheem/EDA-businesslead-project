# Business Leads — Exploratory Data Analysis

A small Python EDA project exploring a 120-record business-lead dataset and its readiness, contact completeness, and notes. The script cleans selected missing values, derives simple readiness/completeness features, and creates charts for the dataset.

**Tech stack:** `Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

## What it covers

- Loads and profiles the CSV, including missing values and descriptive statistics.
- Compares lead readiness and contact-method counts.
- Derives flags/categories such as hot-lead status, notes length, and completeness.
- Saves distribution, readiness, correlation, and box-plot visualizations.

## Files and run instructions

The current repository stores its source and data in `EDAtask.zip`. Extract it, install the Python dependencies, and run the script from the extracted directory so it can find `business_leads.csv`:

```bash
unzip EDAtask.zip
cd EDAtask
python -m pip install pandas numpy matplotlib seaborn
python lec2.5.py
```

The charts are saved as PNG files. Some plotting calls also open interactive windows.

## Scope and deployment

This is exploratory analysis, not a predictive machine-learning model or an AI lead-qualification system. The current source does not document the dataset’s full provenance or licensing; clarify that before redistributing the data. There is no live web demo or verified Vercel deployment for this Python project.
