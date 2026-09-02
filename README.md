# Freska Prisia Putri — Data & AI Portfolio
#### Data Analytics • Business Intelligence • Data Science • Machine Learning • Data Engineering

A collection of end-to-end projects across **Data Analytics, Business Intelligence, Data Warehousing, Machine Learning, and Deep Learning**, focused on transforming raw data into structured insights and practical data-driven solutions.

## Hi, I'm Freska

I am an Information Systems graduate with a strong interest in **Data Analytics, Business Intelligence, Data Science, and Machine Learning**.

My projects cover a broad range of data workflows, including data cleaning, SQL analysis, dimensional modeling, dashboard development, large-scale data processing, predictive modeling, deep learning experimentation, and model deployment.

I enjoy working with data from both business and technical perspectives—whether it involves identifying operational patterns, building analytical dashboards, designing data pipelines, or developing machine learning models for real-world applications.

## Skills & Tools

- **Programming & Data Analysis:** Python, Pandas, NumPy
- **SQL & Databases:** MySQL, SQLite, Spark SQL
- **Business Intelligence:** Power BI, DAX, Power Query
- **Data Visualization:** Power BI, Matplotlib, Plotly
- **Data Warehousing:** Dimensional Modeling, Star Schema, ETL
- **Big Data:** PySpark, Parquet, distributed data processing
- **Machine Learning:** Scikit-learn, classification, forecasting, feature engineering, model evaluation
- **Deep Learning:** TensorFlow/Keras, CNN, LSTM, CNN-LSTM, temporal modeling
- **Computer Vision:** MediaPipe Holistic, landmark-based gesture recognition
- **Model Evaluation:** Cross-validation, LOSO validation, Accuracy, Precision, Recall, F1-score, Top-K Accuracy
- **Model Deployment:** Flask REST API, inference pipeline integration
- **Tools:** Jupyter Notebook, Microsoft Excel, Git, GitHub

# Featured Projects

## CFPB Credit Card Complaints Intelligence

**Data Engineering & Business Intelligence | Databricks · PySpark · Spark SQL · Delta Tables · Unity Catalog**

An independent portfolio project analyzing 9,073 CFPB credit card complaints received in January 2025 through data validation, Bronze–Silver–Gold processing, and a Databricks AI/BI dashboard.

**Key Highlights**

- Built Bronze, Silver, and Gold Delta tables to preserve source data, prepare analytical fields, and generate dashboard-ready summaries.
- Validated complaint IDs, date fields, and selected analytical columns, and reconciled transformed data with saved tables and dashboard aggregates.
- Developed a dashboard covering total complaints, daily complaint volume, company response categories, and response timeliness.
- Reported a 99.71% timely-response rate, with 26 records marked not timely, distinguishing these from the separate “Untimely response” category.
- Published a documented notebook with saved outputs removed and a dashboard PDF, with clear metric definitions and interpretation limits.

**Portfolio Metrics:** 9,073 complaints · 31 daily summaries · 99.71% timely responses

