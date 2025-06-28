# 🚀 Applied Data Science Capstone Project

## 📊 Project Overview

Welcome to the *Applied Data Science Capstone* repository! This project is the final capstone of the IBM Data Science Professional Certificate. It focuses on building a real-world, end-to-end data science solution using Python, data visualization, APIs, web scraping, and machine learning.

The core goal of this capstone is to *predict the successful landing of the Falcon 9 first stage, a critical step in making space launches reusable and cost-effective. SpaceX advertises Falcon 9 rocket launches at a cost of **$62 million, significantly undercutting competitors who charge **$165 million or more* per launch. Accurate prediction of landing success helps optimize costs, operations, and decision-making in commercial spaceflight.

---

## 🧪 Labs and Components

This repository covers several labs and projects which build toward the final solution:

### ✅ 1. Data Collection - API Lab
- Fetched rocket launch data using SpaceX REST APIs.
- Parsed and stored launch data in structured format.

### ✅ 2. Data Collection - Web Scraping Lab
- Collected Falcon 9 launch information from SpaceX’s website using BeautifulSoup.
- Combined scraped data with API data for more comprehensive insights.

### ✅ 3. Data Wrangling
- Cleaned, merged, and transformed data using pandas.
- Dealt with missing values, formatted columns, and removed redundancies.

### ✅ 4. Exploratory Data Analysis (EDA) with SQL
- Queried launch data using SQL via ipython-sql.
- Performed filtering, grouping, and aggregations to derive initial insights.

### ✅ 5. EDA with Visualization Lab
- Created bar charts, pie charts, and histograms using matplotlib and seaborn.
- Analyzed correlations between payload mass, orbit type, and success rates.

### ✅ 6. Interactive Visual Analytics with Folium Lab
- Mapped launch sites on an interactive map using folium.
- Visualized geographic distribution of launches and landing outcomes.

### ✅ 7. Machine Learning Prediction Lab
- Trained multiple models to predict the outcome of Falcon 9 landings.
- Algorithms used: Logistic Regression, Decision Trees, Support Vector Machines (SVM), and k-Nearest Neighbors (KNN).
- Evaluated models based on *accuracy, **precision, **recall, **F1 score, and **ROC-AUC*.
- *Plotted a Confusion Matrix* to visually assess true positives, true negatives, false positives, and false negatives for model performance.

### ✅ 8. Interactive Dashboard with Plotly Dash
- Built an interactive dashboard using Plotly Dash.
- Integrated visualizations, dropdowns, and interactivity to explore:
  - Launch success by site
  - Correlation between payload and success
  - Orbit type vs success

---

│ ├── web_scraping_lab.ipynb
│ ├── data_wrangling.ipynb
│ ├── eda_sql.ipynb
│ ├── eda_visualization.ipynb
│ ├── folium_visual_analytics.ipynb
│ └── machine_learning_prediction.ipynb
└── README.md
