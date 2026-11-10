# Statistical Analysis: Heart Failure Prediction Dataset

A complete statistical analysis project using the Heart Failure Prediction dataset. The notebook computes descriptive statistics, creates three visual models, performs a hypothesis test on maximum heart rate by disease status, and includes a written report with academic citations.

## Project Contents

- `analysis.ipynb` — Full Jupyter notebook (data loading, descriptive statistics, visualizations, hypothesis test, and summary)
- `module_summary.pdf` — Written statistical analysis report with all required sections and references
- `requirements.txt` — Pinned dependencies for reproducibility
- `heart.csv` — Heart Failure Prediction dataset (918 rows, 12 columns)

## Dataset

**Heart Failure Prediction Dataset**  
Source: [Kaggle – Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)  
Combined clinical records from multiple UCI heart-disease collections.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sandipdey2/statistical-analysis-project.git
   cd statistical-analysis-project
Install dependencies:Bashpip install -r requirements.txt
Launch Jupyter and open the notebook:Bashjupyter notebook analysis.ipynb
The notebook runs top-to-bottom without errors.ReproducibilityAll package versions are recorded in requirements.txt (generated with pip freeze). The notebook uses relative paths so it can be executed directly from the project folder.AuthorSandip DeyText
Copy this into a file named `README.md` in your project folder, then commit and push:

```bash
git add README.md
git commit -m "Add README with project overview and run instructions"
git push origin main
