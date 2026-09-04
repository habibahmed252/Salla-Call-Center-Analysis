# Salla Call Center Performance Analysis

> A data analysis project focused on evaluating Call Center operations, agent performance, and key service KPIs using Microsoft Excel, Exploratory Data Analysis, and Power BI.

---

## Project Overview

This project explores Call Center operations through the analysis of operational data from Salla, a Saudi-based e-commerce platform.

As a new domain for me, the project was not limited to building a dashboard. It was an opportunity to understand how Call Centers operate, learn the key performance indicators used to evaluate customer service teams, and explore how data can support operational decision-making.

The project follows a complete data analysis workflow, starting with data cleaning and preparation using Microsoft Excel, followed by Exploratory Data Analysis, KPI evaluation, and interactive dashboard development using Power BI.

The analysis focuses on three main areas:

* Agent Performance
* Operational Performance
* Call Volume and Forecast Analysis

The final dashboard provides an interactive environment for exploring performance across agents, projects, and months.

---

## Business Problem

Call Centers generate large amounts of operational data that can provide valuable insights into customer service quality, employee performance, and operational efficiency.

This project aims to answer key business questions such as:

* Which agents have the highest and lowest efficiency?
* How does Service Level vary across agents?
* Which agents have higher Average Speed of Answer (ASA)?
* What is the overall Abandonment Rate?
* Which projects have the highest abandonment rates?
* How do Actual Calls compare with Forecasted Calls?
* What is the difference between Calls Offered and Calls Handled?
* Which projects demonstrate stronger operational performance?
* How does Call Center performance change across months?
* Are there agents or projects that require further performance monitoring?

---

## Project Objectives

1. Clean and prepare the Call Center dataset.
2. Explore operational patterns and trends.
3. Calculate and evaluate key Call Center KPIs.
4. Compare individual agent performance.
5. Analyze project-level operational performance.
6. Compare Actual Call Volume with Forecasted Call Volume.
7. Analyze Offered, Handled, and Abandoned Calls.
8. Build an interactive Power BI dashboard.
9. Translate analytical results into meaningful business insights.

---

## Data Preparation

Microsoft Excel was used for the initial data cleaning and preparation stage.

The preparation process included:

* Reviewing the dataset structure and data quality.
* Checking missing and inconsistent values.
* Standardizing data formats.
* Preparing fields required for analysis.
* Validating numerical and categorical data.
* Structuring the dataset for Power BI analysis.

---

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the main patterns and relationships within the Call Center data.

The analysis examined:

* Agent performance
* Project performance
* Monthly call volume
* Actual vs Forecasted Calls
* Calls Offered vs Calls Handled
* Abandoned Calls
* Service Level
* Average Speed of Answer
* Efficiency
* Handling Ratio

The EDA stage helped identify the most relevant KPIs and dimensions for the final dashboard.

---

## Key Performance Indicators

| KPI                  | Description                                                                  |
| -------------------- | ---------------------------------------------------------------------------- |
| **Efficiency**       | Measures agent productivity and overall performance.                         |
| **Service Level**    | Measures the percentage of calls answered within the defined service target. |
| **ASA**              | Average Speed of Answer, measuring how quickly incoming calls are answered.  |
| **Abandonment Rate** | Percentage of calls abandoned before being handled.                          |
| **Handling Ratio**   | Relationship between handled calls and offered calls.                        |
| **Calls Offered**    | Total number of calls offered to the Call Center.                            |
| **Calls Handled**    | Total number of calls successfully handled.                                  |
| **Forecasted Calls** | Expected call volume based on the forecast.                                  |
| **Actual Calls**     | Actual call volume received during the analyzed period.                      |

---

## Key Findings

### Overall Performance

| Metric                |       Result |
| --------------------- | -----------: |
| Average Efficiency    |    **89.9%** |
| Service Level         |      **91%** |
| Average ASA           | **9.22 sec** |
| Abandonment Rate      |     **1.3%** |
| Handling Ratio        |    **98.7%** |
| Average Handled Calls |    **5.95K** |

The results indicate strong overall operational performance, with a high handling ratio and relatively low overall abandonment rate.

### Agent Performance

The agent analysis highlights differences in performance across the team.

The dashboard allows performance to be compared using:

* Efficiency
* Service Level
* ASA
* Abandoned Calls
* Handling Ratio

This makes it possible to identify high-performing agents as well as agents whose performance may require further investigation.

### Project Performance

The Call Center operations are distributed across three projects.

The analysis compares projects based on:

