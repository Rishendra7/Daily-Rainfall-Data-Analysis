# Daily Rainfall Data Analysis using PySpark

A big data analysis project that uses **Apache Spark (PySpark v4.0)** to analyze 10,000+ daily rainfall records across districts of Telangana, India. The project covers the full data analysis pipeline — from loading and exploration to transformation and analytical operations.

---

## What this project does

- Loads and explores a real-world rainfall dataset (10,000 rows, 7 columns) from NRSC VIC MODEL
- Performs data cleaning, type inspection, and null/missing value detection
- Runs statistical analysis: average, min, max, stddev, correlation
- Applies PySpark transformations: filtering, grouping, aggregation, sampling
- Demonstrates RDD operations alongside DataFrame API
- Includes a bonus student dataset analysis to showcase analytical operations

---

## Dataset

**Rainfall-Data.csv** — 10,000 records of daily rainfall across Telangana districts

| Column | Description |
|---|---|
| State | State name (Telangana) |
| District | District name (e.g. Mancherial) |
| Date | Date of reading |
| Year | Year |
| Month | Month number |
| Avg_rainfall | Average rainfall in mm |
| Agency_name | Data source agency (NRSC VIC MODEL) |

---

## Notebooks

| Notebook | What it covers |
|---|---|
| `DailyRainfall-Data.ipynb` | Main analysis — loading, exploration, stats, filtering, aggregation |
| `Basic_Operation_on_pyspark.ipynb` | Core PySpark DataFrame operations |
| `Exploring_and_Transforming_Data_with_Pyspark.ipynb` | Data transformation techniques |
| `Data_Sampling_in_pyspark.ipynb` | Sampling strategies in PySpark |
| `Performing_analytical_operations_in_pyspark.ipynb` | Aggregations, group-by, averages per subject/group |
| `Pyspark_Student_Data_Analysis_with_RDD.ipynb` | RDD-based analysis on student dataset |
| `Pyspark_Even_Number_Filter.ipynb` | PySpark filtering example |

---

## Tech stack

- Python 3
- Apache Spark 4.0 (PySpark)
- Jupyter Notebook
- CSV data processing (no external database needed)

---

## How to run

**Prerequisites:** Python 3, Java 8+, Apache Spark installed

```bash
# Clone the repo
git clone https://github.com/Rishendra7/Daily-Rainfall-Data-Analysis.git
cd Daily-Rainfall-Data-Analysis

# Install PySpark
pip install pyspark jupyter

# Launch Jupyter
jupyter notebook
```

Open `DailyRainfall-Data.ipynb` to start with the main analysis.

---

## Key findings

- Dataset contains **10,000 rainfall records** across Telangana districts (2025)
- Data sourced from **NRSC VIC MODEL** (National Remote Sensing Centre)
- Analysis includes district-wise rainfall averages, monthly trends, and statistical summaries
- Full analysis report available in `Daily Rainfall Data Analysis Report.pdf`

---

## Project report

A complete written report is included:
- `Daily Rainfall Data Analysis Report.pdf`
- `Daily Rainfall Data Analysis Report.docx`
