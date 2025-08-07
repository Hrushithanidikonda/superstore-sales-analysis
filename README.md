# superstore-sales-analysis
 Exploratory Data Analysis (EDA) of Superstore Retail Sales Data using Python. Includes trend analysis, profit/loss detection, visualizations, and actionable business insights.

This project performs a detailed **Exploratory Data Analysis (EDA)** on a real-world retail dataset from a global superstore. The aim is to uncover valuable **business insights** by analyzing sales, profits, regions, product categories, and customer segments.

---

##  Objectives

- Identify the most and least profitable regions
- Discover top-performing product categories
- Detect loss-making products and sub-categories
- Analyze monthly sales trends
- Explore customer segment performance
- Create clear visualizations to support business decisions

---

##  Tools & Libraries Used

- Python
- pandas
- matplotlib
- Jupyter Notebook / Google Colab

---

##  Key Insights

-  **Technology** is the most profitable product category
-  **West** region leads in total profit
-  **Tables** and **Bookcases** are frequently sold at a loss
-  **Sales peak in Q4 (October to December)**
-  Most high-value customers come from **Corporate** and **Home Office** segments

---

##  Project Structure

| File | Description |
|------|-------------|
| `superstore-sales-analysis-python.ipynb` | Jupyter notebook with full analysis and code |
| `Sample - Superstore.csv` | Dataset used for analysis |
| `top_profitable_products.csv` | Top 5 products with highest total profit |
| `loss_making_products.csv` | Bottom 5 products with highest losses |
| `README.md` | Project summary and documentation |

---

##  How to Run

1. Download or clone this repository  
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab  
3. Make sure the dataset (`Sample - Superstore.csv`) is in the same directory  
4. Run the cells sequentially

```python
import pandas as pd
df = pd.read_csv("Sample - Superstore.csv", encoding="latin-1")
