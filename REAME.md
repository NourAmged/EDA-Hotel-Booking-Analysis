# Hotel Booking Analysis - Exploratory Data Analysis (EDA)

## Overview
This project analyzes hotel booking data to uncover trends, patterns, and actionable insights for reducing cancellation rates and improving hotel revenue. The analysis focuses on two types of hotels: City Hotel and Resort Hotel, both of which have experienced increased cancellations in recent years.

## Dataset
- **File:** `hotel_bookings.csv`
- **Description:** Contains booking information for a city hotel and a resort hotel, including details such as booking dates, customer type, lead time, cancellation status, and more.

## Objectives
- Explore and clean the hotel booking dataset.
- Identify key factors influencing booking cancellations.
- Visualize booking and cancellation trends.
- Provide recommendations to reduce cancellations and improve revenue.

## Notebooks
- **`final-analysis.ipynb`**: Main notebook containing all data loading, cleaning, analysis, visualizations, and conclusions.

## Key Steps in the Analysis
1. **Import Libraries**: Load essential Python libraries for data analysis and visualization.
2. **Data Loading**: Read the dataset and inspect its structure.
3. **Data Cleaning**: Handle missing values, remove duplicates, and filter outliers.
4. **Exploratory Data Analysis (EDA)**: Analyze booking and cancellation patterns by month, hotel type, customer type, and other features.
5. **Visualization**: Use plots to illustrate trends and findings.
6. **Conclusions & Recommendations**: Summarize insights and suggest strategies for reducing cancellations.

## How to Run
1. Open `final-analysis.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell sequentially to reproduce the analysis and visualizations.
3. Ensure all required Python packages are installed:
   - pandas
   - matplotlib
   - seaborn

## Results & Insights
- August has the highest number of bookings and cancellations.
- City hotels experience more cancellations, likely due to business travelers' unpredictable schedules.
- Resort hotels have longer lead times and lower cancellation rates.
- Transient customers are more likely to cancel than contract or group customers.

## Recommendations
- Implement stricter or tiered cancellation policies, especially for city hotels.
- Offer incentives for early and longer bookings.
- Provide flexible options for business travelers.
- Target marketing and promotions based on customer type and booking patterns.


