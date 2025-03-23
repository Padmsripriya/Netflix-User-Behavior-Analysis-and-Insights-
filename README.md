
# 📌 Project Overview
This project analyzes user data from Netflix to understand viewer preferences, engagement patterns, and demographics using Python (pandas, seaborn, matplotlib, etc.). Let's explore factors like subscription types, favorite genres, and user activity to derive meaningful insights.

# 📂 Dataset

This dataset contains 25,000 fictional Netflix user records generated for analysis, visualization, and machine learning practice. It includes demographic details, subscription type, watch time, and login history for each user.

**Columns:**

User_ID – Unique identifier for each user

Name – Randomly generated name

Age – Age of the user (13 to 80)

Country – User’s country (randomly chosen from 10 options)

Subscription_Type – Type of Netflix plan (Basic, Standard, Premium)

Watch_Time_Hours – Total hours watched in the last month

Favorite_Genre – User’s preferred genre

Last_Login – Last recorded login date within the past year

# 🔍 Analysis Performed
1. Loading and Exploring the Data
2. Data Cleaning and processing:

         a. Checked for missing values (No missing values found)
         b. Converted Last_Login to datetime format

4. User Engagement Analysis:
   
         a. Average watch-time of each subscription type
         b. Number of users watching each genre
         c. Oldest and youngest user age
         d. Number of inactive users since Dec 2024
         e. Number of inactive users since Dec 2024 in each subscription type
         f. Number of users from each country
         g. Average watch time per group (divided based on age)

# 📊 Visualizations
1. Bar Charts: User count by country & subscription type
2. Box Plot: Age distribution across favorite genres

# 🧐 Key Findings

1. The number of users is evenly distributed across the three subscription types: Premium (8,402 users), Basic (8,356 users), and Standard (8,242 users). This suggests that there is no significant preference for a particular plan, indicating a balanced adoption rate among users.
2. The median age for each genre is consistent, around the mid-40s, implying that no single genre is exclusively preferred by younger or older audiences. The age range (10 to 80 years) is wide across all genres, showcasing a broad and diverse audience.
