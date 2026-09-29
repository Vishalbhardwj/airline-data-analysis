# ✈️ Airline Data Analysis

📊 **SQL & Python analysis to identify opportunities for improving flight occupancy and airline profitability.**

---

## 🎯 Overview / Business Problem

This project analyzes airline operational and booking data to identify opportunities to improve **flight occupancy, revenue, and aircraft utilization**.

The main business problem is understanding how effectively available aircraft capacity is being utilized and how increasing occupancy could impact revenue.

---

## 📊 Dataset / Source

The analysis uses the `travel.sqlite` database.

### Main Tables

- ✈️ `aircrafts_data`
- 🛫 `airports_data`
- 🎫 `boarding_passes`
- 🧾 `bookings`
- 🛬 `flights`
- 💺 `seats`
- 🎟️ `ticket_flights`
- 👤 `tickets`

The dataset contains information related to aircraft, flights, bookings, tickets, seats, fares, and boarding passes.

---

## 🛠️ Tools

- 🐍 Python
- 🗃️ SQL
- 🧮 SQLite
- 🐼 Pandas
- 📊 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook

---

## 🔍 Analysis

The project covers:

- 🗄️ Database exploration
- 🔎 Data-quality checks
- ✈️ Aircraft capacity analysis
- 💰 Revenue analysis
- 🎫 Average revenue per ticket
- 💳 Fare analysis
- 🪑 Aircraft occupancy analysis
- 📈 Revenue and occupancy comparison
- 🚀 10% occupancy improvement scenario

### Aircraft Capacity

Aircraft with more than 100 available seats were identified:

| Aircraft | Seats |
|----------|------:|
| 773 | 402 |
| 763 | 222 |
| 321 | 170 |
| 320 | 140 |
| 733 | 130 |
| 319 | 116 |

### Revenue Analysis

Revenue was compared across aircraft types.

- 🥇 **SU9** generated the highest total revenue.
- 📉 **CN1** generated the lowest total revenue.
- 🎫 Average revenue per ticket varied across aircraft types.

### Occupancy Analysis

Average occupancy differed significantly across aircraft types.

| Aircraft | Average Occupancy |
|----------|------------------:|
| 773 | ~65.9% |
| SU9 | ~58.6% |
| CR2 | ~43.0% |

This helps identify differences in how effectively aircraft capacity is being utilized.

---

## 💡 Key Insights

- 🪑 Aircraft occupancy varies considerably across aircraft types.
- 💰 Revenue differs significantly between aircraft types.
- 🎫 Average revenue per ticket varies across aircraft.
- 📉 Lower-occupancy aircraft may provide opportunities for further investigation.
- 🚀 Increasing occupancy can have a meaningful impact on modeled revenue.
- 📊 Revenue and occupancy should be considered together when evaluating aircraft performance.

### 10% Occupancy Scenario

A scenario analysis estimated the potential impact of increasing occupancy by 10%.

| Metric | Result |
|--------|-------:|
| Current modeled revenue | 20.77B |
| Revenue after 10% occupancy increase | 22.84B |
| Modeled increase | ~2.08B |

> ⚠️ This is a scenario analysis based on the assumption that revenue increases proportionally with occupancy. It is not a guaranteed forecast.

---

## 🎯 Recommendations

Based on the analysis:

- 🔍 Investigate low-occupancy aircraft and flights further.
- 💳 Review pricing and fare conditions alongside occupancy.
- 🪑 Focus on improving utilization of existing aircraft capacity.
- 📊 Evaluate revenue and occupancy together when making operational decisions.
- 📈 Conduct route-level and time-based analysis to identify more specific opportunities.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/VishalBhardwj/airline-data-analysis.git
cd airline-data-analysis
```

### 2. Open the Notebook

Open:

`Data Analysis -Airlines.ipynb`

using Jupyter Notebook or JupyterLab.

### 3. Check the Database

Make sure `travel.sqlite` is available in the expected project location.

### 4. Run the Notebook

Run the notebook cells in sequence to reproduce the SQL analysis, calculations, visualizations, and insights.

---

## 🚀 Future Improvements

- 🗺️ Add route-level performance analysis
- 📅 Analyze occupancy by month and time period
- ✈️ Compare aircraft performance by route
- 💳 Analyze fare conditions against occupancy
- 📊 Build an interactive Power BI dashboard
- 🔎 Investigate low-occupancy flights in greater detail

---

## 👤 Author

**Vishal Bhardwaj**

📌 Data Analyst | Python | SQL | Excel | Power BI

---

⭐ This project demonstrates how SQL and Python can be used to analyze airline data and translate operational data into business insights.
