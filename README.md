# Zadera-Sales-Overview-2023
The analysis provides a comprehensive sales transaction dataset containing multiple variables across independent categories (Product ID, Sales Date, Sales Rep, Region, Product Category, Unit Cost, Customer Type, Payment Method, Sales Channel, Region-and-sales-rep) and dependent variables (Sales Amount and Quantity Sold).
Introduction
<img width="2469" height="1247" alt="ZADERA SALES" src="https://github.com/user-attachments/assets/c7619c18-8842-4ae4-aade-5dc6b0d61777" />

The primary objective of this project is to analyze the 2023 sales data to identify key performance indicators such as Total Sales, Gross Profit, and discount Rates across different regions and Product Categories.
The analysis ais to uncover significant trends, correlations, and potential areas for operational or strategic improvement
Problem Being Addressed
The analysis seeks to answer:
•	Which region is the highest contributor to Total sales?
•	Which product categories are driving the most sales and profit?
•	What is the monthly sales trend for the year 2023?
Datasets and Methodologies
Dataset: The analysis provides a comprehensive sales transaction dataset containing multiple variables across independent categories (Product ID, Sales Date, Sales Rep, Region, Product Category, Unit Cost, Customer Type, Payment Method, Sales Channel, Region-and-sales-rep) and dependent variables (Sales Amount and Quantity Sold).
Methodologies: Analysis was conducted using Microsoft Excel with Pivot tables, data aggregation functions, and visualization tools to extract meaningful insights from the raw transactional data.
Data Story
This data is used to track all sales, manage inventory, analyze customer behavior and evaluate sales performance. This dataset contains detailed sales transactions across different products, regions and customers.
Data Source
The dataset originates from an internal retail sales database capturing detailed transaction records across the organization’s entire sales operation. (Kaggle.com)
Data Collection Process
Sales data was systematically gathered through automated point-of-sale systems and integrated sales platforms, capturing each transaction in real-time with associated metadata including customer information, product details, representative assignments, and temporal markers.

Data Structure
The dataset contains 1,000 rows (transactions) and 14 columns (features). Each row represents a single sales transaction. Key Columns include:
•	Sale-Date: Date of the transaction.
•	Sales-Amount: The revenue generated from the sale.
•	Quantity-Sold: Number of units sold.
•	Product-Category: The type of product (e.g., Food, Furniture)

Important Features and Their Significance
Independent Variables:
•	Region: Geographic distribution revealing market penetration and territorial performance
•	Product Category: Product line performance indicating customer preferences and inventory focus areas
•	Sales Representative: Individual performance metrics enabling capability assessment and training needs identification
•	Customer Type: Segmentation between new and returning customers measuring acquisition and retention effectiveness
•	Payment Method: Transaction preference patterns informing infrastructure investment decisions
•	Sale Date: Temporal patterns revealing seasonality and trend identification
•	Sales Channel: Distribution channel effectiveness comparison
Dependent Variables:
•	Sales Amount: Primary revenue metric measuring financial performance
•	Quantity Sold: Volume metric indicating market demand and operational scale
Data Limitations or Biases
•	The data is limited to a single year (2023), which restricts long-term trend analysis.
•	The Unit Cost column contains values that, when multiplied by Quantity-sold, often exceed the Sales Amount, resulting in a consistent pattern of negative Gross Profit in the analysis. This suggests a potential issue with the data quality or an unusual pricing/cost model within the source data.

Data Splitting and Preprocessing
Data Cleaning
 The initial inspection showed no missing values (Non-Null Count for all columns is 1000). Data types were generally correct, with sale-date successfully converted to a datetime object for time-series analysis. No duplicates were removed.

Handling Missing Values
 Not applicable, as all 1,000 records were complete.

Data Transformations
Monthly aggregations were created from daily transaction data to facilitate trend analysis. Regional and categorical groupings were standardized to enable consistent comparison across business dimensions. Sales representative performance metrics were calculated as cumulative totals to provide clear ranking and comparison frameworks.

Data Splitting
The analysis separated independent variables (factors that influence sales such as region, product category, sales representative, customer type, payment method, and sales channel) from dependent variables (outcomes measured by sales amount and quantity sold). This separation enabled correlation analysis and causal relationship exploration between operational factors and performance outcomes

Industry Context
The data belongs to the Retail Industry, specifically in the sale of diverse consumer goods (clothing food, Furniture, Electronics).

