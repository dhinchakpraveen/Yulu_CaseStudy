# Yulu - Demand for Shared Electric Cycles

This project investigates **factors influencing the demand for Yulu's shared electric cycles** in the Indian market.  
By analyzing rental data, the project identifies key variables impacting usage and provides recommendations to optimize service offerings.

---

## 📌 Business Problem

Yulu has experienced **revenue dips** and seeks to understand:

- What factors influence rental demand  
- How seasonality, weather, and working days impact usage  
- Data-driven strategies to **boost utilization and revenue**  

This project aims to:  

- Identify **key demand factors**  
- Perform **statistical analysis** on influencing variables  
- Provide **actionable insights** for service optimization  

---

## 📊 Dataset

The dataset: **`yulu_data.csv`** contains detailed rental information.  
Key features include:

- **Datetime Variables**:  
  - `datetime`: Date and time of rental  
  - `season`: Season (1 = Spring, 2 = Summer, 3 = Fall, 4 = Winter)  
  - `holiday`: 0 = Not a holiday, 1 = Holiday  
  - `workingday`: 0 = Weekend/Holiday, 1 = Workday  

- **Weather & Environmental Factors**:  
  - `weather`: (1 = Clear, 2 = Mist, 3 = Light Rain/Snow, 4 = Heavy Rain/Snow)  
  - `temp`: Temperature (°C)  
  - `atemp`: Feeling temperature (°C)  
  - `humidity`: Humidity (%)  
  - `windspeed`: Wind speed  

- **Rental Counts**:  
  - `casual`: Number of rentals by casual users  
  - `registered`: Number of rentals by registered users  
  - `count`: Total rentals (casual + registered)  

---

## 🏗️ Project Structure

The case study covers the following steps:

1. **Data Exploration**  
   - Inspect dataset structure and characteristics  
   - Handle missing values and outliers (if present)  

2. **Feature Relationships**  
   - Analyze relationships between rental demand (`count`) and independent variables (season, weather, workingday, etc.)  

3. **Statistical Testing**  
   - Apply **t-tests**, **ANOVA**, and **Chi-square tests**  
   - Assess the significance of demand differences across categories  

4. **Insights & Recommendations**  
   - Identify patterns in rental demand  
   - Suggest strategies for **improving service offerings**  

---

## 📈 Outcome

- **Key Demand Factors**  
  - Identification of significant variables influencing shared cycle usage  

- **Statistical Analysis**  
  - Hypothesis testing results on the influence of working days, seasons, and weather conditions  

- **Actionable Insights**  
  - Recommendations for **optimizing availability and pricing** based on demand patterns  

---

## 🚀 Future Work

- Incorporate **time-series forecasting models** (ARIMA, Prophet, LSTMs)  
- Use **machine learning regression models** for demand prediction  
- Build a **dashboard** for real-time demand monitoring  

---

## 📂 Repository Contents

- `notebooks/` → Data exploration, statistical tests, and visualization  
- `scripts/` → Python scripts for preprocessing and analysis  
- `README.md` → Project documentation  

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit a pull request.  

---

## 📜 License

This project is licensed under the **MIT License**.  
