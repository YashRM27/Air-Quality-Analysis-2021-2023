# # 🌍 Air Quality Analysis (2021–2023)

## ## 📌 Overview

This project analyzes Air Quality Index (AQI) and pollutant concentrations across multiple Indian states and cities from **2021 to 2023**.
It includes complete **data cleaning, analysis, visualization**, and a final **Power BI dashboard**.

---

# ## 🧰 Tools & Technologies

* **Python** (Pandas, Matplotlib)
* **Jupyter Notebook**
* **Power BI**
* **GitHub**
* **CSV datasets**

---

# ## 📂 Project Structure

```
project-folder/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

# ## 🧹 Data Cleaning Summary

* Removed duplicates
* Handled missing values
* Renamed columns
* Fixed data types
* Grouped by State / City
* Calculated yearly averages for pollutants:

  * PM2.5
  * PM10
  * NO2
  * SO2

---

# ## 🔍 Exploratory Data Analysis (EDA)

The analysis covers:

### ✔ Top polluted states

### ✔ Least polluted cities

### ✔ Year-wise pollutant trends

### ✔ Pollutant correlations

### ✔ City-wise and state-wise comparisons

---

# ## 📈 Visualizations (Python)

* Line charts for yearly pollutants
* Bar charts for top 25 cities
* State-wise comparison plots
* Heatmap summary

---

# ## 📊 Power BI Dashboard

Includes:

* **Map visual** (pollution by state)
* **Top 10 polluted states**
* **Top 10 least polluted cities**
* **Year selector slicer**
* **KPIs** (Avg PM2.5, PM10, NO2, SO2)
* **Conditional formatting heatmap**

---

# ## 🖼 Screenshots

Add the images like this:

```
![Dashboard](images/dashboard.png)
![Map View](images/map_view.png)
```

---

# ## ⭐ Key Insights

* High pollution States or Union Territory: **Delhi, Bihar, Jharkhand, Uttar Pradesh**
* Low pollution States or Union Territory: **Mizoram, Sikkim, Arunachal Pradesh**
* PM10 is consistently higher than PM2.5
* Pollution slightly decreases from 2021 → 2023

---

# ## 🚀 How to Run This Project

### **1. Clone repository**

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

### **2. Install dependencies**

```bash
pip install pandas matplotlib
```

### **3. Open notebook**

```bash
jupyter notebook notebooks/analysis.ipynb
```

### **4. Open Power BI dashboard**

Load the `dashboard.pbix` file from the **powerbi** folder.

---

# ## 📌 Future Improvements

* Add real-time AQI API
* Add forecasting model (Prophet / ARIMA)
* Publish Power BI dashboard online

---

# ## 📧 Contact

For queries or feedback, feel free to reach out:
**Yash Mavare**
**Email:** [yashrmavare@gmail.com](mailto:yashrmavare@gmail.com)
**LinkedIn:** linkedin.com/in/yashmavare

---
