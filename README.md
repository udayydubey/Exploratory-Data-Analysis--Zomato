# Zomato Restaurant — Exploratory Data Analysis (EDA)

An end-to-end **Exploratory Data Analysis project on the Zomato restaurant dataset**, built with Python, Pandas, Matplotlib and Seaborn.

The project follows a practical analyst workflow: understanding the data, checking data quality, exploring distributions and relationships, identifying patterns/outliers, and converting findings into business insights.

## Project Overview

The dataset contains **9,551 restaurants** across multiple countries and includes information about:

- Restaurant and location details
- Cuisines
- Average cost for two
- Price range
- Aggregate rating and rating category
- Votes
- Online delivery
- Table booking
- Geographic coordinates

### Key Business Questions

- Which cities and cuisines have the highest-rated restaurants?
- What is the relationship between cost, ratings and votes?
- Which price range provides better ratings?
- Does online delivery relate to restaurant ratings?
- Does table booking relate to ratings?
- Where are the outliers and missing values?
- What actionable insights can be derived for a food-tech business?

## EDA Workflow

The notebook follows a complete EDA pipeline:

1. **Introduction to EDA**
2. **Dataset Setup & Loading**
3. **Understanding the Dataset**
4. **Data Quality Assessment**
5. **Univariate Analysis**
6. **Bivariate Analysis**
7. **Multivariate Analysis**
8. **Outlier & Missing Value Analysis**
9. **Feature Relationships & Pattern Discovery**
10. **Business Insights & Conclusions**
11. **End-to-End EDA Summary**
12. **Practice Questions**

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation & cleaning |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter / Google Colab | Notebook environment |

## Key Findings

### Ratings Gap
**22.49%** of restaurants are classified as **Not Rated**, highlighting a large opportunity to increase customer review participation.

### Online Delivery
Only **25.66%** of restaurants offer online delivery.

The notebook finds an average rating of **3.25** for restaurants with online delivery versus **2.47** for restaurants without it.

### Table Booking
Only **12.12%** of restaurants offer table booking.

Restaurants with table booking have an average rating of **3.44**, compared with **2.56** for restaurants without it.

### Price vs Rating
Price Range 4 has an average rating of **3.89**, while Price Range 1 has an average rating of **3.24**.

However, the correlation between cost and rating is only **0.08**, indicating that higher cost alone is not a strong predictor of rating.

### Votes vs Rating
The correlation between votes and rating is **0.41**, suggesting a moderate positive relationship between engagement and restaurant ratings.

### Top-Rated Cuisines
Among cuisines with at least 20 restaurants:

- Italian — **3.95**
- American — **3.92**
- Mexican — **3.85**

North Indian is the most common cuisine with **936 restaurants** in the dataset.

### City Concentration
**New Delhi, Gurgaon and Noida** together account for more than **77%** of the restaurants in the dataset, showing a strong concentration of the dataset around these markets.

## Visualizations

The notebook includes visual analysis such as:

- Rating category distribution
- Average rating by price range
- Top cities by restaurant count
- Distribution plots
- Box plots
- KDE plots
- Scatter plots
- Correlation analysis
- Multivariate comparisons
- Outlier analysis
- Feature relationship analysis

## Data Quality & Cleaning

The project checks and handles:

- Missing values
- Duplicate records
- Data types
- Categorical variables
- Outliers using statistical methods
- Feature transformations
- Binary encoding of selected Yes/No fields
- Creation of an **Is Rated** feature

The final cleaned dataset contains **9,551 rows and 22 columns**.

## Repository Structure

```
Exploratory-Data-Analysis--Zomato/
│
├── Zomato_EDA_Analysis.ipynb
├── zomato.csv
└── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/udayydubey/Exploratory-Data-Analysis--Zomato.git
cd Exploratory-Data-Analysis--Zomato
```

### 2. Install dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook Zomato_EDA_Analysis.ipynb
```

You can also open the notebook directly in **Google Colab**.

## Business Takeaways

The analysis suggests several areas that a food-tech platform could investigate further:

- Increase customer rating participation.
- Expand online delivery adoption.
- Promote table booking where relevant.
- Focus on service and quality rather than price alone.
- Help newer restaurants build early review volume.
- Explore less concentrated markets beyond the dominant cities.
- For India-specific cost analysis, filter the multi-country dataset to Indian Rupees.

> **Note:** These findings are exploratory relationships from the dataset and should not automatically be interpreted as causal effects.

## Practice Questions

The notebook also includes exercises covering:

- Filtering and aggregation
- Cuisine analysis
- City-level analysis
- Percentage calculations
- Price-range comparisons
- IQR-based outlier detection
- Pivot tables
- Writing reusable Python EDA functions

## Author

**Uday Dubey**

Aspiring Data Analyst | BBA Student

---

If you found this project useful, feel free to explore the notebook and connect with me on LinkedIn.
