# 📊 Tamil Nadu District Development Index (TDDI) Dashboard

## 🧾 Overview
This project presents an interactive **Power BI dashboard** to analyze and compare the development levels of districts in Tamil Nadu using a custom-built **Tamil Nadu District Development Index (TDDI)**.

It combines multiple socio-economic indicators into a single composite score to uncover regional disparities and development patterns.

---

## 🎯 Objectives
- Build a **composite development index (TDDI)**  
- Analyze development across **38 districts of Tamil Nadu**  
- Identify **top and bottom performing districts**  
- Provide **data-driven insights** for decision-making

---

## 🧮 TDDI Formula
TDDI =  0.2 x Education Index + 0.3 x Health Index + 0.2 x Infrastructure Index + 0.3 x Economic Index

---
## 📐 Index Calculation Methodology

### 📚 Education Index or Literacy
Education Index = Literacy rate of each district 

### ⚕️ Health Index
Health Index = Health Index = (Normalized Hospitals + Normalized IMR) / 2

where Normalized Hospitals is Number of Hospitals per Lakh Population.<br>
Hospitals per Lakh = (Total Number of Hospitals / Total Population) * 100000.<br>
And Infant Mortality Rate (IMR) is child survival per 1,000 live births.<br>
Infant Mortality Rate = (Number of Deaths Under 1 Year of Age / Total Number of Live Births) * 1000.

### 💰 Economic Index
Economic Index = (Per Capita Income - Min Per Capita Income) / (Max Per Capita Income - Min Per Capita Income)


### 🏗️ Infrastructure Index
Infrastructure Index = Electricity + Sanitation / 2

Where Electricity is Percentage of houses with Electical connection.<br>
And Sanitation is Percentage of houses with laterine.<br>


### 🔢 Normalization (Min-Max Scaling)
All indicators are converted to a 0–100 scale:

Normalized Value = (X - X_min) / (X_max - X_min)

Where:
- X = District value  
- X_min = Minimum value  
- X_max = Maximum value  

---
### ⚖️ Assumptions
- Equal weight for all indicators  
- Normalization removes scale differences  
- Higher score = higher development  

---

## 📊 Dashboard Features
- KPI Cards (Average TDDI, Top District, Bottom District)  
- District-wise comparison (Bar Charts)  
- Pillar-wise analysis (Education or Literacy, Health, Infrastructure, Economy)  
- Interactive slicers (District filtering)  
- Scatter plot for relationship analysis  
- Insights section  

---

## 🖼️ Dashboard Preview
<img width="972" height="532" alt="IMG_20260517_110530" src="https://github.com/user-attachments/assets/89483deb-bc74-4455-89d9-29fa27eb6efc" />


---

## 🛠️ Tools Used
- Power BI  
- DAX  
- Microsoft Excel  

---

## 🔑 Key Insights
- Chengalpattu shows highest development while kallakurici is lowest  
- Some districts lag mainly in Literacy and Economy
- Strong relationship between income and development  

---

## 🚀 How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers to explore district-level insights  
4. Interact with visuals  

---

## 📂 Project Structure
Tamil-Nadu-TDDI-Dashboard  
│── TN development index dashboard.pbix  
│── README.md  
│── Dataset  

---

## ⭐ Support
If you found this useful, consider giving a ⭐ to the repository!
