# Medical Appointment No-Shows Analysis (Excel-Based)

This project explores a real-world dataset of over 100,000 medical appointments in Brazil to understand the factors behind patients missing their scheduled visits. Missed appointments cause inefficiencies and financial losses in healthcare. Using **Microsoft Excel**, this project applies data cleaning, pivot analysis, KPIs, and dashboards to provide actionable insights.

---

## Tools & Technologies Used

- **Microsoft Excel**
  - Data Cleaning (Text to Columns, Date Formatting)
  - Formulas (`IF`, `IFS`, `COUNTIF`, `DATEDIF`, etc.)
  - Pivot Tables
  - Conditional Formatting
  - Data Visualization (Bar Charts, Pie Charts, Line Graphs)
  - Slicers and Filters
  - Dashboard Creation

---

## Dataset

- **Source**: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Features include**:
  - Patient Demographics: `Age`, `Gender`, `Neighborhood`
  - Appointment Details: `Scheduled Day`, `Appointment Day`
  - Health Conditions: `Diabetes`, `Hypertension`, `Alcoholism`
  - SMS Reminder: `SMS_received`
  - **Target Variable**: `No-show` (Yes/No)

---

## Workflow

### 1. Data Cleaning
- Removed duplicates and invalid records (e.g., negative ages)
- Cleaned `DateTime` formats (removed time component)
- Created new columns:
  - `Days_Waited` = `AppointmentDay - ScheduledDay`
  - `Is_Weekend` = Flag for weekend appointments

### 2. Exploratory Data Analysis (EDA)
- Used **Pivot Tables** to explore:
  - Show/No-show rates by `Gender`, `Age Group`, `Weekday`, `SMS_received`
  - Average waiting time by show status
  - No-show trends by week or region

### 3. KPIs & Dashboard
- Key Metrics:
  - Total Appointments
  - Total No-shows
  - No-show Rate %
  - Show-up Ratio by SMS, Day, and Gender
- Created an **interactive Excel dashboard** with:
  - Slicers for dynamic filtering
  - KPI cards
  - Visual charts and summaries

---

##  Insights

- Higher no-show rates seen among:
  - Patients with **same-day** or **long waiting periods**
  - Patients who **did not receive SMS reminders**
  - **Adults** and those from certain **neighborhoods**
  - **Scholarship patients** despite financial support

- **SMS reminders** significantly improve attendance

---

### ecommendations

- Send **SMS reminders** consistently  
- Avoid **same-day** or **long-delay** appointments  
- Prioritize **high-risk patients** on mid-week days (e.g., Tuesday/Wednesday)  
- Investigate and address **low-attendance neighborhoods**

---

## Project Goal

To support clinics and hospitals in **reducing appointment no-shows** by:
- Identifying key behavioral and scheduling patterns
- Offering Excel-based dashboards and reports for operational use

---

## Project Status

- Data Cleaning Completed  
- Pivot Table EDA Done  
- Dashboard Created  

---

##  Files Included

- `Medical_NoShow_Analysis.xlsx` – Main Excel file with:
  - Raw & Cleaned Data (separate sheets)
  - Pivot Tables
  - Dashboard Sheet
  - Calculated Fields and KPIs

---

## Author

**Bhaskar Bharati**  
📧 [vaskarv959@gmail.com](mailto:vaskarv959@gmail.com)  
🔗 [LinkedIn: bhaskar-bharati](https://www.linkedin.com/in/bhaskar-bharati/)

---

**If you found this helpful, consider starring the repo!**
