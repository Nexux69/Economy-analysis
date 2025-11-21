# Economy-analysis

A small, friendly exploration of the "Cost of Living Index 2022" dataset. This repository contains a Jupyter notebook that inspects the data, performs basic cleaning, creates visualizations, and surfaces initial observations and ideas for further analysis.

Table of contents
- What’s in this repo
- Quick start
  - Run in Google Colab
  - Run locally
- Requirements
- Dataset
- What the notebook does
- Ideas for next steps
- Contributing
- License & credits
- Contact

What’s in this repo
- analysis.ipynb — the main Jupyter notebook with the exploratory analysis.
- Cost_of_Living_Index_2022.csv — (expected) dataset used by the notebook. Add this file to the repo or upload it to your Colab session.
- README.md — this document.

Quick start

Run in Google Colab (recommended for quick start)
1. Open analysis.ipynb in Google Colab.
2. Upload `Cost_of_Living_Index_2022.csv` when prompted (Colab file upload) or mount your Google Drive and place the CSV there.
3. Run the notebook cells sequentially.

Run locally
1. Clone the repository:
   git clone https://github.com/Nexux69/Economy-analysis.git
2. Create and activate a virtual environment (recommended):
   python3 -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   .venv\Scripts\activate     # Windows (PowerShell)
3. Install dependencies:
   pip install -r requirements.txt
   If you don't have a requirements file, install:
   pip install pandas numpy matplotlib seaborn jupyterlab
4. Ensure `Cost_of_Living_Index_2022.csv` is in the repo root (or update the path in the notebook).
5. Run Jupyter and open the notebook:
   jupyter notebook analysis.ipynb

Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- (Optional) Google Colab — for cloud execution and easy file uploads

Dataset
The notebook uses a "Cost of Living Index 2022" CSV. If you plan to republish analysis or visuals, please cite the original data source. Replace or update the CSV file with the canonical dataset you obtained and add attribution where appropriate.

What the notebook does
- Loads the CSV and previews the data (head, tail, columns, shape)
- Basic cleaning and type checks (missing values, dtypes)
- Visualizations: distributions, pairwise comparisons, and possible correlations between indices
- Short summary observations and suggestions for deeper analysis

Ideas for next steps / improvements
- Normalize indices to a single scale for easier cross-country comparison.
- Add regional grouping (continent) to compare regions rather than individual countries.
- Merge with GDP / population / median income datasets to analyze affordability vs purchasing power.
- Build an interactive dashboard (Streamlit / Dash) for live filtering and exploration.
- Add tests and CI for reproducible results.

Contributing
Contributions are welcome. If you want to add better plots, notebook commentary, or merge other datasets:
- Open an issue to discuss big changes.
- Send a pull request with a clear description of what you changed.
- If you forked the repo and built something cool, please open a PR or create an issue so we can link to it.

License & credits
- The code in this repo is provided as-is. If you want a specific license (e.g., MIT), add a LICENSE file to the repository.
- Credit the original dataset source when republishing or sharing derived visuals.

Contact
If anything in the notebook is unclear or you want help extending it, reach out on GitHub: @Nexux69.

Thanks for checking out this small exploration — let’s make data less boring together. 🚀
