Restaurant Data Analysis in Indian Metropolitan Areas
Author: Sankalp Biswal
Date: 2023-11-15

Introduction
This project involves an extensive exploratory data analysis (EDA) of a dataset containing information on 900 restaurants across 13 metropolitan areas in India. The dataset consists of 127,657 observations and 12 attributes, including restaurant ratings, prices, votes, and cuisine types.

Dataset Overview
Source: Kaggle - Zomato Restaurants Dataset for Metropolitan Areas
Attributes:
Restaurant Name: Name of the restaurant.
Dining Rating: Customer ratings for the dining experience.
Delivery Rating: Customer ratings for the delivery service.
Dining Votes: Number of votes for the dining experience.
Delivery Votes: Number of votes for the delivery service.
Cuisine: Type of cuisine offered.
Place: Location of the restaurant.
City Name: Name of the metropolitan area where the restaurant is located.
Item Name: Name of specific dishes offered by the restaurant.
Best Seller: Indicates whether the item is a best-selling dish.
Votes: Number of votes for specific items.
Prices: Prices of items offered by the restaurant.
Project Structure
1. Data Import and Libraries
Utilized R programming language with libraries such as ggplot2, tidyverse, janitor, mice, and others.
Loaded the dataset from a CSV file.
2. Data Cleaning
Standardization: Cleaned and standardized variable names for consistency.
Missing Data Handling: Addressed missing values using Predictive Mean Matching (PMM) to impute missing ratings and votes.
3. Data Analysis and Visualization
Dining and Delivery Ratings: Explored the distribution of ratings using histograms.
Pricing Distribution: Analyzed the distribution of food prices through a histogram and examined the relationship between prices and average ratings using scatter plots.
Restaurant Distribution by City: Visualized the distribution of restaurants across different cities, identifying Hyderabad as the city with the most restaurants.
Top Restaurants: Identified the top 10 restaurants by count, with McDonald’s leading.
City-Specific Analysis: Focused on New Delhi, highlighting Laxmi Nagar as the area with the highest number of restaurants.
Cuisine Distribution: Categorized cuisines into broader categories (e.g., Indian, Asian, Western) and analyzed their distribution, with Western cuisine dominating the dataset.
4. Descriptive Statistics
Computed descriptive statistics for the numeric columns in the dataset, including mean, standard deviation, minimum, and maximum values.
Summary of Insights
Price and Rating Correlation: Higher prices do not necessarily correlate with higher ratings.
City Analysis: Hyderabad has the highest number of restaurants, followed by Jaipur and Mumbai.
Cuisine Dominance: Western cuisine is the most common, followed by Fast Food and Indian cuisines.
Top Restaurants: McDonald’s, Domino’s Pizza, and Burger King are the top three restaurants by the number of outlets.
Delhi Analysis: Laxmi Nagar has the highest number of restaurants in New Delhi.
Usage
Clone the Repository:
bash
Copy code
git clone <repository-url>
Install Required Libraries: Install the necessary R libraries by running the following command in your R environment:
R
Copy code
install.packages(c("ggplot2", "tidyverse", "janitor", "mice", "plotly", "kableExtra"))
Run the Analysis: Open the R script in your preferred R environment (RStudio, etc.) and run it step by step to replicate the analysis.
Conclusion
This project provided valuable insights into the restaurant landscape across Indian metropolitan areas, with a focus on ratings, pricing trends, and cuisine types. The visualizations and statistical analysis offer a clear picture of the dining preferences and trends in these regions.

License
This project is licensed under the MIT License - see the LICENSE file for details.