[Repository](https://github.com/freskaprisiaa-web/cfpb-complaints-intelligence) | [Notebook](https://github.com/freskaprisiaa-web/cfpb-complaints-intelligence/blob/main/notebooks/01_data_understanding_public.ipynb) | [Dashboard PDF](https://github.com/freskaprisiaa-web/cfpb-complaints-intelligence/blob/main/dashboard/CFPB_Credit_Card_Complaints_January_2025.pdf)

---

## Multi-Label Car Condition Classification & AI Dataset Pipeline

**Computer Vision & Deep Learning | Python · TensorFlow/Keras · EfficientNetB0 · Playwright · Scikit-learn**

An end-to-end computer vision project for identifying the open or closed state of five vehicle components from rendered images. The project covers programmatic image acquisition, state-derived multi-label annotation, dataset quality control, leakage-aware splitting, transfer learning, validation-only threshold selection, and error analysis.

**Key Highlights**

- Generated and audited **960 simulator images** covering all **32 binary state combinations**, with 30 viewpoints per combination and balanced positive/negative observations for every label.
- Built a reproducible Playwright-based data-collection pipeline that derives labels directly from controlled simulator states and automatically checks image integrity, completeness, and duplication.
- Designed an **azimuth-grouped train/validation/test split** to prevent different zoom levels from the same camera orientation from leaking across datasets.
- Compared frozen **MobileNetV2** and **EfficientNetB0** transfer-learning models, then partially fine-tuned the stronger validation candidate.
- Selected per-label decision thresholds exclusively on validation data before evaluating the locked model on an untouched test set.
- Achieved **0.735 Macro F1**, **0.726 Micro F1**, and **0.761 Mean ROC-AUC** on the test set after validation-based threshold optimization.
- Performed label- and viewpoint-level error analysis while clearly documenting the limitations of simulator-generated data and the absence of real-world vehicle validation.

**Portfolio Metrics:** 960 images · 32 state combinations · 5 target labels · 0.735 Macro F1 · 0.726 Micro F1

[Repository](https://github.com/freskaprisiaa-web/car-condition-multilabel-classification) |
[Notebook](https://github.com/freskaprisiaa-web/car-condition-multilabel-classification/blob/main/notebook/car_condition_multilabel_classification.ipynb)


## Furniture Export Sales, Fulfillment & Forecasting Intelligence

**Business Analytics & Business Intelligence | Python · SQL · Excel · Power BI · DAX · Forecasting**

An end-to-end business analytics project that transforms public global retail-order data into a validated decision-support workflow for furniture commercial performance, profitability, order-to-ship fulfillment, forecasting, operational monitoring, process improvement, and business requirements.

**Key Highlights**

- Prepared and validated **51,290 source order lines**, including a Furniture analytical subset of **9,876 order lines** and **8,240 logical orders**.
- Established consistent, aggregate-safe KPI definitions across Python, SQL, Excel, and Power BI for Sales, Profit, Profit Margin, loss exposure, lead time, and Shipping Cost Ratio.
- Identified approximately **4.11 million in Furniture Sales**, **285 thousand in Profit**, and a **6.94% Profit Margin**, while highlighting Tables as the primary sub-category requiring profitability investigation.
- Built a reusable SQLite analytical layer containing indexed facts, quality checks, curated views, and business queries that reconcile with the Python analytical outputs.
- Developed a **12-sheet Excel operational report** with native tables, formula-driven reporting, charts, conditional formatting, and recurring monitoring views.
- Created a **4-page Power BI dashboard** covering Executive Overview, Market & Product Performance, Fulfillment & Shipping Performance, and Forecast & Improvement Priorities.
- Evaluated four time-series forecasting approaches using expanding rolling-origin backtesting and selected **Holt-Winters Additive** with **12.07% WAPE** for the six-month point forecast.
- Translated analytical evidence into seven monitoring workstreams, governed KPI definitions, system requirements, user stories, acceptance criteria, and evidence-to-requirement traceability.
- Completed **1,415/1,415 controlling analytical validation checks** across the main delivery phases.

**Portfolio Metrics:** 4.11M Sales · 6.94% Profit Margin · 12.07% Forecast WAPE · 1,415/1,415 validation checks

[Repository](https://github.com/freskaprisiaa-web/furniture-export-sales-fulfillment-forecasting) |
[Recruiter Summary](https://github.com/freskaprisiaa-web/furniture-export-sales-fulfillment-forecasting/blob/main/docs/RECRUITER_PROJECT_SUMMARY.md) |
[Excel Report](https://github.com/freskaprisiaa-web/furniture-export-sales-fulfillment-forecasting/blob/main/excel/Furniture_Business_Performance_Operational_Report.xlsx) |
[Power BI Screenshots](https://github.com/freskaprisiaa-web/furniture-export-sales-fulfillment-forecasting/tree/main/screenshots/powerbi)


## Customer Experience & SLA Performance Monitoring

**CRM Operations Analytics | Python · SQL · Excel · Power BI · DAX**

End-to-end customer experience and service-operations analytics project covering **85,907 customer-support interactions**, from data validation and KPI design through SQL analysis, operational reporting, Power BI monitoring, prioritization, and business recommendations.

**Key Highlights**
- Analyzed **85,907 support interactions** across issue categories, channels, CSAT, response performance, and operational segments.
- Built a validated KPI framework covering **Average CSAT, Low CSAT Rate, Median/P90 Response Time, and 60-minute analytical SLA compliance**.
- Developed reusable **SQLite analytics** for customer experience, issue concentration, response performance, SLA monitoring, and periodic reporting.
- Created a **10-sheet Excel operational report** for executive KPIs, daily/weekly monitoring, issue drill-down, channel/SLA analysis, and operational screening.
- Built a **4-page Power BI dashboard** covering Executive Overview, Issue & Customer Experience, Service & SLA Performance, and Operational Screening.
- Designed an interpretable **Priority 1 / Priority 2 / Watchlist / Context** follow-up framework without arbitrary weighted scoring.
- Identified **Returns as primarily scale-led**, while **Email showed a smaller but elevated CX/service signal**, supporting different operational follow-up approaches.
- Translated validated findings into evidence-based investigation and monitoring recommendations while preserving non-causal interpretation.

**Portfolio Metrics:** 4.24 Average CSAT · 14.57% Low CSAT · 6 min Median Response · 78.67% Analytical SLA Compliance

[Repository](https://github.com/freskaprisiaa-web/customer-experience-sla-monitoring)

## Retail Demand Intelligence & Continuous Improvement

**Independent Kaggle Competition Project | CRISP-DM**  
`Python` `SQL` `Excel` `Power BI` `Forecasting` `Business Analysis`

End-to-end retail analytics project that transforms more than **3 million sales records** from 54 stores and 33 product families into demand forecasts, KPI monitoring, recurring reports, and continuous-improvement recommendations.

- Integrated sales, promotions, transactions, holidays, oil prices, store, and product data.
- Developed a leakage-safe 16-day forecasting workflow with **0.551 RMSLE**, **17.2% WAPE**, and **−1.5% bias**.
- Built interactive Power BI dashboards for sales performance and forecast monitoring.
- Produced Excel management reports, SQL analysis, KPI definitions, business requirements, and an improvement backlog.
- Generated a Kaggle-ready submission containing **28,512 predictions**.

[Repository](https://github.com/freskaprisiaa-web/retail-demand-intelligence) |
[Notebook](https://github.com/freskaprisiaa-web/retail-demand-intelligence/blob/main/analysis.ipynb) |
[Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmRkZDRkYmUtODM2Yy00OTYxLTgwMjktOTk4MzJkYjk4YTI4IiwidCI6IjkwYWZmZTBmLWMyYTMtNDEwOC1iYjk4LTZjZWI0ZTk0ZWYxNSIsImMiOjEwfQ%3D%3D) |
[Excel Report](https://github.com/freskaprisiaa-web/retail-demand-intelligence/blob/main/Retail_Demand_Intelligence.xlsx) |
[Kaggle Competition](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)


## Real-Time BISINDO Gesture Recognition — Deep Learning Thesis Project

An end-to-end deep learning project for recognizing dynamic Indonesian Sign Language (**BISINDO**) gestures in real time.

This project was developed as part of my undergraduate thesis and combines landmark-based computer vision, temporal deep learning, feature engineering, signer-independent evaluation, and deployment-oriented inference integration.

### Key Highlights

- Processed **713 gesture sequences** collected from **7 independent school signers**
- Classified **15 dynamic BISINDO gesture classes**
- Represented each gesture as a **30-frame temporal sequence**
- Extracted **159 MediaPipe Holistic landmark features per frame**
- Engineered an additional **35 relational landmark features**, resulting in **194 features per frame**
- Evaluated multiple model configurations using **seven-fold Leave-One-Signer-Out (LOSO) cross-validation**
- Compared temporal deep learning architectures for signer-independent gesture recognition
- Selected a **Relational CNN-LSTM** model based on observed performance, compact architecture, and deployment suitability
- Achieved:
  - **88.25% mean accuracy**
  - **86.32% Supported Macro-F1**
  - **97.12% mean Top-3 accuracy**
- Integrated the final model into a **Flask inference API** for real-time application use

### Model Comparison

| Model | Input | Accuracy | Supported Macro-F1 | Top-3 Accuracy |
|---|---:|---:|---:|---:|
| CNN-LSTM Baseline | `(30,159)` | 74.56% | 70.55% | 92.33% |
| Landmark Temporal Transformer | `(30,159)` | 79.88% | 76.41% | 90.92% |
| **Relational CNN-LSTM** | **`(30,194)`** | **88.25%** | **86.32%** | **97.12%** |

The Relational CNN-LSTM achieved the **highest observed performance** among the evaluated models. However, the pairwise gains were not statistically significant after Holm correction, so the result is presented as the strongest observed configuration rather than proof of universal superiority.

### Technical Scope

- **Domain:** Computer Vision, Deep Learning, Sign Language Recognition
- **Data Type:** Temporal landmark sequence data
- **Feature Representation:** MediaPipe Holistic landmarks + relational landmark features
- **Evaluation Strategy:** Seven-fold Leave-One-Signer-Out cross-validation
- **Deployment:** Flask-based inference API for real-time integration

**Tech Stack:** Python, TensorFlow/Keras, MediaPipe Holistic, NumPy, Pandas, Scikit-learn, Flask, Jupyter Notebook

[View Repository](https://github.com/freskaprisiaa-web/bisindo-learn-ai-platform)


## Multi-Branch Retail Performance Data Warehouse & BI - DWBI Course Final Project

End-to-end Business Intelligence and Data Warehouse academic project integrating sales, inventory, CRM, promotions, targets, returns, and forecasting data for multi-branch retail decision-making.

[GitHub Repository](https://github.com/freskaprisiaa-web/retail-performance-data-warehouse-bi) | [Live Dashboard](https://freskaprisiaa-web.github.io/retail-performance-data-warehouse-bi/dashboard.html)

Key Highlights:

- Designed a dimensional warehouse with 6 conformed dimensions and 5 fact tables across 12 retail branches
- Processed 120,000 sales records through automated ETL, validation, and reconciliation workflows
- Developed Power BI and HTML dashboards covering revenue, target attainment, margin, stockout, returns, and channel performance
- Generated a Q1 2026 baseline forecast of 16,668 units with 7.9% backtest MAPE

**Tech Stack:** Power BI, DAX, Power Query, Python, SQL, SQLite, MySQL, Jupyter Notebook, Excel


## Motorcycle Dealer Sales, Inventory & Financing Analytics - Self Project

End-to-end dealership analytics project using synthetic sales, inventory, financing, and branch target data.

[GitHub Repository](https://github.com/freskaprisiaa-web/motorcycle-dealer-analytics) | [Live Dashboard](https://freskaprisiaa-web.github.io/motorcycle-dealer-analytics/dashboard.html)

Key Highlights:

- Analyzed 82,709 synthetic sales transactions across multiple branches
- Built MySQL queries, automated data validation, and KPI analysis
- Created a Q1 2026 demand forecast with 1.4% backtest MAPE
- Developed an Excel scorecard and executive dashboard

**Tech Stack:** Python, MySQL, Excel, Jupyter Notebook, Data Visualization

## E-Commerce Clickstream & Customer Funnel Analytics - Big Data Management Course Final Project

End-to-end big data analytics project examining customer journeys, conversion funnels, and purchasing behavior.

[GitHub Repository](https://github.com/freskaprisiaa-web/pyspark-ecommerce-clickstream-analytics) | [Live Dashboard](https://freskaprisiaa-web.github.io/pyspark-ecommerce-clickstream-analytics/dashboard.html)

Key Highlights:

- Built a PySpark pipeline for 102,505 events, 50,000 sessions, and 6,635 synthetic orders
- Analyzed customer funnels, acquisition channels, product categories, and RFM segments
- Identified conversion opportunities across devices and marketing channels
- Delivered reproducible analysis through Jupyter Notebook, Parquet, and an interactive dashboard

**Tech Stack:** PySpark, Spark SQL, Python, Jupyter Notebook, Parquet


## Warehouse Fulfillment & Delivery Performance Analysis - Self Project
End-to-end logistics analysis project using Python, SQL, and Power BI.

https://github.com/freskaprisiaa-web/warehouse-fulfillment-analysis

Key Highlights:
- Built KPI metrics (cycle time, delay rate, cost efficiency)
- Performed vendor & shipment mode performance analysis
- Identified high-risk countries and high-cost shipments
- Developed an interactive Power BI dashboard

Tech Stack: Python, SQL, Power BI

## Warehouse Operations Intelligence Dashboard - Self Project
End-to-end data analytics project simulating warehouse operations to enable real-time monitoring, improve data integrity, and support operational decision-making.

https://github.com/freskaprisiaa-web/warehouse-operations-intelligence

This project builds a complete data pipeline and interactive dashboard to monitor key warehouse KPIs and identify operational bottlenecks.
Key highlights:
- Developed data pipeline for inbound, outbound, inventory, and exception data processing
- Built KPI monitoring system including GR Turnaround Time (GR TAT), Delay Rate, WO Cycle Time, and Inventory Mismatch
- Designed Power BI dashboard for real-time operational visibility
- Identified supplier and product-level inefficiencies impacting warehouse performance
- Implemented data validation and anomaly detection to improve data integrity
The project demonstrates how data-driven insights can improve warehouse efficiency, reduce delays, and enhance operational control.


## Machine Learning vs Deep Learning Across Data Types - Self Project
End-to-end comparative analysis of Machine Learning and Deep Learning models across three different data types: tabular (Titanic), image (MNIST), and text (Disaster Tweets). 

https://github.com/freskaprisiaa-web/ml-vs-dl-data-analysis

This project evaluates model performance, preprocessing strategies, and trade-offs between accuracy, complexity, and training time. Results show that:
- Random Forest outperforms deep learning on small tabular data
- CNN achieves the highest accuracy on image data (98.4%)
- Logistic Regression performs best on short-text classification

The project highlights that model selection should be driven by data characteristics rather than model complexity.

