# Crm-Sales-And-Pipeline(Interactive Dashboard)
## Project Objective 
--To design and implement a comprehensive CRM & Sales Pipeline Dashboard in Power BI that enables stakeholders to monitor and analyze the full sales journey — from lead acquisition to deal closure — by tracking key performance indicators such as conversion rates, sales cycle durations, deal values, and forecast accuracy. 

--The goal was to provide actionable insights across products, industries, geographies, and sales representatives, helping the business identify bottlenecks, optimize sales performance, and drive strategic decision-making through real-time interactive visualizations.

##Link Of Dashboard

 <a href="https://github.com/sah777s/Crm-Sales-And-Pipeline">Dashboard</a>

 ## ❓ Business Questions Solved by This Dashboard

### 🔄 Sales Funnel & Conversion Efficiency
- [x] How many leads were generated, and how many converted into customers?
- [x] What is our overall lead-to-customer conversion rate?
- [x] At which sales stages are most leads dropping off?
- [x] What is the average sales cycle duration across all deals?
- [x] Are there delays between lead acquisition and deal closure?
- [x] How many open deals are still in progress at each stage?

### 👥 Sales Team Performance
- [x] Which sales representatives are consistently closing the highest deal values?
- [x] Which sales reps have the fastest and slowest sales cycles?
- [x] How do different sales reps perform across industries or countries?
- [x] Who is responsible for the most lost opportunities?
- [x] Are there reps who are not converting leads past the initial stage?

### 📅 Trend & Forecast Accuracy
- [x] How are monthly sales trending — are we growing or declining?
- [x] Which months showed peak and lowest deal closures?
- [x] How accurate are our sales forecasts compared to actual close dates?
- [x] Are there significant gaps between expected and actual close dates?
- [x] Is our pipeline sufficient to meet future targets based on current progress?

### 🧩 Product & Industry Insights
- [x] Which product lines are generating the most revenue?
- [x] Which industries show the highest conversion rates?
- [x] Where are we losing the most deals by product or industry?
- [x] Which product has the most open deals that may convert soon?
- [x] Are certain products performing better in specific regions or industries?

### 🌍 Geographic & Market Segmentation
- [x] Which countries are contributing most to our deal value?
- [x] Which countries have the highest or lowest conversion rates?
- [x] Are there regional patterns in lost deals or delayed closures?
- [x] How does deal value break down by organization size (small/medium/large)?

### 💰 Deal Value & Opportunity Size
- [x] What is the total deal value currently in the pipeline?
- [x] How does deal value distribute across won, lost, and open stages?
- [x] What is the average value of a won deal?
- [x] How many small, medium, and large deals are we handling?
- [x] What is our highest value closed deal, and who closed it?

- [ ] ## 🔧 Project Process – Step-by-Step Workflow

1. **🎯 Requirement Gathering**
   - Identified business needs: track leads, monitor conversions, assess sales rep performance, analyze deal flow.
   - Defined KPIs: Conversion Rate, Avg. Sales Cycle, Forecast Accuracy, Deal Value by Segment.

2. **📁 Data Collection & Understanding**
   - Imported CRM dataset with 3,000+ leads (Excel format).
   - Key fields: Owner, Product, Industry, Country, Lead Dates, Deal Value, Probability %, Status, Stage.

3. **🧹 Data Cleaning & Transformation (Power Query)**
   - Removed invalid/missing date rows.
   - Standardized categories (e.g., Status, Industry names).
   - Replaced missing values with blanks or labeled as "Open Deal".
   - Ensured consistent date formats (Lead, Expected Close, Actual Close).

4. **🧮 Calculated Columns & Measures (DAX)**
   - Created date table using `CALENDAR()` and linked to Actual & Expected Close Dates.
   - Defined key metrics:
     - `Conversion Rate`
     - `Sales Cycle (Days)`
     - `Forecast Accuracy`
     - `Lost Opportunity Rate`
     - `Deal Value by Owner/Industry/Product/Size`

