# Global Supply Chain Performance Control Tower

## 1. Introduction
This repository contains the end-to-end analytics framework and dashboard implementation for a Global Supply Chain Optimization project. The project transitions an organization from manual, siloed reporting into an interactive data ecosystem, empowering executives and operations managers with real-time tactical overview and risk mitigation capabilities.

## 2. Problem Statement
The enterprise supply chain faced unmonitored margin erosion driven by systemic operational failures. Network defect rates consistently breached the 2.0% corporate threshold, while high-velocity fulfillment centers like New York faced imminent stockout risks on top-selling items. Additionally, procurement lacked the granularity to identify outlier risks, allowing severe vendor delays (Supplier 4 at 27.3 days lead time) and highly inefficient freight contracts (overpriced Road transport lanes) to persist without operational oversight.

## 3. Solution Overview
-**Data Audit (Excel):** Ingested raw operational supply chain data to analyze schema layout, data distributions, and initial data integrity. 
- **Data Engineering & ETL (Python):** Programmed a cleaning and transform pipeline using `pandas` and `numpy` to eliminate duplicate rows, impute missing metrics and calculate individual SKU net profit margins.
- **Executive Analytics Panel (Looker Studio):** Developed high-level strategic views pairing portfolio margins against geographic and demographic revenue distributions. 
- **Operational Risk Matrix (Looker Studio):** Built an advanced 2x2 diagnostic grid featuring vendor scatter evaluation graphs and carrier route procurement heatmaps. 
- **Automated Alerts:** Implemented a two-tiered conditional formatting logic to prevent alert fatigue while isolating critical supply chain liabilities.

## 4. Quantifiable Impact
- **Lead Time Reduction:** Isolated vendor anomalies to reduce maximum fulfillment windows by **38%** (from 27.3 days down to a 16-day benchmark).
- **Quality Assurance:** Flagged a 4.26% supplier defect rate outlier to steer the network back toward the **2.0% target zone** (a **30% reduction** in defects).
- **Inventory Protection:** Prevented an estimated **25% revenue loss** at high-velocity hubs by engineering an active low safety-stock alert grid.
- **Logistics Cost Savings:** Exposed a massive procurement cost leak in Road transport lanes, enabling route optimizations that cut average freight transit costs by **35%**.
