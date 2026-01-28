# Tips_Dataset_Analysis
This project performs an exploratory data analysis (EDA) on the classic Tips dataset to uncover insights into tipping behavior. We examine relationships between total bill, gender, smoking status, day of week, time of day, and party size using visualizations built with pandas, matplotlib, and seaborn.

## Dataset
The tips - tips (1).csv dataset contains information about tips received by a waiter over time. Each row represents one dining experience:
total_bill: Total bill in dollars. tip: Tip in dollars. sex: Gender of the payer (Male/Female). smoker: Whether the party included smokers (Yes/No).
day: Day of the week (Thur, Fri, Sat, Sun). time: Time of day (Lunch/Dinner). size: Size of the party.

## Analysis Highlits
The notebook covers comprehensive EDA through these steps:

## Data Inspection
1.Load data into pandas DataFrame
2. Preview with .head(), .tail()
3.Check data types (.info()), stats (.describe())
4. Identify unique values and missing data

## Data Visualization
Visualizations Created:
1. Bar plots: Sex, total_bill, and smoker relationships
2. Box plots: Total_bill distribution by day and smoker status
3. Catplots: Tip vs. size by smoker status
4. Strip plots: Total_bill by time and smoker
5. Boxen plots: Time distribution by party size
6. Heatmaps: Average tips by time and smoker status
7. Scatter plots: Total_bill vs. tip (with custom limits)
8. Line plots: Time vs. party size
9. Histograms: Total_bill distribution
10. Hexbin plots: Density of total_bill vs. tip

## How to Run
1.Clone the repository
2. Install dependencies
3. Ensure dataset is ready
4. Run the analysis

 ## Key Insights Preview
 
1. Dinner tips tend to be higher than lunch
2. Larger parties tip proportionally less
3. Smokers tip slightly less on average
4. Saturdays show highest total bills
