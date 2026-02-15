🚗 EV Market Analysis – Web Scraping & Exploratory Data Analysis
📌 Project Overview

This project analyzes the Global Electric Vehicle (EV) Market using Web Scraping and Exploratory Data Analysis (EDA) techniques.

Electric Vehicles are transforming sustainable transportation. However, EV models vary significantly in:

🔋 Battery Capacity
🚗 Real Driving Range
🛡 Safety Ratings
⚡ Charging Speed
📦 Cargo & Towing Capacity
💰 Pricing across countries

This project extracts EV data from an online comparison platform and performs detailed analysis to uncover patterns in pricing, performance, and market positioning across countries.

🎯 Problem Statement
The rapid growth of the EV market has created large variations in:
Pricing
Battery capacity
Safety ratings
Charging capabilities
Performance metrics
across countries like:
Germany 🇩🇪
Netherlands 🇳🇱
United Kingdom 🇬🇧

These variations make it difficult for:
Buyers to select the best EV
Manufacturers to analyze competitors
Policymakers to promote effective EV adoption
This project identifies the key attributes influencing EV pricing and market segmentation.

🎯 Objectives

Analyze EV specifications and pricing differences across countries
Compare vehicles by seat category and safety rating
Study battery capacity vs real-world range
Identify price trends by safety category
Determine most and least expensive EV brands
Evaluate acceleration vs vehicle weight
Analyze charging capability vs price
Provide insights for customers, manufacturers, and policymakers

🌐 Data Source

Data was collected via web scraping from:
EV Database (EV Comparison Website)
🔗 https://ev-database.org/

Filtered Vehicle Data URL Used:
https://ev-database.org/#group=vehicle-group&rs-pr=10000_100000&rs-er=0_1000&rs-ld=0_1000&rs-ac=2_23&rs-dcfc=0_400&rs-ub=10_200&rs-tw=0_3000&rs-ef=100_350&rs-sa=-1_5&rs-w=1000_3500&rs-c=0_5000&rs-y=2010_2030&s=1&p=0-10

📌 Extracted Features

Brand & Model
Price (UK, Germany, Netherlands)
Battery Capacity
Real Driving Range
Efficiency
Safety Rating
Charging Power (AC/DC)
Acceleration (0–100 km/h)
Vehicle Weight
Cargo & Towing Capacity

⚠️ Data collected strictly for educational and analytical purposes.

🛠 Tools & Technologies Used
Python
Requests
BeautifulSoup
Pandas
NumPy
Matplotlib
Seaborn
Regex (Data Cleaning)

🌐 Web Scraping Workflow

Sent HTTP requests using requests
Parsed HTML using BeautifulSoup
Extracted structured EV specifications
Cleaned data using Pandas
Standardized currencies (€ / £)
Performed Exploratory Data Analysis

🧹 Data Cleaning & Preprocessing

Handled missing numerical values using median
Filled categorical missing values using mode
Removed high-null columns (availability status)
Verified no duplicate records
Confirmed dataset has no missing values after preprocessing

📊 Key Insights
💰 Price Comparison Across Countries

Germany & Netherlands show strong mid-range dominance (€30k–€70k)
UK market is comparatively more budget-focused
Premium EV outliers exist in all markets

🛡 Safety Category
91.8% EVs fall under High Safety
Strong positive relationship between safety and price

🔋 Battery Capacity vs Real Range
Strong positive correlation
Larger battery → Higher real-world range

⚡ Charging Capability vs Price
Rapid DC charging mainly available in premium EVs
Charging speed significantly influences pricing segment

🚀 Acceleration vs Weight
Heavier EVs often compensate with stronger motors
Performance is not purely weight-dependent

🏆 Business Insights
Buyers should evaluate value-for-money metrics (range + safety + price)
Manufacturers can optimize battery efficiency to compete in mid-range
Policymakers should support affordable high-safety EV models

⚠ Challenges Faced

Inconsistent website structure during scraping
Missing fields and currency normalization
Multi-country comparative visualizations
Feature engineering for better analytical insights

📌 Conclusion

This project demonstrates that:
Battery capacity, safety rating, and charging technology significantly impact EV pricing.
The UK market shows more affordability compared to Germany and the Netherlands.
Battery size strongly influences real-world driving performance.

The analysis provides actionable insights for buyers, manufacturers, and policymakers in the evolving EV ecosystem.
