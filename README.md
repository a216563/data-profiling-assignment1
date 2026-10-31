# Assignment 1: Data Profiling (EDA) Report

## Team Information

- **Member 1:** Tashvindren A/L Parthiben (Matric No: A216563)
- **Member 2:** JEEVENEISH A/L D.K. RAJAN (A216686)
- **Member 3:** MALCOLM PAUL ([Insert Matric No])


## Scenario Overview

This project profiles public sector digital infrastructure using the official **Malaysia Government Mobile Applications Dataset (GAMMA)** from data.gov.my. The analysis examines application lifecycles, deprecation tracking, data quality issues, and platform deployment balance to evaluate the dataset's suitability for public administration analytics.

The main questions are:
- What proportion of government applications are active versus decommissioned, and how reliably are shutdown dates recorded?
- How do application lifespans and release frequencies vary across Android, iOS, and Huawei platforms?
- Are certain government agencies overrepresented in the dataset, potentially introducing bias?

## Data Source

- **Source:** [data.gov.my – Government Mobile Applications](https://data.gov.my/data-catalogue/government_apps)
- **Direct CSV API:** https://storage.data.gov.my/publicadmin/government_apps.csv
- **Publishing Body:** Jabatan Digital Negara, Ministry of Digital, Malaysia
- **Acquisition Method:** The dataset is retrieved directly from the public CSV endpoint using Python pandas.

## Repository Contents

- `assignment1_data_profiling.ipynb` – Jupyter notebook containing the scenario, data source, data profiling, data quality issue handling, diagnostic visualizations, PII and bias risk assessment, and conclusion.
- `requirements.txt` – Python dependencies required to run the notebook.
- `README.md` – Project overview and instructions.

## Instructions to Run the Notebook

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/data-profiling-assignment1.git
cd data-profiling-assignment1
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Install the Dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `assignment1_data_profiling.ipynb`.

### 4. Execute the Notebook

Run all cells sequentially from top to bottom.

An internet connection is required to retrieve the dataset from the public CSV endpoint.

## Expected Outputs

The notebook should include:

1. Scenario and research questions.
2. Data source and acquisition method.
3. Missing-value analysis and handling.
4. Outlier detection and handling.
5. Identification and correction of other data quality issues.
6. At least two labeled diagnostic charts.
7. PII and bias risk assessment.
8. Conclusion on data suitability and remaining limitations.

## Notes

- All team members and matric numbers must be included.
- The notebook must execute from top to bottom without errors.
- Data cleaning decisions should be explained and justified.
- The analysis should focus on data quality and profiling rather than only presenting findings.