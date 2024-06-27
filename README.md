# 🏙️ Airbnb Dashboard

## Overview
The dashboard provides a detailed analysis of Airbnb listings in New York City, focusing on various aspects such as bookings, reviews, pricing, and neighborhood-specific insights. It aims to help stakeholders understand the dynamics of the Airbnb market in NYC and make informed decisions.

## 📊 Dataset Details
The dataset (`AB_NYC_2019.csv`) contains data on Airbnb listings in New York City, with columns such as:
- `id`: Listing ID
- `name`: Name of the listing
- `host_id`: ID of the host
- `host_name`: Name of the host
- `neighbourhood_group`: Main borough (e.g., Manhattan, Brooklyn)
- `neighbourhood`: Specific neighborhood
- `latitude`: Latitude coordinate
- `longitude`: Longitude coordinate
- `room_type`: Type of room (e.g., Entire home/apt, Private room)
- `price`: Price per night
- `minimum_nights`: Minimum number of nights required for booking
- `number_of_reviews`: Total number of reviews
- `last_review`: Date of the last review
- `reviews_per_month`: Average number of reviews per month
- `calculated_host_listings_count`: Number of listings the host has
- `availability_365`: Number of days the listing is available per year

## 📈 Dashboard Explanation
- **🏨 Total Bookings by Neighborhood Group and Room Type:** Visualizes the count of bookings for different room types across various neighborhood groups.
- **📆 Average Reviews per Month by Room Type and Neighborhood Group:** Displays the average number of reviews per month for each room type and neighborhood group.
- **🏅 Top 10 Hosts by Total Reviews:** Lists the top hosts based on the number of reviews they received, along with their neighborhood and average price.
- **📅 Total Reviews by Year:** Shows the total number of reviews received each year, indicating market growth and activity over time.
- **🗺️ Average Price in the Neighborhood - Room Type: All:** A map illustrating the distribution of prices across neighborhoods for all room types.
- **🏘️ Total Neighborhood by Neighborhood Group:** A pie chart showing the proportion of listings in each neighborhood group.
- **📊 Total Bookings by Month and Neighborhood Group - Room Type:** Displays monthly bookings segmented by neighborhood group and room type.
- **💰 Average Price by Neighborhood Group - All:** A chart showing the average price per neighborhood group.
- **🏙️ Average Price in the Neighborhoods - Neighborhood Group: Bronx:** Highlights average prices within the Bronx neighborhood group, showing the most and least expensive areas.

## 📋 Conclusion
The analysis of Airbnb listings in New York City reveals several key insights:

- **Popular Neighborhoods and Room Types:**
  - **📍 Manhattan and Brooklyn:** These neighborhoods are the most popular, with the highest number of bookings.
  - **🏠 Entire Home/Apt:** The preferred room type, indicating a preference for privacy and space.

- **Review Patterns and Host Performance:**
  - **⭐ High Review Rates:** Manhattan and Queens have higher average reviews per month.
  - **🏆 Top Hosts:** Successful hosts are primarily located in Manhattan and Brooklyn, suggesting the importance of location and guest satisfaction.

- **Pricing Insights:**
  - **💸 Higher Prices in Manhattan:** Manhattan listings command the highest prices, followed by Brooklyn.
  - **📉 Bronx Price Variability:** Pricing in the Bronx varies significantly, indicating the need for neighborhood-specific pricing strategies.

- **Temporal Trends:**
  - **📈 Increase in Reviews:** There has been a significant increase in reviews, particularly in 2019, reflecting growth in the Airbnb market.
