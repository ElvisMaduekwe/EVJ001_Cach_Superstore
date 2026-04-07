Introduction
<img width="2215" height="1083" alt="Dashboard 1" src="https://github.com/user-attachments/assets/31de8e24-bfec-4b48-a4e6-cecdd5c49f7b" />

What if most of a company’s revenue came from just a few customers, products, and regions?

That was the key question I set out to answer while analyzing a retail dataset from Cach Superstore, a business operating across multiple states in the United States.

The objective of this project was to evaluate key sales parameters and generate insights that would help stakeholders make informed decisions. Specifically, the analysis aimed to improve revenue generation, enhance customer satisfaction, and optimize overall sales performance.

To achieve this, I explored several business questions, including sales trends over time, top-performing customers, salesperson contributions, regional performance, and product category effectiveness.

Story of Data
The dataset was sourced from the company’s internal records and represents daily transactional activities. Each row corresponds to a single transaction, while columns include key variables such as revenue, product category, customer, salesperson, region, city, state, and payment method.
<img width="2544" height="1478" alt="Cach Superstore Raw data " src="https://github.com/user-attachments/assets/ce9132db-a2dc-4399-83a3-9146594613b9" />

The data provides a comprehensive view of how the business operates — capturing what products are sold, who buys them, where they are sold, and who facilitates the sales.

Some of the most significant variables for this analysis included revenue, customer names, sales representatives, product categories, transaction dates, and geographic locations.

During the data review process, i identified missing values were in the product category column. These gaps affected related fields such as shipping fees and revenue, which could influence the accuracy of insights if not properly handled.

Data Splitting and Preprocessing
Before beginning the analysis, I cleaned and prepared the dataset to ensure accuracy and consistency.

I removed duplicates , corrected inconsistencies, and ensured all variables were formatted appropriately (dates, currency, and text). Missing values in the product category column were temporarily labeled as “Shipping Fee Error” to maintain workflow while awaiting clarification.

I then structured the data into:

Dependent variables such as revenue, shipping fees, and quantity
Independent variables such as customer, region, salesperson, product category, and location
<img width="1088" height="638" alt="Data splitting" src="https://github.com/user-attachments/assets/5480105c-1e81-4647-b004-4f8c04dc6876" />

This structure made it easier to analyze relationships and generate insights.

The dataset belongs to the retail industry, and the key stakeholders include business executives, sales teams, and marketing departments who rely on these insights for decision-making.

Pre-Analysis
At this stage, the focus was on defining the direction of the analysis.

Key questions were outlined, including:

How sales vary over time
Who the top customers are
Which regions and categories perform best
<img width="1688" height="985" alt="Pre analysis" src="https://github.com/user-attachments/assets/ca0823b1-e9b7-49b2-8786-6b894ce91b7b" />

The dataset was converted into an Excel table, and Pivot Tables were created to explore these questions. This phase served as a roadmap, ensuring the analysis remained focused and aligned with business objectives.

In-Analysis
During the analysis, several key observations were made.

Sales showed a strong seasonal trend, with December recording the highest sales at $66,642.78, while February recorded the lowest at $19,985.50.
<img width="1023" height="451" alt="Sales trend report" src="https://github.com/user-attachments/assets/ab898300-1142-4f4e-9cba-2d5c8d64278f" />

Customer contribution was highly concentrated. Company D generated the highest revenue at $67,180.50, while Company K, ranked tenth, generated $21,937.08.

<img width="810" height="610" alt="Top 10 Customers" src="https://github.com/user-attachments/assets/d690aa46-99dd-4f43-bc9a-82a59198a4b3" />

Salesperson performance varied significantly. Nancy Freehafer recorded the highest sales at $104,252.34, while Jan Kotas recorded the lowest at $16,350.50.

<img width="976" height="509" alt="Sales by rep" src="https://github.com/user-attachments/assets/ff48e1cc-10f3-4456-a2f9-05c5aa3a4205" />

Regionally, the North contributed 32.57% of total revenue, making it the top-performing region, while the West contributed 20.97%, making it the lowest.
<img width="640" height="565" alt="Sales by region" src="https://github.com/user-attachments/assets/b431658a-0123-49ab-8406-98300348626d" />

In terms of product categories, Beverages generated $110,577.11, while Grains generated only $2,884.00. Additionally, minor discrepancies labeled as “Shipping Fee Error” accounted for $30.00.
<img width="899" height="460" alt="Top  5 sales category" src="https://github.com/user-attachments/assets/ed5666ca-7543-4811-8228-f0229fdc26cb" />
<img width="318" height="393" alt="Sales by category pivot" src="https://github.com/user-attachments/assets/287ea1c0-c5bf-4738-b599-8eff221c8ad4" />

Geographically, New York emerged as the top-performing city and state with $67,180.50, while Nevada recorded the lowest at $15,365.50.
<img width="1480" height="908" alt="State Performance" src="https://github.com/user-attachments/assets/4a02b96f-57fc-4107-accd-e83fbb89f5cd" />

Transaction analysis showed that most purchases fell within the $0–$1000 range (over 216 transactions), while transactions between $7000–$8000 occurred only once.

<img width="1114" height="512" alt="Transaction by amount" src="https://github.com/user-attachments/assets/35b424aa-2077-40e6-8b54-8570141f90eb" />

Post-Analysis and Insights

After analyzing the dataset, several important insights emerged.

Revenue performance is uneven across regions, with stronger output in the North and East, while the West underperforms despite similar structure.

Sales success is strongly linked to high-performing product categories, particularly Beverages and Sauces.

There is also a noticeable customer concentration risk, where a few customers contribute a large portion of revenue.

Seasonality plays a significant role, with Q4 (especially December) driving peak sales, while early months like February lag behind.

Additionally, the gap between top and low-performing sales representatives highlights an opportunity to improve overall team productivity through structured strategies.

Recommendations

Based on the insights, several recommendations can be made.

The West region’s underperformance (20.97%) should be investigated to identify whether the issue lies in market demand, sales execution, or marketing strategy. Successful approaches from the North (32.57%) can be adapted to improve results.

The performance gap between Nancy Freehafer ($104,252.34) and Jan Kotas ($16,350.50) suggests a need for training, mentorship, and performance-based incentives.

Customer dependency should be reduced by strengthening relationships with mid-tier customers such as Company K ($21,937.08) while maintaining top clients like Company D ($67,180.50).

From a product perspective, the company should continue to leverage Beverages ($110,577.11) while reassessing low-performing categories like Grains ($2,884.00).

Seasonal fluctuations should also be managed by introducing targeted campaigns during low-performing months such as February.

Conclusion
This project highlights how data can be used to uncover meaningful insights that drive business decisions.

It shows that revenue is often driven by a small number of key factors — top customers, strong regions, and high-performing product categories. While this creates opportunities for growth, it also introduces risks that must be managed strategically.

Key Takeaways

Data analysis is not just about numbers, but about solving business problems
A small number of factors often drive the majority of results
Data cleaning and preparation are critical to accurate insights
Clear storytelling is essential for communicating findings effectively
Insights must always translate into actionable business decisions
References & Appendices

Dataset: Cach Superstore internal sales data
Tool used: Microsoft Excel (Pivot Tables, Charts, Data Cleaning)
