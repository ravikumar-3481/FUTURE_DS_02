# 📊 Facebook Ads Campaign Performance Analysis  

<p align="center">
  <img width="1100" height="500" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Dashboard.jpg" alt="Facebook Ads Dashboard Overview">
</p>

---

## 🧠 Project Overview  
Businesses invest heavily in social media advertising, yet many struggle to answer key performance questions:

- Are the campaigns actually performing well?  
- Which ads generate the most engagement and conversions?  
- How efficiently is the ad spend utilized in terms of CTR and ROI?  
- Where should the marketing budget be reallocated for better outcomes?  

This project analyzes **Facebook Ads Campaign data** to uncover actionable insights and visualize them through an **interactive Power BI dashboard**.  
The goal is to empower **data-driven marketing decisions** and **optimize ad performance**.

---

## 🗂️ Dataset Information  
- **Source:** [Kaggle – Facebook Ad Campaign Dataset](https://www.kaggle.com/datasets/madislemsalu/facebook-ad-campaign)  
- **Size:** 761 rows × 15 columns  
- **Key Fields:** `impressions`, `clicks`, `spent`, `total_conversion`, `approved_conversion`  

---

## 🛠️ Tools & Technologies  
- **Python:** Data cleaning, EDA, and metrics computation (`Pandas`, `Matplotlib`, `Seaborn`)  
- **Power BI:** Interactive dashboard creation and KPI tracking  
- **Jupyter Notebook:** Exploratory analysis and visualization  

---

## 🚀 Project Workflow  

### **1️⃣ Data Cleaning & Preparation**
- Fixed **misaligned entries** and ensured data consistency via Google Sheets.  
- Converted **date fields** to `datetime` format.  
- Handled **missing values** and removed **duplicates**.  
- Engineered new metrics:  
  - CTR (Click-Through Rate)  
  - CPC (Cost per Click)  
  - CPA (Cost per Acquisition)  
  - ROI (Return on Investment)  
  - Conversion Rate  

---

### **2️⃣ Exploratory Data Analysis (EDA)**  
- Descriptive statistics and value distributions.  
- Engagement analysis across impressions, clicks, and conversions.  
- Performance segmentation by **age** and **gender** demographics.  

---

### **3️⃣ Dashboard Design (Power BI)**  
- KPI summary: *Impressions, Clicks, Spend, Conversions, CTR, ROI, CPA*  
- Engagement insights: *Top ads by CTR and conversions*  
- Demographic breakdowns: *CTR by Age, ROI by Gender, CPA by Age*  
- ROI vs CTR correlation visualization  

---

## 📈 Visual Insights  

### 🔹 Power BI Dashboard  
<p align="center">
  <img width="1100" height="500" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Dashboard.jpg" alt="Power BI Dashboard">
</p>

---

### 🔹 Jupyter Notebook Visuals  

**CTR Distribution Across Ads**  
<p align="center">
  <img width="570" height="352" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Ctr.png" alt="CTR Distribution">
</p>

**Average CPA by Gender**  
<p align="center">
  <img width="420" height="347" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Cpa.png" alt="CPA by Gender">
</p>

**CTR vs ROI Relationship**  
<p align="center">
  <img width="530" height="402" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Screenshot%202025-10-23%20000433.png" alt="CTR vs ROI">
</p>

**Average CPA by Age Group**  
<p align="center">
  <img width="532" height="355" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Screenshot%202025-10-23%20000512.png" alt="CPA by Age Group">
</p>

**Spend vs Approved Conversions**  
<p align="center">
  <img width="768" height="493" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Screenshot%202025-10-23%20000547.png" alt="Spend vs Conversions">
</p>

**ROI by Gender**  
<p align="center">
  <img width="422" height="350" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Screenshot%202025-10-23%20000612.png" alt="ROI by Gender">
</p>

**CTR by Age Group**  
<p align="center">
  <img width="546" height="363" src="https://github.com/ravikumar-3481/FUTURE_DS_02/blob/main/Images/Screenshot%202025-10-23%20000634.png" alt="CTR by Age Group">
</p>

---

## 💡 Key Insights  
- The campaign delivered **78M+ impressions**, **11K+ clicks**, and **585 conversions**.  
- CTR remained **very low (0.01%)**, indicating low engagement despite massive reach.  
- Some ads (e.g., **Ad ID 1121206**) achieved **exceptional ROI (~34x)** with modest spend.  
- The **30–34 age group** and **male demographic** performed best in terms of ROI.  

---

## 🎯 Recommendations  
- Run **A/B testing** on creatives to boost CTR.  
- **Reallocate budget** to high-ROI ads and target high-performing demographics.  
- Optimize **landing pages** to lower CPA.  
- Implement **real-time KPI monitoring** (CTR, CPC, ROI) for continuous optimization.  

---

## 🧾 Conclusion  
The analysis reveals a significant gap between **reach** and **engagement**.  
While the campaign achieved massive visibility, **click-through and conversion rates** remained underwhelming.  
However, identifying **high-ROI ads** and **profitable audience segments** enables marketers to **optimize budget allocation** and **improve ROI efficiency**.  

This project demonstrates how **data analytics** can turn raw ad data into **strategic marketing insights**, enabling smarter decisions and higher campaign performance.

---

## 📁 Project Structure  
```bash
├── Data/
│   └── data.csv              
├── Images/                    
│   ├── Ctr.png
│   ├── Cpa.png
│   ├── Screenshot_2025-10-23_000433.png
│   ├── Screenshot_2025-10-23_000512.png
│   ├── Screenshot_2025-10-23_000547.png
│   ├── Screenshot_2025-10-23_000612.png
|   ├── insights.png
|   ├── dashboard.jpg
│   └── Screenshot_2025-10-23_000634.png
├── index.ipynb                
├── Facebook Ads Report.pbix
├── FinalData.csv             
└── README.md
 
```
### 🧑‍💻 Aurhor
**Ravi Vishwakarma**
🔗 [**Linkedin**](https://www.linkedin.com/in/ravi-vishwakarma67)
🔗 [**Portfolio**](https://profileravi.vercel.app)
🔗 [**Github**](https://github.com/ravikumar-3481)
