# Sales-Analysis

## Business Problem
This superstore aims to adapt to increasing competition in the global retail market. The primary goal is to utilise data analysis to gain a deeper understanding of customers, products, and regional performance. It would aid the company to optimise product offerings, pricing strategies, and regional operations.

The following assessment explores key business questions, such as:

- Which **markets and regions** generate the highest sales and profit?
- Which **product categories** perform best?
- How do **discounts** impact profitability?
- What are the most common **shipping priorities and modes**?
- Which customer segments contribute the most revenue?

## Tools Used
- Excel (exploratory analysis)
- Power BI (dashboard & visualisation)

## Approach
1. Adding columns for better business insight, such as:
    
- **profit_margin** → Shows efficiency of sale
- **revenue_per_unit** → Helps identify pricing patterns
- **cost** → Analyse cost structure
- **shipping_ratio** → Shows logistic efficiency
- **order_month** → Helps answer trends
- **order_quarter**→ Helps answer seasonality
- **shipping_days**→ Used to evaluate logistics vs **order_priority**
- **is_profitable**→ Useful in dashboard making
- **discount_level** → Analyse the benefits of discounts
    
2. Create pivot tables:
- Which segments are most profitable?
- Do discounts increase or decrease profit?
- Which regions underperform?
- Are high-priority orders actually faster?

## Key Insights
- The consumer segment contributes to the highest total profit ($749K), due to its large sales volume. However, the Home Office demonstrates the strongest profitability efficiency, with the highest profit margin (5.27%), suggesting a greater return per sale.
- Higher discounts are associated with increased sales but damage profitability. High-end discount orders generated $1.93 million in revenue but resulted in a loss of $ 814,000 and a 61% profit margin, making aggressive discounting an unsustainable pricing strategy.
- While several regions boast high sales, profitability significantly varies. Canada demonstrates the highest efficiency, achieving a 25% profit margin despite a low sales volume. On the contrary, regions such as EMEA, Africa and SEA underperform, exhibiting negative margins despite substantial sales, indicating structural profitability issues.
- Although the logistics system successfully prioritises urgent orders, the cost of fulfilling critical orders may outweigh the financial benefit, indicating inefficiencies in cost management for high-priority deliveries.

## Recommendations
### Pricing Strategy
- Introduction of strict discount caps to avoid loss-making transactions by preventing high discount levels
- Shifting from blanket discounting to more targeted promotions (e.g. specific products, segments, or regions)
- Implementing profit-based approval rules to protect company margins by overseeing high discount deals
- Identify products/regions heavily reliant on discounted sales and reassess pricing strategies

### Market/Regional Focus
- Prioritise investment in Canada and the West due to their strong profit margins
- Maintain volume in the Consumer segment, but improve its margins through selective discounting
- Reallocate resources or adjust strategies in unprofitable regions through pricing changes, cost reduction or market exit
- Tailoring strategies by customer segments, expanding higher-margin segments like Home Office

### Operational Efficiency
- Review the cost structure, especially for critical and high-priority shipping, where costs outweigh benefits
- Introduce cost controls or alternative fulfilment methods for urgent deliveries
- Align priority shipping with profitability thresholds, not just urgency

## Visuals
[View the Dashboard (PDF)](https://github.com/christiannugal-lab/Sales-Analysis-Project/blob/main/Sales%20Analysis%20Dashboard%20v2.pdf)
![](https://github.com/christiannugal-lab/Sales-Analysis-Project/blob/main/PowerBI%20Dashboard%20Image.png)

#### Update
update with dashboard image and link
