
#  Netflix Movies and TV Shows - Exploratory Data Analysis (EDA)

##  Project Overview
This project performs an in-depth exploratory data analysis (EDA) on the Netflix Movies and TV Shows dataset. The goal is to uncover insights about content types, regional distribution, genre popularity, rating trends, and time-based content growth using univariate, bivariate, and multivariate visualizations.

##  Dataset
- **Source**: [Netflix Movies and TV Shows Dataset] (https://drive.google.com/file/d/1xJGllnE12mAggLuRo8b0oNSshUlG8GvF/view)
- **Size**: ~7,700 records
- **Features**: Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genres, Description

##  Problem Statement
To analyze Netflix content data to uncover trends and insights about content type, popularity by region, genre distribution, and user engagement patterns based on ratings and release years.

##  Business Objective
To help Netflix make data-driven decisions for:
- Content acquisition
- Regional expansion
- Genre investment
- User-targeted recommendations

---

##  Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Data Preprocessing
- Handled missing values in `director`, `cast`, and `country`
- Converted `date_added` to datetime format
- Extracted `year_added` and `month_added`
- Converted `duration` to numeric format for movies

---

##  EDA Highlights

###  Univariate Analysis
- ~70% content are **Movies**
- **USA**, **India**, and **UK** are top content-producing countries
- Most content falls under **TV-MA** and **TV-14** ratings

###  Bivariate Analysis
- **TV Shows** dominate teen-friendly ratings (TV-14)
- **India** favors Movies; **USA** has balanced content types

###  Multivariate Analysis
- Increasing content additions from **2015 to 2020**
- **Drama** and **Comedy** are top genres across both types
- Genre preferences vary by rating and type

---

## Sample Visualizations
- Pie chart for Movies vs TV Shows
- Bar chart for top countries
- Line plot for content growth over time
- Heatmaps for missing values
- Multivariate charts for Genre vs Rating vs Type

---

## Insights & Recommendations
- Netflix should:
  - Expand region-specific content (e.g., India, UK)
  - Focus more on TV Shows for younger demographics
  - Invest in top-performing genres like Drama, Comedy, and Action

### Negative Insight
- Excessive focus on a few genres or youth-centric ratings may neglect niche audiences and limit diversification.

---

##  Final Conclusion
The EDA provides actionable insights into Netflix’s content trends and user preferences. These findings can support strategic decisions for content creation, licensing, and audience targeting.

