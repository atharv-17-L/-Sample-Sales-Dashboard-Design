📊 Simple Sales Dashboard using Power BI
🗂️ Project Overview
This project demonstrates how to design a basic interactive sales dashboard using Power BI, based on a sample sample_sales.csv dataset.

The dashboard provides clear visual insights into sales performance by:

Product Category

Region

Monthly Trends

This helps business users quickly understand key sales patterns and identify top-performing segments.

📈 Key Features
✅ Visuals Included:

Line Chart — Sales over time (Month-Year)

Bar Chart — Sales by Region

Donut Chart — Sales by Product Category

✅ Interactivity:

Filter/Slicer to drill down by Region or Category

✅ Highlights:

Clean, easy-to-read visuals

Effective color coding to emphasize top performers

Instant insights for decision making

📂 Repository Structure
bash
Copy code
simple-sales-dashboard/
├── data/
│   └── sample_sales.csv
├── output/
│   ├── dashboard_screenshot.png   # or dashboard.pdf
│   └── INSIGHTS.txt               # 3–4 key findings
└── README.md
🚀 How to Reproduce
1️⃣ Open Power BI Desktop (free to download)

2️⃣ Load the data:

Click Home > Get Data > Text/CSV

Select sample_sales.csv

3️⃣ Prepare data:

Create Month-Year:
FORMAT([Order Date], "MMM YYYY")

4️⃣ Create visuals:

Add Line Chart, Bar Chart, and Donut Chart

Use Month-Year on X-axis for time trends

5️⃣ Add Slicers:

For Region or Category

6️⃣ Customize colors and layout to highlight insights.

7️⃣ Export:

Take a screenshot or Export to PDF

8️⃣ Write insights:

Summarize 3–4 key findings in INSIGHTS.txt

💡 Example Insights
sql
Copy code
1️⃣ The West region recorded the highest sales in Q3.
2️⃣ The Technology category generates the highest average sales.
3️⃣ Sales peak towards the end of each year, indicating a strong seasonal pattern.
📌 Tools Used
Power BI Desktop

Optional: Python & Pandas for data cleaning (if needed)

🎯 Outcome
By completing this project, you gain hands-on experience with:

Interactive dashboard design

Basic data aggregation and visualization

Communicating business insights visually

📜 License
Open for learning, educational demos, and practice.

✅ Happy Dashboarding! 🚀
