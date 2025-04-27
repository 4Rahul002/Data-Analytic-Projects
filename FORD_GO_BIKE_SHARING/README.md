# **🚴‍♂️ Ford GoBike Trip Data Analysis (January 2018)**

Welcome to my exploratory data analysis (EDA) project on the Ford GoBike System Data.
This project involves cleaning, visualizing, and drawing insights from real-world bike-sharing trip data from San Francisco Bay Area.

## **Project Objective**

Understand bike usage patterns by subscribers and customers.

Analyze trip durations across hours, days, and seasons.

Identify demographic trends among riders.

Provide operational insights for better fleet and station management.

## **🧹 Data Cleaning**
Converted start_time and end_time to datetime format.

Created new features like hour, day, month, season, and age.

Removed unrealistic trip durations (outliers) using IQR method.

Handled missing values by dropping or imputing appropriately.

📊 Exploratory Data Analysis (EDA)
➡️ Univariate Analysis
Trip duration distribution

Hourly and daily ride counts

User type and gender distributions

Age distribution

➡️ Bivariate Analysis
Trip duration by user type

Gender vs Trip Count

Hourly usage across user types

Trip duration vs Rider's Age

Seasonal impact on trip duration

➡️ Multivariate Analysis
Heatmap of trips across day and hour

Age vs Trip Duration colored by Gender

Hourly Trip Duration across User Types

➡️ Correlation and Relationships
Correlation heatmap of numerical variables

Pairplot of important trip features colored by user type

## **📋 Key Findings**
Average trip duration is around 14.5 minutes.

Subscribers use bikes mainly for commuting (peak in mornings and evenings).

Customers take longer trips, likely for leisure.

Males dominate the ridership population.

Most active age group: 25-40 years old.

Data available is only for January (Winter), so seasonal trends are limited.

🛠 Technologies Used
Python 3

Pandas

NumPy

Matplotlib

Seaborn

🙌 Acknowledgments
Ford GoBike (Now known as Bay Wheels) for the publicly shared trip data.

Inspiration from Udacity Data Analyst Nanodegree projects.

📜 License
This project is licensed under the MIT License.
Feel free to use, share, or improve with credits! 🚀

✍️ Author
Name: Rahul

GitHub: 4Rahul002