5. **📊 Dashboard Design in Power BI**
   - Built report pages:
     - Sales Funnel Overview
     - Sales Rep Performance
     - Product & Industry Insights
     - Time Trends & Forecasts
     - Geo & Org Size Analysis
   - Used visuals:
     - Funnel, bar/column charts, line chart, donut, KPI cards, maps, slicers.
   - Implemented drilldowns (e.g., Industry > Organization, Product > Status).

6. **🎛️ Interactivity & Filters**
   - Added slicers: Country, Owner, Product, Industry, Status, Date Range.
   - Enabled cross-filtering and drill-throughs for detailed analysis.

7. **📈 Insight Extraction**
   - Derived actionable insights:
     - Low final-stage conversion (2.77%)
     - Medium orgs contributed 62.7% of total deal value
     - April had an 18.38% MoM drop in sales performance
     - Laura Thompson was the top closer with $2.05M

8. **📤 Dashboard Deployment**
   - Published `.pbix` file with documentation and screenshots.
   - Hosted on GitHub and shared with stakeholders.
  
   -![Screenshot 2025-06-28 203458](https://github.com/user-attachments/assets/fabbcad0-38c4-47fc-a640-dc7aff051700)
   ![Screenshot 2025-06-28 203511](https://github.com/user-attachments/assets/1f3b46f5-9141-495b-b5fb-c5ea01584209)
   ![Screenshot 2025-06-28 203527](https://github.com/user-attachments/assets/349ffa62-1f59-4dcd-9a17-0eaad0577c51)
   ![Screenshot 2025-06-28 203544](https://github.com/user-attachments/assets/fb4bff51-7d76-4310-b2b4-2cad35d9f965)
   ![Screenshot 2025-06-28 203559](https://github.com/user-attachments/assets/1f001204-bb2c-40a3-9305-8de7671a8b64)
   ![Screenshot 2025-06-28 203623](https://github.com/user-attachments/assets/de334131-32f1-4b4e-bac5-407dae5d0d1d)
   - 
 ##📊 Project Insights


  🔄 Sales Funnel & Conversion
Over 3,000 leads were tracked with a final-stage conversion rate of only 2.77%, signaling significant drop-offs after the “Proposal Sent” stage.

Lost opportunity rate was 2.03%, showing a need to strengthen middle-funnel engagement.

The funnel clearly highlighted weak points in the lead progression — particularly during the transition from “Qualified” to “Proposal Sent.”

🧑‍💼 Sales Team Performance
Laura Thompson emerged as the top performer, closing $2.05M in deal value, followed by Michael Brown with $1.38M.

Sales cycle analysis revealed wide variations — from 52 days (fastest) to 71 days (slowest), suggesting performance benchmarking opportunities.

Sales reps with longer cycles and low closure rates can be targeted for coaching or support.

📆 Forecast Accuracy & Time Trends
The average forecast accuracy deviation was 139.35 days, indicating significant misalignment between expected and actual close dates.

Peak sales occurred in March ($50K), while May saw the lowest performance ($25K), with April recording an 18.38% MoM drop.

These trends support adjusting forecast models and pipeline pacing strategies.

🧩 Product & Market Insights
Custom Solutions and SAAS were the most valuable products, contributing 40.11% and 37.73% of total deal value respectively.

By industry, Entertainment (5.74%) and IT & ITES (4.39%) had the best conversion rates.

Medium-sized organizations contributed 62.7% ($5.2M) of total deal value — a strong segment to prioritize.

🌍 Geographic Analysis
Top conversions came from Germany, Switzerland, and Italy.

Lost deals were more concentrated in the Government & Healthcare sector, with a 3.16% loss rate.

##✅ Final Conclusion
The CRM & Sales Pipeline Dashboard successfully delivered a 360° view of sales operations, helping stakeholders:

Monitor real-time sales funnel health

Identify top and underperforming reps, products, and markets

Evaluate sales cycle efficiency and forecast reliability

Pinpoint strategic segments for growth and retention

This data-driven approach empowers decision-makers to optimize resource allocation, improve lead nurturing strategies, and increase overall pipeline efficiency. The interactive Power BI solution is designed for scalability and can be extended with predictive analytics, lead scoring, or integration with live CRM APIs.


