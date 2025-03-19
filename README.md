# README

## Project Overview
This project analyzes the Airbnb rental market in New York City using the "Airbnb New York Listings" dataset. It focuses on spatial and price-related trends across different boroughs, summarizing key insights through data visualization and queries.

## Dataset
- Source: [Kaggle - Airbnb New York Listings](https://www.kaggle.com/datasets/an1005/airbnb-new-york-listings)
- Records: 36,058
- Key Attributes: 
  - `name`, `host_name`, `neighbourhood_group`, `neighbourhood`
  - `latitude`, `longitude`, `price`, `room_type`
  - `number_of_reviews`, `last_review`
  - Derived attribute: `price_category`

## Tasks
1. **Analyze - Discover**: Identify the neighbourhood_group with the highest average housing price in 2024.
2. **Query - Summarize**: Find the proportion of “Private room” listings priced between 0-200 USD in the highest-priced neighbourhood_group.
3. **Search - Locate**: Identify the top three hosts with the most listings that received more than 50 reviews in Q4 of 2024.
4. **Analyze & Query - Visualize**: Display the geographical distribution of listings for the top host from Task 3.

## Tools & Methods
- Data filtering and aggregation for price and reviews.
- Spatial analysis using latitude and longitude.
- Visualization techniques for geographic data distribution.

## Results
- Insights into price variations across boroughs.
- Summary statistics for affordable room options.
- Host activity trends and their spatial distribution.

This project enables better understanding of Airbnb market trends through structured queries and data visualization.