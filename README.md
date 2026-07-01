# Flight-Price-Prediction---EDA-Feature-Engineering
This project focuses on Exploratory Data Analysis (EDA) and Feature Engineering on a Flight Price Prediction dataset. The goal is to clean, transform, and prepare the data for building a machine learning model that can predict flight ticket prices.
## Objectives
* Explore and understand the dataset structure.
* Perform data cleaning and preprocessing.
* Engineer features from date and time columns.
* Handle categorical variables using encoding techniques.
* Visualize data distributions and relationships using Seaborn and Matplotlib.
* Prepare the dataset for predictive modeling.
---
## Dataset Features
The dataset contains information related to flight bookings, including:
* Airline
* Date of Journey
* Source
* Destination
* Route
* Departure Time
* Arrival Time
* Duration
* Total Stops
* Additional Information
* Price (Target Variable)
---
## Exploratory Data Analysis
The following EDA tasks were performed:
* Loaded and explored the dataset.
* Examined data types and summary statistics.
* Identified and handled missing values.
* Analyzed categorical and numerical features.
* Visualized feature distributions and relationships using:
  * Distribution Plots
  * Count Plots
  * Box Plots
  * Correlation Heatmap
## Feature Engineering

The following transformations were applied:

* Extracted **Date**, **Month**, and **Year** from `Date_of_Journey`.
* Extracted **Arrival Hour** and **Arrival Minute** from `Arrival_Time`.
* Extracted **Departure Hour** and **Departure Minute** from `Dep_Time`.
* Converted extracted features into appropriate numeric data types.
* Removed redundant columns after feature extraction.
* Encoded the `Total_Stops` column into numerical values.
* Applied **One-Hot Encoding** to:

  * Airline
  * Source
  * Destination

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```text
Flight-Price-Prediction-EDA/
│
├── Flight_Price_EDA.ipynb
├── flight_price.xlsx
├── README.md
└── requirements.txt
```

---

## Key Learning Outcomes

* Data preprocessing and cleaning
* Feature engineering techniques
* Handling missing values
* Categorical feature encoding
* Exploratory data analysis
* Data visualization using Seaborn and Matplotlib

---

## Conclusion

This project demonstrates a complete workflow for exploratory data analysis and feature engineering on a real-world flight pricing dataset. The dataset has been cleaned, transformed, and analyzed to generate meaningful insights while preparing it for future machine learning applications.
