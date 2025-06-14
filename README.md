📊 Simple Sales Dashboard using Power BI

🗂️ Project Overview
This project demonstrates how to build a basic interactive sales dashboard using Power BI, based on a sample dataset (sample_sales.csv).
The dashboard provides clear visual insights into sales performance by:

Product Category

Region

Monthly Trends

This helps business users quickly understand key sales patterns and identify top-performing areas.

📈 Key Features
✅ Visuals Included

Line Chart: Sales trends over time (Month-Year)

Bar Chart: Sales by Region

Donut Chart: Sales by Product Category

✅ Interactivity

Filter/Slicer for Region or Category

✅ Highlights

Clean and simple design

Colors emphasize top performers

Easy to interpret and share


📂 Repository Structure
bash
Copy code
simple-sales-dashboard/
├── data/
│   └── sample_sales.csv
├── output/
│   ├── dashboard_screenshot.png  # or dashboard.pdf
│   └── INSIGHTS.txt              # 3–4 key insights
└── README.md

🚀 How to Reproduce
Open Power BI Desktop (free to download)

Import Data

Click Home > Get Data > Text/CSV

Select sample_sales.csv

Prepare Data

Create a Month-Year column:
FORMAT([Order Date], "MMM YYYY")

Create Visuals

Add Line Chart, Bar Chart, and Donut Chart

Use Month-Year on X-axis for time series

Add Filters/Slicers

For Region and/or Category

Customize

Adjust colors, layout, and labels for clarity

Export

Take a screenshot or export the dashboard as PDF

Summarize Insights

Write 3–4 key findings in INSIGHTS.txt

💡 Example Insights
The West region had the highest sales in Q3.

Technology category generated the highest average sales.

Sales peaked in the last quarter, showing a seasonal trend.


🛠️ Tools Used
Power BI Desktop

(Optional) Python & Pandas for data cleaning


🎯 Outcome
By completing this project, you will:

Practice importing data into Power BI

Create clean, interactive dashboards

Summarize data visually for business stakeholders



✅ Happy Dashboarding! 🚀
