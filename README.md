# Amsterdam Airbnb Data Analysis

## Overview 
This is a Data Analysis Project focused on Airbnb accommodations in Amsterdam.
The goal of the project is to explore and analyze the Airbnb market in Amsterdam to understand pricing patterns, popular neighborhoods, seasonal trends, and accommodation types.

## Data
The datasets include: 
- **Listings data** — information about hosts, property types, locations, capacities, and prices.
- **Calendar data** — availability and prices for each listing over the next 1.5 years.
- **Reviews data** — textual reviews written by guests.

These datasets can be found on [Inside Airbnb website](https://insideairbnb.com/get-the-data/).

## Project Objectives
In this project I performed a descriptive and exploratory data analysis to answer the following questions: 
- Which neighborhoods are the most popular among tourists?
- What factors influence the price of accommodations?
- Which property types have the highest and lowest occupancy rates?
- What are the seasonal trends in occupancy?

The conclusions can be used for 
- Airbnb business - for insights in further development  
- City tourism development - to understand the distribution of tourist demand in Amsterdam
- Airbnb hosts - to pricing planning and increased occupancy
- Tourists - to plan trips based on seasonality and prices

## Technologies 
Python Packages used:
- Pandas - data manipulation 
- Seaborn & Matplotlib - data visualization 
- Plotly - interactiv charts and maps 

## Analysis
The analysis included the following steps:
1. **Data Cleaning and Preparation**
- Removed irrelevant columns
- Handled inconsistent data formats
- Converted data types for correct analysis
2. **Descriptive Statistics**
- Calculated average, median, and distribution for price, occupancy rate, and other metrics
- Compared statistics across neighborhoods and property types
3. **Exploratory Data Analysis (EDA)**
- Visualized geographical distribution of listings
- Compared prices across neighborhoods and room types
- Analyzed occupancy rates by property type and location
- Examined seasonal patterns and travel trends by month and years 
4. **Visualization**
- Created bar plots, box plots, heatmaps, and geographical maps with Seaborn, Matplotlib, and Plotly

## Conclusion
- Most of the listings are clustered in Oud-West neighbourhood.
- The next two most popular neighbourhoods of listings are De Pijp and Centrum-West.
- Average price of all Amsterdam accommodations is 223€.
- De Pijp (250€), Zuid (249,5€) and Centrum-West (245€) are the most expensive neighbourhoods.
- The most of listing are entire units.
- The three most expensive property types are huts, entire condos and entire guesthouses.
- The most listing are for two or three people which means that people travel to Amsterdam in couples or families.
- Prices are based on neighbourhoods, capacity and room types.
- There is the trend towards an increase of travel and short-term rent.
- December to February are the quietest months
- May, April, August, July are the most popular months for travelling in Amsterdam.
- The occupancy rate is high — 77% which indicates high demand and popularity among tourists and/or a potential shortage of available accommodations on the market
- The greatest demand is concentrated in the areas adjacent to the city center.
