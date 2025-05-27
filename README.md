# Airbnb-Rent-Price-Analysis

This project focuses on performing an exploratory data analysis (EDA) of Airbnb listings to uncover the factors that significantly impact rental prices. The goal is to help hosts, travelers, and Airbnb itself make data-driven decisions for pricing strategies, business optimization, and enhanced user satisfaction.


Project Objective:

The primary aim is to understand what drives the pricing of Airbnb listings. With thousands of listings across different cities and varying amenities, the pricing structure can appear arbitrary. By analyzing attributes such as room type, cancellation policies, number of bedrooms and beds, accommodation capacity, and location features, this project strives to reveal patterns and derive actionable insights.


Dataset Overview:

The dataset comprises key features such as:

Room Type: Entire home/apartment, Private room, Shared room

Price: Actual price per night

Accommodation Capacity: Number of guests that can be accommodated

Number of Bedrooms and Beds

Cancellation Policy: Flexible, Moderate, Strict

Location Details: City, Latitude, Longitude

Other Features: Availability, Review scores, Minimum nights, etc.

The data was cleaned to handle missing values, remove outliers, and convert categorical features into a usable format for analysis. Aggregations and summary statistics were computed to support further exploration.


Exploratory Data Analysis:

The project began with univariate and bivariate analyses:

Room types were analyzed against average prices. Entire apartments had the highest average price, followed by private rooms and shared rooms.

Cancellation policies influenced pricing. Listings with strict policies generally had higher average prices, indicating host confidence and possibly higher-quality listings.

The number of beds, bedrooms, and guest capacity were also positively correlated with price.

Additional plots, statistical summaries, and correlation matrices revealed which numerical attributes had the strongest relationship with rental price.


Key Questions and Hypotheses:

A structured approach was followed by framing questions such as:

Do private rooms cost more than shared rooms?

Does the number of accommodations affect price?

Is there a relation between price and the number of beds?

How do different cancellation policies affect pricing?

These hypotheses were tested with visualizations and summary statistics. For example, private rooms were found to be significantly more expensive than shared rooms, and the number of beds and accommodation capacity were positively linked to pricing, though with diminishing returns beyond certain thresholds.


Insights and Recommendations:

Room Type Matters: Entire homes consistently charge more, while shared rooms are the most budget-friendly.

Size Drives Price: More beds and larger accommodation capacity correlate with higher price but should be balanced against occupancy rates.

Cancellation Policy Premium: Listings with strict cancellation policies fetched higher prices, likely signaling premium or more professional properties.

Price Optimization: Hosts can benefit from adjusting room features and policies to align with high-performing categories in their area.


Conclusion:

This Airbnb project successfully demonstrates the power of EDA in drawing meaningful business insights from complex datasets. The findings not only help hosts optimize listing prices but also guide Airbnb in designing pricing algorithms and recommendation systems. By combining statistical analysis with domain understanding, this project highlights key levers that influence user behavior and revenue generation in the sharing economy.

