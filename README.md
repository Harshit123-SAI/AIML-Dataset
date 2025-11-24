zomato_data-set 🍽 Zomato Data Analysis and Feature Engineering by Murli Rathi

📘 Project Overview This project performs Exploratory Data Analysis (EDA) and Feature Engineering on the Zomato dataset to uncover insights about restaurants across various countries. It focuses on cleaning, analyzing, and transforming raw data into a structured format suitable for further modeling or visualization.

The main notebook 1-eda-feature-engineering.ipynb includes:

Data cleaning and preprocessing Handling missing and duplicate values Merging datasets Feature extraction and encoding Exploratory visualizations and insights 📂 Files in This Repository File Name Description 1-eda-feature-engineering.ipynb Jupyter Notebook containing all steps of EDA and feature engineering. zomato.csv Main dataset containing restaurant information such as name, location, cuisine, and ratings. Country-Code.xlsx Reference file mapping Country Code to country names for merging with the main dataset. 🧩 Key Objectives Data Cleaning

Handle null values and inconsistent data. Remove duplicates and irrelevant columns. Data Merging

Combine zomato.csv with Country-Code.xlsx to include country names. Feature Engineering

Extract and encode relevant features (e.g., cuisines, price range, rating). Convert categorical data into numerical form. Exploratory Data Analysis (EDA)

Visualize relationships between cuisines, ratings, and locations. Identify top cuisines, popular cities, and restaurant trends. 🧠 Insights You Can Expect Top countries and cities with the most restaurants Most popular cuisines globally and regionally Correlation between restaurant ratings, price range, and location Trends in online delivery and dine-in preferences 🛠 Tech Stack Python 3.x Jupyter Notebook Libraries Used: pandas numpy matplotlib seaborn plotly (optional, for interactive visualization) openpyxl (for Excel data import) 🚀 How to Run the Project Clone or download this repository. Install dependencies: pip install pandas numpy matplotlib seaborn plotly openpyxl
