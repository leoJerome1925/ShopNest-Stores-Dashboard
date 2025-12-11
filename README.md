📊 ShopNest Store Dashboard – Full Analysis & Documentation (GitHub Ready)
📌 Project Overview
The ShopNest Store Dashboard is an end-to-end retail analytics solution built using Power BI, designed to analyze sales, customer experience, delivery efficiency, product performance, and geographic trends.
The dashboard centralizes key business KPIs such as:
•	Total Sales
•	Average Order Value (AOV)
•	Average Customer Rating
•	On-Time Deliveries
•	Delayed and Not Delivered Orders
•	State-wise revenue contribution
•	Product performance based on sales and ratings
This dashboard enables business leaders to:
•	Monitor operational efficiency
•	Identify product categories needing improvement
•	Optimize delivery processes
•	Understand customer satisfaction
•	Improve sales strategies across regions
________________________________________
🧭 Dashboard Layout & Components
The dashboard is divided into three major analytics sections:
________________________________________
⭐ 1. KPI Overview (Top Section)
This section provides at-a-glance business-critical metrics.
Key KPIs displayed:
Metric	Insight
Total Sales: 13.59M	Strong annual revenue indicating healthy order volume.
AOV: 120.65	Customers spend ~120 per transaction on average.
Avg Rating: 4.07	Indicates good customer experience overall.
On-time Deliveries: 89K	Reflects reliability of the delivery system.
Order Delays: 7,827	Suggests potential inefficiencies in logistics.
Not Delivered: 2,965	Indicates customer dissatisfaction and business loss.

⭐ Why this matters:
These KPIs quickly showcase the health of the business, letting management monitor performance and take corrective actions on delays, non-deliveries, and low-rated products.
________________________________________
⭐ 2. Operational & Sales Insights (Left to Center Blocks)
🔹 Product-wise Delay Orders
Shows total delayed orders by product category.
•	bed_bath_table, health_beauty, sports_leisure are the largest contributors.
•	Highlights supply chain issues within specific product lines.
🔹 Top 10 Categories by Total Sales
Ranks categories based on revenue.
•	health_beauty and watches_gifts lead the sales performance.
•	This helps the business focus marketing and inventory investment on top performers.
🔹 Monthly Delivery Status
Breaks down:
•	On-time orders
•	Delayed orders
•	Not delivered orders
This highlights seasonal patterns, operational bottlenecks, and logistical inefficiencies.
🔹 Payment Method Distribution
A donut chart showing:
•	credit card
•	boleto
•	voucher
•	debit card
Credit card is the dominant payment method, indicating:
•	customers prefer digital payments
•	opportunities for partner bank cashbacks & offers
________________________________________
⭐ 3. Product Performance Insights (Right Side)
🔹 Top 10 Highest Rated Products
Categories like:
•	cds_dvds_music, fashion_children, books_technical
Score consistently high (~4.3–4.6).
This is useful for:
•	product placement
•	upselling
•	cross-selling
🔹 Top 10 Lowest Rated Products
Categories like:
•	security_and_services (2.50)
•	office_furniture, construction_tools
A very low rating indicates:
•	poor quality
•	late deliveries
•	mismatch between expectation vs delivered product
A red flag for customer churn.
________________________________________
⭐ 4. Revenue Analysis Section (Bottom Row)
📈 Revenue by Quarter
A line chart showing:
•	Strong performance in Q2
•	Decline in Q3 and Q4
This pattern may suggest:
•	seasonality
•	customer demand fluctuations
•	promotional campaign impact
📊 Yearly & Quarterly Breakdown
The waterfall-style revenue analysis visual reveals how revenue progressed from:
•	2016 → 0.05M
•	2017 → 6.16M
•	2018 → 7.39M
The business shows strong year-over-year growth, especially between 2016 and 2017.
🗺 State-wise Sales
An interactive map displaying revenue distribution across states of Brazil.
Identifies:
•	high-demand regions
•	low-performing areas needing targeted marketing
•	distribution optimization opportunities
________________________________________
⭐ 5. Filters (Right Corner)
Filters allow slicing the dashboard by:
•	Year
•	Quarter
These enable dynamic views for:
•	performance analysis
•	comparisons
•	trend discovery
________________________________________
🧠 Overall Insights & Business Interpretation
✔ Strong Sales Growth
Revenue displays a consistent multi-year increase.
✔ Delivery Efficiency Needs Improvement
High delayed & not delivered orders suggest:
•	logistics bottlenecks
•	vendor performance issues
•	high-risk product categories
✔ Customer Experience Mostly Positive
Average rating of 4.07 is strong, but lowest-rated categories need urgent attention.
✔ High Sales Dependence on Specific Categories
health_beauty and watches_gifts dominate revenue.
Diversification opportunities exist.
✔ Payment Behavior
Credit cards dominate; promoting EMI or cashback offers may increase conversions.
✔ Geographic Sales Variance
Some states drive significant revenue—ideal for:
•	targeted promotions
•	stocking high-demand products
________________________________________
🛠 Technical Details (For GitHub)
Tools Used
•	Power BI Desktop
•	DAX Measures
•	Power Query
•	Data Modeling
•	Custom Formatting
Key Model Components
•	Fact tables: orders, payments, deliveries
•	Dimension tables: products, customers, states, categories
•	Relationships: star schema optimized for performance