Stakeholders
Key stakeholders include:
•	Sales Team: for performance insights
•	Marketing Department: for discount impact and
•	Senior Management: for strategic resource allocation
Value to the Industry
In the retail industry, data-driven insights translate directly to competitive advantage.
This analysis provides actionable intelligence that enables the business to optimize inventory allocation based on regional and categorical performance, enhance sales team effectiveness through targeted training and territory optimization, improve customer retention through understanding behavior patterns, and maximize revenue through seasonal planning and payment infrastructure investments.
The insights support strategic decisions that improve operational efficiency, increase market share, and drive sustainable revenue growth.
Pre-Analysis
Project Split
Category One (Independent Variables):
•	Product ID
•	Sale Date
•	Sales Rep
•	Region
•	Product Category
•	Unit Cost
•	Customer Type
•	Payment Method
•	Sales Channel
Category Two (Dependent Variables):
•	Sales Amount
•	Quantity Sold
Potential Analysis Questions
•	Top performing Region
•	Sales performance analysis by Product category
•	Sales performing analysis by Sale Rep
•	Sales rep performance by quantity sold
•	Sales performance analysis by customer type
•	Sales trends over time by sales amount
•	Impact of cost variations on quantity sold
•	sales performance by sales channel
•	Pricing strategies on quantity sold
•	Quantity sold across customer segment
•	Region-and-sales-rep performance
Potential Insights
•	Identify market opportunities and areas needing improvement.
•	Understanding which products and categories drive the most sales revenue 
•	Identify top sales performers and recognize their contributions, also helps in understanding which reps might need additional training or support to meet their targets
•	Finetune which customer types generate the most sales allows for targeted marketing efforts.
•	Identify which types of customers are most valuable and improve customer service, and develop products that better meet the needs of the most important segments.
•	Discovering seasonal trends allows for better resource allocation and marketing campaign timing.
•	Finetune how changes in the product's cost affect how much they can sell.
•	To finetune the most effective generating sales revenue
•	To evaluate the effectiveness of different pricing tactics like discounts, promotions or bundles.
•	To understand customer behavior and inform decisions on targeted marketing, loyalty programs and sales strategies.
Initial Observations
Before conducting detailed statistical analysis, preliminary examination of the dataset revealed several promising patterns. The data appeared well-balanced across most categories, suggesting a diversified business model without over-reliance on any single product line or geographic region.
Initial aggregations indicated that both customer acquisition and retention efforts were yielding comparable results, which suggested effective marketing strategies in both areas.
The temporal distribution of sales transactions showed clear variation across months, indicating potential seasonal patterns that warranted deeper investigation. Regional distribution appeared uneven in early observation, suggesting that some territories might be outperforming others significantly.
Sales representative performance showed noticeable variance, indicating opportunities for performance optimization through training or territory rebalancing.
These preliminary observations guided the focus of the detailed analysis toward understanding the drivers behind regional disparities, seasonal fluctuations, and individual performance variations, while also validating the effectiveness of balanced strategies in customer segmentation and product diversification.
In-Analysis
Sales Performance by Region
OBSERVATIONS:
•	The North region is the top-performing region, with the highest sales of $1,369,612.51
•	East is the second performing region, generating $1,259,792.93 Revenue 
•	West region generated $1,235,608.86 revenue
•	South region is the least performing region with sales of $1,154,250.86
PRE INSIGHTS:
•	The North Region may have a larger market, more effective sales strategies or a higher concentration of customers.
•	The East and West regions have very similar sales figures, the difference between their sales is relatively small.
•	The South region has the power sales performance among the four, this could indicate potential challenges such as a smaller market, less effective marketing or an opportunity for improvement.
Sales Performance by Sales Representatives
OBSERVATIONS
 
