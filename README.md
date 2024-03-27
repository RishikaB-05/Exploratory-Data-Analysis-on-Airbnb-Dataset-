# Exploratory-Data-Analysis-on-Airbnb-Dataset-
![image](https://github.com/RishikaB-05/Exploratory-Data-Analysis-on-Airbnb-Dataset-/assets/157221360/50e56131-5ce4-4ab0-b437-25a681ea1fec)

# About Airbnb -
Airbnb, Inc., based in San Francisco, California, operates an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.
# Business Context
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb has become one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data — data that can be analyzed and used for security, business decisions, understanding of customers’ and providers’ (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services, and much more.
This dataset has around 49,000 observations in it with 16 columns and it is a mix of categorical and numeric values. Let’s Explore and analyze the data to discover key understandings.
# Project Architecture
![image](https://github.com/RishikaB-05/Exploratory-Data-Analysis-on-Airbnb-Dataset-/assets/157221360/fafdbc56-cff1-4647-99d4-c9fb22af6b95)

# Step -1: Basic Dataset Understanding -
This dataset has around 48,895 observations with 16 columns and it is a mix between categorical and numeric values.
The info( ) method prints information about the data frame.
The information contains the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).
By basic inspection, a particular property name will have one particular hostname hosted by that same individual but a particular hostname can have multiple properties in an area. So, host_name is a categorical variable here. Also neighbourhood_group (comprising of Manhattan, Brooklyn, Queens, Bronx, Staten Island), neighborhood, and room_type (private, shared, Entire home/apt) fall into this category.
The describe( ) method returns a description of the data in the DataFrame. If the DataFrame contains numerical data, the description contains this information for each column :
 count — The number of not-empty values.
 mean — The average (mean) value. 
 std — The standard deviation.
 Cleaning the Null Values -
Either we can drop the null values or we can fill it as per the requirement I’m going to drop the ‘ID’ column as it’s not needed for this project and fill the rest of the columns column ‘name’, ‘host_name’, ‘last_review’, ‘reviews_per_month
# Step 2: Asking Questions.
1. What are the most popular neighborhoods for Airbnb rentals in New York City? How do prices and availability vary by neighborhood?
2. How has the Airbnb market in New York City changed over time? Have there been any significant trends in terms of the number of listings, prices, or occupancy rates?
3. Are there any patterns or trends in terms of the types of properties that are being rented out on Airbnb in New York City? Are certain types of properties more popular or more expensive than others?
4. Are there any factors that seem to be correlated with the prices of Airbnb rentals in New York City?
5. the best area in New York City for a host to buy property at a good price rate and in an area with high traffic ?
6. How do the lengths of stay for Airbnb rentals in New York City vary by neighborhood? Do certain neighborhoods tend to attract longer or shorter stays?
7. How do the ratings of Airbnb rentals in New York City compare to their prices? Are higher-priced rentals more likely to have higher ratings?
8. Find the total number of Reviews and Maximum Reviews by Each Neighborhood Group.
9. Find the Most reviewed room type in Neighborhood groups per month.
10. Find the Best location listing/property location for travelers.
11. Find the best location listing/property location for Hosts.
12. Find Price variations in NYC Neighborhood groups.
# Conclusion :
Through this exploratory data analysis and visualization, we gained several interesting insights into the Airbnb rental market. This Airbnb dataset for the 2019 year appeared to be a very rich dataset with a variety of columns that allowed us to do deep data exploration on each significant column presented. We proceeded with Questions and Scenarios like which ‘neighbourhood_group’ has the highest number of Airbnb’s and what areas were more popular than another, their price variations, and their availability as per room types. Also, we emphasized on key findings which host has the highest bookings and reviews. Also, we emphasized on Which neighborhoods to stay in if I’m low on cash in that also how we can stay in luxury properties. Next, we made good use of latitude and longitude columns to create a geographical heatmap color-coded by the price of listings
I have used Seaborn, matplotlib, and Plotly Express to create all the visualizations. This is just a glimpse of EDA on the Airbnb dataset and there are no predictions involved.
