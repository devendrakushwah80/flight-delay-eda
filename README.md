# Airline Delay Cause Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on airline flight delay data to understand the **primary causes of arrival delays** and their relationships with different operational factors.

The analysis focuses on identifying:
- Common delay reasons
- Correlation between delay causes and arrival delays
- Patterns in airline operational performance

This project is intended as a **learning-focused EDA notebook** and a **foundation for future predictive modeling**.

---

## 📊 Dataset Description
Dataset Link :- https://www.kaggle.com/datasets/abdelazizel7or/airline-delay-cause
The dataset contains aggregated airline delay statistics, including:

- `arr_delay` – Total arrival delay (minutes)
- `arr_del15` – Number of flights delayed by 15+ minutes
- `carrier_delay` – Delay due to airline carrier
- `weather_delay` – Delay caused by weather conditions
- `nas_delay` – Delay from National Airspace System
- `security_delay` – Delay due to security reasons
- `late_aircraft_delay` – Delay from late-arriving aircraft
- `carrier_ct`, `weather_ct`, etc. – Count of delay occurrences
- Flight arrival and cancellation statistics

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plots

---

## 🔍 Steps Performed

### 1️⃣ Data Loading & Inspection
- Loaded CSV data using Pandas
- Checked dataset shape, columns, and data types
- Reviewed summary statistics

### 2️⃣ Data Quality Checks
- Missing value analysis
- Duplicate record detection

### 3️⃣ Exploratory Data Analysis
- Correlation matrix for numeric features
- Heatmap visualization to understand relationships
- Distribution analysis using histograms
- Pair plots for selected delay variables

### 4️⃣ Visualization & Insights
- Scatter plots between delay counts and arrival delays
- Comparison of different delay causes
- Identification of frequently occurring delay types

---

## 📈 Key Insights
- **Carrier and NAS delays** occur most frequently compared to other causes
- **Arrival delays show moderate correlation** with operational delay counts
- Weather-related delays are less frequent but can have significant impact
- Multiple delay causes often contribute simultaneously to arrival delays

---

## 📂 Project Structure
├── Airline_Delay_Cause_EDA.ipynb
├── Airline_Delay_Cause.csv
└── README.md


---

## 🚀 Future Improvements
- Feature engineering for predictive modeling
- Time-based analysis (monthly / yearly trends)
- Machine learning models to predict arrival delays
- Advanced visualization dashboards

---

## 📚 Learning Outcome
This project strengthened understanding of:
- Real-world EDA workflow
- Correlation analysis and visualization
- Interpreting operational aviation data

---

## 👤 Author
**Devendra Kushwah**  
Aspiring Data Analyst / Machine Learning Enthusiast
