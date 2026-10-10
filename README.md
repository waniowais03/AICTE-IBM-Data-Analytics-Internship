# Retail Sales Data Analysis and AI-Based Sales Prediction

**Author:** Owais Bashir Wani

## Project overview
This educational project analyzes retail order data using Python and builds a machine-learning model to estimate order sales. It includes data inspection, basic cleaning, category/region/monthly analysis, visualizations, and a Random Forest regression model.

## Dataset
The bundled file `data/sales_data.csv` is **synthetic sample data generated for demonstration**. It does not represent a real business, customer, or official internship dataset. The dataset is included in this repository so the notebook can run without downloading data. If the internship coordinator supplied a required dataset, replace this demo dataset and update the analysis/report before submission.

Columns: `Order_ID`, `Order_Date`, `Region`, `Category`, `Product`, `Quantity`, `Unit_Price`, `Discount`, `Sales`.

## Tools and technologies
- Python
- pandas and NumPy for data handling
- Matplotlib for charts
- scikit-learn for the Random Forest regression model
- Jupyter Notebook

## Project files
- `OwaisBashirWani_RetailSalesAnalysis.ipynb` — complete analysis and model notebook
- `requirements.txt` — Python dependencies
- `OwaisBashirWani_ProjectReport.docx` — project report
- `README.md` — project documentation
- `data/sales_data.csv` — synthetic demonstration dataset

## Setup and run
1. Install Python 3.10 or later.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Create and activate a virtual environment (optional but recommended):
   - Windows: `py -m venv .venv` then `.venv\Scripts\activate`
   - macOS/Linux: `python3 -m venv .venv` then `source .venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Start Jupyter: `jupyter notebook`
7. Open `OwaisBashirWani_RetailSalesAnalysis.ipynb` and choose **Run All**.

## Methodology
1. Load and inspect the data.
2. Remove duplicate rows and records with missing required fields or invalid quantities/prices/sales.
3. Aggregate sales by category, region, and month.
4. Train a Random Forest regressor using a train/test split.
5. Evaluate with MAE, RMSE, and R² and compare actual versus predicted sales.

## Limitations
Because the dataset is synthetic, findings and model metrics are only a demonstration of the workflow. They must not be presented as real-world business results. The model uses order characteristics to estimate the generated `Sales` value; this is a learning exercise, not a production forecasting system.

## GitHub upload
Create a public repository (if permitted by your internship rules), upload all files while preserving the `data` folder, and commit the changes. Copy the repository URL into the certificate-verification form's **GitHub Repository** field. Do not upload private data, passwords, API keys, or personal customer information.
