# Airbnb-dashboard
# 🏠 Global Airbnb Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

An end-to-end business intelligence project analyzing **279,411 Airbnb listings** across **10 global cities** — uncovering pricing dynamics, host behavior, seasonal trends, and market evolution from 2008 to 2021.

---

## 📊 Dashboard Preview

<img width="848" height="635" alt="Screenshot 2026-05-25 at 4 22 19 PM" src="https://github.com/user-attachments/assets/4adf5d4b-9be7-4489-b28a-f624684148ef" />
<img width="846" height="636" alt="Screenshot 2026-05-25 at 4 22 49 PM" src="https://github.com/user-attachments/assets/d26f01e4-e30a-4cf8-a614-65540cd061cb" />
<img width="845" height="637" alt="Screenshot 2026-05-25 at 4 23 07 PM" src="https://github.com/user-attachments/assets/2d50463f-0cb6-4af5-8a5f-f97f4a52c534" />
<img width="847" height="637" alt="Screenshot 2026-05-25 at 4 23 29 PM" src="https://github.com/user-attachments/assets/5ba29430-968d-43a9-bc44-96b4887008a9" />


---

## 🗂️ Project Structure

```
airbnb-dashboard/
│
├── airbnb_dashboard.pbix       # Power BI dashboard file
├── Untitled.ipynb              # Data cleaning & EDA notebook
├── screenshots/                # Dashboard preview images
└── README.md
```

---

## 🔍 Key Findings

### 📈 Market Growth & Lifecycle
- **2015** marked the peak of total listings globally; regulatory pressures thereafter caused a significant decline
- **2016** saw Airbnb achieve profitability by Q3 despite fewer new listings — showing improved monetization
- **2019** recovery was halted by the COVID-19 pandemic, resetting growth trajectories

### 🌍 City-Level Insights
- **Paris** dominates with **64,583 listings**, accounting for a significant share of total market volume; Paris + New York + Sydney together represent **48% of all listings**
- **Bangkok** commands the highest average nightly price at **$1,100/night**, followed closely by Cape Town at **$1,069/night**
- **Rome** offers the most budget-friendly options at an average of **$65/night**

### 💰 Pricing Dynamics
- **Entire Place Premium: 63.5%** — guests pay significantly more for full-property rentals vs shared/private rooms
- **Superhost Premium: 23.3%** — verified superhosts consistently command higher prices across all 10 cities
- Each additional bedroom adds approximately **$133** to the nightly price
- Hotel rooms listed on Airbnb carry the highest median prices, as they tend to be ultra-luxury properties targeting unique-stay seekers

### 🏡 Host Behavior
- Hosts with acceptance rates above 50% offer the cheapest listings — pointing to strong demand for affordable, short-term housing
- **Over two-thirds** of Airbnb hosts are fully verified (identity + profile picture), keeping trust levels high
- Only **0.22%** of hosts are unverified and anonymous — a negligible fraction of the platform

### 📅 Seasonality
- New host listings **peak in July** and again at year-end/start, suggesting strong mid-year and holiday season onboarding cycles
- **Paris and Rome** dominate monthly review share year-round, reflecting Europe's consistent tourism demand

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Interactive dashboard design and visualization |
| **Python (Pandas, Matplotlib)** | Data cleaning, exploratory data analysis |
| **Jupyter Notebook** | EDA workflow and preprocessing |
| **DAX** | Custom measures and KPI calculations in Power BI |

---

## 📦 Dataset

- **Source:** Inside Airbnb (publicly available listings data)
- **Scope:** 10 Cities — Paris, New York, Sydney, Rio de Janeiro, Istanbul, Rome, Bangkok, Cape Town, Mexico City, Hong Kong
- **Size:** 279,411 listings | 181,788 unique hosts | 143 property types | 5,368,825 total reviews
- **Time Period:** 2008–2021

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/airbnb-dashboard.git
   cd airbnb-dashboard
   ```

2. **Run the EDA notebook**
   ```bash
   jupyter notebook Untitled.ipynb
   ```

3. **Open the Power BI Dashboard**
   - Open `airbnb_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
   - Interact with city filters, slicers, and drill-through pages

---

## 💡 Business Recommendations

- **Increase marketing spend for host acquisition in Q2–Q3** to capitalize on mid-year listing seasonality
- **Target Bangkok and Cape Town** for premium host acquisition — highest revenue-per-listing potential
- **Promote Superhost program** — 23.3% pricing premium incentivizes quality and boosts platform revenue
- **Focus affordable inventory efforts** in Paris and New York — high listing volume + demand concentration

---

## 👤 Author

**Gaurav Sarkar**  
Data Analyst | Business Intelligence  
[LinkedIn](https://www.linkedin.com/in/gaurav-sarkar-90618a272/)
