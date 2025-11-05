**USA Financial Insights: Automated Data Pipeline & Power BI Dashboard**

**Purpose**
The USA Financial Insights Dashboard automates the entire journey of financial data — from field agents’ submissions to actionable business intelligence.
By integrating Outlook, Zapier, Google Drive, GCP, Python, and Power BI, this system eliminates manual data handling, providing instant and reliable financial reporting.

**Tech Stack**
The dashboard and pipeline were built using the following tools and technologies:
-**Outlook** – Source of financial data (agents email CSV/Excel reports).
-**Zapier** – Automation bridge to transfer email attachments to Google Drive.
-**Google Drive** – Intermediate cloud storage for incoming files.
-**Python (ETL)** – Cleans, merges, and standardizes data; runs on Google Cloud.
-**Google Cloud Platform (GCP)** – Hosts Python scripts, Cloud Storage buckets, and optional BigQuery integration.
-**Power BI Desktop & Service** – Data visualization and automated dashboard refresh.
-File Format – .csv for raw data, .pbix for dashboard file.

**Data Source**

**Source**: Financial reports collected by field agents and sent via Outlook.
Each agent submits structured data (sales, transactions, expenses, revenue summaries) as .csv or .xlsx files.
These files are automatically routed to Google Drive via Zapier, then processed and consolidated using Python before visualization.

**Features**

**Business Problem**

Financial organizations often rely on scattered, manually collected spreadsheets from multiple agents, leading to delays, errors, and inefficiencies in reporting.
**Goal of the Dashboard**
To build a fully automated financial reporting pipeline that:
Eliminates manual intervention in data collection and aggregation.
Ensures real-time and accurate reporting.
Provides centralized insights through dynamic Power BI visuals.

**Workflow Overview**
**Agents → Outlook → Zapier → Google Drive → GCP (Python ETL) → Power BI**


**Business Impact & Insights**

-Time Savings: Eliminated manual download/upload of reports — saving hours weekly.
-Accuracy Boost: Reduced data entry errors through automated ingestion and cleaning.
-Faster Decisions: Real-time Power BI updates support faster financial analysis.
-Scalable Architecture: New agents or data sources can be added without redesigning the pipeline.
-Cloud-Ready: Fully compatible with GCP and Power BI Service for enterprise deployment.

**Dashboard Preview**

![Dashboard Snapshot](https://github.com/the-bipul-kumar/USA-FINANCIAL-DATA/blob/main/financial_page1.png)
![Dashboard Snapshot](https://github.com/the-bipul-kumar/USA-FINANCIAL-DATA/blob/main/financial_page2.png)


