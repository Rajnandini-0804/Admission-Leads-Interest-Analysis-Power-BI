Admission Leads Interest Analysis – Power BI
📌 Project Overview

This project focuses on analyzing High Interested and Low Interested admission leads using Power BI. The goal is to help the admission team understand lead quality, response behavior, follow-ups, and future trends for better admission planning.

🎯 Objective

To create an interactive Power BI dashboard that:

Classifies admission leads into High Interest and Low Interest

Tracks follow-ups and response time

Analyzes conversion rate

Forecasts future trends

Allows drill-through to individual student details

🧾 Dataset Description

The dataset contains admission enquiry details such as:

Lead ID

Student Name

Inquiry Date

Interest Level (High / Low)

Follow-Up Count

Response Time (Days)

Admission Status (Enrolled / Not Enrolled)

A Star Schema model is used with:

Fact Table: Admission Leads

Dimension Tables: Student, Date, Interest Level

🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Excel (Data Source)

📊 Dashboard Features
1️⃣ KPI Cards

Total Leads

Enrolled Leads

Conversion Rate (%)

Average Response Time

2️⃣ Interest Analysis

Bar chart comparing High vs Low Interested Leads

3️⃣ Follow-Up Analysis

Sum of follow-ups by interest level

4️⃣ Conversion Rate Analysis

Conversion Rate calculated using DAX

Conversion Rate (%) =
DIVIDE([Enrolled Leads], [Total Leads], 0) * 100
5️⃣ Trend Analysis

Line chart showing inquiry trends over time

6️⃣ Forecasting

Forecast applied on response time trend to predict future behavior

7️⃣ Drill-Through

Drill-through page to view individual student details


🧠 Key Insights

High Interested leads have a higher conversion rate

Faster response time increases enrollment chances

Follow-ups play a major role in lead conversion

Forecast helps plan future admission workload

⚠️ Limitations

Interest level is based on available data

More accuracy can be achieved using call logs, emails, or counselor feedback

📌 Conclusion

This Power BI dashboard provides a clear and interactive way to analyze admission leads. It helps decision-makers focus on high-quality leads and improve admission strategies.

📎 Project Use Case

Admission Team

Education Consultants

Business/Data Analysts

👩‍💻 Author

Rajnandini Bhosale 
Power BI & Data Analytics Enthusiast

⭐ If you like this project, feel free to star the repository!