•	The top performing sales Rep is David with the highest total sales of $1,141,737,36
•	Bob is a close second, with sales of $1,080,990.63_Eve is the third with sales of $970,183.99
•	Alice is the fourth with sales of $965,541.77
•	Charlie is the least performing sales Rep with sales of $860,811.48
PRE INSIGHTS:
•	Charlie has the lowest sales figures among the group. His performance is significantly lower than the others, particularly compared to David, this indicates he may need additional support, training or a revised sales strategy.    
Customer Type Sales Performance 
OBSERVATION:
•	Sales are almost perfectly split between Returning customers ($2,513,006.93) and new customers ($2,506,258.30).
PRE INSIGHT:
•	The company has a balanced sales strategy, successfully attracting new customers while also retaining and generating revenue from existing ones.
•	The close balance suggests that the current marketing and retention efforts are effective on both fronts.
Sales Trend Report
OBSERVATIONS:
•	Sales figures fluctuate significantly throughout the year, with a high of $495,420.37 in January and a low of $367,837.60 in September 
•	The year starts strong with high sales in January ($495,420.37) and March ($402,638.77), sales also increase again at the end of the year in November ($467,482.90) and December ($392,643.58)
•	There is a noticeable decline in sales during the third quarter July ($374,242.88), August ($443,171.28), and September ($367,837.60), reaching the lowest point in September.
PRE INSIGHTS:
•	The sales trend report suggests that the company's performance is influenced by seasonality. 
•	The peak in January, November and December could be related to holiday shopping or end of year budget cycles.
•	The nonlinear sales trend means that the company cannot rely on consistent monthly revenue.
Sales Performance by Product category 
OBERVATIONS:
•	Clothing is the top performing product category with the highest sales of $1,313,474.36
•	Furniture is the second performing product category with sales of $1,260,517.69
•	Electronics generated $1,243,499.64
•	Food is the lowest performing product category with sales of $1,201,773,54
PRE INSIGHTS:
•	Clothing may be the most popular or highest-demand product within the company offerings.
•	The sales figures for furniture and Electronics are quite close to each other indicating a similar level of performance for these two categories.
•	The food category has the lowest sales among the four, placing it at the bottom, this could be due to a smaller product range, lower prices, or less demand compared to the other categories.    
Sales Performance by Sales Channel
OBSERVATIONS:
•	The Retail sales channel generates slightly more revenue with sales totaling $2,560,431.30
•	The online sales channel is very close in performance with sales totaling $2,458,833.93
PRE INSIGHTS:
•	While both channels are strong, the slight lead of Retail suggests there might be opportunities to further optimize the online experience or marketing to close the small gap and potentially make online the leading channel or to understand what drives the slight edge in retail to replicate it online if possible.    
TOP 5 Region-and-Sales-Rep Performance
 OBSERVATIONS:
•	The chart combines sales data for specific sales Rep within specific regions, highlighting top 5 performing combinations _
•	South-David is the highest performing combination with sales of $331,416.99
•	East-Bob is a close second generating $309,876.11 in sales.
•	North-Eve is the third highest with sales of $304,172.20 
•	North-Charlie is the fourth highest with sales of $299,799.01
•	West-Bob $286,449.28 is the fifth
 PRE INSIGHTS:
•	David who was identified as the top overall sales rep, appears to perform exceptionally well in the South region. As the South region was previously noted as the lowest performing region, David's success there suggests that with the right talent, the South region has significant potential.
•	Bob appears twice in the top 5, demonstrating strong performance in both the East and West regions, this indicates his versatility or effectiveness across different geographical areas.
•	Charlie was the lowest overall sales performer his North-Charlie combination still made it into the top 5 of region-and-sales rep Performance. This suggests that Charlie might be highly effective in specific context despite his overall lower total, or that the North region itself is so strong that even a lower-performing rep contributed significantly there.           
       
                 Data Visualizations and Charts
Sales by Region
 
                                                    Sales Performance by Region
The Bar Chart reveals regional performance distribution with North leading at $1,369,612.51 (dark orange) East at $1,259,792.93 (medium dark orange) West at $1,235,608.93 (medium light orange), and South significantly lagging at $1,154,251(light orange)
The visual representation makes the South region’s underperformance immediately apparent, accounting for only 23% of total sales compared to the North’s 27.3%. The chart emphasizes the need for immediate intervention in the South region while highlighting the North’s best practices that should be replicated.

Product Category Performance
 
                                 Sales Performance by Product Category
The column bar chart ranks product categories with Clothing leading at $1,313,474 (dark orange), followed by Furniture at $1,260,518, Electronics at $1,243,500, and Food at $1,201,774 (light orange). The visualization demonstrates the relatively narrow $111,700 range across all categories, representing successful product diversification.
The chart shows that while Clothing leads, no category dominates excessively, reducing business risk. The visual supports recommendations for modest expansion in the Food category while maintaining strong performance across all product lines.
Sales Representatives Performance
 
                      Sales Representatives Performance
