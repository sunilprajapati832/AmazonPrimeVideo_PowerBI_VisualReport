# Amazon Prime Video Data Analysis Power BI Dashboard Project

## Project Overview
This project aims to explore and analyze Amazon Prime user data to uncover insights about user engagement, subscription patterns, genre preferences and customer satisfaction. The dataset provides a comprehensive view of user demographics, behavior and subscription details, enabling effective business insights and visualization using Power BI.

## Dataset Details
* Dataset Name: amazon_prime_cleaned.csv
* Total Columns: 22
* The dataset contains the following user attributes:

| **S.No.** | **Column Name** | **Description** |
|------------|----------------|-----------------|
| 1 | `user_id` | Unique identifier for each user. |
| 2 | `name` | Full name of the customer. |
| 3 | `email_address` | Registered email address for the account. |
| 4 | `username` | Username used to access the platform. |
| 5 | `date_of_birth` | Date of birth of the customer. |
| 6 | `gender` | Gender of the customer. |
| 7 | `location` | Geographic location or city of the customer. |
| 8 | `membership_start_date` | The date when the Prime membership began. |
| 9 | `membership_end_date` | The date when the Prime membership expired or is set to expire. |
| 10 | `subscription_plan` | Type of plan (e.g., Monthly, Annual, Trial). |
| 11 | `payment_information` | Payment method or status for the user. |
| 12 | `renewal_status` | Indicates if the membership was renewed or cancelled. |
| 13 | `usage_frequency` | Frequency of Prime Video usage (Daily, Weekly, Monthly). |
| 14 | `purchase_history` | Summary of purchases or transactions made. |
| 15 | `favorite_genres` | Genres most watched or liked by the user. |
| 16 | `devices_used` | Devices used to access Prime Video (TV, Mobile, Laptop, etc.). |
| 17 | `engagement_metrics` | Numeric engagement score or activity indicator. |
| 18 | `feedback_ratings` | Average customer feedback rating or satisfaction score. |
| 19 | `customer_support_interactions` | Count of customer service or support interactions. |
| 20 | `membership_duration_days` | Total number of days of active membership. |
| 21 | `membership_active` | Boolean flag indicating if membership is currently active. |
| 22 | `high_engagement` | Indicates high engagement customers (based on defined threshold). |

## Data Cleaning & Preparation
The dataset was cleaned and preprocessed using Python (Pandas, NumPy) and exported as a refined .csv file for Power BI visualization. Key cleaning steps included:
* Handling missing or null values
* Formatting date columns (DOB, membership dates)
* Standardizing categorical values (e.g., Gender, Subscription Plan)
* Removing duplicates and invalid user entries
* Deriving calculated fields such as:
   * membership_duration_days
   * membership_active
   * high_engagement

## Power BI Dashboard Overview
The Power BI dashboard offers an interactive visualization experience that helps explore user insights in a clear and business-focused manner.
* Key Metrics Displayed:
    * Total Users
    * Average Feedback Rating
    * Total Support Interactions
* Filters:
    * Devices Used: SmartTV | Smartphone | Tablet
* Graphs & Visualizations:
    * 🍩 Donut Chart: Favorite Genres Count (Drama, Action, Horror, Romance, Comedy, etc.)
    * 📈 Line Chart: Favorite Genres by Gender (Male vs Female)
    * 📊 Bar Chart: Users by Gender
    * 📉 Vertical Bar Chart: Renewal Subscription Trends (Increase, Decrease, Total)
    * 🥧 Pie Chart: Subscription Plans (Monthly, Annually)
    * 🌍 Google Map Visualization: Users by Country

## Purpose
This dashboard helps analyze:
* Genre popularity across demographics
* Renewal and retention trends
* Device-based user engagement
* Feedback distribution and support interaction frequency

## Tools & Technologies Used
- **Power BI Desktop** – Dashboard creation and DAX measures.  
- **Power Query** – Data cleaning and transformation.
- **IDE** - PyCharm (Python)  
- **Microsoft Excel / CSV** – Dataset source format.  
- **GitHub** – Version control and project hosting.  

## Project Files

| **File Name** | **Description** | **Download Link** |
|----------------|----------------|------------------|
| `AmazonPrimePowerBI_VisualReport.pbix` | Power BI dashboard report file | [Download Here](https://github.com/sunilprajapati832/AmazonPrimeVideosDashboard/blob/main/AmazonPrimePowerBI_VisualReport.pbix) |
| `amazon_prime_cleaned.csv` | Cleaned dataset used for visualization | [Download Dataset](https://github.com/sunilprajapati832/AmazonPrimeVideosDashboard/blob/main/amazon_prime_cleaned.csv) |
| Dashboard Images | Preview screenshots of dashboard visuals | Available in the `Images/` folder on repository |












## ✨ Project Highlights

- Demographic breakdown (gender, location, age)
- Subscription plan distribution (Annual, Monthly)
- User engagement metrics and feedback ratings
- Devices used and content preferences
- Membership lifecycle and renewal status
- Customer support interaction summary
- Purchase history analysis






## 📈 Power BI Dashboard

I created a comprehensive Power BI dashboard to visualize key trends and insights based on the above data.

👉 https://github.com/sunilprajapati832/AmazonPrimeVideo_PowerBI_VisualReport/blob/main/AmazonPrimePowerBI_VisualReport.pbix

## 🔍 EDA Questions Solved

This dashboard is based on solving the following questions from the original project:

1. Retrieve the names and email addresses of all users  
2. Find the number of users by gender  
3. Get the usernames and membership start dates of users who joined before a certain date  
4. Count the number of users from a specific location (e.g. Port...)  
5. Subscription plans and their user count  
6. Usernames with payment info  
7. Renewal status of subscriptions  
8. Average usage frequency  
9. Users with specific purchase history  
10. Favorite genres of users and their count  

---



