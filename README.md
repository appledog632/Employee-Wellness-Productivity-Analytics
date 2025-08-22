# Employee Wellness & Productivity Dashboard (Power BI)

## Project Overview
This project designs an **interactive Power BI dashboard** that explores the relationship between **employee wellness and workplace productivity**.  
By integrating HR, absenteeism, healthcare, and remote work datasets, the dashboard reveals insights into how stress, health, and workload influence organizational efficiency.

---

## Objectives
- Identify trends in **absenteeism** and stress-related leaves.  
- Analyze the effect of **workload and overtime** on productivity.  
- Track **healthcare costs** and suggest preventive wellness programs.  
- Predict **attrition risk** by department/role and highlight burnout factors.  
- Compare **engagement & balance** metrics across workforce segments.  

---

## Data Sources
The dashboard uses multiple public datasets (for academic/demo use only):

1. [IBM HR Analytics – Employee Attrition & Performance (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-employee-attrition-performance)  
2. [Absenteeism at Work Dataset (UCI)](https://archive.ics.uci.edu/dataset/203/absenteeism+at+work)  
3. [Health Insurance Claims – Synthetic Data (Kaggle)](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
4. [Remote Work & Mental Health Survey (Kaggle)](https://www.kaggle.com/datasets/blurredmachine/remote-work-and-mental-health)  
5. [Microsoft Human Resources Sample (Official)](https://learn.microsoft.com/en-us/power-bi/sample-human-resources) *(optional reference)*  

> ⚠️ Note: Datasets come from different sources and are **logically integrated** (via Date/aggregates), not at individual employee level.

---

## Dashboard Features
### 1. **Overview Page**
- KPIs: Absenteeism Hours, Avg Absence per Employee, Total Claims, Avg Claim, Attrition Rate, Overtime %, Avg Work-Life Balance.  

### 2. **Absenteeism Analysis**
- Trends of sick/stress leaves.  
- Reasons grouped into categories (mental, respiratory, injury, etc.).  
- Seasonal absence patterns.  

### 3. **Workload vs Productivity**
- Scatter: workload vs. performance hit target.  
- Distribution of overtime & its link to productivity.  

### 4. **Healthcare Costs**
- Medical claim trends over time.  
- Cost distribution by claim type.  
- Insights into preventive wellness impact.  

### 5. **Attrition Prediction**
- Attrition rates by department, job role, and overtime.  
- Key Influencers visual to show top drivers of attrition.  

### 6. **Engagement & Balance**
- Work-life balance vs. job satisfaction (IBM HR).  
- Mental health trends in remote work dataset.  
