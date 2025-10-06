# Flipkart Laptop Market Analysis

## Project Overview
- This project focuses on analyzing the laptop market using data scraped from Flipkart.
- **Objective:** Understand market trends, brand preferences, pricing strategies, and laptop specifications.
- The dataset is cleaned, structured, and visualized using Python and Power BI.

## Repository Structure
laptop-market-analysis/
│── data/ # Sample cleaned dataset (CSV)
│── notebooks/ # Jupyter notebooks for scraping & cleaning
│── reports/ # Power BI dashboards & exports
│── README.md # Project documentation
│── web_scrapping.md # Web scraping overview

## Data Description
- Laptop specifications:
  - Brand & Model
  - Processor Brand & Generation
  - RAM & Storage
  - Operating System & Platform
  - Display Size & Type
- Pricing and discount information:
  - Original Price
  - Discounted Price
  - Discount Percentage
- Additional attributes:
  - Warranty
  - Ratings & Reviews
  - Availability

## Web Scraping
- Detailed scraping methodology is provided in [`web_scrapping.md`](web_scrapping.md).
- **Tools used:**
  - Python, BeautifulSoup, Requests, Pandas, Regex
- Dynamic pages handled, missing values filled, duplicates removed for a clean dataset.

## Analysis & Dashboard
- Data cleaning and preprocessing done in Jupyter notebooks.
- **Key Insights & Visualizations in Power BI:**
  - Brand-wise price distribution
  - RAM vs Price analysis
  - Storage type vs Price trends
  - Discount patterns across brands
- Interactive dashboards with slicers and drill-through pages.

## Key Learnings
- Understanding market trends and popular laptop configurations.
- Price and discount analysis to identify competitive strategies.
- Hands-on experience with web scraping, data cleaning, and visualization.

## Tools & Technologies
- Python (BeautifulSoup, Requests, Pandas)
- Power BI (Visualizations, Dashboards)
- Git & GitHub for version control
- Jupyter Notebook for data cleaning and exploration

## GitHub Repository
- Full project available at: [Flipkart Laptop Analysis](https://github.com/Jaideep0710/flipkart-laptop-analysis.git)

## How to Use
1. Clone the repository:  
   `git clone https://github.com/Jaideep0710/flipkart-laptop-analysis.git`
2. Explore notebooks in `notebooks/` for scraping and cleaning steps.
3. View dashboards and reports in `reports/`.
4. Use `data/` folder for the cleaned CSV dataset ready for analysis.

## License
- This project is for educational purposes.
