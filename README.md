# Marketing Campaign Performance Dashboard

## Project Overview

This project analyzes marketing campaign performance across multiple channels and provides actionable business insights using Python, Jupyter Notebook, and Power BI.

The dashboard helps evaluate campaign effectiveness by analyzing key metrics such as Revenue, Cost, Clicks, Conversions, and ROI.

---

## Objectives

* Analyze marketing campaign performance.
* Compare revenue generation across marketing channels.
* Measure campaign profitability using ROI.
* Evaluate conversion performance.
* Visualize business metrics through an interactive Power BI dashboard.

---

## Dataset Information

The dataset contains marketing campaign details including:

| Column      | Description                      |
| ----------- | -------------------------------- |
| CampaignID  | Unique campaign identifier       |
| StartDate   | Campaign start date              |
| EndDate     | Campaign end date                |
| Channel     | Marketing channel                |
| Impressions | Number of impressions            |
| Clicks      | Number of clicks                 |
| Leads       | Number of leads generated        |
| Conversions | Number of successful conversions |
| Cost_USD    | Campaign cost                    |
| Revenue_USD | Revenue generated                |

---

## Feature Engineering

Additional metrics were created for deeper analysis:

### Click Through Rate (CTR)

CTR = (Clicks / Impressions) × 100

### Conversion Rate

Conversion Rate = (Conversions / Clicks) × 100

### Cost Per Click (CPC)

CPC = Cost_USD / Clicks

### Cost Per Acquisition (CPA)

CPA = Cost_USD / Conversions

### Return on Investment (ROI)

ROI = ((Revenue_USD - Cost_USD) / Cost_USD) × 100

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI
* Git & GitHub

---

## Dashboard Features

### Executive Overview

* Total Revenue
* Total Cost
* Total Conversions
* Average ROI

### Channel Performance Analysis

* Revenue by Channel
* Cost by Channel
* ROI by Channel
* Clicks by Channel

### Business Insights

* Most profitable marketing channel
* Best ROI-performing campaigns
* Cost efficiency analysis
* Conversion performance comparison

---

## Key Insights

* Identified top-performing marketing channels based on revenue.
* Measured profitability using ROI analysis.
* Evaluated customer conversion effectiveness.
* Compared campaign spending against generated revenue.
* Highlighted opportunities for budget optimization.

---

## Repository Structure

```text
marketing-campaign-performance-dashboard/
│
├── Marketing_Campaign_Dashboard.pbix
├── marketing_campaign_performance.ipynb
├── marketing_campaign_performance.csv
├── marketing_campaign_processed.csv
├── README.md
```

## Future Enhancements

* Predict campaign revenue using Machine Learning.
* Build a Streamlit web application.
* Add campaign forecasting.
* Perform customer segmentation analysis.

---

## Author

Yuvaraj Kumar

Marketing Campaign Performance Analysis Project
Built using Python, Power BI, and GitHub.
