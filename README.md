# VOIS_AICTE_Oct2025_VaidikSharma
Airbnb_DIY_Project
🏨 Airbnb Hotel Booking Analysis
📘 Project Overview

The hospitality industry has experienced a major shift with the rise of online booking platforms enabling short-term rentals and tourism.
Airbnb, a pioneer in this domain, allows hosts to rent out properties to guests without owning the listings directly.

This project explores the New York City Airbnb dataset to uncover valuable insights about pricing, customer satisfaction, availability, and host behavior using Python-based data analysis and visualization techniques.

🎯 Problem Statement

To analyze the Airbnb dataset for New York City and derive meaningful insights regarding:

Property distribution across neighborhoods

Pricing patterns and service fee correlations

Review trends and host verification impacts

Availability trends and host performance

The objective is to help hosts, guests, and tourism analysts make data-driven decisions in the hospitality industry.

👥 End Users

Hosts – to optimize their pricing and occupancy strategies

Guests – to choose better accommodation options based on price and reviews

Researchers – to study trends in short-term rentals

Policy Makers – to understand the short-term housing market dynamics

⚙️ Technologies Used

Programming Language: Python

Libraries:

pandas – Data cleaning and manipulation

numpy – Numerical computation

matplotlib, seaborn, plotly – Data visualization

Tools: Google Colab / Jupyter Notebook

Dataset Format: CSV (new.csv)

Version Control: GitHub

🧹 Data Cleaning & Preprocessing

Steps performed:

Removed duplicates and irrelevant columns (license, house_rules).

Cleaned monetary columns (price, service_fee) by removing $ and ,.

Converted data types to appropriate formats (datetime, float, int).

Fixed inconsistent naming (neighbourhood_group, host_identity_verified, etc.).

Filtered out invalid entries (availability_365 > 365).

📊 Exploratory Data Analysis (EDA)

The analysis was carried out to answer key questions about Airbnb listings:

Property Type Distribution

Entire homes/apartments are the most common listings.

Neighborhood Popularity

Manhattan and Brooklyn have the highest number of listings.

Average Pricing by Area

Manhattan leads with the highest average price per listing.

Price vs Service Fee

A positive correlation was observed (higher price → higher service fee).

Host Insights

Top 10 hosts account for a significant share of listings.

Verified hosts receive higher average review ratings.

Availability and Listings Count

More listings per host correlate with lower availability.

📈 Key Visualizations

Bar charts: Property type and neighborhood group distributions

Line charts: Average price by construction year

Regression plots: Price vs Service Fee

Boxplots: Review rates by host verification

Bar charts: Top 10 hosts by listing count

(All visualizations were created using Seaborn and Matplotlib.)

🔍 Insights & Conclusions

Manhattan dominates the Airbnb market in both pricing and number of listings.

Entire homes/apartments are preferred by guests.

Verified hosts tend to receive better reviews, showing the importance of trust.

Service fee is proportionate to the listing price, maintaining a consistent commission structure.

Highly active hosts often balance lower availability with more listings to maximize revenue.
