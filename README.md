# Zomato Restaurant EDA — Python, Pandas, Matplotlib & Seaborn

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistics-4c72b0?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

> An end-to-end Exploratory Data Analysis of **9,551 restaurants**, focused on data quality, restaurant characteristics, ratings, pricing, engagement, delivery, table booking, and business insights.

## Executive Summary

This project follows a practical analyst workflow:

**Understand → Clean → Explore → Compare → Visualize → Interpret**

The analysis combines statistical exploration and business-oriented questions to understand patterns in restaurant data.

## Dataset

The dataset contains **9,551 restaurant records** across multiple countries.

Key attributes include:

- Restaurant and location details
- Cuisines
- Average cost for two
- Price range
- Aggregate rating and rating category
- Votes
- Online delivery
- Table booking
- Geographic coordinates

## Business Questions

- Which cities and cuisines have the highest ratings?
- How are restaurants distributed across price ranges?
- What is the relationship between cost and rating?
- How are votes related to ratings?
- Do restaurants with online delivery show different average ratings?
- How do table-booking restaurants compare with others?
- Where are missing values and outliers concentrated?

## EDA Workflow

1. Dataset setup and loading
2. Dataset structure and data types
3. Data-quality assessment
4. Univariate analysis
5. Bivariate analysis
6. Multivariate analysis
7. Missing-value analysis
8. Outlier detection
9. Feature relationships
10. Business insights
11. End-to-end summary
12. Practice questions

## Key Findings

### Ratings

**22.49%** of restaurants are classified as **Not Rated** in the dataset.

### Online Delivery

**25.66%** of restaurants offer online delivery.

Average rating:
- With delivery: **3.25**
- Without delivery: **2.47**

This is an observed association in the dataset, not evidence that delivery causes higher ratings.

### Table Booking

**12.12%** of restaurants offer table booking.

Average rating:
- With table booking: **3.44**
- Without table booking: **2.56**

Again, this is an observed relationship rather than a causal conclusion.

### Price vs Rating

- Price Range 4 average rating: **3.89**
- Price Range 1 average rating: **3.24**
- Cost-rating correlation: **0.08**

The low correlation indicates that cost alone is not a strong linear predictor of rating in this dataset.

### Votes vs Rating

Correlation: **0.41**, indicating a moderate positive association between votes and ratings.

### Cuisine Analysis

Among cuisines with at least 20 restaurants, the analysis identifies:

- Italian — **3.95** average rating
- American — **3.92**
- Mexican — **3.85**

North Indian is the most common cuisine with **936 restaurants**.

### City Concentration

New Delhi, Gurgaon and Noida together represent more than **77%** of the restaurants in the dataset, showing strong geographic concentration.

## Data Quality & Cleaning

The project covers:

- Missing values
- Duplicate records
- Data types
- Categorical variables
- Outliers using statistical methods
- Feature transformations
- Binary encoding
- Creation of an `Is Rated` feature

The final cleaned dataset contains **9,551 rows and 22 columns**.

## Visualizations

The notebook includes:

- Rating distributions
- Price-range comparisons
- City distributions
- Box plots
- KDE plots
- Scatter plots
- Correlation analysis
- Multivariate comparisons
- Outlier analysis
- Feature-relationship visualizations

## Business Takeaways

The analysis highlights several areas a food-tech business could investigate:

- Increase review participation.
- Explore delivery adoption and customer experience.
- Study table-booking adoption.
- Analyze service quality alongside price.
- Help newer restaurants build review volume.
- Explore markets outside the most concentrated cities.

## Important Analytical Note

This is an **exploratory analysis**. Relationships observed in the dataset should not automatically be interpreted as causal effects. Results also depend on the dataset's coverage, definitions, and limitations.

## Project Structure

```text
Exploratory-Data-Analysis--Zomato/
├── README.md
├── Zomato_EDA_Analysis.ipynb
└── zomato.csv
```

## How to Run

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook Zomato_EDA_Analysis.ipynb
```

You can also open the notebook in Google Colab.

## Skills Demonstrated

**Python • Pandas • Matplotlib • Seaborn • Data Cleaning • EDA • Statistics • Data Visualization • Business Insight Generation**

---

### Author

**Uday Dubey**  
BBA Student | Aspiring Data Analyst

[GitHub](https://github.com/udayydubey)

⭐ If you found the project useful, feel free to star the repository.
