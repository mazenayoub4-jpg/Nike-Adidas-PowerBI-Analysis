# Nike-Adidas-PowerBI-Analysis
"An end-to-end Power BI dashboard analyzing Nike and Adidas product data, featuring Star Schema modeling, YoY growth metrics, and customer sentiment analysis."
# 👟 Nike vs. Adidas: Global Market & Sentiment Analysis

This is my professional analysis comparing Nike and Adidas product data. I focused on building a clean data model and using advanced calculations to find real business insights.

---

## 📊 Dashboard Overview
The dashboard provides a high-level executive summary and deep-dive analytics, focusing on:
* *Market Share:* Distribution of products and volume between Nike and Adidas.
* *Pricing Intelligence:* Analysis of Average Listing Prices and their impact on ratings.
* *Customer Sentiment:* Visualizing feedback trends and product satisfaction scores.
* *Global Presence:* Geospatial mapping of inventory and market reach.

## 🛠️ Technical Implementation

### 1. Data Engineering & ETL
* *Source:* Cleaned and processed CSV datasets.
* *Processing:* Used Power Query to handle null values, standardize brand naming, and format currency strings.
* *Schema:* Implemented a *Star Schema* (Fact/Dimension tables) for optimized query speed and model scalability.

### 2. Advanced Analytics (DAX)
Engineered custom DAX measures for sophisticated business logic:
* *Year-over-Year (YoY) Sales:* Calculated growth trends using Time-Intelligence functions.
* *Dynamic Narratives:* Used AI-driven Smart Narratives to generate automated insights based on user filters.
* *Rating Normalization:* Standardized product feedback to create a unified "Product Performance" score.

### 3. UI/UX & Design
* *Brand Identity:* Used a cohesive grey-scale professional theme with brand-specific accents.
* *Precision Layout:* Applied strict alignment and distribution rules for a clean, corporate look.
* *Interactivity:* Integrated *Custom Tooltips* and *Slicers* for an intuitive user experience.

## 🚀 Key Insights
* Identified a *50/50 Market Share* split in the current dataset, indicating high competition.
* Correlated *Feedback Volume* with *Final Ratings* to identify top-performing product categories.
* Visualized global "Hotspots" for inventory distribution across Europe, Africa, and the Americas.

## 📁 Repository Structure
* /Data: Raw and Cleaned CSV files.
* /Reports: The .pbix Power BI project file.
* /Screenshots: Dashboard views and Data Model diagrams.

---

### 📝 License
This project is licensed under the *MIT License* - feel free to use the logic and design for your own analysis.

*Developed by Mazen Ayoub*
