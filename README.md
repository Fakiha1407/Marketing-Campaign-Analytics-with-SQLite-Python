# Marketing-Campaign-Analytics-with-SQLite-Python
This project analyzes synthetic marketing campaign data using Python, SQLite, and data visualization libraries such as matplotlib and seaborn. It simulates how marketing teams can use campaign data to extract insights on customer engagement, revenue, and demographics.

## Project Highlights
Synthetic data generation using Faker

SQLite database creation and querying

SQL-based analysis of campaign performance

Visualizations for campaign insights

Exported results as PNG charts in an /images folder

## Dataset Description
The dataset is synthetically generated and contains the following features:
## Column	Description
customer_id	Unique identifier for each customer
age	Age of the customer
gender	Gender (Male/Female)
region	Region of the customer (North/South/etc.)
campaign_channel	Channel used (Email, SMS, etc.)
campaign_date	Date the campaign was sent
response	Whether the customer responded (Yes/No)
amount_spent	Amount spent if responded, else 0
## Technologies Used
Python 3
Pandas
SQLite3
Matplotlib
Seaborn
Faker

## Analysis Performed
📬Response Rate by Campaign Channel

Calculates response rate for each channel (Email, SMS, etc.)

💰 Revenue Share by Region

Sums revenue from responding customers per region

📅 Monthly Campaign Response Trend

Tracks number of sent and responded campaigns month-by-month

👥 Customer Demographics by Gender

Counts customers by gender

💵 Average Spending by Campaign Channel

Shows average spend per channel for responding customers

Customer Distribution by Region and Gender

Stacked bar chart of gender split across regions
## Visual Output
All charts are saved in the images folder:

response_by_channel.png

revenue_share_pie.png

monthly_trend.png

customer_demographics_by_gender.png

average_spending_by_channel.png

customer_count_by_region_and_gender.png
## Run
git clone https://github.com/Fakiha1407/Marketing-Campaign-Analytics-with-SQLite.git
