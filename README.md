# 📦 Project Overview

This repository contains a collection of notebooks, datasets, and visualization files focused on web scraping Amazon India’s top 30 best-selling products across multiple categories and performing data-driven analysis using Power BI to understand how customer reviews and ratings vary across categories.

The objective of this project is to analyze the relationship between product categories, total number of reviews, and average customer ratings, helping identify patterns in consumer behavior and market performance.

The project was implemented using Python (Jupyter Notebook) for data extraction and preprocessing, followed by Power BI for interactive dashboard creation.

# 🛠️ Project Structure

* Amazon_Best_Seller_Web_Scraping_Data.ipynb
Python notebook used to scrape Amazon India’s best-seller data using BeautifulSoup and ScraperAPI.

* AmazonBestSellers_{date}.csv
Raw dataset containing the scraped top 30 best-selling products across categories (data is dynamic and may vary over time).

* Amazon_Web_Scraping_Cleaned_Data.csv
Cleaned and transformed dataset created using Pandas, optimized for analysis and visualization.

* AMAZON BESTSELLER'S DASHBOARD.pbix
Power BI dashboard analyzing:

  * Category-wise distribution of products
  * Relationship between the number of reviews and the average rating
  * Category-level review engagement patterns


# ▶️ How to Run the Project

1. Clone or download this repository to your local machine.

1. Install VS Code from:
https://code.visualstudio.com/

1. Create an account on ScraperAPI and generate an API key:
https://dashboard.scraperapi.com/login

1. Replace the API key in the notebook with your own ScraperAPI key.

1. Launch Jupyter Notebook via VSCode.

1. Open and run Amazon Web Scraping.ipynb to scrape data.

1. The scraped data will be saved as AmazonBestSellers_{date}.csv.

1. Data cleaning and preprocessing will generate Amazon_Web_Scraping_Cleaned_Data.csv.

1. Open AMAZON BESTSELLER'S DASHBOARD.pbix in Power BI to explore the interactive dashboard.

⚠️ Note: Amazon best-seller data is highly dynamic and may differ each time the scraper is run.

# 📊 Results & Insights

1. The Power BI dashboard provides insights into:

1. How review volume varies across product categories

1. Correlation between average rating and number of reviews

1. Categories with high engagement but lower average ratings

1. Identification of categories where popularity does not necessarily imply higher customer satisfaction

These insights help understand consumer trust, engagement, and category-level performance trends on Amazon India.

# 🚀 Future Enhancements

1. Scrape additional product attributes (discounts, brands, delivery type)

1. Automate data collection using scheduled ETL pipelines

1. Perform time-series analysis on review growth

1. Apply sentiment analysis on customer reviews

1. Extend the dashboard with predictive insights
