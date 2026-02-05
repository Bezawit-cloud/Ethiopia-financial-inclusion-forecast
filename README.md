# Ethiopia Financial Inclusion Dashboard

This interactive Streamlit dashboard allows users to explore historical financial inclusion data, understand event impacts, and view forecasts for Ethiopia (2025-2027).
[https://ethiopia-financial-inclusion-forecast-hclh5tkoehvcacprkdfgmy.streamlit.app/]

---

## **Features**

1. **Overview Page**
   - Key metrics for the latest year
   - Account Ownership, Mobile Money Accounts, and Active Usage Rate
   - Quick visual summary cards

2. **Trends Page**
   - Interactive time series plots of historical data
   - Filter by year range
   - Compare different financial inclusion indicators

3. **Forecasts Page**
   - Forecasts for 2025-2027
   - Scenario selection: Base, Optimistic, Pessimistic
   - Visualizes confidence intervals and expected trends

4. **Inclusion Projections Page**
   - Progress toward 60% account ownership target
   - Scenario-based projections
   - Interactive progress visualization

---

## **Installation**

1. Clone this repository:

```bash
git clone <https://github.com/Bezawit-cloud/Ethiopia-financial-inclusion-forecast>
cd ethiopia-fi-forecast
python -m venv venv
venv\Scripts\activate
source venv/bin/activate
pip install -r requirements.txt
Running the Dashboard

Make sure your CSV files are in the repository folder (or dashboard/ if using a subfolder):

observations.csv – Historical financial inclusion data

events.csv – Event-impact data

forecasts.csv – Forecasted values from Task 4

Run the app:

streamlit run app.py


Open the link shown in the terminal to view the dashboard in your browser.
Usage

Use the sidebar to navigate between pages: Overview, Trends, Forecasts, Inclusion Projections.

Use sliders, dropdowns, and scenario selectors to interact with the data.

Download tables/visualizations if needed.

Notes

This dashboard uses relative paths for CSV files. Make sure the files are present in the repository when deploying to Streamlit Cloud.

Forecasts include Base, Optimistic, and Pessimistic scenarios.

Key metrics are updated dynamically based on the latest year in observations.csv

