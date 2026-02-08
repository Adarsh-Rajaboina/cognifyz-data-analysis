# 🍽️ Restaurant Data Analysis (Cognifyz Internship)

## 📌 Description

This repository contains my work for the **Cognifyz Technologies Data Analysis Internship**, covering **Level 1, Level 2, and Level 3** tasks.  
The project performs **Exploratory Data Analysis (EDA)** on a restaurant dataset using **Python** to extract insights about cuisines, cities, ratings, price ranges, online services, votes, geographic distribution, restaurant chains, and review text.

--

## 📊 Project Overview

The analysis is divided into three levels:

### ✅ Level 1 – Fundamentals of EDA
- Top cuisines and their percentage share  
- City-wise restaurant analysis and average ratings  
- Price range distribution  
- Impact of online delivery on ratings  

### ✅ Level 2 – Deeper Insights
- Restaurant ratings distribution and average votes  
- Cuisine combinations and their ratings  
- Geographic analysis using latitude and longitude  
- Restaurant chains analysis (ratings and popularity)  

### ✅ Level 3 – Advanced Relationships
- Restaurant reviews (text analysis: keywords, review length vs rating)  
- Votes analysis (highest/lowest votes and correlation with ratings)  
- Price range vs services (online delivery and table booking)  

Each task is implemented in a **separate Python script** for clarity.

---

## 📂 Data Source

The dataset is provided as part of the **Cognifyz Internship Programme** and includes information such as:

- Restaurant name and city  
- Cuisines  
- Aggregate ratings and votes  
- Price range  
- Online delivery and table booking availability  
- Latitude and longitude  
- Review text (for Level 3 Task 1)

---

## 💡 Business Problem

Restaurants and food platforms need **data-driven insights** to:

- Understand **popular cuisines** and customer preferences  
- Identify **high-performing cities** and rating trends  
- Analyze **pricing strategies** and service availability  
- Measure **popularity vs quality** (votes vs ratings)  
- Learn from **customer reviews** (common keywords and review patterns)  

---

## 🎯 Project Objectives

### Level 1
- **Task 1 – Top Cuisines:** Identify top 3 cuisines and calculate their percentage share.  
- **Task 2 – City Analysis:** Find the city with the most restaurants, compute average ratings per city, and identify the highest-rated city.  
- **Task 3 – Price Range Distribution:** Visualize and calculate the percentage of restaurants in each price range.  
- **Task 4 – Online Delivery:** Calculate the percentage offering online delivery and compare ratings with and without delivery.

### Level 2
- **Task 1 – Restaurant Ratings:** Analyze rating distribution and calculate the average number of votes.  
- **Task 2 – Cuisine Combinations:** Identify common cuisine combinations and analyze their ratings.  
- **Task 3 – Geographic Analysis:** Plot restaurant locations using latitude and longitude and observe clustering.  
- **Task 4 – Restaurant Chains:** Identify chains and analyze their ratings and popularity.

### Level 3
- **Task 1 – Restaurant Reviews (Text Analysis):**  
  - Extract common positive and negative keywords.  
  - Calculate average review length.  
  - Analyze the relationship between review length and rating.
- **Task 2 – Votes Analysis:**  
  - Identify restaurants with highest and lowest votes.  
  - Analyze correlation between votes and ratings.
- **Task 3 – Price Range vs Services:**  
  - Analyze how price range relates to online delivery and table booking availability.  
  - Determine whether higher-priced restaurants are more likely to offer these services.

---

## 🔍 Steps Followed

1. **Data Loading & Inspection**  
   - Loaded the CSV dataset using pandas.  
   - Inspected columns, data types, and missing values.

2. **Data Cleaning & Preparation**  
   - Handled missing values and ensured correct data types.  
   - Processed multi-value columns like *Cuisines*.  
   - Cleaned and prepared review text for text analysis (Level 3).

3. **Analysis & Visualization**  
   - Used grouping, aggregation, sorting, and correlation analysis.  
   - Created visualizations (bar charts, distributions, comparisons, scatter plots, etc.) to support insights.

---

## 🔧 Tools Used

- **Programming Language:** Python  
- **Libraries:** pandas, matplotlib  
- **Techniques:** Exploratory Data Analysis (EDA), text analysis, aggregation, correlation analysis, visualization  

---

## 📈 Key Findings (Summary)

### 🍽️ Cuisines
- The dataset is dominated by a few cuisines such as **North Indian, Chinese, and Fast Food**.

### 📍 Cities
- **New Delhi** has the highest number of restaurants.  
- Some cities show **higher average ratings** despite fewer restaurants.

### 💰 Price Range
- Most restaurants fall into **lower and mid price ranges**, with fewer in premium and luxury categories.

### 🚀 Online Delivery
- Only a **fraction of restaurants** offer online delivery.  
- Restaurants with online delivery tend to have **higher average ratings**.

### ⭐ Ratings & Votes
- Ratings are mostly concentrated in the **mid-range (around 2.5 to 4.0)**.  
- Votes and ratings show a **weak to moderate positive correlation**.

### 🍽️ Cuisine Combinations
- Multi-cuisine restaurants (e.g., **North Indian & Chinese**) are common and often well-rated.

### 🌍 Geography
- Restaurants are **clustered around major cities**, not evenly distributed.

### 🏪 Chains
- Popular chains appear multiple times and show **variation in ratings and popularity**.

### 📝 Reviews (Level 3)
- Certain **positive and negative keywords** appear frequently in reviews.  
- Review length shows a **relationship with rating**, indicating stronger opinions in longer reviews.

### 💰 Price vs Services
- **Higher-priced restaurants** are more likely to offer:
  - Online delivery  
  - Table booking  
