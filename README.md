# Economy-analysis

Hey — welcome! 👋 This repo contains a friendly exploration of the "Cost of Living Index 2022" dataset. The main analysis happens in:

- `analysis.ipynb` — a Jupyter / Google Colab notebook that reads the CSV, inspects the data, and creates plots and summaries to help understand cost-of-living differences between countries.

Dataset used in the notebook:
- `Cost_of_Living_Index_2022.csv` — indexes such as Cost of Living, Rent Index, Groceries Index, Restaurant Index, and Local Purchasing Power.

---

## Dashboard (screenshot)

Below is your dashboard screenshot. To show this in the repo, save the image to `images/dashboard.png` (create the `images/` folder if needed). The README references that path so the image will render on GitHub.

<img src="https://raw.githubusercontent.com/OWNER/REPO/BRANCH/path/to/image.png" alt="Cost-of-living dashboard" width="800" />

Figure: Dashboard view (screenshot provided).

---

## How to include your screenshot in the repository

1. Create an images folder and add the screenshot file:
   - Save your screenshot locally as `dashboard.png`.
   - Put it in a folder called `images` at the repository root so the path is `images/dashboard.png`.

2. Commit and push:
   ```bash
   mkdir -p images
   # copy your file into images/dashboard.png, then
   git add images/dashboard.png README.md
   git commit -m "Add dashboard screenshot and README"
   git push
   ```

If you'd like, I can prepare the exact commit message or show a one-line curl/GitHub CLI command to upload the file if you prefer not to use the git client.

---

## How to run the notebook

Option A — Google Colab (recommended for quick start)
- Open `analysis.ipynb` in Colab, upload `Cost_of_Living_Index_2022.csv` when prompted (or upload the CSV to the Colab session) and run the cells.

Option B — Local
- Install Python 3.8+ and create a virtualenv:
  ```bash
  python -m venv .venv
  source .venv/bin/activate   # macOS / Linux
  .venv\Scripts\activate      # Windows
  pip install pandas numpy matplotlib seaborn jupyterlab
  jupyter notebook analysis.ipynb
  ```
- Make sure `Cost_of_Living_Index_2022.csv` is next to the notebook or update the path in the notebook.

---

## Notes & next steps
- The README now references your dashboard screenshot at `images/dashboard.png`. Add that file to the repo and GitHub will render it automatically.
- Suggestions for extending the project: normalize indices for direct comparison, add continent grouping, merge with GDP or income data, build an interactive dashboard with Streamlit or Dash.

Thanks — I added the README content above with the embed for your screenshot. If you want, I can also create the `images/` folder and commit the image for you if you give me permission to push to your repo (or you can upload the image yourself using the steps above).
