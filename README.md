# IBM_Capstone_project
# 🌐 Survey-Based Technology Trends Dashboard (IBM Cognos Project)

This project explores global technology usage and developer preferences using a dataset derived from a comprehensive developer survey. The data was analyzed, cleaned, and visualized through interactive dashboards built in **IBM Cognos Analytics**.

---

## 📁 Project Contents

- 📊 **Survey Dashboard** (PDF Report)
- 📈 IBM Cognos Dashboard Screenshots
- 🧹 Cleaned Dataset (Excel)
- 🧠 Executive summary & findings (PowerPoint-ready content)

---

## 📌 Dataset Used

**Original Dataset Name:** `survey_data_updated 5.csv`  
**Source:** Provided with the course assignment  
**Original Format Issues:**  
Several columns contained **multi-select answers** separated by `;` (e.g., languages, databases, platforms, web frameworks).

---

## 🔧 Data Cleaning (Fixes Made for Cognos)

To prepare the data for Cognos Analytics:

- Cleaned multi-select fields by **splitting values into individual rows**:
  - `LanguageHaveWorkedWith`
  - `LanguageWantToWorkWith`
  - `DatabaseHaveWorkedWith`
  - `DatabaseWantToWorkWith`
  - `PlatformHaveWorkedWith`
  - `PlatformWantToWorkWith`
  - `WebframeHaveWorkedWith`
  - `WebframeWantToWorkWith`
- Removed blank values and standardized formatting.
- Compiled all cleaned data into an Excel workbook (`Cognos_Final_Prepared_Data.xlsx`) with separate sheets for each category.

---

## 📊 IBM Cognos Dashboard Tabs

1. **Current Technology Usage**
   - Top 10 Languages, Databases, Platforms, Web Frameworks
2. **Future Technology Trends**
   - Most Desired Languages, Databases, and Tools
3. **Demographics**
   - Age, Country, and Education Level insights

👉 **Dashboard Link:**  
📎 [View Cognos Dashboard](https://us3.ca.analytics.ibm.com/bi/?perspective=dashboard&id=iB33336341DF241D6A2D8FF856CD9F24B)

---

## 🔍 Key Findings

- JavaScript, Python, and SQL are the most widely used technologies.
- TypeScript and Rust are gaining popularity among future tools.
- PostgreSQL and MySQL dominate current database usage.
- Cloud platforms (AWS, Azure) and frameworks like React and Vue.js are preferred.
- Developers are highly educated, mostly aged 25–34.

---

## 🧠 Insights for Organizations

- Align hiring and training with current dominant tools.
- Begin preparing teams for emerging technologies.
- Rethink curriculum and workforce development strategy accordingly.

---

## 📤 How to Reuse

You may reuse this project structure or cleaned dataset to build additional dashboards using:
- IBM Cognos Analytics
- Google Looker Studio
- Tableau or Power BI

---

## 📄 License

Open for educational use. Please credit this repository if used in public-facing work.
