# Sales Analysis — Superstore Project

## Overview

This project presents an exploratory data analysis (EDA) of the Superstore sales dataset, containing transactional data with information on sales, profits, discounts, product categories, and regions. The goal is to uncover patterns and insights that support business decision-making and optimize sales strategies.

## Project Structure

```
analise_vendas/
│
├── data/                  # Raw data files (.csv)
├── images/                # Saved plots and charts (.png)
├── notebooks/             # Jupyter notebooks with analysis (.ipynb)
└── README.md              # Project documentation
```

## Dataset

The dataset used is from a fictional company, Superstore, provided as `Superstore.csv` inside the `data/` folder. It contains sales transactions with columns such as date, region, category, product, sales amount, profit, and discount.

## Tools and Libraries

- Python 3.9+
- Jupyter Notebook
- Pandas for data manipulation
- Seaborn and Matplotlib for visualization
- Git for version control

## Methodology

The analysis follows these steps:

1. **Data Import and Cleaning**  
   - Loading data from CSV  
   - Checking for missing values and data types  
   - Data cleaning and formatting

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Sales, profit, and discount distribution analysis  
   - Regional and category performance  
   - Top products identification

3. **Insights and Findings**  
   - Regions with the highest sales  
   - Most profitable categories  
   - Effect of discounts on profitability  
   - Top 10 products contributing to revenue

## Visualizations

Below are some key charts from the analysis:

### Sales by Category

![Sales by Category](images/sales_by_category.png)  
*This bar plot shows total sales for each product category, highlighting the dominant categories.*

### Top 10 Products by Sales

![Top Products](images/top_10_products.png)  
*This chart presents the top 10 best-selling products by sales volume.*

### Regional Sales Distribution

![Sales by Region](images/sales_by_region.png)  
*Sales breakdown by region showing which areas generate the most revenue.*

## Key Results

- The South region leads in total sales volume, followed by the North.  
- The Technology category is the most profitable, while Furniture leads in sales volume.  
- Discounts negatively impact profit margins, as seen in the negative correlation between discount and profit.  
- The top 10 products represent about 60% of total sales.

## How to Run the Project

To reproduce this analysis locally, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/yourusername/analise_vendas.git
```

2. Navigate to the project directory:

```bash
cd analise_vendas
```

3. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate       # On Linux/Mac
venv\Scripts\activate        # On Windows
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Launch Jupyter Notebook and open the analysis:

```bash
jupyter notebook notebooks/01_sales_analysis_superstore.ipynb
```

6. Execute the notebook cells to reproduce analysis and regenerate plots (saved in `images/`).

## Contact

For questions or collaboration:

- Diego  
- LinkedIn: https://www.linkedin.com/in/diego-juliano-lima-figueredo-7112816a/
- GitHub: https://github.com/diegojlfigueredo

---

This project is part of Diego's data analysis portfolio, demonstrating practical skills and professional presentation.
