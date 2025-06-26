# RTS Data Analyst Take-Home Assignment

This repository contains my solution for the RTS Data Analyst take-home case study.  
It demonstrates my approach to data cleaning, exploration, business logic, and actionable recommendations for content production by theme.

---

## 📁 Project Structure

- `data/` — Input datasets from RTS
- `notebooks/` — Jupyter notebook with the full workflow (`rts_analysis.ipynb`)
- `reports/` — Final presentation slides
- `dashboards/` — Power BI dashboard file(s)
- `requirements.txt` — Python dependencies

---

## 🧪 Environment Setup

1. **Clone the repository:**
    ```bash
    git clone <your_repo_url>
    cd rts-data-analyst-case
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/rts_analysis.ipynb
    ```

---

## 📊 How to Reproduce the Analysis

1. Make sure all datasets are in the `data/` folder.
2. Open `rts_analysis.ipynb` and run all cells for:
    - Data cleaning (dates, numeric values, outliers)
    - Merging of audience metrics with theme tags
    - Calculation of KPIs at theme and segment level
    - Automated recommendations based on business logic
    - Export of cleaned and analyzed data
3. To explore the interactive dashboard, open the Power BI file in `dashboards/`.

---

## 🧩 Key Python Libraries

- pandas
- numpy
- matplotlib
- scipy

(See `requirements.txt` for full details.)

---

## 🚦 Solution Overview

- **Objective:**  
  Recommend content production volumes by theme (info, sport, musique, société, humour) and help RTS understand which editorial functions (acquisition, retention, loyalty) each theme supports.
- **Methodology:**  
    - Robust data cleaning (formatting, outlier capping)
    - Calculation and normalization of KPIs
    - Business-rule recommendations using quantile-based thresholds
    - Clear outputs: segment/theme tables, dashboard, and presentation slides
- **Outputs:**  
    - Cleaned data and KPIs
    - Theme and segment-level recommendations
    - Power BI dashboard and slides

---

## 📬 Contact

Questions or feedback? Reach out at [your email] or [LinkedIn].

