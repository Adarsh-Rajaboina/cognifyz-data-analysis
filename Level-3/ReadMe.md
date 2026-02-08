# 🍽️ Restaurant Data Analysis – Level 3 (Cognifyz Internship)

## 📌 Description

This folder contains my solutions for **Level 3** of the **Cognifyz Technologies Data Analysis Internship**.  
Level 3 focuses on **analyzing relationships between key variables** in the dataset, such as popularity (votes), ratings, price range, and service availability.

⚠️ **Important:** The provided dataset does **not** contain text reviews. Therefore, **Task 1 (Restaurant Reviews – text analysis)** is **not applicable** and is not included. This level covers **Task 2 and Task 3**, which are fully supported by the dataset.

---

## 📊 Project Overview

Level-3 analysis includes:

- **Votes Analysis** – Identifying restaurants with the highest and lowest votes and studying the correlation between votes and ratings.  
- **Price Range vs Services** – Analyzing how price range relates to the availability of online delivery and table booking.

---

## 📂 Data Source

The dataset is provided as part of the **Cognifyz Internship Programme** and contains:

- Aggregate ratings  
- Votes  
- Price range  
- Online delivery availability  
- Table booking availability  
- City and restaurant information  

---

## 💡 Business Problem

Food platforms and restaurant businesses want to understand:

- Whether **more popular restaurants (higher votes)** also receive **better ratings**  
- Whether **higher-priced restaurants** are more likely to offer **additional services** such as:
  - Online delivery  
  - Table booking  

These insights help in **pricing strategy, service offerings, and business positioning**.

---

## 🎯 Project Objectives (Level 3)

- **Task 2 – Votes Analysis:**  
  - Identify the restaurants with the **highest** and **lowest** number of votes.  
  - Analyze the **correlation** between votes and aggregate rating.

- **Task 3 – Price Range vs Services:**  
  - Analyze the relationship between **price range** and the availability of **online delivery** and **table booking**.  
  - Determine whether **higher-priced restaurants** are more likely to offer these services.

---

## 🔍 Steps Followed

1. **Data Loading & Inspection**  
   - Loaded the dataset using pandas.  
   - Focused on columns related to votes, ratings, price range, and service availability.

2. **Data Preparation**  
   - Converted service availability columns into usable formats.  
   - Ensured votes and ratings columns were numeric and clean.

3. **Analysis & Visualization**  
   - Identified extreme cases (highest and lowest votes).  
   - Calculated correlation between votes and ratings.  
   - Grouped data by price range to compare service availability.  
   - Created plots to visualize these relationships.

---

## 🔧 Tools Used

- **Programming Language:** Python  
- **Libraries:** pandas, matplotlib  
- **Techniques:** Correlation analysis, grouping, aggregation, visualization (EDA)

---

## 📈 Key Findings (Level 3)

### 🗳️ Votes Analysis
- Restaurants with **more votes** tend to have **slightly higher ratings**, but the relationship is **weak to moderate**.  
- This means popularity and rating are related, but **not strongly dependent** on each other.

### 💰 Price Range vs Services
- **Higher price range restaurants** are more likely to:
  - Offer **online delivery**  
  - Provide **table booking** options  
- Lower price range restaurants are less likely to offer these additional services.
