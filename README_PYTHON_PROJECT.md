
# Python Data Analysis Project – Sales Insights

## 📌 Project Title
Sales Data Analysis using Python

## 📖 Project Overview
This project focuses on analyzing sales data using **Python** to extract meaningful business insights.  
It demonstrates core Python skills such as data manipulation, aggregation, and basic visualization,

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📂 Project Structure
```
python-sales-data-analysis/
│── README.md
│── sales_data.csv
│── sales_analysis.ipynb
│── requirements.txt
```

## 📊 Dataset Description
`sales_data.csv`
| Column Name | Description |
|------------|-------------|
| order_id | Unique order ID |
| order_date | Date of order |
| customer_id | Customer identifier |
| product | Product name |
| quantity | Units sold |
| price | Price per unit |
| region | Sales region |

## 🔍 Analysis Performed
- Total sales calculation
- Monthly sales trend analysis
- Top-selling products
- Region-wise revenue distribution
- Average order value

## 🧪 Sample Python Code
```python
import pandas as pd

df = pd.read_csv("sales_data.csv")

df["total_amount"] = df["quantity"] * df["price"]

monthly_sales = df.groupby("region")["total_amount"].sum()
print(monthly_sales)
```

## 📈 Visualizations
- Bar chart for region-wise sales
- Line chart for monthly revenue trends

## ▶️ How to Run the Project
1. Clone the repository
2. Install dependencies  
   ```
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook  
   ```
   jupyter notebook
   ```
4. Run `sales_analysis.ipynb`

## 📈 Key Learnings
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Using Pandas for business insights
- Creating basic visualizations


**Python Data Analysis Project:**
- Analyzed sales data using Python (Pandas, NumPy)
- Performed data aggregation and trend analysis
- Created visualizations to present insights
- Improved data-driven decision-making skills

## 👤 Author
**Durga Rao Thaddi**  
B.Sc Computers (2020)  
Aspiring Data Analyst / Python Developer