The chart ranks sales representatives with David leading at $1,141,737 (dark orange), Bob at $1,080,991 (medium dark Orange), Eve at $970,184 (medium orange), Alice at $965,542 (medium light orange), and Charlie at $860,811 (light orange).
The visualization clearly shows the $280,926 performance gap between the highest and lowest performers. The chart reveals that while the top four representatives perform within a more reasonable range, Charlie’s significant underperformance stands out.
Sales Performance by Sales Channel
 
                             Sales Performance by Sales Channel
The doughnut chart reveals that the Retail sales channel generates slightly more revenue with sales totaling $2,560,431.30 (dark Orange) while the online sales channel is very close in performance with sales totaling $2,458,833.93 (light Orange)
Sales Performance by Customer-Type 
                                   Sales Performance by Customer-type
The Doughnut chart reveals that Sales are almost perfectly split between Returning customers at $2,513,006.93 (dark orange) and new customers at $2,506,258.30 (light orange).

Recommendations and Observations
Observations
•	The South region has the lowest sales figures compared to the North, East, and West regions, this indicates it has the most room for growth and the potential for the highest return on investment for targeted improvement efforts.
•	The sales performance is relatively balanced across the top three categories (Clothing, Furniture, Electronics), with a noticeable drop-off for the food category.
•	The sales performance is not evenly distributed among the team. There is a clear hierarchy with David leading the team and Charlie lagging behind.
•	The stability of returning customer sales is a strong indicator of customer satisfaction and loyalty.
•	The dip in sales during the third quarter indicated a potential area for strategic intervention   
•	The pie chart visually confirms a nearly even split in sales contribution between the Retail and Online channels, with Retail having a slightly larger slice.
•	David's top performance in the South region which was previously identified as the overall lowest performing region, highlights David's significant individual capability to drive sales even in challenging markets.
•	David's consistent lead in quantity indicates he has effective methods for closing deals and moving products.                        
Recommendations         
•	Conduct a quick market analysis in the South region to understand local consumer preferences for food products, if there are specific types of foods that are popular or in high demand.
•	Launch a sales promotion or a marketing campaign specifically for Food items in the South region, this could include discounts, bundle offers, or local advertisements.
•	Implement a targeted coaching and development plan for Charlie, the lowest performing sales Rep, the goal is to identify the root causes of his underperformance and provide the specific support needed to bring his sales closer to the team average.
•	Invest in customer loyalty programs and upselling strategies for returning customers to further capitalize on this balanced sales mix.
•	Creating Marketing campaigns, special promotions, or product launches during the third quarter of the year could help to stabilize revenue and reduce the impact of this seasonal lull.
•	Personalize online marketing campaigns based on previous retail purchases and vice versa, to encourage cross-channel engagement.  
•	Facilitate regular sessions where top-performing-region -sales combinations can share their insights with a wider sales team.
•	Encourage David to share his strategies for generating high sales volume. Organize a session where David can present his approach to maximize unit sales including how he manages his pipeline, qualifies leads or close deals efficiently                 
                                   
                    
  Conclusion
The Zadera Retail Sales Performance analysis reveals a highly effective sales team capable of generating consistent, high-volume revenue across all regions particularly in the North. The analysis demonstrated that success in retail requires simultaneous optimization across multiple dimensions: geographic markets, product categories, sales force effectiveness, customer segmentation, payment infrastructure, and temporal planning.
Limitations
Seasonal patterns observed represent a single year of data, and multi-year analysis would be required to confirm these patterns are consistent and not anomalous. The customer type classification (new vs. returning) lacks depth in understanding customer demographics, preferences, or purchase frequency that would enable more nuanced segmentation strategies.
Scope: The analysis did not include operational costs which would be necessary to calculate Net Profit
Future Research 
Multi-Year Trend Analysis: Analyzing multiple years of data would validate whether observed seasonal patterns and performance rankings are consistent or represent year-specific anomalies. This would enable more confident forecasting and planning.
Channel Performance Deep Dive: The dataset includes sales channel information (online vs. retail) that was not fully explored in this analysis. Understanding channel-specific performance, customer preferences, and profitability would inform omnichannel strategy development
References
Analytical Tools
•	Microsoft Excel







