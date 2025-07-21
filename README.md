# 📊 Product Sales Dashboard

An interactive Streamlit web app for visualizing product sales performance using charts like bar, pie, and sunburst. The dashboard provides insights into sales, profit, and discount distribution across different product categories and sub-categories.

---

## ✨ Features

- ✅ **Category Selection:** Filter data dynamically by one or more product categories
- 📈 **Bar Chart:** View total sales by SubCategory
- 🥧 **Pie Chart:** View profit by SubCategory
- 🌞 **Sunburst Chart:** Visualize discount breakdown by Category → SubCategory → Discount

---

## 📁 Project Structure

product-sales-dashboard/
├── app.py # Streamlit app code
├── PSales.csv # Sales dataset (CSV file)
├── requirements.txt # List of Python dependencies
└── README.md # Project documentation (this file)




---

## 🧾 Sample Dataset Format (`PSales.csv`)

Ensure your CSV file contains the following columns (headers **must match exactly**):

| Category | SubCategory | Sales | Profit | Discount |
|----------|-------------|-------|--------|----------|
| Furniture | Chairs     | 150.0 | 25.0   | 0.1      |
| Office Supplies | Binders | 200.0 | 50.0 | 0.2      |
| Technology | Phones     | 800.0 | 150.0  | 0.05     |

You can create your own file in Excel or Google Sheets and export it as `PSales.csv`.

---

## 🖥️ Setup Instructions

Follow these steps to run the app locally:

### 1. Clone the Repository
git clone https://github.com/your-username/product-sales-dashboard.git
cd product-sales-dashboard

2. (Optional) Create a Virtual Environment
python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

If you don't have a requirements.txt, create it using:bash
pip install streamlit pandas plotly
pip freeze > requirements.txt


4. Add Your Dataset
Place your PSales.csv file inside the project folder (same location as app.py).

5. Run the Streamlit App
streamlit run app.py
