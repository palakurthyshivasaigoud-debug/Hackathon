 Food Delivery Data Integration & Analysis
Project Description

This project demonstrates an end-to-end data integration and analysis pipeline for a food delivery platform using multiple data formats. The objective is to combine transactional, user, and restaurant data into a single source of truth and perform meaningful analytical insights.

The project loads datasets from CSV, JSON, and SQL formats, merges them using LEFT JOIN operations, and generates a final consolidated dataset for analysis. All analytical queries are performed on the merged dataset to ensure data consistency and accuracy.

Datasets Used

orders.csv – Contains order-level transaction details

users.json – Stores user profile and membership information

restaurants.sql – Includes restaurant metadata such as cuisine type and ratings

Key Operations Performed

Loaded structured data from CSV, JSON, and SQL sources

Executed LEFT JOINs using:

user_id (orders ↔ users)

restaurant_id (orders ↔ restaurants)

Created final_food_delivery_dataset.csv as the unified dataset

Handled missing records gracefully using left joins

Converted date fields for time-based analysis

Analysis & Insights

The project answers key business questions, including:

Order volume and revenue analysis by membership type

City-wise revenue distribution

Average order value for Gold members

Impact of restaurant ratings on order frequency

Identification of top-performing cities and restaurants

Technologies Used

Python

Pandas (data manipulation)

SQLite (SQL execution)

JSON handling

Jupyter Notebook

Outcome

The final merged dataset acts as the single source of truth for all analytical queries. This project showcases practical skills in data engineering, data analysis, and multi-format data handling, making it suitable for hackathons, academic submissions, and portfolio projects.
