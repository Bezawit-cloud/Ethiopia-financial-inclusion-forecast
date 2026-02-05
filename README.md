# Ethiopia Financial Inclusion Dashboard

This interactive Streamlit dashboard allows users to explore historical financial inclusion data, understand event impacts, and view forecasts for Ethiopia (2025-2027).

---

## **Live Dashboard**

You can access the live dashboard here:  
[**Open Dashboard**](https://ethiopia-financial-inclusion-forecast-hclh5tkoehvcacprkdfgmy.streamlit.app/)

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
git clone <YOUR_REPO_LINK>
cd ethiopia-fi-forecast
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
Activate the environment:

Windows:

bash
Copy code
venv\Scripts\activate
Mac/Linux:

bash
Copy code
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Dependencies include: streamlit, pandas, matplotlib, seaborn, plotly

Running the Dashboard Locally
Ensure your CSV files are in the repository folder (or dashboard/ if using a subfolder):

observations.csv – Historical financial inclusion data

events.csv – Event-impact data

forecasts.csv – Forecasted values from Task 4

Run the app:

bash
Copy code
streamlit run app.py
Open the link shown in the terminal to view the dashboard in your browser.

Usage
Use the sidebar to navigate between pages: Overview, Trends, Forecasts, Inclusion Projections.

Use sliders, dropdowns, and scenario selectors to interact with the data.

Download tables/visualizations if needed.

Notes
This dashboard uses relative paths for CSV files. Make sure the files are present in the repository when deploying to Streamlit Cloud.

Forecasts include Base, Optimistic, and Pessimistic scenarios.

Key metrics are updated dynamically based on the latest year in observations.csv.




