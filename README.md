# 🗽 NYC 311 Service Requests Analysis Using Python & Power BI

## 📌 Project Overview

This project analyzes the **NYC 311 Service Requests** dataset using **Python** and **Power BI** to identify complaint patterns, service demand, agency workload, borough-wise distributions, reporting channels, and geographic hotspots.

The project includes:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Statistical Analysis
- Data Visualization
- Interactive Power BI Dashboard
- End-to-End Automation Workflow using **n8n + Python + Google Sheets + Power BI**

---

## Problem Statement

New York City's 311 service receives thousands of public service requests every day. These requests cover different types of complaints across multiple city departments. Analyzing this data helps identify common issues, understand complaint trends, compare service demand across boroughs, evaluate agency workload, and find complaint hotspots. This project uses Python to analyze the NYC 311 Service Requests dataset and provide insights that support better decision-making and improve public services.

---

# 📂 Dataset

| Details | Value |
|---------|-------|
| Dataset | NYC 311 Service Requests |
| Source | NYC Open Data Portal |
| Records | **500,000** |
| Features | **23 Columns** |
| File Type | CSV |

---

# 📁 Project Files

📂 **Google Drive**

This drive contains:

- ✅ Raw Dataset
- ✅ Final Cleaned Dataset
- ✅ Google Colab Notebook
- ✅ Python Source Code
- ✅ Project Report
- ✅ Power BI Dashboard Files

**Drive Link**

👉 https://drive.google.com/drive/folders/1Q9d4fv4l2_PndqP8LEvf_bjfwsVpCBZk?usp=sharing

---

# 🎯 Objectives

- Analyze major public service issues.
- Identify the top complaint categories.
- Compare complaint distribution across boroughs.
- Evaluate agency-wise workload.
- Analyze request trends and current request status
- Analyze reporting channels.
- Identify complaint hotspots.

---

# 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab
- Power BI
- n8n
- Google Sheets
- Git
- GitHub

---

# 🧹 Data Preprocessing

- Performed Exploratory Data Analysis (EDA)
- Checked missing values
- Removed duplicate records
- Converted date columns
- Removed invalid latitude & longitude values
- Removed unnecessary columns
- Handled missing values
- Created new engineered features

### Feature Engineering

- Complaint State
- Year
- Month
- Month Name
- Day
- Day Name
- Hour

---

# 📈 Statistical Analysis

## Measure of Central Tendency

- Mean Daily Requests: **10,414**
- Median: **10,889**
- Most days recorded **10K–11K** requests.
- Demand remained consistent throughout the analysis.

| Metric | Value |
|---------|-------|
| Mean | **10,414.09** |
| Median | **10,889** |
| Mode | **21** |

<img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/aa686f69-84d7-4bb1-9de1-73fcf85129a5" />

---

## Daily Request Variability

Daily Service Request Variation
- Moderate variation in daily requests.
- Most values remained within one standard deviation.
- Stable service demand across the analysis period.


| Metric | Value |
|---------|-------|
| Variance | **5,526,419.08** |
| Standard Deviation | **2,350.90** |

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/b4268f58-28f9-4c8e-8011-5e3944f91170" />

---

## Agency Workload

Agency-wise Service Request Distribution
- Large variation across agencies.
- Few agencies handled most requests.
- Supports workload balancing.


| Metric | Value |
|---------|-------|
| Variance | **4,029,909,858.57** |
| Standard Deviation | **63,481.57** |

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/2fa9ac79-1d15-423b-936c-0e3028c761c4" />

---

## Distribution Analysis

Reporting Channel Distribution
- Online reporting dominated.
- Phone and Mobile were also popular.
- Digital reporting is the preferred method.

| Metric | Value |
|---------|-------|
| Skewness | **0.743** |
| Kurtosis | **1.716** |

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/9d900ab2-2ed4-4d27-a06c-57451ccbc1e3" />

---

## 5️⃣ Top 10 Complaint Types

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/7234426d-8243-4a7b-a7e8-adca00535ed2" />

| Complaint Type | Requests |
|---------------|---------:|
| Illegal Parking | **82,944** |
| Noise – Residential | **53,673** |
| Noise – Street/Sidewalk | **35,304** |
| Blocked Driveway | **25K+** |
| Unsanitary Condition | High Volume |

### Summary

- Illegal Parking was the most common complaint.
- Noise-related complaints ranked second and third.
- Parking and noise issues dominated NYC complaints.

---

## 6️⃣ Agency-wise Service Request Volumes

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/debb49db-0ff5-49eb-b3ca-37434747f9a4" />

| Agency | Requests |
|---------|---------:|
| NYPD | **244,377** |
| HPD | **70,943** |
| DSNY | **39,559** |

### Summary

- NYPD handled the highest workload.
- HPD ranked second.
- DSNY ranked third.

---

## 7️⃣ Service Request Status

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/74d5312f-e566-45fe-afc8-45a186f763b3" />

| Status | Requests |
|---------|---------:|
| Closed | **422,187** |
| In Progress | **36,618** |
| Open | **27,515** |

### Summary

- Majority of requests were successfully closed.
- Only a small percentage remained open.

---

## 8️⃣ Reporting Channels

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/c537cb54-057c-4aa9-90c3-290cdcffe7b4" />


| Channel | Requests |
|----------|---------:|
| Online | **228,945** |
| Phone | **117,856** |
| Mobile | **106,551** |
| Unknown | **36,110** |

### Summary

- Citizens preferred online reporting.
- Phone remained an important reporting channel.
- Mobile applications were also widely used.

---

## 9️⃣ Complaint Categories Across Boroughs

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/85b14455-e428-4ef3-9782-b7234d97f02f" />

