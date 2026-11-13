# 📊 E-Commerce Sales Analysis (Superstore EDA)

An Exploratory Data Analysis (EDA) project on retail store sales using Python to discover key profit drivers, product performance, and business trends.

## 🚀 Tech Stack
- **Language:** Python 3.13
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook (`.venv` virtual environment)

## 📂 Dataset Features
The dataset contains transaction-level retail metrics:
* `Ship Mode`, `Segment`, `Country`, `City`, `State`, `Postal Code`, `Region`
* `Category`, `Sub-Category`
* `Sales`, `Quantity`, `Discount`, `Profit`

## 📈 Visualizations Generated
The analysis generates 4 key visual insights saved directly as high-resolution PNG charts:
1. **Sales vs Profit by Category (`category_sales_profit.png`):** Compares total revenue against profitability across core business departments (Furniture, Office Supplies, Technology).
2. **Total Sales by Ship Mode (`shipmode_sales.png`):** Evaluates logistics preferences and total revenue generated across different shipping methods.
3. **Impact of Discount on Profitability (`discount_profit.png`):** Analyzes how discount rates directly correlate with profit margins, highlighting loss-making thresholds.
4. **Net Profit by Sub-Category (`subcategory_profit.png`):** Breaks down individual product lines into net profit (green) and net loss (red) contributors.

## ⚙️ How to Run Locally
1. Clone the repository and navigate to the project directory.
2. Ensure Python virtual environment is activated:
   ```bash
   .venv\Scripts\activate