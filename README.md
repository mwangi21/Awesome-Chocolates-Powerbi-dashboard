# Awesome-Chocolates-Powerbi-dashboard
Interactive Power BI dashboard for Awesome Chocolates, featuring detailed analytics on sales, profit, products, regions, and sales team performance. Built to visualize insights, track KPIs, and support data-driven decisions.



## 🎯 Objective

To create a data-driven reporting dashboard that:
- Tracks key performance indicators (KPIs) such as Sales, Profit, Cost, Boxes, and Shipments
- Evaluates individual salesperson performance
- Evaluate individual products performance
- Analyzes product-level and regional profitability
- Supports business decisions with actionable insights through filters and trends



## 🖼️ Main Dashboard Snapshot

![Main Dashboard](./AwesomeChocolates%20Images/Awesome%20Chocolates%20Dashboard.PNG)



## 📊 Key Metrics

| Metric               | Value         | Description                                |
|----------------------|---------------|--------------------------------------------|
| **Total Sales**      | $34M          | Cumulative sales across all products       |
| **This Month Sales** | $2.53M        | Latest month's sales total                 |
| **Total Profit**     | $20.5M        | Net profit (Sales - Cost)                  |
| **Total Cost**       | $14M          | Accumulated product and shipment costs     |
| **Boxes Sold**       | 2M            | Quantity of chocolate boxes sold           |
| **Shipments**        | 6K            | Number of shipments made                   |
| **Profit Margin**    | 60.3%         | Gross profit margin                        |
| **MoM Sales Change** | -10.8%        | Month-over-month sales drop                |

---

## 📈 Trend Analysis Visuals

### 📅 Sales Over Time
![Sales Trend](./AwesomeChocolates%20Images/Sales%20by%20Start%20of%20the%20Month.PNG)

### 📦 Boxes Trend
![Boxes Trend](./AwesomeChocolates%20Images/Boxes%20By%20Start%20of%20The%20Month.PNG)

### 💸 Cost Trend
![Cost Trend](./AwesomeChocolates%20Images/Cost%20by%20Start%20of%20the%20Month.PNG)

### 💰 Profit Trend
![Profit Trend](./AwesomeChocolates%20Images/Profits%20by%20Start%20of%20the%20Month.PNG)

### 🚛 Shipments Trend
![Shipments by Month](./AwesomeChocolates%20Images/Shipments%20By%20the%20start%20of%20the%20Month.PNG)


## 🚚 Shipment Distribution View

![Shipment Histogram](./AwesomeChocolates%20Images/Shipment%20Analysis.PNG)

- **Histogram** of shipment volume distribution
- **LBS Efficiency Gauge** shows 10.2% logistics weight efficiency



## 🍬 Product-Level Insights

![Product-Level View](./AwesomeChocolates%20Images/Product%20Analysis.PNG)

Key highlights:
- Highest profit margin: **Peanut Butter Cubes** (87.1%)
- Underperformers: **Baker's Choco Chips**, **Drinking Coco**
- Balanced products: **Organic Syrup**, **Orange Choco**



## 👥 Sales Team Breakdown

![Salesperson Analysis](./AwesomeChocolates%20Images/Sales%20Person%20Analysis.PNG)

- Lists all sales reps with metrics for:
  - Sales revenue
  - Profit earned
  - Profit margin %
  - Logistics weight contribution (LBS %)
- Top reps: **Marney O’Breen**, **Kelci Walkden**, **Van Tuxwell**



## 🎛️ Dynamic Filters and Slicers

![Sidebar Filters](./AwesomeChocolates%20Images/slicer.PNG)

- Product Category: Bars, Bites, Other
- Region Selector: USA, UK, India, Canada, Australia, New Zealand

Users can interactively adjust the visuals using slicers for granular insights.

## 🧱 Data Model Overview

![Data Model View](./AwesomeChocolates%20Images/Model%20view.PNG)

### Core Tables:
- `shipments`: Fact table containing cost, box counts, product, date, geography
- `products`: Dimension with chocolate types and costs
- `people`: Dimension for sales rep metadata
- `calendar`: Date hierarchy for trends and MoM calculations
- `locations`: Geography region mapping

### DAX Measures:
- Latest MoM Sales Change %, Profit Change %, LBS %, and more
- Included in the `_Measures` table and controlled via `Measure Selector`


## 🛠 Technologies Used

- Power BI Desktop
- Power Query (Data Shaping)
- DAX (for custom metrics and KPIs)
- Star Schema Modeling
- Matrix, KPI Cards, Line/Bar Charts, Slicers




## 👩🏽‍💻 Author

**Edwin Wanjohi**  
📫 :wanjohiiedwin@gmail.com  
🔗 [LinkedIn]www.linkedin.com/in/eddie-wanjohi

---


