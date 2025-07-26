# metro-analytics
Namma Metro Ridership Analysis: A Data-Driven Approach to Urban Mobility
1. Executive Summary
This project provides a comprehensive data analysis and forecasting solution for Bengaluru's Namma Metro ridership. By leveraging Python and advanced analytics techniques, this study aims to transform raw ridership data into actionable insights for strategic decision-making. The key outcomes include:

Understanding Ridership Patterns: A detailed analysis of daily, weekly, and seasonal ridership trends.

Payment Method Deep Dive: A breakdown of ridership by ticket type to identify market share and digital adoption.

Predictive Forecasting: A 90-day forecast of future ridership to support operational planning and resource allocation.

Interactive Dashboard: A professional Power BI dashboard to visualize all key metrics and findings.

2. Problem Statement
As Bengaluru's urban population grows, understanding and predicting public transit usage is crucial for operational efficiency. Namma Metro requires insights into ridership dynamics to optimize train schedules, manage revenue streams, and plan for future expansion. This project addresses these needs by providing a data-driven framework for analysis and prediction.

3. Data Source
The analysis is based on the NammaMetro_Ridership_Dataset.csv file, a time-series dataset containing daily ridership figures for the entire metro network. Key data points include ridership categorized by various payment methods such as Smart Cards, Tokens, and different QR-based platforms.

4. Methodology & Technical Stack
The project follows an end-to-end data analytics workflow, from data ingestion to final visualization.

Data Preparation: The raw CSV data was ingested and cleaned using Pandas. Feature engineering was performed to derive time-based metrics (Day of Week, Is Weekend) and a Total Daily Ridership column.

Exploratory Data Analysis (EDA): Insights were extracted through visualizations created with Matplotlib, Seaborn, and Plotly.

Advanced Forecasting: A time-series model was built using fbprophet. The model was configured with weekly and yearly seasonality to accurately capture ridership fluctuations and predict future trends.

Interactive Dashboarding: A dynamic and user-friendly dashboard was developed in Power BI to present key metrics and facilitate data exploration for stakeholders.

Technical Stack:

Languages: Python

Libraries: pandas, numpy, matplotlib, seaborn, plotly, fbprophet

Business Intelligence: Power BI Desktop

Version Control: Git & GitHub

5. Key Insights & Business Recommendations
Ridership Trends: The analysis reveals a clear upward trajectory in overall ridership, with a significant and predictable drop on weekends.

Payment Method Dominance: Smart Cards remain the primary mode of payment, accounting for over 50% of daily ridership. However, QR-based payments are showing consistent and accelerated growth.

Actionable Recommendation:

Operational: Optimize train frequency and staff scheduling by using the Day-of-Week patterns to match supply with demand.

Marketing: Launch targeted promotions for QR-based payments to further accelerate digital adoption and reduce reliance on physical tokens.

Strategic: Utilize the ridership forecast to inform long-term budgeting and resource planning for infrastructure expansion.
