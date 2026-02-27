# SUPERSTORE-SALES-ANALYSIS
Exploratory data analysis of global superstore sales data
We analyzed the Superstore dataset to identify which product categories and regions are driving the most profit and where losses are occurring.
## Question 
Which product categories and regions contribute most to revenue and profit, and which ones are underperforming?
## Dataset 
**Source**: Superstore Dataset(https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
**Size**: 9994 rows × 21 columns
**Time period**: 2014–2017
**Key fields**:
Order ID — unique order identifier
Category — product category (Furniture, Office Supplies, Technology)
Region — sales region
Sales — sales amount in USD
Profit — profit in USD
## Tools Use
-Excel
## Key Findings
1.The Technology category generated the highest total profit: $550,000, while Furniture had the highest number of sales but lower profit margins.
2.he West region contributed the most to overall sales (35% of total sales), but the Central region showed lower profitability despite moderate sales
3.Orders above $1,000 accounted for 15% of total revenue but 30% of total returns, highlighting risk in high-ticket items.
4.Revenue grew consistently from 2014-2017,showing strong business expansion
5.19% of orders are loss-making, indicating pricing inefficiencies
6.The Central region has the lowest profitability, likely due to high discount levels
## Visualisation
![MonthlySalesTrend] <img width="1694" height="1115" alt="MonthlySalesTrend" src="https://github.com/user-attachments/assets/991635dd-039e-4cf1-82bf-061d959cfca1" />
This shows that the monthly trend grow consistently,which shows strong business expansion
![YearlySalesTrend] <img width="1735" height="993" alt="YearlysalesTrend" src="https://github.com/user-attachments/assets/27fefa54-0b06-47ab-94e7-a49761396cfb" />
## How to Reproduce
1. Clone this repo
2. Install requirements: `pip install pandas matplotlib seaborn`
3. Open `notebooks/01-exploration.ipynb`
4. Run all cells
## What I'd Do Next
1.Analyze month-over-month trends to see seasonal effects on sales.
2.Examine customer segmentation to target high-profit customers.
3.Investigate return reasons for high-value orders to reduce loss.

