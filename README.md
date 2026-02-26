Online Retail Mini Data Analytics Project


Focus: Identify bestselling products and understand when customers buy the most.

Quick exploratory analysis of the famous Online Retail dataset (UK transactions only) 

 Dataset
 
- Source: [Online Retail Dataset on Kaggle)
- File: `OnlineRetail.csv` (~541,909 rows originally)
- Time period: Dec 2010 – Dec 2011
- After cleaning (UK only, no cancellations/returns): ~486,286 transactions

Business Questions

1. Which products are our bestsellers (by quantity and by revenue)?
2. When do customers buy the most? (hour of day and day of week)

Key findings

Sales by hour of the day

<img width="452" height="203" alt="image" src="https://github.com/user-attachments/assets/55075e02-0353-4cde-9165-ed59eb730bdf" />



Figure 1 shows sales by hours of the day

Shopping activity follows a strong daily rhythm. Total sales peak sharply at 12:00 noon with £1,218 thousand, closely followed by 15:00 (£1,197 thousand), 10:00 (£1,177 thousand), and 13:00 (£1,062 thousand). The main active shopping window runs from 10:00 to 15:00, during which the majority of daily revenue is generated. Sales are very low before 8:00 and drop off significantly after 17:00–18:00.


Sales by days of the weeks


<img width="445" height="246" alt="image" src="https://github.com/user-attachments/assets/5ded36c1-b35a-4802-8a46-4f4658b198ae" />


Figure 2: shows sales by the days of the weeks

On a weekly level, Tuesday stands out as the strongest day with approximately £1,850 thousand in sales, followed by Thursday (£1,750 thousand) and Wednesday (£1,600 thousand). Monday, Friday, and Sunday show moderate activity, while Saturday has almost no recorded sales — likely due to no weekend dispatch or operational closure during that period

Recommendation

Based on these findings, a straightforward business recommendation is to time promotional emails, push notifications, and flash sales to arrive between 10:00 and 12:00. This window captures the beginning of the strongest daily shopping surge and should help improve engagement and conversion rates.

The project uses Python with pandas for data manipulation and matplotlib/seaborn for visualisation. The large CSV file is not uploaded — please download it directly from Kaggle.

