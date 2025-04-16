# Medical Appointment No-Shows Prediction

This project analyzes a real-world dataset of over 100,000 medical appointments in Brazil to predict whether a patient will show up for their scheduled appointment. Missed appointments can lead to operational inefficiencies and increased healthcare costs. By leveraging data analysis and machine learning, this project aims to uncover patterns in patient behavior and provide insights to reduce no-shows.

---

## Tools & Technologies Used

- **Python** (pandas, numpy)
- **Data Visualization:** matplotlib, seaborn
- **Machine Learning:** scikit-learn (Logistic Regression, Random Forest, etc.)
- **SQL (DuckDB)** – for optional SQL-style queries
- **Jupyter Notebook**

---

## Dataset

- **Source:** [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- Contains features like:
  - Patient demographics (age, gender, neighborhood)
  - Scheduled and appointment dates
  - Health conditions (diabetes, hypertension)
  - SMS reminders
  - Target variable: `No-show` (Yes/No)

---

## Project Workflow

1. **Data Cleaning**
   - Handled date formatting, column renaming, and missing values
   - Encoded categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Analyzed attendance trends by age, gender, health conditions, SMS reminders
   - Created new features like `days_between_scheduling` and `is_weekend`

3. **Feature Engineering**
   - Created meaningful input features for modeling
   - Checked feature correlation and importance

4. **Modeling**
   - Trained classification models: Logistic Regression, Random Forest
   - Evaluated using Accuracy, Precision, Recall, and Confusion Matrix

5. **Business Insight**
   - Identified top factors influencing no-shows (e.g., long scheduling gaps, missed SMS)
   - Suggested strategies to reduce appointment no-shows

---

## Visualizations
- No-show rates by age, SMS received, and appointment weekday
- Distribution plots of scheduling gaps
- Feature importance (bar charts)

---

## Project Goal

To support hospitals and clinics in reducing missed appointments by predicting at-risk patients and improving communication or scheduling strategies through data.

---

## Status

  In Progress – EDA, Feature Engineering, and Baseline Modeling Complete  
  Upcoming – Model optimization, visualization improvements, and deployment planning

---

## Contact

**Bhaskar Bharati**  
📧 Email: [vaskarv959@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/bhaskar-bharati/]  
