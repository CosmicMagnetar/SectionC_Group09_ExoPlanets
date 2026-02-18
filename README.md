# 🌌 Exoplanet Discovery Analytics  
### Data Visualization & Analytics (DVA) Capstone Project

---

## 📌 Project Information

- **Course:** Data Visualization and Analytics (DVA)  
- **Group Number:** 09  
- **Section:** C  
- **Project Title:** Understanding Exoplanet Discovery Patterns Using Data Analytics  

---

## 👥 Team Members

| S.No | Name             | Enrollment Number |
|-----:|------------------|-------------------|
| 1    | Krishna          | 2401010237 |
| 2    | Neeraj Singh     | 2401010297 |
| 3    | Satyam Singh     | 2401010430 |
| 4    | Rudraksh Rathod  | 2401010396 |
| 5    | Antik Mondal     | 2401010084 |
| 6    | Bineet Keshari   | 2401010130 |

---

## 🧠 Project Overview

The discovery of exoplanets (planets outside our solar system) has accelerated over the past few decades due to advancements in observational technology and detection methods. However, exoplanet datasets are heavily influenced by **observational bias, method feasibility, and technological constraints**.

This project analyzes historical exoplanet discovery data to identify:

- Which detection methods are most effective  
- How technology impacts discovery growth  
- What types of planets are over- or under-represented  
- Why discovery outcomes differ across methods  

The project follows an **industry-style analytics workflow**, transforming raw scientific data into **actionable insights** using structured data cleaning, KPI design, exploratory analysis, dashboarding, and recommendations.

---

## 🎯 Objectives

- Prepare raw astronomical data for reliable analysis  
- Identify discovery efficiency differences across detection methods  
- Analyze technology-driven discovery trends  
- Highlight observational bias in detected exoplanets  
- Build an interactive dashboard for decision support  
- Provide data-backed recommendations for future missions  

---

## 📂 Project Structure

├── Raw Dataset/
│ └── exoplanets_raw.csv
│
├── Cleaned Dataset/
│ ├── exoplanets_cleaned.csv
│ └── Cleaning_Log.md
│
├── Analysis & Pivot Tables/
│ ├── pivot_tables.xlsx
│ └── derived_columns.csv
│
├── Dashboard/
│ └── Exoplanet_Dashboard.png
│
├── Documentation/
│ ├── Project_Report.pdf
│ └── Contribution_Matrix.pdf
│
├── Presentation/
│ └── Final_Presentation.pptx
│
└── README.md

---

## 🧹 Data Cleaning & Preparation

The raw dataset contained several challenges common to scientific data:

- Scientific uncertainty values (± ranges, citations)
- Mixed numeric and text formats
- Inconsistent categorical labels
- High missing-value density
- Observational noise and bias

### Cleaning Actions Performed
- Extracted best-estimate numeric values
- Removed uncertainty ranges and textual clutter
- Standardized units (Mass, Radius, Distance, Temperature)
- Created derived analytical categories (Mass, Distance, Period, Star Type)
- Ensured planet-level uniqueness
- Documented all steps in a data dictionary

All cleaning and transformations were performed in **Google Sheets**, as required by the course.

---

## 📊 KPIs & Analytical Framework

The analysis was guided by decision-oriented KPIs:

- Discovery count by detection method  
- Discovery trend over time  
- Average planet mass by discovery method  
- Distance vs discovery feasibility  
- Detection bias across orbital and stellar characteristics  

These KPIs focus on **efficiency, bias, and scalability**, rather than simple descriptive statistics.

---

## 📈 Dashboard Overview

The final dashboard provides two analytical layers:

### Executive View
- Total exoplanets discovered  
- Average distance from Earth  
- Average host star temperature  
- High-level discovery patterns  

### Operational View
- Method-wise discovery dominance  
- Bias across mass, distance, and orbital period  
- Time-based discovery evolution  
- Interactive filters for detailed drill-down analysis  

The dashboard supports both **strategic overview** and **deep analytical exploration**.

---

## 💡 Key Insights

- Transit-based methods dominate discoveries due to high scalability  
- Discovery growth is driven primarily by technological advancements  
- Large and close-in planets are over-represented  
- Each detection method reveals a different subset of planets  
- Distance strongly limits detection diversity  

---

## 🧭 Recommendations

- Prioritize scalable transit survey missions  
- Use radial velocity techniques for targeted confirmation  
- Reserve imaging methods for distant, massive exoplanets  
- Invest in higher sensitivity detection instruments  
- Adopt hybrid detection strategies to reduce observational bias  

---

## ⚠️ Limitations & Future Scope

### Limitations
- Dataset reflects observational and technological bias  
- Incomplete physical parameters for many exoplanets  
- Limited coverage of post-2009 discoveries  

### Future Scope
- Integration of newer mission data (Kepler, TESS, JWST)  
- Detection probability and bias-correction modeling  
- Advanced habitability analysis  
- Real-time dashboard expansion  

---

## 🛠️ Technologies Used

- Google Sheets (Data cleaning, pivots, KPIs, dashboard)  
- Pivot Tables & Spreadsheet Functions  
- Looker Studio (optional visualization layer)  
- Markdown & PDF for documentation  
- PowerPoint for final presentation  

---

## 🚀 Getting Started

1. Review the raw dataset to understand original data complexity  
2. Follow the Cleaning_Log.md for transformation logic  
3. Explore pivot tables in the Analysis folder  
4. View the dashboard snapshot for insights  
5. Refer to the Project Report for full methodology  

---

## 🏁 Conclusion

This project demonstrates that exoplanet discovery data reflects **observational constraints and technological feasibility** more than true planetary abundance. By explicitly acknowledging bias and limitations, the analysis provides **realistic, decision-oriented insights** that can guide future space exploration strategies.

---
