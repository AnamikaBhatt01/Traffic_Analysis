accident-severity-analysis-powerbi
🚦 US Traffic Accident Severity Analysis Dashboard
50K data rows out of millions to work upon

This project focuses on analyzing accident severity patterns using real-world US traffic accident data.

The main goal was to understand how factors like weather conditions, time of day, and road infrastructure impact the severity of accidents and identify high-risk patterns.

🔧 Project Workflow

Instead of directly loading the raw dataset into Power BI, the data was first pre-processed using Python in Google Colab.

In Colab, I:

Filtered out only the relevant columns such as:

Start Time

Severity

Weather Conditions

Junction

Traffic Signal

Stop Sign

Crossing

Latitude & Longitude

Created derived features like:

Hour of Accident

Time of Day (Morning / Afternoon / Evening / Night)

Month (for trend analysis)

Once the required filtering and feature engineering was done, the cleaned dataset was exported and imported into Power BI for visualization.

📊 Power BI Dashboard

In Power BI, DAX measures were created for:

Total Accidents

Severe Accidents (Severity 3–4)

Severity Rate

The following interactive visuals were built:

Monthly Accident Trend

Weather-wise Accident Distribution

Time of Day vs Severity

Road Infrastructure Impact

Peak Accident Hour Analysis

Accident Hotspot Mapping (using Latitude & Longitude)

Note: Azure Maps visual was not available, so the standard Map visual was used to plot accident hotspots using geographical coordinates.

📌 Key Insight

Accident severity tends to be higher during evening hours, especially under foggy weather conditions and near road junctions.

🛠 Tools Used

Python (Google Colab)

Power BI

DAX

Data Cleaning & Feature Engineering

Data Visualization

This project helped me connect Python-based preprocessing with Power BI dashboarding as part of building my analytics portfolio.
