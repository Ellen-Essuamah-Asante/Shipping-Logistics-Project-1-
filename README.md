# 📦 Trade Data Analysis Project

This repository contains a comprehensive analysis of international trade data, focused on uncovering insights into trade types, freight charges, modes of transport, container usage, and country-level performance.

---

## 🧠 Project Objective

The primary goal is to explore trade patterns to support data-driven decision-making on:

- **Freight cost optimization**
- **Market prioritization**
- **Peak shipping periods**
- **Mode of transport efficiency**
- **Container usage impact**

---

## 📁 Dataset Overview

The dataset includes structured monthly trade records with the following key features:

- `trdtype`: Trade type (Import or Export)
- `freight`: Freight charges
- `disagmot`: Mode of transport
- `contcode`: Containerization status
- `df`: Goods origin (Domestic or Foreign)
- `country`: Country of origin/destination
- `month`: Transaction month

---

## 🛠️ Methodology

1. **Data Preparation**
   - Combined multiple CSV files by year and month
   - Dropped irrelevant columns (e.g., `mexstate`, `canprov`)
   - Applied mapping dictionaries for human-readable values

2. **Exploratory Data Analysis (EDA)**
   - Aggregated and visualized key metrics
   - Compared trade volumes, container usage, transport modes, and monthly activity

3. **Statistical Testing**
   - Performed ANOVA to test if containerized shipments incur lower freight charges

4. **Visualizations**
   - Created bar charts, count plots, and stacked bars using `matplotlib` and `seaborn`
   - Applied data labels and formatted axes in millions or billions for clarity

---

## 📌 Key Insights

- Non-containerized shipments tend to incur higher freight charges
- Certain countries contribute more to exports or imports, highlighting trade imbalances
- Peak shipping months identified for both imports and exports
- Most frequently used modes of transport revealed
- Export and import trends vary significantly by month and country
