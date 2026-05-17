# 🏥 Healthcare Hospital Dashboard

> **Power BI analytics dashboard** built on a comprehensive healthcare dataset — analyzing patient demographics, diagnosis trends, treatment outcomes, billing, and hospital operational metrics.

---

## 📌 Project Overview

This project transforms raw healthcare records into a clean, interactive Power BI dashboard that helps hospital stakeholders track:

- Patient demographics and admission patterns
- Most common diagnoses and medical conditions
- Length of stay distribution
- Billing amounts and insurance coverage breakdown
- Treatment outcome trends across doctors and departments

---

## 🗂️ Repository Structure

```
📦 healthcare-hospital-dashboard
 ┣ 📁 Images/                        # Dashboard screenshots
 ┣ 📊 healthcare_dataset.xlsx        # Source dataset
 ┣ 📊 Hospital_DashBoard.pbix        # Power BI dashboard file
 ┗ 📄 README.md
```

---

## 📦 Dataset Overview

The `healthcare_dataset.xlsx` contains patient-level records including:

| Column | Description |
|---|---|
| `Patient Name` | Patient identifier |
| `Age` | Patient age |
| `Gender` | Male / Female |
| `Blood Type` | Patient blood group |
| `Medical Condition` | Primary diagnosis |
| `Date of Admission` | Hospital admission date |
| `Doctor` | Attending doctor |
| `Hospital` | Hospital name |
| `Insurance Provider` | Insurance company |
| `Billing Amount` | Total billed amount |
| `Room Number` | Assigned room |
| `Admission Type` | Emergency / Elective / Urgent |
| `Discharge Date` | Date of discharge |
| `Medication` | Prescribed medication |
| `Test Results` | Normal / Abnormal / Inconclusive |

---

## 🔧 Tools Used

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard, data modeling, DAX |
| **Microsoft Excel** | Source data |

---

## 📊 Dashboard Highlights

**KPI Cards**
- Total Patients
- Average Billing Amount
- Average Length of Stay (Days)
- % Abnormal Test Results

**Visuals**
- Patient count by medical condition (bar chart)
- Admission type breakdown — Emergency / Elective / Urgent (donut)
- Billing amount by insurance provider (bar chart)
- Age group distribution of patients (histogram)
- Test result outcomes by condition (stacked bar)
- Gender split across conditions (grouped bar)
- Monthly admission trend (line chart)
- Top doctors by patient volume (table)

**Slicers**
- Medical condition
- Admission type
- Insurance provider
- Gender
- Date range

---

## 💡 Key Insights

- **Emergency admissions** have the highest average billing amounts
- Certain medical conditions show significantly higher rates of **abnormal test results**
- Average length of stay differs meaningfully across **admission types**
- Some insurance providers are concentrated in specific **age bands**
- Top 3 doctors handle a disproportionate share of total patient volume

---

## 🚀 How to Use

1. Open **Power BI Desktop**
2. Load `healthcare_dataset.xlsx` via **Get Data → Excel**
3. Open `Hospital_DashBoard.pbix`
4. Refresh data source if prompted

---

## 👤 Author

**[Your Name]**
[LinkedIn](https://linkedin.com/in/yourprofile) · [Portfolio](https://yourportfolio.com) · [Email](mailto:you@email.com)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*Data used for educational and analytical purposes only.*
