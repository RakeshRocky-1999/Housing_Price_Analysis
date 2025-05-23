# 🏠 Residential House Price Analysis

## 📊 Project Summary

This Power BI dashboard project provides a comprehensive **analysis of Residential House Price**, built using **Google BigQuery** as the data source. It presents critical insights into **house price trends, market performance, and the impact of macroeconomic factors** across various regions and property types.

The dashboard is designed for **real estate analysts, investors, policy makers, and homebuyers** who seek data-driven insights to inform property decisions in Denmark.

---

## 🧠 Key Features

### 1. **Market Overview**
- Dynamic KPI cards displaying total sales, average price per square meter, and transaction counts.
- Temporal trend analysis of house prices over time.
- Interactive maps to visualize regional price variations.

### 2. **Sales Performance**
- Quarterly breakdown of total sales, median prices, and price changes.
- Percentage changes between offer and purchase prices to reflect market competitiveness.
- Sales grouped by region, area, and city for micro-level insights.

### 3. **House Type Analysis**
- Comparative analysis of property types: Detached, Semi-detached, Apartments, etc.
- Size vs. price visualizations: `SQM`, `no_rooms`, `year_built`.
- Price per square meter comparison by property type and location.

### 4. **Macroeconomic Impact**
- Integrated economic indicators: 
  - `DK Inflation Rate (%)`
  - `Nominal Interest Rate (%)`
  - `Yield on Mortgage Credit Bonds (%)`
- Time series overlays to analyze macroeconomic trends vs. real estate pricing.

---

## 🗂️ Dataset Overview

The dataset includes:
- **House Details**: `house_type`, `year_build`, `no_rooms`, `sqm`, `zip_code`
- **Sales Metrics**: `purchase_price`, `sqm_price`, `%_change_between_offer_and_purchase`
- **Location Info**: `city`, `area`, `region`
- **Time & Economy**: `date`, `quarter`, `interest_rate`, `inflation_rate`, `mortgage_yield`

**Source**: Google BigQuery public dataset (integrated via Power BI).

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Google BigQuery** (as the external data source)
- **Power Query** for data transformation
- **DAX** for calculated columns and KPIs
- **Interactive Visuals**: 
  - Tree Maps
  - Area & Line Charts
  - Slicers and Filters
  - Maps (using postal codes and regions)

---

## 🚀 How to Use

1. Clone the repository (if available).
2. Open the `.pbix` file in Power BI Desktop.
3. Refresh the dataset (ensure BigQuery credentials are available).
4. Interact with visual elements like filters, slicers, and maps for exploratory insights.

---

## 📌 Highlights

- Built a **responsive and filterable Power BI dashboard** connected to Google BigQuery.
- **Extracted actionable insights** such as undervalued regions, macroeconomic correlations, and house type pricing dynamics.
- Enables stakeholders to **make strategic decisions** regarding property investment, pricing, and policy formulation.

---

## ✨ Screenshots

> *(Add a few screenshots of your dashboard here for better visual appeal on GitHub or your portfolio)*
> 
<img width="616" alt="House Market Overview" src="https://github.com/user-attachments/assets/18ef65a1-e905-42b8-91e6-5602b34fbb09" />

<img width="617" alt="Sales Performance" src="https://github.com/user-attachments/assets/b1c50bfe-0a95-46d7-a92e-b8831c2194ca" />

<img width="616" alt="House Types" src="https://github.com/user-attachments/assets/9e49fb48-b0f6-4f37-814c-05453f97b9a4" />


---

## 📬 Contact

**Rakesh B**  
Data Analyst | Power BI | Python | SQL  
📧 rakesh.analytics@example.com  
📎 [LinkedIn](https://www.linkedin.com/in/rakesh-b-9b7709290/) 

---

## 📝 License

This project is for educational and portfolio purposes only.
