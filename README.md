# Spotify User Churn Analysis & Interactive Dashboard

An exploratory data analysis project to identify key behavioral drivers of customer churn on Spotify, featuring a Python-based data processing workflow and an interactive Power BI dashboard.

---

##  dashboards

![Screenshot of the Spotify Dashboard](Spotify Churn Dasboard.png)

---

## 🎯 Project Description & Goal

The primary challenge for subscription-based services like Spotify is customer retention. This project aims to perform an exploratory data analysis (EDA) to identify the main behavioral factors that correlate with customer churn (users who cancel their subscription). The goal is to provide data-driven insights that can be used to design more effective customer retention strategies.

---

## 🛠️ Workflow

1.  **Data Cleaning & Transformation (Python):** The raw data from `spotify_churn_dataset.csv` was cleaned and processed using the Pandas library in Python. This process included removing irrelevant data, renaming columns for clarity, and creating new, more insightful categories (e.g., grouping subscription types into "Free vs. Paid").
2.  **Visualization & Dashboard (Power BI):** The cleaned data was then exported to a new CSV file and imported into Power BI. An interactive dashboard was built to visualize the key findings, featuring slicers for dynamic data exploration.

---

## 💡 Key Insights

* **Overall Churn Rate:** Approximately **25.9%** of the users in this dataset churned.
* **Free Users Are Most at Risk:** Users with a "Free" subscription plan show a proportionally much higher churn rate compared to paid users.
* **Behavior is Key:** Churned users tend to have a **lower average listening time** and a **higher average skip rate**, indicating lower engagement and satisfaction levels.

---

## 🔧 Tools Used

* **Python:** For data cleaning and transformation.
    * *Libraries:* Pandas, Matplotlib, Seaborn, Scikit-learn
* **Power BI:** For creating the interactive dashboard.
    * *Language:* DAX (for creating measures like Churn Rate)

---

## 🚀 How to Run

1.  **View the Dashboard:** The main dashboard screenshot is included above.
2.  **Explore the Power BI File:** Download the `Dashboard Spotify.pbix` file and open it with Power BI Desktop to interact with the full dashboard.
3.  **Run the Python Code:** Open the `analisis_spotify.ipynb` file using Jupyter Notebook to review the data cleaning and analysis process.
