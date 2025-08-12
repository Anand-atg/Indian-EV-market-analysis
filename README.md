# Indian EV Market Analysis – Power BI Report

## 📌 Overview
This Power BI report provides **strategic insights** into the Electric Vehicle (EV) market in India.  
It analyzes sales trends, market share by manufacturers, vehicle type distribution, and geographic adoption patterns to guide decision-making for manufacturers, investors, and policymakers.

The report focuses on **AtliQ Motors** – a leading U.S. EV manufacturer aiming to expand from a **<2% market share in India** to a significant presence.

---

## 📊 Data Sources
The dataset includes:

- **Sales Data:** Monthly and yearly EV sales (FY 2022–2024)
- **Manufacturer Data:** Market share and sales segmented by manufacturer
- **Vehicle Type:** 2-wheelers vs 4-wheelers distribution
- **Revenue Growth:** Calculated from CAGR and penetration trends
- **Geographic Insights:** State-wise EV adoption and penetration rates

---

## 🔄 ETL Process
Before building the dashboard, the dataset was cleaned and transformed:

1. **Extract** – Imported CSV files into Excel & Power BI  
2. **Transform** –  
   - Removed duplicates & handled missing values  
   - Standardized date formats, state names, and categories  
   - Merged multiple datasets into a unified model  
   - Applied correct data types for accuracy  
3. **Load** –  
   - Created a **Star Schema** in Power BI  
   - Added DAX measures & calculated columns for KPIs

---

## 🔍 Key Insights
- **EV Penetration:** National average is **3.6%**; Goa leads with **9.8%**
- **Top Players:**  
  - 2W: Ola, TVS  
  - 4W: Tata Motors, M&M  
- **Seasonality:** March consistently records **peak sales**
- **Growth:** 4W CAGR is higher than 2W despite smaller volumes
- **Manufacturing Location:** Tamil Nadu identified as the optimal hub

---

## 📈 Dashboard Features
- **Sales Trends:** Year-on-year and month-on-month growth
- **Market Share Analysis:** Interactive visuals for top brands
- **Vehicle Segment Comparison:** 2W vs 4W patterns
- **Geographic View:** State-wise penetration rates and hotspots
- **KPIs:** Revenue growth, CAGR, penetration rate, sales volume

---

## 💡 Recommendations
1. **Competitive Pricing & Financing** – Attractive loan & EMI options  
2. **Localized Models & Awareness Campaigns** – Tailor products for Indian consumers  
3. **Infrastructure Development** – Expand charging network before scaling sales

---

## 🛠 Tools Used
- **Power BI** – Data modeling & interactive visualization
- **DAX** – Custom calculations for KPIs
- **Excel** – Data cleaning & transformation
- **ETL Concepts** – Extract, Transform, Load


## Conclusion
This Power BI analysis offers comprehensive insights into the Indian EV market, covering essential metrics for understanding growth, competition, and regional demand. It serves as a valuable resource for automotive companies, investors, and policymakers to evaluate and strategize for the Indian EV landscape. 
