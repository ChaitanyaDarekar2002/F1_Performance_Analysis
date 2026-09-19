# 🏎️ Formula 1 Racing Analysis Dashboard

An interactive **Formula 1 Racing Analysis** project built using **Microsoft Power BI** to analyze drivers, constructors, races, circuits, race performance, winners, sponsorship markets, and historical Formula 1 trends across different decades.

The project transforms Formula 1 data into an interactive dashboard that provides insights into driver performance, constructor success, race characteristics, and the evolution of Formula 1 over time.

---

## 📌 Project Workflow

**Dataset → Data Cleaning & Preparation → Data Modeling → Power BI → DAX → Interactive Dashboard → Insights**

### 1️⃣ Get Dataset

The project starts with Formula 1 historical data containing information related to:

- Drivers
- Constructors
- Races
- Circuits
- Grand Prix
- Race Results
- Wins
- Race Duration
- Race Laps
- Race Length
- Year
- Decade
- Continent
- Sponsorship Market

---

## 🧹 2️⃣ Data Cleaning & Preparation

The raw Formula 1 data was prepared before creating the Power BI dashboard.

The data preparation process included:

- Checking the dataset structure
- Handling missing values
- Removing duplicate records
- Cleaning column names
- Correcting data types
- Standardizing driver and constructor names
- Creating decade and year-based fields
- Preparing race and winner information
- Preparing the final dataset for Power BI

---

## 📊 3️⃣ Power BI Dashboard

Microsoft Power BI was used to build an interactive Formula 1 analysis dashboard.

The dashboard contains multiple pages focused on historical trends, drivers, constructors, and race performance.

---

## 🏁 Dashboard 1 — Formula 1 Overview

The overview page provides a historical analysis of Formula 1 racing.

### 📌 Key KPIs

- 🌍 **Continents:** 6
- 🏎️ **Constructors:** 37
- 👨‍🏎️ **Drivers:** 115
- 🔄 **Average Laps per Race:** 64.62

### 📈 Visualizations

- Unique Winners by Decade
- Competitiveness Index by Decade
- Race Length Variety by Decade
- Grand Prix Winners by Country
- Dominant Circuits
- Race Evolution
- Year / Decade analysis
- Continental analysis

### 🌍 Geographic Analysis

<img width="1907" height="978" alt="Screenshot 2026-09-19 153143" src="https://github.com/user-attachments/assets/0e67136a-8603-4982-8e02-fedbded94656" />


---

## 🏆 Dashboard 2 — Drivers & Constructors

The second page focuses on driver and constructor performance.

### 📌 Key KPIs

- 🏎️ Top Driver
- 🏆 Top Driver Wins
- 📊 Win Share
- 🏁 Total Wins
- 🏭 Top Constructor
- 🏆 Constructor Wins

### 📊 Visualizations

#### Dominant Drivers

The dashboard compares drivers based on their total race wins.

Examples include:

- Lewis Hamilton
- Michael Schumacher
- Max Verstappen
- Sebastian Vettel
- Alain Prost

#### Team Profitability / Wins

A treemap is used to analyze constructor wins and compare team performance.

#### Top Constructors

Constructor performance is compared using total wins.

Examples include:

- Ferrari
- McLaren
- Mercedes
- Red Bull Racing
- Williams

#### Grand Prix Wins

The dashboard analyzes the number of Grand Prix wins by country.

#### Top Sponsorship Market

The dashboard compares Formula 1 activity across different continents and sponsorship markets.

---

## 📅 Decade Analysis

The dashboard allows users to explore Formula 1 performance across different decades:

- 1950s
- 1960s
- 1970s
- 1980s
- 1990s
- 2000s
- 2010s
- 2020s

This makes it possible to analyze how drivers, constructors, races, and competitiveness changed over time.

---

## 🎛️ Interactive Filters

The dashboard includes filters for:

- Decade
- Year
- Constructor
- Continent
- Race
- Driver

These filters allow users to dynamically explore Formula 1 historical data.

---

## 💡 Key Insights

The dashboard helps analyze:

- Most successful Formula 1 drivers
- Most successful constructors
- Driver wins across different eras
- Constructor performance over time
- Number of unique winners by decade
- Race length variation across decades
- Average race laps
- Dominant circuits
- Grand Prix wins by country
- Geographical distribution of Formula 1
- Evolution of race duration
- Continental Formula 1 activity
- Historical competitiveness trends

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI** | Dashboard & Data Visualization |
| **Power Query** | Data Cleaning & Transformation |
| **DAX** | Measures & Calculations |
| **Data Modeling** | Data Relationships & Analysis |
| **GitHub** | Project Documentation |

---

## 🔄 Project Pipeline

```text
Raw Formula 1 Dataset
          ↓
Data Cleaning & Transformation
          ↓
Data Preparation
          ↓
Data Modeling
          ↓
DAX Measures
          ↓
Power BI Dashboard
          ↓
Interactive Analysis
          ↓
Historical Formula 1 Insights
