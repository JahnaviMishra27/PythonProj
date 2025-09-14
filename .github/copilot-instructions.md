# Copilot Instructions for PythonProj

## Project Overview
This workspace is organized for data analysis and visualization using Jupyter Notebooks. The main focus is on job skill analytics, data cleaning, merging, and visualization. The project is structured into two main folders:
- `Advanced/`: Contains notebooks for advanced data cleaning, merging, and visualization tasks.
- `Project/`: Contains notebooks for exploratory data analysis (EDA) and job skill analysis.

## Key Patterns & Conventions
- **Notebook-centric workflow:** All code is written and executed in Jupyter Notebooks (`.ipynb`). Each notebook typically starts with data import, cleaning, analysis, and visualization steps.
- **File naming:** Notebooks are numbered to indicate workflow order (e.g., `1_cleaning_chart.ipynb`, `2_Job_Skill.ipynb`).
- **Data flow:** Data is loaded, cleaned, and merged across multiple notebooks. Intermediate results may be saved and loaded between notebooks.
- **Visualization:** Common libraries include `matplotlib`, `seaborn`, and `plotly`. Use clear, labeled plots for all visualizations.
- **Python environment:** Use a consistent Python environment for all notebooks. Install dependencies via notebook cells or workspace environment tools.

## Developer Workflows
- **Running notebooks:** Open notebooks in VS Code and run cells sequentially. Ensure kernel is set to the correct Python environment.
- **Adding dependencies:** Install new packages using `!pip install <package>` in a notebook cell or update the workspace environment.
- **Debugging:** Use cell-by-cell execution to isolate issues. Print intermediate results for troubleshooting.
- **Data files:** Place all data files in a dedicated folder (not present yet; create `data/` if needed). Reference data files with relative paths.

## Integration Points
- **External data:** Notebooks may load CSV or Excel files. Ensure data files are available locally.
- **No custom modules:** All code is currently inline in notebooks; no Python packages or scripts are imported from the workspace.

## Example Workflow
1. Open `Project/1_EDA.ipynb` and run all cells to perform initial data exploration.
2. Proceed to `Project/2_Job_Skill.ipynb` for skill analysis.
3. Use notebooks in `Advanced/` for further cleaning, merging, and visualization.

## Best Practices
- Keep notebooks organized and well-commented.
- Save intermediate results if needed for downstream analysis.
- Use markdown cells to document analysis steps and findings.

---
For questions or missing conventions, ask the user for clarification or examples from their workflow.
