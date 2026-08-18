# Supplement Sales Exploratory Data Analysis (EDA)

Exploratory data analysis of weekly supplement sales data using Python, Pandas, Matplotlib, and Seaborn.

## Objective

This project aims to perform an exploratory data analysis (EDA) on weekly supplement sales data in order to uncover patterns in overall sales performance, product-level performance, category performance, platform performance, location performance, and product returns. The goal is to translate raw transactional data into clear, actionable insights that describe how revenue is generated, where it is concentrated, and where risk (through returns) exists across the business.

## Business Questions

1. What does the overall revenue trend look like over time?
2. Which product categories generate the most revenue?
3. How does revenue break down by location and sales platform?
4. Which products are the best sellers, and which have the highest return rates?
5. Is there a relationship between discounting and sales volume?
6. Are there seasonal or monthly patterns in the data?
7. Which categories are most profitable after accounting for returns?

## Dataset

The dataset (`Supplement_Sales_Weekly_Expanded.csv`) contains weekly sales records for supplement products, including revenue, units sold, units returned, discount, price, category, location, and sales platform.

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings
- **Revenue trend and seasonality:** Daily revenue from 2020 to 2025 shows no steady upward or downward trend but does show clear volatility, peaking above $110,000 in 2022 and dipping below $70,000 in late 2022, with a secondary spike in mid 2024/early 2025. At the monthly level, units sold follow a repeating cycle pattern roughly 9,500 to 12,000 units, pointing to a recurring seasonal demand cycle
- **Category, location, and platform performance:** Vitamin and Mineral is the clear revenue and profit leader ($420,000-$430,000), with Performance and Protein forming a secondary tier ($280,000-$290,000). The remaining categories (Amino Acid, Omega, Fat Burner, Hydration, Herbal, Sleep Aid) form a flat baseline around $150,000. Revenue is evenly split across all three locations and sales platforms, with no single location or platform dominating - indicating a well-diversified sales strategy rather than dependence on one channel.
- **Best sellers:** Top-selling products (Biotin, Zinc, Pre Workout) are only marginally ahead of the rest, each generating close to $140,000-$150,000 in revenue, so the product mix is fairly balanced rather than driven by a few standout SKUs. Return rates are low across the board around 1%, so returns are not a meaningful drag on any particular product's performance.
- **Profitability:** Since return rates are uniformly low (~1%), category profitability closely mirrors category revenue - Vitamin and Mineral remains the top profit generator, followed by Performance and Protein, confirming that returns have minimal impact on overall category profit margins.


## Overall Conclusion

The business shows a stable, diversified sales structure: revenue is spread evenly across locations and platforms, product returns are negligible, and profitability tracks revenue closely because there is little return-driven erosion. Vitamin and Mineral products are the primary growth and profit driver and warrant continued investment, while Performance and Protein represent a secondary opportunity. A useful next step is analyzing the discount-to-sales relationship to determine whether promotional pricing drives incremental volume or simply erodes margin.

