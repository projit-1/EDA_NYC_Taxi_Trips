🚖 NYC Yellow Taxi Trips - Exploratory Data Analysis (EDA)

📌 Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the NYC Yellow Taxi Trips (January 2025) dataset using Python and Pandas. The objective is to understand trip patterns, passenger behavior, fare distributions, revenue trends, and data quality while demonstrating practical data analysis skills.
The dataset contains millions of taxi trip records, making it suitable for practicing real-world data analysis and preparing for freelance platforms such as Upwork.
📂 Dataset
•	File: yellow_tripdata_2025-01.parquet
•	Source: NYC Taxi & Limousine Commission (TLC)
•	Format: Apache Parquet
•	Records: Millions of taxi trips
•	Features: Pickup/Dropoff time, Trip distance, Fare amount, Tip amount, Passenger count, Payment type, Pickup and Dropoff locations, Total amount, and more.
🛠️ Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Missingno
•	Jupyter Notebook
📊 Project Objectives
•	Load and inspect a large real-world dataset.
•	Clean and prepare the data.
•	Handle missing values and duplicate records.
•	Engineer new features from datetime columns.
•	Analyze trip duration and travel distance.
•	Explore fare, tip, and revenue distributions.
•	Detect and investigate outliers.
•	Perform grouping and aggregation analyses.
•	Answer business-related analytical questions.
•	Visualize important trends and distributions.
📋 Exploratory Data Analysis Performed
1. Data Inspection
•	Dataset shape
•	Column names
•	Data types
•	Dataset information
•	Summary statistics
2. Data Cleaning
•	Missing value analysis
•	Duplicate detection
•	Memory usage analysis
•	Unique value inspection
3. Feature Engineering
Created new variables including:
•	Pickup Year
•	Pickup Month
•	Pickup Day
•	Pickup Hour
•	Pickup Weekday
•	Weekend Indicator
•	Trip Duration
•	Average Speed
•	Tip Percentage
4. Trip Analysis
•	Trip duration statistics
•	Trip distance distribution
•	Longest and shortest trips
•	Average travel speed
•	Peak travel hours
5. Fare Analysis
•	Fare distribution
•	Average fare
•	Maximum and minimum fare
•	Revenue analysis
•	Tip analysis
•	Total amount analysis
6. Outlier Detection
•	IQR-based outlier detection
•	Extreme fare values
•	Unrealistic trip distances
•	Negative or invalid records
7. GroupBy Analysis
Examples include:
•	Revenue by Vendor
•	Average Fare by Payment Type
•	Average Distance by Passenger Count
•	Hourly Revenue
•	Daily Revenue
•	Vendor Performance
•	Payment Method Comparison
8. Location Analysis
•	Most popular pickup locations
•	Most popular dropoff locations
•	Highest revenue pickup zones
9. Correlation Analysis
•	Correlation matrix
•	Relationship between numerical variables
10. Data Visualization
•	Histograms
•	Bar charts
•	Box plots
•	Correlation heatmap
•	Missing value visualization

📈 Business Questions Answered
This project answers several business-oriented questions, including:
•	Which hour has the highest number of taxi trips?
•	Which weekday generates the most revenue?
•	Which payment method provides the highest average tip?
•	Which vendor generates the highest revenue?
•	What is the average trip duration?
•	Which trips have the highest total fare?
•	Which locations are the busiest?
•	How does trip distance affect fare amount?
•	What percentage of trips occur during weekends?
•	Which trips have unusually high tips?
📁 Project Structure
NYC-Taxi-EDA/
│
├── yellow_tripdata_2025-01.parquet
├── EDA_NYC_Taxi_Trips.ipynb
├── README.md
└── requirements.txt

▶️ How to Run
Clone the repository
git clone https://github.com/projit-1/EDA_NYC_Taxi_Trips
Install dependencies
pip install pandas numpy matplotlib pyarrow missingno
Launch Jupyter Notebook
jupyter notebook
Open:
EDA_NYC_Taxi_Trips.ipynb

📦 Required Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import missingno as msno

📌 Key Skills Demonstrated
•	Data Cleaning
•	Exploratory Data Analysis (EDA)
•	Data Wrangling
•	Feature Engineering
•	GroupBy Operations
•	Statistical Analysis
•	Data Visualization
•	Outlier Detection
•	Business Intelligence
•	Pandas
•	NumPy
•	Matplotlib
•	Jupyter Notebook
📚 Learning Outcomes
Through this project, I strengthened practical experience in:
•	Working with large datasets
•	Cleaning real-world data
•	Performing advanced EDA
•	Creating meaningful business insights
•	Preparing datasets for machine learning
•	Writing clean, reproducible analysis in Python

🚀 Future Improvements
•	Interactive dashboards using Plotly
•	Geographic analysis with taxi zone maps
•	Predictive fare estimation models
•	Time series forecasting
•	Machine learning for trip duration prediction
👤 Author
Projit Mondol
Aspiring Data Analyst with experience in Python, SQL, Pandas, Excel, and Data Visualization.
⭐ Project Highlights
•	Real-world dataset containing millions of records
•	End-to-end exploratory data analysis workflow
•	Practical business insights

