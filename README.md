# SwissClub Sales Analysis and Optimal Storage Location

This repository contains the analysis for **SwissClub**, an Indian activewear brand. The project focuses on understanding weekly revenue trends, product performance, and optimizing storage locations using delivery data.

## Project Overview

### 1. Major Sales Spike Analysis (`Merge Sheets on Zip v2.ipynb`)
- **Objective:** Analyze weekly sales performance to identify major sales spikes and dips.
- **Key Insights:**
  - **Sales Spike:** On **2020-12-13**, sales increased by **687.78%** WoW, driven by an average discount of **14.87%**.
  - **Sales Dip:** On **2020-12-27**, sales dropped by **83.20%** WoW, with a minimal average discount of **0.40%**.
  - **Top Cities:** Mumbai and Bengaluru contributed the highest revenue during the spike.
- **Recommendations:**
  - Increase the frequency of strategic promotions.
  - Target marketing efforts in key cities like Mumbai and Bengaluru.
  - Optimize inventory management for high-demand periods.

### 2. Optimal Storage Location Analysis (`location.ipynb`)
- **Objective:** Optimize warehouse locations using KMeans clustering to enhance logistics efficiency.
- **Key Findings:**
  - Delivery locations clustered into distinct groups for optimal distribution.
  - Proposed warehouse locations:
    - **Western Region:** Maharashtra
    - **Southern Region:** Karnataka (Central Hub)
    - **Northern Region:** Uttar Pradesh
- **Recommendations:**
  - Establish regional warehouses to minimize shipping distances and improve customer service.
  - Implement data-driven logistics strategies for cost-effective operations.

## Repository Structure
```plaintext
.
├── Merge Sheets on Zip v2.ipynb    # Analysis of major sales spikes and dips
├── location.ipynb                  # KMeans clustering for optimal storage locations
├── data/                           # Raw and processed data files (add as needed)
├── README.md                       # Project documentation
└── assets/                         # Visualization assets (graphs, charts)
