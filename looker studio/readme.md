### Loan Health Dashboard with Looker – Capstone Project
📌 Overview

This project is part of my Data Analytics Capstone journey, where I applied the final two stages of the data journey: Analyze and Activate.

The goal was to design and implement an interactive dashboard in Looker (Google Cloud BI tool) to help the Treasury department at TheLook Fintech monitor loan health metrics and make data-driven decisions.

# 🎯 Business Objective

Trevor, the head of Treasury, wanted quick and user-friendly access to key loan health metrics. The dashboard needed to answer four critical business questions:

What is the total outstanding amount of all loans?

What percentage of outstanding loans fall into each status category?

Which states have the highest number of outstanding loans?

Which customers own their homes outright and have current loans?

By addressing these, the Treasury team can better manage risk, compliance, and financial health.

# 🛠️ Tools & Technologies

Google Looker (Looker Studio Enterprise) – Dashboard creation and visualization

SQL – Querying and preparing loan data

LookML – Dataset modeling and reusable data structures

Google Cloud Platform (BigQuery + Looker integration) – Data storage and reporting backend

# 🔄 Project Workflow
Step 1: Connect Data to Looker

Integrated TheLook Fintech loan dataset with Looker.

Verified schema fields: loan balances, statuses, borrower location, homeowner index.

Step 2: Build Visualizations

Created four key insights to answer Treasury’s business questions:

Total Outstanding Loan Balances – A KPI card showing the total financial exposure.

SQL query aggregated outstanding balances.

Loan Status Distribution – Pie chart displaying categories such as current, late, defaulted, charged off, paid off.

Calculated percentages of loans by status.

Top 10 States with Outstanding Loans – Bar chart showing states with the highest concentration of loans.

Joined with geographic data for visualization.

Homeowners with Current Loans – Table listing customers who own homes outright and still have active loans.

Applied filters using homeowner income index and loan status.

Step 3: Enhance Dashboard Functionality

Enabled cross-filtering across charts to allow interactive exploration.

Configured automatic refresh scheduling for near real-time updates.

Customized dashboard formatting for readability and stakeholder presentations.

Step 4: Deliver & Publish

Shared the dashboard within Looker workspace.

Configured permissions for Treasury team members to access and interact with reports.

# 📊 Dashboard Preview

Dashboard Screenshot:


Walkthrough Video:
▶️ Loan Health Dashboard Demo

# 📈 Key Outcomes

Provided Treasury with a single source of truth for loan health monitoring.

Improved ability to track loan performance, risk exposure, and compliance.

Delivered a portfolio-ready dashboard showcasing real-world BI and cloud analytics skills.

# 💡 Skills Gained

Looker BI Development: Building dashboards, cross-filtering, and refresh scheduling.

SQL Querying: Data preparation, aggregation, and filtering for dashboard metrics.

LookML Modeling: Structuring reusable datasets for visualization.

Data Storytelling: Translating business requirements into actionable insights.

Cloud Analytics: Integrating Google Cloud BigQuery with Looker for reporting.
