
# Blood-Bank-Operations-Donor-Eligibility-Analytics
An interactive multi-page Power BI dashboard designed to analyze blood bank inventory, donor eligibility, and monthly donation trends from an operational dataset.


## 🎯 Objective
To develop a comprehensive Power BI analytics dashboard that:

🩸 Monitors real-time blood group inventory and identifies critical stock levels.

👥 Analyzes donor demographics, age distributions, and eligibility status.

📈 Visualizes monthly donation frequencies to track operational trends over time.


## 🛠️ Tech Stack & Key Concepts
* **BI Tool:** Power BI Desktop
* **Data Transformation:** Power Query (Data cleaning, type casting, removing nulls)
* **Data Modeling:** Star Schema / Relational modeling
* **Analytics:** DAX (Data Analysis Expressions) for custom calculated columns and measures


  **## 📊 Dashboard Structure & Key Features

### 1. Executive Overview

<img width="1080" height="582" alt="Blood Bank Overview" src="https://github.com/user-attachments/assets/fb4fefe5-3dd0-4f11-b8c8-36635afaf333" />

* **Key Metrics:** Monitors total donor counts and total blood units collected at a glance.
* **Breakdown:** Visualizes blood group distribution alongside gender-wise donor metrics.

### 2. Donor Eligibility & Health Analysis

<img width="1110" height="588" alt="Donor Eligibility Healtgh" src="https://github.com/user-attachments/assets/05be1e53-520c-4976-9a51-3cdcf6d4b659" />

* **Health Metrics:** Compares donor weight against eligibility criteria.
* **Demographics:** Visualizes age group vs. donor count to isolate target demographics for future drives.

### 3. Donation Frequency & Trend Analysis

<img width="1107" height="597" alt="Monthly Donation Trends Table" src="https://github.com/user-attachments/assets/1a658b44-0f01-43c9-ae20-f758a91c4e41" />

* **Time-Series:** Tracks donation fluctuations month-over-month to identify seasonal peaks.
* **Summary Table:** A granular breakdown filtering total units donated by blood group and date.

### 4. Inventory & Management Insights
<img width="1103" height="596" alt="Blood Demand Availability Insights" src="https://github.com/user-attachments/assets/935c4e06-2e2b-4a79-bdc2-71fda4968b16" />

* **Stock Tracking:** Highlights high-risk/low-stock blood types to prevent critical shortages.
* **Availability Status:** Displays real-time operational availability of the donor pool.


  ## 💡 Key Insights & Findings
* **Critical Stock Alert:** Visualizations highlight that specific negative or rarer blood groups face low stock counts, signaling a need for targeted donor drives.
* **Seasonal Peaks:** The Donation Over Time chart indicates significant drops/peaks in certain months (e.g., April drops vs. June peaks), allowing the bank to plan inventory safeguards in advance.
* **Eligibility Trends:** A significant percentage of potential donors fall under temporary deferral/ineligibility status, pinpointing an opportunity to optimize communication on donor requirements before they visit.


## 🚀 How to View
1. Clone this repository to your local machine.
2. Ensure you have **Power BI Desktop** installed.
3. Open the `Student blood donation power bi project.pbix` file to interact with the dashboards.
