# Myntra Sales Analytics Dashboard

An interactive sales analytics dashboard built using **Python**, **Streamlit**, and **Plotly** to analyze Myntra sales data through dynamic visualizations, business KPIs, and AI-powered insights. The dashboard enables users to monitor sales performance, explore trends, evaluate customer behavior, and generate intelligent business recommendations using Google Gemini.

---

## Features

- 📊 Interactive sales dashboard with responsive visualizations
- 📈 Monthly and daily sales trend analysis
- 🏷️ Brand-wise and category-wise performance analysis
- 📍 State-wise and city-wise sales analysis
- 👥 Customer demographics and rating analysis
- 📊 Key business KPI monitoring
- 🤖 AI-powered sales insights and recommendations using Google Gemini
- 🔍 Dynamic filtering by date, category, and state
- 🔄 Automatic dataset refresh on data updates
- 🔐 Secure user authentication and registration system
- ⚡ Fast and responsive Streamlit interface

---

## Dashboard Highlights

### Business KPIs

- Total Sales
- Total Orders
- Average Product Rating
- Average Discount

### Sales Analysis

- Monthly Sales Trends
- Daily Sales Trends
- Brand Performance
- Category Performance
- Sub-category Distribution

### Customer Analysis

- Customer Age Distribution
- Product Rating Distribution

### Geographical Analysis

- State-wise Sales
- Top Cities by Sales

### AI Sales Assistant

The integrated Google Gemini AI Assistant allows users to ask business questions such as:

- Which brand has the highest sales?
- Which category performs the best?
- Which brands are most popular in a specific city?
- Generate business insights from the dataset.
- Recommend strategies to improve sales performance.
- Analyze trends based on selected filters.

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Dashboard | Streamlit |
| Data Visualization | Plotly, Matplotlib |
| Machine Learning Libraries | Scikit-learn |
| AI Integration | Google Gemini API |
| Authentication | SHA-256 Password Hashing |
| Version Control | Git & GitHub |

---

## Project Structure

```
myntra-analytics/
│
├── dashboard.py              # Main dashboard application
├── auth.py                   # User authentication module
├── data_watcher.py           # Automatic dataset monitoring
├── requirements.txt
├── Myntra_dataset_large.csv
├── users.csv
├── README.md
└── .env
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/SuhaniNautiyal/myntra-sales-analytics-dashboard.git
cd myntra-sales-analytics-dashboard
```

### Create a Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/macOS

```bash
python -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file in the project root.

```env
GEMINI_API_KEY=your_gemini_api_key
```

---

## Running the Application

Start the Streamlit application.

```bash
streamlit run dashboard.py
```

Open your browser and visit:

```
http://localhost:8501
```

---

## Dataset

The dashboard analyzes Myntra sales data containing information such as:

- Order Date
- Product Category
- Sub-category
- Brand Name
- Original Price
- Discount Percentage
- Discounted Price
- Product Ratings
- Customer Age
- Customer ID
- State
- City

---

## Key Insights Generated

The dashboard enables users to:

- Identify top-performing brands and categories.
- Track sales performance over time.
- Compare sales across states and cities.
- Analyze customer demographics.
- Monitor product ratings and discounts.
- Discover sales patterns using interactive visualizations.
- Generate AI-assisted business recommendations.

---

## Deployment

The application can be deployed easily on **Streamlit Cloud**.

### Steps

1. Push the repository to GitHub.
2. Create a new Streamlit Cloud application.
3. Select the repository and branch.
4. Set `dashboard.py` as the entry point.
5. Add the following secret:

```env
GEMINI_API_KEY=your_gemini_api_key
```

6. Deploy the application.

---

## Future Enhancements

- Predictive sales forecasting
- Inventory optimization
- Customer segmentation
- Sales report export (PDF/Excel)
- Role-based access control
- Additional business KPI dashboards

---

## Author

**Suhani Nautiyal**

GitHub: https://github.com/SuhaniNautiyal
