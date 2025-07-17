# 🛒 Retail Price Optimization Dashboard

This project focuses on retail price optimization using the **Online Retail** dataset. The goal is to analyze customer transactions and identify the optimal pricing strategy to maximize profit while visualizing insights through an interactive **Power BI dashboard**.

---

## 📊 Dashboard Overview

![Dashboard Overview](Dashboard%20overview.png)

The dashboard includes:

- 💰 Monthly revenue trends
- 📦 Top-selling products by revenue
- 🎯 Profit curve visualization
- 💡 Optimal price recommendations
- 📉 Price vs Quantity correlation
- 🔍 Slicers for dynamic filtering

---

## 🛠 Tools & Technologies

- **Python** (Jupyter Notebook) — Data cleaning, modeling & analysis
- **Pandas / NumPy / Matplotlib / Seaborn**
- **Power BI** — Data visualization & dashboard design
- **Scikit-learn** — Price prediction modeling

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Cleaned_onlineRetail_for_powerBi.csv` | Cleaned dataset ready for Power BI |
| `Optimization_Results.csv` | Optimal price & max profit per product |
| `Profit_curve_data.csv` | Price vs Profit data used for curve plotting |
| `Retail_price_optimization.pbix` | Power BI dashboard file |
| `Correlation matrix.png` | Correlation heatmap of numerical features |
| `Dashboard overview.png` | Snapshot of the dashboard |
| `Price_prediction.png` | Visualization of predicted prices |
| `Price_vs_quantity.png` | Scatter plot: Price vs Quantity |
| `Profit_curve.png` | Profit vs Price curve |
| `Revenue_by_month.png` | Monthly revenue bar chart |
| `Top_products.png` | Top products by revenue (donut chart) |

---

## 📌 Key Insights

- Products have varied optimal price points for maximizing profit
- Some high-volume items are underpriced
- Revenue is highly seasonal, with spikes during Q4
- Correlation between unit price and quantity purchased is weak

---

## 🧠 How the Optimization Works

The model estimates profit at different price levels based on historical sales and builds a **profit curve**. The **optimal price** is selected at the peak of this curve for each product.

---

## 📎 Usage

To explore the dashboard:

1. Download the `Retail_price_optimization.pbix` file
2. Open in Power BI Desktop
3. Use slicers to filter by product, time, and more

---

## 🔗 Connect

Feel free to connect with me on [LinkedIn](http://linkedin.com/in/khoshaba-odeesho-17b5b92aa) to discuss data analysis, business intelligence, or collaborative work!

---

## 📃 License

This project is for educational and portfolio purposes.
