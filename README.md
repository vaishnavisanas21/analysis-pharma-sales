# analysis-pharma-sales 
# Analysing Pharmaceutical Sales Data

## 📌 Project Overview

This project analyzes pharmaceutical sales data using **Python, Pandas, and Matplotlib**.

The main goal is to understand sales patterns across different pharmaceutical drug categories (ATC codes), identify the drugs with the highest sales, and investigate whether respiratory drugs show seasonal sales patterns.

The analysis is performed using the `salesdaily.csv` dataset.

---

## 🎯 Objectives

The project answers the following questions:

1. What are the total sales quantities for each drug category (ATC code)?
2. Which individual drug categories have the highest total sales?
3. Which three drugs have the highest sales in:

   * January 2015
   * July 2016
   * September 2017
4. Which drug has sold the most in 2017?
5. Which drug category has the highest average daily sales?
6. Are respiratory drugs (R03) sold more during specific months?

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data loading, cleaning, grouping, and analysis
* **Matplotlib** – Data visualization
* **Jupyter Notebook** – Interactive analysis

---


## 📊 Dataset

The dataset contains daily pharmaceutical sales information organized by **ATC (Anatomical Therapeutic Chemical) codes**.

The main drug categories included in the dataset are:

* M01AB
* M01AE
* N02BA
* N02BE
* N05B
* N05C
* R03
* R06

The dataset also contains the date and total sales information.


---

## 🔍 Analysis Performed

### 1. Total Sales by Drug Category

Pandas `groupby()` is used to calculate the total sales for each ATC code.

The results are visualized using a bar chart to make comparison between drug categories easier.

### 2. Highest-Selling Drug Categories

The total sales of each ATC code are calculated and sorted in descending order to identify the highest-selling categories.

### 3. Monthly Sales Analysis

Sales are filtered for:

* January 2015
* July 2016
* September 2017

The three highest-selling drug categories for each period are identified.

### 4. Sales in 2017

The dataset is filtered to include only records from 2017.

The sales of each drug category are then aggregated to determine which category had the highest total sales during the year.

### 5. Average Daily Sales

The average daily sales are calculated for every ATC code.

This helps identify which drug category has the highest average sales per day.

### 6. Respiratory Drug Analysis

The `R03` category represents respiratory drugs.

Monthly sales are calculated for R03 to investigate whether there is a seasonal pattern in respiratory drug demand.

A line chart is used to visualize the monthly trend.

---

## 📈 Key Findings

The analysis produced the following major findings:

* **N02BE** has the highest overall sales among the drug categories.
* **N02BE** also had the highest sales in 2017.
* **N02BE** has the highest average daily sales.
* **R03 respiratory drug sales show seasonal variation**, with sales generally higher during colder months and lower during warmer months.

---

