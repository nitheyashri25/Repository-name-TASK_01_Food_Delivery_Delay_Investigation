# Food Delivery Delay Pattern Investigation

**Project Overview**

Food delivery platforms process thousands of orders daily. Delayed deliveries can negatively affect customer satisfaction, increase operational costs, and reduce customer retention. This project investigates the factors contributing to food delivery delays using statistical analysis and exploratory data analysis (EDA).

The objective is to identify key delay-causing factors and provide actionable business recommendations to improve delivery performance.

---

## Problem Statement

Recently, customer complaints regarding delayed food deliveries have increased. The operations team wants to understand:

* Why are deliveries getting delayed?
* Which factors contribute most to delays?
* Does weather affect delivery performance?
* Does traffic increase delivery time?
* Do experienced couriers perform better?
* What operational improvements can reduce delays?

This project performs statistical investigation and data analysis to answer these business questions.

---

## Dataset Description

**Dataset Used:** Food Delivery Times Dataset

### Features

| Feature                | Description                              |
| ---------------------- | ---------------------------------------- |
| Order_ID               | Unique order identifier                  |
| Distance_km            | Distance between restaurant and customer |
| Weather                | Weather condition during delivery        |
| Traffic_Level          | Traffic condition during delivery        |
| Time_of_Day            | Morning, Afternoon, Evening, Night       |
| Vehicle_Type           | Delivery vehicle used                    |
| Preparation_Time_min   | Restaurant food preparation time         |
| Courier_Experience_yrs | Courier experience in years              |
| Delivery_Time_min      | Actual delivery time                     |

### Derived Feature

**Delay_Minutes**

A new feature was created to measure delivery delays:

Delay_Minutes = Delivery_Time_min − Expected_Delivery_Time

This enables delay-based statistical analysis.

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
* Git
* GitHub

---

## Methodology

### Phase 1: Data Understanding

* Loaded dataset
* Checked data types
* Identified missing values
* Checked duplicate records
* Understood feature definitions

### Phase 2: Statistical Analysis

Calculated:

* Mean
* Median
* Mode
* Standard Deviation
* Variance
* Quartiles

Analyzed delay distribution and central tendency.

### Phase 3: Outlier Investigation

Detected unusual delivery delays using:

* Box Plot
* IQR Method
* Z-Score Method

### Phase 4: Relationship Analysis

Studied relationships between:

* Distance vs Delay
* Traffic vs Delay
* Weather vs Delay
* Preparation Time vs Delay
* Courier Experience vs Delay

Used:

* Scatter Plots
* Correlation Matrix
* Heatmaps
* Boxplots

### Phase 5: Hypothesis Testing

#### Null Hypothesis (H0)

Weather does not affect delivery delay.

#### Alternative Hypothesis (H1)

Weather significantly affects delivery delay.

Performed ANOVA testing and interpreted results in business terms.

### Phase 6: Business Insights

Generated insights and recommendations based on statistical findings.

---

## Visualizations

The project includes:

* Delay Distribution Histogram
* Box Plot for Outlier Detection
* Correlation Heatmap
* Distance vs Delay Scatter Plot
* Preparation Time vs Delay Scatter Plot
* Traffic Level vs Delay Box Plot
* Weather vs Delay Box Plot

---

## Key Findings

1. Traffic congestion significantly increases delivery delays.

2. Adverse weather conditions contribute to longer delivery times.

3. Longer delivery distances increase delay probability.

4. Restaurant preparation time has a direct impact on delays.

5. Courier experience influences delivery efficiency.

6. Statistical testing was used to evaluate the impact of weather on delays.

---

## Business Recommendations

### Traffic Management

* Implement route optimization systems.
* Use live traffic monitoring.
* Increase delivery personnel during peak hours.

### Weather-Aware Planning

* Introduce weather-adjusted delivery estimates.
* Allocate additional riders during adverse weather.

### Restaurant Efficiency

* Monitor restaurants with excessive preparation times.
* Improve kitchen workflow and order processing.

### Courier Allocation

* Assign experienced couriers to long-distance deliveries.
* Introduce performance-based incentives.

### Customer Experience

* Provide accurate estimated delivery times.
* Notify customers proactively about expected delays.

---

## Project Structure

TASK_01_Food_Delivery_Delay_Investigation/

├── Food_Delivery_Times.csv

├── Task1.ipynb

├── README.md

└── requirements.txt

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

requirements.txt:

```text
pandas
numpy
matplotlib
seaborn
scipy
```

---

## Future Improvements

* Build delay prediction models using Machine Learning.
* Integrate real-time traffic and weather APIs.
* Create interactive dashboards using Power BI or Tableau.
* Perform city-wise analysis using enriched datasets.
* Develop delivery performance monitoring systems.

---

## Conclusion

This project successfully investigates food delivery delay patterns using statistical analysis and exploratory data analysis techniques. The findings provide valuable operational insights that can help food delivery companies improve delivery efficiency, reduce delays, and enhance customer satisfaction.
