This project analyzes hotel booking data from 2015–2017 to understand cancellation patterns, customer behavior, and revenue impact. The goal is to identify the main reasons behind cancellations and suggest strategies that hotels can use to improve revenue and reduce booking cancellations.

Business Problem

Hotels often face high cancellation rates, especially from city hotels and online travel agencies. 
This leads to:

Loss of revenue.
Empty rooms that could have been sold.
Poor forecasting of demand.

 Key Questions

What factors influence hotel booking cancellations?
Which hotel type (City or Resort) faces more cancellations?
Are cancellations higher during specific months or seasons?
Does pricing (Average Daily Rate) affect cancellations?
Which customer segments and countries cancel the most?

📊 Hypotheses

Higher prices (ADR) lead to more cancellations.
Customers booking far in advance (long lead times) cancel more often.
Online Travel Agencies have higher cancellation rates compared to direct bookings.
Summer months (peak season) experience more cancellations.

🗂 Dataset

File: hotel_bookings.csv
Size: 119,390 rows × 32 columns
Period: 2015–2017


 Tools Used

Python (Pandas, Numpy)
Data Visualization: Matplotlib, Seaborn
Jupyter Notebook

 Key Findings

Cancellation Rate: ~37% of all bookings were canceled.

Hotel Type:

City Hotels → ~42% cancellations
Resort Hotels → ~28% cancellations

Seasonality: Summer months (July, August) saw more cancellations.

ADR (Average Daily Rate): Cancelled bookings had higher ADR values.
Market Segments: Online Travel Agencies (OTAs) contributed nearly 47% of bookings and had the highest cancellations.

Top Countries with Cancellations: Portugal, UK, USA, Spain, France.

 Recommendations

Adjust pricing strategy in peak months to lower cancellations.
Offer discounts for non-refundable bookings.
Encourage direct bookings through loyalty programs and promotions.
Introduce deposit requirements for long lead-time bookings.
Target marketing campaigns towards repeat guests and direct customers.


