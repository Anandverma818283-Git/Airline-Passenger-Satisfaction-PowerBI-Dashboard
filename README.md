# ✈️ Airline Passenger Satisfaction — Power BI Data Analysis

## 📌 Project Overview

This project analyzes **129,880 airline passenger records** to identify the key factors that influence customer satisfaction.

Using **Power BI** and **Power Query**, the project explores passenger demographics, travel classes, customer types, service quality, online services, and flight delays to uncover patterns and differences between **satisfied** and **neutral/dissatisfied** passengers.

The interactive dashboard provides a clear overview of passenger satisfaction and highlights the services that have the strongest relationship with the overall passenger experience.

---

## 🛠️ Tools & Technologies

* **Power BI** — Data visualization and dashboard development
* **Power Query** — Data cleaning and transformation
* **CSV** — Data source and data dictionary
* **DAX** — Measures and calculations

### 📂 Data Sources

* `airline_passenger_satisfaction.csv` — Main passenger dataset
* `data_dictionary.csv` — Dataset column definitions

---

## 📊 Dashboard Overview

### 1️⃣ Demographics & General Satisfaction

This dashboard provides a high-level overview of the passenger population and overall satisfaction levels.

![General Satisfaction](Dashboard%20Images/Screenshot%202026-09-25%20053758.png)

### 📌 Key Metrics

| Metric                       |           Value |
| ---------------------------- | --------------: |
| 👥 Total Passengers          |     **129,880** |
| 😊 Average Satisfaction Rate |      **43.45%** |
| 🎯 Satisfaction Target       |      **80.00%** |
| 🎂 Average Age               |    **39 Years** |
| ✈️ Average Flight Distance   | **1,190 Miles** |

### 🔍 Key Insights

* **Travel Class:** Business class passengers have a noticeably higher satisfaction rate than Economy passengers.
* **Travel Type:** Passengers traveling for business purposes generally report higher satisfaction than passengers traveling for personal reasons.
* **Customer Loyalty:** Returning customers represent the majority of passengers, while a considerable portion are still neutral or dissatisfied.
* **Satisfaction Gap:** The current satisfaction rate of **43.45%** is significantly below the **80% target**, indicating substantial opportunities for service improvement.

---

### 2️⃣ Service Quality & Delay Analysis

This dashboard focuses on the relationship between **service quality, flight delays, and overall passenger satisfaction**.

![Service Quality](Dashboard%20Images/Screenshot%202026-09-25%20053839.png)

### 🔍 Key Insights

#### ⏱️ Delays vs. Satisfaction

Average departure and arrival delays are slightly higher among **neutral/dissatisfied passengers** compared with satisfied passengers.

#### 💻 Online Services

**Ease of Online Booking** and **Online Boarding** show clear differences between satisfied and dissatisfied passengers, highlighting the importance of a smooth digital travel experience.

#### 💺 In-flight Services

**Seat Comfort** and **In-flight Wi-Fi Service** are among the notable service factors that differentiate satisfied passengers from neutral/dissatisfied passengers.

#### ⭐ Overall Service Rating

The average overall service rating is:

* **Satisfied Passengers:** 4.00
* **Neutral/Dissatisfied Passengers:** 3.64

This difference indicates a clear relationship between passengers' perception of service quality and their overall satisfaction.

---

## 📈 Key Findings

The analysis highlights several factors associated with passenger satisfaction:

1. **Travel class** plays an important role, with Business passengers showing higher satisfaction than Economy passengers.
2. **Business travel** is associated with higher satisfaction compared with Personal travel.
3. **Online services** such as booking and boarding contribute to differences in passenger experience.
4. **Seat comfort and Wi-Fi service** are important areas of service quality.
5. **Flight delays** are slightly higher among neutral/dissatisfied passengers.
6. There is a significant gap between the current **43.45% satisfaction rate** and the **80% target**.

---

## 🚀 How to Use This Repository

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Explore the Data

Review:

```text
airline_passenger_satisfaction.csv
data_dictionary.csv
```

The data dictionary provides definitions and descriptions for the dataset columns.

### 3. Open the Power BI Dashboard

Open:

```text
Airline Passenger Satisfaction.pbix
```

using **Power BI Desktop**.

You can interact with the dashboard by:

* Applying filters
* Exploring passenger segments
* Comparing travel classes
* Analyzing satisfaction levels
* Exploring service quality
* Investigating delays and their relationship with satisfaction

---

## 📁 Repository Structure

```text
Airline-Passenger-Satisfaction/
│
├── 📊 Airline Passenger Satisfaction.pbix
│
├── 📂 Data/
│   ├── airline_passenger_satisfaction.csv
│   └── data_dictionary.csv
│
├── 📂 Dashboard Images/
│   ├── Screenshot 2026-09-25 053758.png
│   └── Screenshot 2026-09-25 053839.png
│
└── 📄 README.md
```

---

## 👨‍💻 Author

### **Amr Ramadan**

**Data Analyst | Software Developer**

🔗 **GitHub:** [(https://github.com/AmrRamadan01092)]

---

## ⭐ Project Highlights

**129K+ Passenger Records** · **Power BI Dashboard** · **Power Query** · **DAX** · **Customer Satisfaction Analysis** · **Service Quality Analysis** · **Data Visualization**
