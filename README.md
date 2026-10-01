# Zomato Data Analysis & Preprocessing  

## 📌 Project Overview

This project is based on the Zomato restaurant dataset obtained from Kaggle.

The project focuses on data cleaning, preprocessing, manipulation, and basic visualization using Python and Pandas. Various operations were performed to clean the dataset, handle missing and duplicate values, standardize columns, and prepare the data for analysis.

## 📂 Dataset

The dataset used in this project is:

`zomato.csv`

The dataset contains information about restaurants, including restaurant name, location, online ordering, table booking, rating, votes, restaurant type, cuisines, approximate cost, and other related attributes.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Data Cleaning & Preprocessing

The following operations were performed on the Zomato dataset:

- Loaded the CSV dataset using Pandas
- Explored the dataset using `df.info()`
- Checked the shape and structure of the dataset
- Examined unique values in the `rate` column
- Removed `/5` from the `rate` column and converted the values into a suitable format
- Removed unnecessary columns from the dataset
- Handled and removed null/missing values
- Checked the dataset shape after cleaning
- Examined the `listed_in(city)` column
- Removed `listed_in(city)` as it provided similar information to another location-related column
- Removed commas from the cost column to make the values suitable for numerical operations
- Renamed columns for better readability and consistency
- Cleaned and standardized the `rest_type` column
- Grouped restaurant types with fewer than 1000 occurrences into an `Others` category
- Checked the cleaned dataset using Pandas

## 📊 Data Visualization

Basic visualizations were created using Matplotlib and Seaborn.

A count plot was used to visualize the distribution of restaurants across different locations.

## 🎯 Objective

The main objective of this project was to understand and practice real-world data cleaning and preprocessing techniques using Python and Pandas.

The project demonstrates how raw restaurant data can be cleaned, organized, transformed, and prepared for further analysis.

## 📁 Project Files

- `zomato.csv` – Original Zomato dataset obtained from Kaggle
- `zomato.ipynb` – Jupyter Notebook containing the complete Python code, data cleaning operations, preprocessing, and visualizations
- `README.md` – Project documentation

## 👩‍💻 Author

**Radhika Singh**
