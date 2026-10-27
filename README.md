# Superstore Sales Analysis & Customer Retention Tracking
This repository contains an end-to-end data analysis workflow utilizing Python, Pandas, Matplotlib, and Seaborn to extract actionable business insights from retail transaction records (using the classic Superstore dataset).

📋 Project Overview
The goal of this project is to analyze sales operations and customer behaviors over a multi-year period (2014-2017). The analysis covers several dimensions, including:

Sales Performance: Breakdown by geographic region, product category, and customer segment.
Shipping Performance: Investigation of order-to-shipping durations and their relationship to revenue metrics.
Customer Lifetime Value: Identification of top customers and tracking of their recent orders.
Customer Retention Dynamics: Year-over-Year (YoY) cohort retention rates indicating business health.
Growth Forecasting Foundation: Yearly Sales Trends combined with dual-axis YoY Revenue Growth metrics.
🚀 Key Insights discovered
Regional Dominance: The West and East regions drive the highest volume of total revenue.
Customer Cohorts: Year-over-Year customer retention grew steadily, indicating stronger customer loyalty over time (rising from 73.45% in the 2014-2015 cohort to 87.46% in 2016-2017).
Shipping & Turnaround: Orders taking 4 to 5 days to ship generated the highest chunk of total sales.
Year-over-Year Growth: Following a slight sales decline in 2015 (-2.83%), sales surged in 2016 with a growth rate of 29.47% and sustained positive growth of 20.36% in 2017.
🛠️ Technical Workflow & Libraries
Data Cleaning: Handled missing values, duplicates, and validated column structures.
Temporal Conversion: Converted object date fields to Datetime objects to engineer accurate shipping durations and calendar cohort groupings.
Visualization: Designed structured plots utilizing dual-axis parameters (matching sales volume curves against growth percentages) using matplotlib.pyplot and seaborn.
# Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
