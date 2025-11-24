# Startup Funding Analysis Project

## Overview

This project analyzes **startup funding data** using a combination of **data preprocessing (CSV)** and **interactive visualizations (Power BI)**.  
The main goal is to understand how startups are funded over time, what kind of investors participate, and how funding patterns vary by sector, city, and stage.

The project is based on:
- A cleaned dataset: `startup_funding.csv`
- A Power BI dashboard: `startup funding cleaned.pbix`

---

## Project Files

- `startup_funding.csv`  
  Cleaned dataset containing startup funding information (such as startup name, sector, city, investor details, funding amount, and funding type/stage).

- `startup funding cleaned.pbix`  
  Power BI report file with interactive dashboards and visualizations built on top of the cleaned dataset.

---

## Objectives

- To explore and understand **trends in startup funding**.
- To analyze **funding amounts** across:
  - Different **sectors/industries**
  - Different **cities/locations**
  - Different **funding stages/types**
- To identify **top-funded startups** and **active investors**.
- To build **visual dashboards** that make insights easy to understand.

---

## Dataset Description

> File: `startup_funding.csv`

Typical columns (may vary slightly depending on your final cleaned version):

- `StartupName` – Name of the startup  
- `IndustryVertical` / `Sector` – Sector/industry of the startup  
- `SubVertical` – More specific sub-sector (if available)  
- `CityLocation` – City where the startup is based  
- `InvestorsName` – Name(s) of the investor(s)  
- `InvestmentType` / `InvestmentnType` – Type of funding (e.g., Seed, Series A, Debt, etc.)  
- `AmountInUSD` / `AmountInINR` – Funded amount  
- `Date` – Date of the funding round  
- Any derived/cleaned columns you created (e.g., `Year`, cleaned `City`, converted amounts, etc.)

You can update the exact column names to match your dataset.

---

## Power BI Dashboard

> File: `startup funding cleaned.pbix`

The Power BI report includes (you can adjust according to your actual pages):

- **Overview Page**
  - Total funding amount
  - Total number of startups
  - Total number of funding rounds
  - Total number of unique investors

- **Funding by Sector**
  - Bar/column charts showing total funding amount per sector
  - Pie/donut charts for distribution of startups by sector

- **Funding by City**
  - Visuals comparing major startup hubs (e.g., Bengaluru, Mumbai, Delhi, etc.)
  - Maps or bar charts showing city-wise funding

- **Funding Over Time**
  - Line charts showing funding trends by year/month
  - Growth in number of deals over time

- **Top Startups & Investors**
  - Tables or bar charts of:
    - Top funded startups
    - Most active investors (by number of deals or total amount)

You can mention each report page name if you have them (like *Overview*, *City-wise Analysis*, *Sector-wise Analysis*, etc.).

---

## Tools & Technologies

- **Data Source**: `startup_funding.csv`
- **Data Cleaning / Preprocessing**: (e.g., Excel / Python / Power BI Power Query – mention what you used)
- **Visualization Tool**: Microsoft **Power BI**
- **File Type**: `.pbix` (Power BI report)

---

## Steps Performed

1. **Data Collection**
   - Obtained raw startup funding dataset from an online source / given by faculty (update as per your case).

2. **Data Cleaning**
   - Handled missing values
   - Standardized city names, sectors, and investors where required
   - Converted funding amounts to a consistent numeric format
   - Created new columns like `Year` (from `Date`), etc.

3. **Data Import into Power BI**
   - Loaded `startup_funding.csv` into Power BI
   - Verified data types (date, number, text)

4. **Data Modeling (if applicable)**
   - Created calculated columns/measures (e.g., total funding, count of startups, etc.)

5. **Dashboard Building**
   - Designed interactive charts and visuals
   - Added slicers/filters for year, city, sector, and funding type

6. **Insights & Interpretation**
   - Observed which sectors are getting the highest funding
   - Identified which cities are leading in startup investments
   - Found the most active investors and the biggest deals

---

## How to Open and Use the Project

1. **Open the Dataset (Optional)**
   - Use Excel / Notepad / Python / any CSV viewer to open `startup_funding.csv`.

2. **Open the Power BI Report**
   - Install **Microsoft Power BI Desktop**.
   - Open `startup funding cleaned.pbix` in Power BI.
   - Interact with filters, slicers, and charts to explore:
     - Funding by year, city, sector
     - Top startups and investors

---

## Key Insights (You Can Customize)

You can fill this section with 3–6 bullet points from your actual analysis, for example:

- Bengaluru, Mumbai, and Delhi are the **top three cities** in terms of total funding.
- **E-commerce and technology startups** attract the highest share of funding.
- A small number of investors account for a large portion of the total investment.
- Funding activity increased significantly after **[year]**.
- Seed and early-stage funding are the most common, but later-stage rounds account for higher total amounts.

---

## Limitations

- Data may not include **very recent funding rounds**.
- Some records have **missing or inconsistent investor/sector information**.
- The dataset may be biased towards **well-publicized funding deals**.

---

##
