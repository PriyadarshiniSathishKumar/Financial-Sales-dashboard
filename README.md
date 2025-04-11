## 📊 Financial Sales Dashboard

The **Financial Sales Dashboard** is an interactive data visualization tool built with **Streamlit**, **Plotly**, and **DuckDB**. It allows users to upload a financial Excel file and visualize key performance indicators (KPIs), trends, and summaries to make better business decisions.

---

### 🔧 Features

- Upload Excel financial data via a simple UI
- View KPIs such as Accounts Receivable, Payable, Equity Ratio, and Debt Equity
- Monthly vs yearly comparisons using bar and line charts
- Beautiful Plotly-based visuals (bar, line, gauge, and KPI metrics)
- Uses DuckDB to perform SQL queries on in-memory Pandas DataFrames
- Dashboard includes:
  - Monthly budget vs forecast trends
  - Yearly sales per account
  - Business unit sales comparison

---

### 📁 File Structure

- `streamlit_app.py`: Main application file
- `requirements.txt`: Python dependencies

---

### 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/financial-sales-dashboard.git
cd financial-sales-dashboard
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run streamlit_app.py
```

---

### ✅ Requirements

- Python 3.8+
- Streamlit
- DuckDB
- Pandas
- Plotly
- openpyxl

---

### 📂 Sample Input

Upload a cleaned Excel file with columns like:
- `Year`, `Account`, `Scenario`, `business_unit`, `Jan`, `Feb`, ..., `Dec`

---

### 📸 Output


https://github.com/user-attachments/assets/acb6bb9a-6052-49cf-9586-907d7fbe44e4




---
