# 🍽️ Restaurant Data Analysis – Level 3 (Cognifyz Internship)

## 📌 Description

This folder contains my solutions for **Level 3** of the **Cognifyz Technologies Data Analysis Internship**.  
Level 3 focuses on **advanced analysis and relationships** within the dataset, including text-based review analysis, popularity (votes) vs ratings, and how price range affects service availability.

---

## 📊 Project Overview

Level-3 analysis includes:

- **Restaurant Reviews (Text Analysis)** – Extracting common positive and negative keywords, analyzing review length, and studying its relationship with ratings.  
- **Votes Analysis** – Identifying restaurants with the highest and lowest votes and analyzing the correlation between votes and ratings.  
- **Price Range vs Services** – Analyzing how price range relates to the availability of online delivery and table booking.

---

## 📂 Data Source

The dataset is provided as part of the **Cognifyz Internship Programme** and contains information such as:

- Review text  
- Aggregate ratings  
- Votes  
- Price range  
- Online delivery availability  
- Table booking availability  
- City and restaurant information  

---

## 💡 Business Problem

Food platforms and restaurant businesses want to understand:

- What **customers talk about most** in reviews (positive and negative keywords)  
- Whether **longer or more detailed reviews** are associated with higher or lower ratings  
- Whether **popular restaurants (more votes)** also have **better ratings**  
- Whether **higher-priced restaurants** are more likely to offer **additional services** such as:
  - Online delivery  
  - Table booking  

These insights help in **service improvement, pricing strategy, and customer experience optimization**.

---

## 🎯 Project Objectives (Level 3)

- **Task 1 – Restaurant Reviews (Text Analysis):**  
  - Identify the most common **positive and negative keywords** from review text.  
  - Calculate the **average review length**.  
  - Analyze whether there is a **relationship between review length and rating**.

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
   - Inspected columns related to reviews, ratings, votes, price range, and services.

2. **Data Preparation**  
   - Cleaned review text (removed nulls, basic text preprocessing).  
   - Ensured votes and ratings columns were numeric.  
   - Converted service availability columns into usable formats.

3. **Analysis & Visualization**  
   - Performed keyword frequency analysis on review text.  
   - Calculated review length and compared it with ratings.  
   - Identified restaurants with extreme vote counts.  
   - Computed correlation between votes and ratings.  
   - Grouped data by price range to compare service availability.  
   - Created plots to visualize these relationships.

---

## 🔧 Tools Used

- **Programming Language:** Python  
- **Libraries:** pandas, matplotlib (and standard text processing libraries)  
- **Techniques:** Text analysis, correlation analysis, grouping, aggregation, visualization (EDA)

---

## 📈 Key Findings (Level 3)

### 📝 Restaurant Reviews (Text Analysis)
- Certain **positive and negative keywords** appear frequently in reviews.  
- Review length shows a **relationship with ratings** (longer reviews tend to reflect stronger opinions, either positive or negative).

### 🗳️ Votes Analysis
- Restaurants with **more votes** tend to have **slightly higher ratings**, but the relationship is **weak to moderate**.  
- Popularity and rating are related, but **not strongly dependent** on each other.

### 💰 Price Range vs Services
- **Higher price range restaurants** are more likely to:
  - Offer **online delivery**  
  - Provide **table booking** options  
- Lower price range restaurants are less likely to offer these additional services.
## 📁 Project Structure

