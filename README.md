# Customer Trends Data Analysis — Resume-Ready Project

This repository contains an end-to-end data analysis portfolio project demonstrating data cleaning, exploratory analysis, SQL-based analytics, and interactive reporting with Power BI. It's written and organized to be résumé-friendly: clear goals, reproducible steps, and copy-ready bullets you can paste into a CV.

**Tech stack:** Python (pandas, numpy), SQL (MySQL/Postgres/MS SQL compatible), Power BI, Jupyter Notebook

**Data:** `customer_shopping_behavior.csv` — simulated retail/customer transactional and demographic data used for analysis and modeling.

**One-line summary:** Performed end-to-end customer behavior analysis to identify high-value segments, purchase drivers, and actionable retention strategies using Python, SQL, and Power BI.

**What I did (high level):**

- **Data engineering:** cleaned and normalized transaction and customer records; handled missing values and data types for downstream analysis.
- **Exploratory analysis:** computed cohort, frequency, recency, and monetary metrics; created segmentations and churn indicators.
- **SQL analytics:** implemented business questions as parameterized SQL queries in `customer_behavior_sql_queries.sql` to support reproducible reporting.
- **Visualization & reporting:** built an interactive Power BI dashboard (source file included if present) to surface trends and KPIs for stakeholders.
- **Insights & recommendations:** distilled technical results into business recommendations aimed at increasing retention and average order value.

**Quick start**

1. Clone the repo and open the notebook:

```powershell
git clone <your-fork-or-local-path>
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

2. Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter or VS Code to run the analysis end-to-end.
3. (Optional) Load data into a SQL database if you want to run the SQL queries:
    - Create a database in MySQL/Postgres/MS SQL
    - Run the Python notebook cells that push the `customer_shopping_behavior.csv` data into the database
    - Open and run queries in `customer_behavior_sql_queries.sql`
4. Open the Power BI file (if included) or connect Power BI to your SQL database to reproduce the dashboard visuals.

**Files of interest**

- `Customer_Shopping_Behavior_Analysis.ipynb`: main analysis notebook (data cleaning, EDA, SQL connectivity)
- `customer_behavior_sql_queries.sql`: organized SQL queries answering business questions
- `customer_shopping_behavior.csv`: dataset used in the analysis

**How to reproduce locally (conda / venv)**

1. Create environment and install dependencies:

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt  # or install pandas, numpy, sqlalchemy, jupyterlab
```

2. Launch Jupyter:

```bash
jupyter lab
```

If you want, I can create a `requirements.txt` with the minimal packages.

**Résumé-ready bullets (copy these directly into your CV)**

- Performed end-to-end customer behavior analysis using Python and SQL to identify high-value customer segments and key purchase drivers, enabling targeted retention strategies.
- Built parameterized SQL queries and an interactive Power BI dashboard to surface actionable KPIs for stakeholders, improving decision-making speed.
- Cleaned and transformed a transactional customer dataset to support cohort and RFM analyses, producing data used across cross-functional reporting.

**Notes & next steps**

- If you'd like, I can add a `requirements.txt`, a short `CONTRIBUTING.md`, or a one-page PDF project summary tailored for your resume.

**License**
MIT

---