### Summary

- Brooklyn recorded the highest complaint volume.
- Queens ranked second.
- Illegal Parking dominated every borough.
- Noise complaints were common across Bronx, Brooklyn, and Queens.
- Staten Island had the fewest requests.

---

## 🔟 Daily Service Request Trend

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/374de25d-b206-471c-8e34-c5af2561cd54" />

### Summary

- Daily requests remained stable.
- Peak observed during mid-June.
- Small spike during late May.
- Trend supports staffing and operational planning.

---

## 1️⃣1️⃣ Geographic Complaint Hotspots

<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/8fc96b69-e559-4af4-b48f-cf8c6a96986f" />

### Summary

- Complaint hotspots identified across NYC.
- Brooklyn and Queens showed the highest concentration.
- Geographic analysis supports resource allocation.

---

## 1️⃣2️⃣ Top Complaint Categories by Borough

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/5b93d4dd-68aa-47e7-a22f-7c3a6ecc2c42" />

### Summary

- Illegal Parking was the leading complaint.
- Brooklyn generated the highest number of complaints.
- Queens followed closely.
- Borough-wise analysis supports targeted service planning.

---

## 1️⃣3️⃣ Agency-wise Complaint Distribution Across Boroughs

<img width="700" height="450" alt="image" src="https://github.com/user-attachments/assets/cf01efc1-3fdc-4308-a5fb-391a37c35a57" />

### Summary

- NYPD handled the largest workload.
- HPD and DSNY followed.
- Brooklyn and Queens required more operational resources.

---

# 📊 Power BI Dashboard

<img width="999" height="600" alt="image" src="https://github.com/user-attachments/assets/3b7db19d-9b3f-4741-a404-ab41d5e0f467" />

Dashboard Includes:

- KPI Cards
- Top Complaint Types
- Agency-wise Analysis
- Request Status
- Reporting Channels
- Daily Trends
- Borough Analysis
- Geographic Map
- Interactive Filters

---

# 📌 Key Findings

- Processed **500,000** service requests.
- Analyzed **23** dataset features.
- Created **13 Python visualizations**.
- Built **1 Interactive Power BI Dashboard**.
- Developed an **Automated Reporting Workflow**.
- Illegal Parking was the most common complaint.
- Brooklyn and Queens had the highest complaint volumes.
- NYPD handled the largest workload.
- Most requests were successfully resolved.
- Online reporting was the preferred reporting channel.
- Geographic hotspot analysis identified high-demand service areas.

# 🤖 Project Extension – Automation Workflow

## 📌 Overview

As an extension of the **NYC 311 Service Requests Analysis** project, an end-to-end automation workflow was developed using **n8n, Python, Google Sheets, and Power BI** to automate data processing, reporting, and dashboard updates. This workflow minimizes manual effort, ensures data consistency, and provides up-to-date insights for decision-making.

---

## 🚀 Automation Workflow

```text
Schedule Trigger
        │
        ▼
Python Data Processing
        │
        ▼
Google Sheets Update
        │
        ▼
Power BI Dashboard Refresh
        │
        ▼
Updated Reports & Insights
```

---

## ✨ Key Features

- ✅ Automated data extraction and processing.
- ✅ Automated data updates to Google Sheets.
- ✅ Automated dashboard data refresh.
- ✅ Reduced manual intervention in reporting.
- ✅ Improved data accuracy and consistency.
- ✅ Increased reporting efficiency.
- ✅ Delivered up-to-date insights for analysis and decision-making.

---

## 🛠️ Tools Used

- n8n
- Python
- Google Sheets
- Power BI

---

## 📂 Automation Project Repository

To extend the NYC 311 Service Requests Analysis project, an end-to-end automation workflow was developed using **n8n, Python, Google Sheets, and Power BI**. The automation pipeline streamlines the complete reporting process by automatically extracting, processing, storing, and visualizing data, reducing manual effort and ensuring dashboards remain up to date.

Instead of manually cleaning data, updating spreadsheets, and refreshing dashboards, the workflow automates each step, enabling faster reporting and more reliable business insights.

Explore the complete automation workflow, implementation details, source code, and documentation:

🔗 **GitHub Repository**

**NYC 311 Service Requests Analytics Automation Pipeline (n8n + Python + Power BI)**

https://github.com/ShaliniSakthivel-DA/NYC-311-Service-Requests-Analytics-Automation-Pipeline-n8n-Python-PowerBI

---

## n8n Automation Workflow Image 

<img width="900" height="350" alt="image" src="https://github.com/user-attachments/assets/d97e0ad8-d0d1-4b26-8ab0-a1f1c190e07d" />

## 📁 Automation Files

The Google Drive folder contains:

- ✅ n8n Workflow
- ✅ Python Automation Code
- ✅ Google Sheets Integration Files
- ✅ Power BI Dashboard
- ✅ Automation Documentation
- ✅ Supporting Project Files

🔗 **Google Drive**

https://drive.google.com/drive/folders/1POY4G-dUzMokOqf6VHbHHbex1jTpyojD?usp=sharing

---

## 📈 Automation Benefits

- Reduced manual reporting effort.
- Improved workflow efficiency.
- Automated dashboard updates.
- Faster reporting and analysis.
- Better data accuracy.
- Scalable and reusable automation pipeline.

---

# 👩‍💻 Author

**Shalini Sakthivel**

**Skills**

- Python
- SQL
- Power BI
- Tableau
- Excel
- Data Analytics
- n8n Automation

**LinkedIn**

https://www.linkedin.com/in/shalini-sakthivel-b5b6ba18a/

**GitHub**

https://github.com/ShaliniSakthivel-DA
