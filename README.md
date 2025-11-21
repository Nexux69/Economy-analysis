```markdown
# Economy-analysis

A small exploratory data analysis project using the "Cost of Living Index 2022" dataset. The main notebook `analysis.ipynb` (Colab-compatible) performs data loading, basic cleaning, and visualizations of cost-of-living metrics by country and region.

## Contents
- `analysis.ipynb` — Jupyter / Colab notebook with the analysis and visualizations.
- `Cost_of_Living_Index_2022.csv` — dataset used by the notebook.
- `images/analysis_dashboard.png` — screenshot of the dashboard visualizations (place the image here).

## Preview
Below is a screenshot of the dashboard/visualizations from the notebook:

![Analysis Dashboard](images/analysis_dashboard.png)

If the above image does not render on GitHub, you can also reference the raw file directly:
![Analysis Dashboard (raw link)](https://github.com/Nexux69/Economy-analysis/blob/main/Dashboard.png)

## How to run
1. Open `analysis.ipynb` in Jupyter Notebook or Google Colab.
   - To open in Colab: upload the notebook to Colab or use "Open with Colab" if available.
2. Make sure the CSV file `Cost_of_Living_Index_2022.csv` is in the same directory (the notebook expects `/content/Cost_of_Living_Index_2022.csv` when run in Colab if you upload the file through the Colab UI).
3. Install requirements if running locally:
   - Python 3.8+
   - pandas
   - numpy
   - matplotlib
   - seaborn
   Example (pip):
   ```
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the notebook cells sequentially.

## Notes
- The notebook uses Colab's file upload helper in the first cell; when running locally you may need to adjust the file path or load the CSV directly with `pd.read_csv("Cost_of_Living_Index_2022.csv")`.
- Save your dashboard screenshot to `images/analysis_dashboard.png` so it appears in this README.

## License
Add a license file if you wish (e.g., MIT). This README does not create any license by itself.
```
