
# 30 Days — 30 Data Analysis Projects

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

Day  | Project    | Tool Used
-----| ----------- | --------- 
1    | [BlinkIt Sales Analysis](https://github.com/dev01734/30-Day---30-Data-Analyses-Projects/tree/main/1-BlinkIt%20SQL)   | SQL


---------------------------------------------------------------------------------------------------------------------------------------------------------------------

> A personal challenge repository: one small data analysis project per day for 30 days. Each project is a focused, reproducible analysis with code, data, and short write-up or notebook.

This workspace contains individual project folders (example: `1-BlinkIt SQL`) used to practice common analysis tasks: cleaning, joins, aggregation, time-series, visualization, and interpretation.

## Goals

- Build a consistent portfolio of 30 short, self-contained analyses.
- Practice a mix of SQL-style queries, pandas workflows, and visual storytelling.
- Produce reproducible notebooks and small artifacts (CSV, plots, short notes) for each day.

## Repository structure (convention)

Each project should live in its own top-level folder and follow this pattern:

- `NN-Project-Title/` (NN = 01..30)
	- `NN-Project-Title.ipynb` — primary notebook (analysis, visuals, narrative)
	- `data/` — raw or sample CSVs used for the project (don't store very large files)
	- `README.md` — short summary and notes for this project
	- `requirements.txt` or `environment.yml` (optional) — dependencies specific to the project
	- `scripts/` (optional) — helper scripts (e.g., build sqlite, ETL, reproducible runs)

Example: `1-BlinkIt SQL/` (already in this workspace) contains `blinkit SQl.ipynb`, `Customers.csv`, `Orders.csv`, and `OrderDetails.csv`.

## Naming and style conventions

- Use `NN-Short-Title` for folder names so projects sort chronologically.
- Notebook names should begin with the same `NN-` for clarity.
- Keep notebooks short (30–200 cells) and focused on a single question or theme.
- Add a short `README.md` in each project stating the question, data sources, and key takeaways.

## Quick start (Windows PowerShell)

1. Clone or open this workspace.
2. Create and activate a virtual environment (recommended):

```powershell
python -m venv .venv
\.venv\Scripts\Activate.ps1
```

3. Install core packages used across projects:

```powershell
pip install pandas jupyter matplotlib seaborn pandasql sqlalchemy
```

4. Open a project's notebook (example):

```powershell
jupyter notebook "g:\30 Data Analyst\1-BlinkIt SQL\blinkit SQl.ipynb"
```

Or open the folder in VS Code and use the built-in notebook support.

## Project checklist (template)

- [ ] Short question or objective
- [ ] Data sources listed (files & schema)
- [ ] Data loading and cleaning steps in notebook
- [ ] One or more reproducible analyses (code + comments)
- [ ] Key visualizations and an interpretation bullet list
- [ ] Small README with findings and how to run

## Reproducibility tips

- Keep raw data in `data/` and derived artifacts in `outputs/` if needed.
- Pin important dependencies with a `requirements.txt` for each project.
- For SQL-style work, consider adding a small script to import CSVs into a local SQLite DB for faster queries.
