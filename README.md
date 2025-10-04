# STT 810 Project

A concise overview of the project assets and how to get started.

## How to Clone

- Using HTTPS:
  - `git clone https://github.com/<your-username>/<your-repo>.git`
- Using SSH:
  - `git clone git@github.com:<your-username>/<your-repo>.git`
- Then change into the project directory:
  - `cd "STT 810 Project"`

If this repository is not yet on GitHub, you can initialize it locally:
- `git init`
- `git add .`
- `git commit -m "Initial commit"`
- Create a new repository on your hosting provider (e.g., GitHub), then add it as a remote:
  - `git remote add origin https://github.com/<your-username>/<your-repo>.git`
  - `git push -u origin main` (or `master`, depending on your default branch)

## Files and Purpose

- `analysis.ipynb`
  - The main Jupyter Notebook for exploration, modeling, and results. Open this to review or rerun the analysis.

- `crime_unnormalized_features.csv`
  - Features (predictor variables) in their original, unscaled form.

- `crime_unnormalized_targets.csv`
  - Target/outcome variable(s) in original, unscaled form.

- `crime_normalized_features.csv`
  - The same feature set after normalization/scaling for modeling consistency.

- `crime_normalized_targets.csv`
  - Target/outcome variable(s) after normalization/scaling if used in analysis.

- `communities.names`
  - Variable names and brief descriptions/metadata for the dataset columns. Helpful for understanding each feature/target.

## Getting Started

- Prerequisites
  - Git installed to clone the repository.
  - Python 3.8+ and VSCode.
  - Instead of VSCode, you can use Positron. It is a free IDE that is great for data science and works well with Jupyter Notebooks.

- Install Jupyter (if needed):
  - `pip install notebook`  (or `pip install jupyterlab`)

- Launch Jupyter and open the notebook:
  - `jupyter notebook`  (or `jupyter lab`)
  - In the browser UI, open `analysis.ipynb` and run the cells.

## Notes

- Normalized vs. unnormalized files: The normalized CSVs are prepared for modeling steps that benefit from scaled inputs. The unnormalized CSVs preserve original values for reference and interpretation.
- If you have a specific environment (packages/versions), consider adding a `requirements.txt` or `environment.yml` so others can reproduce results exactly.
