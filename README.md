# Pricing Strategy Analysis — UK Online Retail (2010–2011)

## Overview
A end-to-end pricing strategy analysis of a UK-based online retailer using 
500,000+ transactions. The project identifies optimal pricing, models discount 
impact, and finds bundle opportunities using price elasticity of demand.

## Key Findings
| Finding | Result |
|---------|--------|
| Price Elasticity | -0.67 (Inelastic) |
| Optimal Price Point | £X.XX |
| Discount Strategy | Discounts reduce revenue — avoid blanket discounts |
| Top Bundle Pair | [your top pair from output] |
| Top International Market | Netherlands |

## Project Structure
| File | Description |
|------|-------------|
| `price_vs_demand.ipynb` | Main analysis notebook (Python) |
| `pvsd.pbix` | Power BI dashboard |
| `retail_clean.csv` | Cleaned transaction data |
| `product_data.csv` | Product-level aggregated data |
| `discount_impact.csv` | Discount simulation results |
| `price_scenarios.csv` | Price change scenario results |
| `bundle_pairs.csv` | Co-purchase bundle recommendations |
| `pricing_strategy_summary.csv` | Final summary of findings |

## Tools Used
- **Python** — pandas, numpy, matplotlib, seaborn, scikit-learn
- **Power BI** — interactive dashboard
- **Dataset** — UCI Online Retail II (Kaggle)

## Analysis Steps
1. Data cleaning — removed returns, nulls, zero prices, non-product rows
2. Exploratory analysis — revenue trends, top products, country breakdown
3. Price elasticity — log-log OLS regression to measure demand sensitivity
4. Discount strategy — revenue simulation at each discount level
5. Price scenarios — modelled revenue impact of ±5% to ±20% price changes
6. Bundle analysis — co-purchase frequency to identify bundle opportunities

## How to Run
1. Download `OnlineRetail.csv` from [Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
2. Place it in the same folder as the notebook
3. Run all cells in `price_vs_demand.ipynb`
4. CSVs will be exported automatically
5. Open `pvsd.pbix` in Power BI Desktop

## Dashboard Preview
*(add a screenshot of your Power BI dashboard here)*
