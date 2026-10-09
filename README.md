# ✈️ Travel App Customer & Booking Analytics

## 📌 Project Overview

The **Travel App Customer & Booking Analytics** project analyzes travel app customer information, booking behavior, destinations, travel preferences, and booking performance using Python and Power BI.

The project uses **Pandas** for data cleaning and analysis, **Matplotlib** for data visualization, and **Microsoft Power BI** to build an interactive dashboard that presents key insights in an easy-to-understand format.

## 🎯 Project Objectives

- Understand customer demographics and travel preferences.
- Analyze bookings across destinations, cities, and travel types.
- Examine booking amounts, trip durations, and customer ratings.
- Compare completed, cancelled, and pending bookings.
- Explore customer loyalty and app usage.
- Identify popular destinations, packages, and transport modes.
- Present business insights through visualizations and an interactive Power BI dashboard.

## 🛠️ Technologies Used

- **Python** – Data analysis and processing
- **Pandas** – Data cleaning, manipulation, and statistical analysis
- **Matplotlib** – Data visualization
- **Microsoft Power BI** – Interactive dashboard development
- **Jupyter Notebook / VS Code** – Python development environment
- **CSV** – Dataset storage

## 📂 Project Structure

Travel-App-Customer-Booking-Analytics/
│
├── raw_travel_dataset.csv
├── cleaned_travel_dataset.csv
├── travel_analysis.py
├── Travel_App_Dashboard.pbix
└── README.md


## 📊 Project Workflow

### 1. Dataset Understanding
- Loaded the dataset using Pandas.
- Examined the first and last records.
- Checked dataset dimensions, column names, and data types.
- Generated descriptive statistics.
- Identified numerical and categorical columns.

### 2. Data Quality Checking and Cleaning
- Checked for missing values and duplicate records.
- Identified invalid numerical values and inconsistent text entries.
- Standardized city and destination names.
- Converted appropriate columns to numeric data types.
- Handled missing and invalid values where appropriate.
- Saved the cleaned dataset as a CSV file.

### 3. Exploratory Data Analysis (EDA)
Performed statistical and category-based analysis to understand:

- Customer demographics and city distribution.
- Popular travel destinations and packages.
- Booking amounts and trip durations.
- Customer and hotel ratings.
- Booking statuses and transport preferences.
- Loyalty membership and app usage.

### 4. Data Visualization
Created charts using Matplotlib:

- Bar charts for customer, destination, travel, package, booking status, transport, and payment analysis.
- Histograms for age, booking amount, and trip duration.
- Boxplots for booking amounts and customer ratings.
- Pie charts for travel type and booking status distributions.

### 5. Power BI Dashboard
Developed a Power BI dashboard to present travel app analytics visually.

The dashboard can be used to explore customer trends, destination performance, booking behavior, travel preferences, and other relevant metrics based on the available dataset.

The Power BI dashboard file (`.pbix`) is included in this repository so that users can download it and explore the report using Microsoft Power BI Desktop.

## 📈 Key Business Questions

This project investigates questions such as:

- Which destinations receive the most bookings?
- Which cities contribute the highest number of customers?
- Which travel and package types are most popular?
- What is the average booking amount and trip duration?
- How do customer ratings vary across destinations?
- What proportion of bookings are completed, cancelled, or pending?
- How do loyalty members compare with non-loyalty members?
- Which transport modes and payment methods are most commonly used?

## ⚙️ Installation and Usage

### Prerequisites

Install Python and the required libraries.

```bash
pip install pandas matplotlib
```

### Run the Python Analysis

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Ensure the cleaned CSV file is in the same folder as the Python script.
4. Run the analysis script:

```bash
python travel_analysis.py
```

The script displays statistical results in the terminal and generates Matplotlib charts.

If you use a Jupyter Notebook, you can execute the analysis cells individually.

### Open the Power BI Dashboard

1. Download the `.pbix` file from this repository.
2. Install Microsoft Power BI Desktop.
3. Open the downloaded file in Power BI Desktop.
4. If prompted, update the dataset file path to match your local CSV location.
5. Refresh the data if necessary to view the report.

## 💡 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical analysis using Pandas
- Data visualization using Matplotlib
- Business insight generation
- Interactive dashboard development using Power BI
- Data storytelling and analytical thinking

## 🏁 Conclusion

This project demonstrates an end-to-end data analytics workflow, from dataset understanding and data quality checking to exploratory analysis, visualization, and dashboard reporting.

By combining Python and Power BI, the project transforms travel customer and booking data into meaningful insights that can support better business understanding and decision-making.