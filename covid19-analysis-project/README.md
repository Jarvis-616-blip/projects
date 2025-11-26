
# COVID-19 Data Analysis Project
This folder contains a ready-to-run Jupyter Notebook for the Module 12 assignment: **COVID-19 Data Analysis**.

## Files in this folder
- `COVID19_Data_Analysis.ipynb` — the main Jupyter Notebook with code, EDA and instructions.
- `Module12_CaseStudy_COVID19.csv` — placeholder synthetic dataset (created only if the LMS file is missing).
- `Module12_World_Happiness.csv` — placeholder synthetic dataset (created only if the LMS file is missing).
- `merged_covid_happiness_summary.csv` — will be created by the notebook if merging succeeds.

## How to use
1. Replace the placeholder CSVs with the real dataset files from your LMS if you have them, or keep them for testing.
2. Open and run `COVID19_Data_Analysis.ipynb` in Jupyter Notebook / JupyterLab / Google Colab.
3. After running, zip this folder and upload to Google Drive. Share the zip as requested in the assignment portal.

## Notes
- The notebook is intentionally defensive: it creates small synthetic datasets so the analysis runs even when source files are not present. Replace them with real data for real results.
- If your dataset uses different column names (e.g., `Confirmed` instead of `cumulative_cases`), modify the notebook cell labeled "Prepare for merge" to match your files.

---