* Efficiency
* Abandonment Rate
* Calls Offered
* Calls Handled
* Overall call volume

This comparison helps identify differences in operational performance between projects.

### Monthly Trends

Monthly analysis provides insight into changes in:

* Call volume
* Efficiency
* ASA
* Abandoned Calls
* Actual vs Forecasted Calls

This helps identify periods of higher demand and potential operational gaps.

---

# Power BI Dashboard

The final dashboard was developed using Power BI to provide an interactive view of Call Center performance.

## Dashboard Pages

### 1. Overview

The Overview page provides a high-level summary of Call Center performance.

It includes:

* ASA
* Handling Ratio
* Service Level
* Abandonment Rate
* Agent performance comparison
* Monthly efficiency trends
* Project-level performance
* Monthly ASA analysis

![Overview Dashboard](Dashboard/Overview.png)

---

### 2. Agents Performance

This page focuses on individual agent performance and comparison.

It includes:

* Efficiency
* Service Level
* ASA
* Abandoned Calls
* Agent-level comparisons
* Project distribution
* Monthly filtering
* Individual agent filtering

![Agents Performance Dashboard](Dashboard/Agents_Performance.png)

---

### 3. Operations Performance

This page focuses on Call Center operational performance.

It includes:

* Abandoned Calls
* Forecasted Calls
* Handled Calls
* Abandonment Rate
* Actual vs Forecasted Calls
* Offered vs Handled Calls
* Project-level performance
* Monthly trends

![Operations Performance Dashboard](Dashboard/Operations_Performance.png)

---

## Dashboard Features

### Interactive Navigation

Users can navigate between the different dashboard pages to explore the analysis from multiple perspectives.

### Dynamic Filtering

The dashboard allows users to filter the analysis by:

* Agent
* Project
* Month

### Comparative Analysis

Multiple KPIs and visualizations are combined to make it easier to compare:

* Agents
* Projects
* Monthly performance
* Actual vs Forecasted call volume

---

## Project Workflow

```text
Raw Data
    |
    v
Data Cleaning & Preparation
    |
    v
Exploratory Data Analysis
    |
    v
KPI Calculation & Validation
    |
    v
Power BI Dashboard Development
    |
    v
Interactive Business Analysis
    |
    v
Business Insights
```

---

## Tools & Technologies

* **Microsoft Excel** — Data cleaning and preparation
* **Power Query** — Data transformation
* **Power BI** — Interactive dashboard development
* **Exploratory Data Analysis** — Pattern and trend analysis
* **Data Visualization** — Interactive visual storytelling
* **KPI Analysis** — Performance measurement and evaluation

---

## Dashboard Demo

A walkthrough of the interactive Power BI dashboard is available on YouTube.

**[Watch the Dashboard Demo](https://youtu.be/GDPwByksQpA?si=Ncrk2i_UQ5vzBHkM)**

The video demonstrates:

* Overview dashboard
* Agent performance analysis
* Operations performance
* Interactive filters
* Dashboard navigation
* KPI analysis

---

## Repository Structure

```text
Salla-Call-Center-Analysis/
│
├── README.md
│
├── Data/
│   └── cleaned_data.xlsx
│
├── Analysis/
│   └── EDA_Analysis.xlsx
│
└── Dashboard/
    ├── Overview.png
    ├── Agents_Performance.png
    └── Operations_Performance.png
```

> The Power BI `.pbix` file is not included in this repository. Dashboard screenshots and a video walkthrough are provided to demonstrate the final result.

---

## Recommendations

Based on the analysis, several areas can be considered for further investigation:

1. Review lower-performing agents and identify potential training needs.
2. Investigate differences in abandonment rates between projects.
3. Analyze the gap between forecasted and actual call volumes to improve forecasting accuracy.
4. Investigate periods with higher call volumes to support capacity planning.
5. Study the practices of high-performing agents that could potentially be applied across the team.
6. Continue monitoring KPIs over time to identify performance changes.

---

## Conclusion

This project was an opportunity to explore the Call Center domain from a data analysis perspective and understand how operational data can be transformed into meaningful performance insights.

By combining Excel-based data preparation, exploratory analysis, KPI evaluation, and Power BI visualization, the project demonstrates a structured approach to analyzing agent performance and Call Center operations.

Beyond the technical implementation, the project helped me explore a new business domain and understand how data can support operational monitoring, performance evaluation, and data-driven decision-making.

This project is part of my ongoing portfolio development, with a focus on exploring different business domains through practical Data Analysis and Business Intelligence projects.

---

## Project Status

**Completed**
