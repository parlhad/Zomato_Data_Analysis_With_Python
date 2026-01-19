# 🍽️ Zomato Data Analysis with Python – Business Analytics Project

An end-to-end **Python-based Exploratory Data Analysis (EDA)** project performed on Zomato restaurant data to understand **restaurant distribution, ratings behavior, online delivery adoption, and market dominance**.

This project focuses on transforming raw restaurant data into **business-ready insights** that can support decision-making in the food-tech domain.

python, data-analysis, exploratory-data-analysis, zomato, pandas, matplotlib, seaborn, food-tech, data-analytics
---

## 📌 Project Overview

Zomato is a leading food discovery and delivery platform operating across multiple countries.  
With thousands of restaurants listed, Zomato relies heavily on data to understand **customer satisfaction, restaurant quality, delivery penetration, and regional performance**.

This project analyzes Zomato’s restaurant dataset to identify **patterns in ratings, delivery availability, country-wise dominance, and growth opportunities** using Python.

---

## 🎯 Problem Statement

Zomato needs to understand:

- How restaurants are distributed across countries
- How customer ratings are spread across the platform
- How widely online delivery is adopted
- Where quality and delivery gaps exist
- Which markets dominate the platform

The challenge is to **convert raw restaurant metadata into meaningful business insights**.

---

## 🎯 Business Objectives

- Analyze restaurant distribution across countries
- Study customer rating patterns
- Measure online delivery penetration
- Identify quality gaps and growth opportunities
- Support data-driven platform and delivery strategy decisions

---

## 📂 Dataset Overview

The dataset represents **restaurant-level metadata** where:

- Each row represents one restaurant listed on Zomato
- Data includes ratings, delivery availability, and location details

### Key Columns:
- `Restaurant ID`
- `Country Code`
- `City`
- `Cuisines`
- `Average Cost for two`
- `Has Online delivery`
- `Aggregate rating`
- `Rating text`
- `Votes`

For analysis accuracy, only restaurants with **valid ratings** were considered.

---

## 🧠 Analysis Approach

The project follows a **structured industry-style analytics workflow**:

1. Data loading and inspection  
2. Data cleaning (duplicates and missing values)  
3. Filtering unrated restaurants  
4. Exploratory Data Analysis (EDA)  
5. Distribution and comparison analysis  
6. Business interpretation of results  

The focus is on **clarity, correctness, and business relevance** rather than complex modeling.

---

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📈 Business Impact

This analysis helps Zomato stakeholders to:

- Understand dominance of key markets (especially India)
- Identify under-penetration of online delivery
- Recognize rating distribution and quality gaps
- Prioritize delivery expansion opportunities
- Improve restaurant discovery and platform trust

---

## 📚 Key Learnings

- Real-world Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing techniques
- Handling categorical and rating-based data
- Translating raw data into business insights
- Writing structured, industry-ready analytics projects

---


**Q1️⃣ How many restaurants are present in the dataset with valid ratings?**  
**Insight:** The dataset contains **7,403 rated restaurants** after removing unrated entries.  
**Business Value:** Ensures all analysis is based on reliable customer feedback.

**Q2️⃣ Which country has the highest number of restaurants on Zomato?**  
**Insight:** **India leads with 6,513 restaurants**, contributing the majority of listings.  
**Business Value:** Confirms India as Zomato’s core and most competitive market.

**Q3️⃣ What are the top 5 countries by restaurant count?**  
**Insight:** The top countries include **India, Australia, Brazil, South Africa, and Sri Lanka**.  
**Business Value:** Helps identify primary and secondary international markets.

**Q4️⃣ How many restaurants provide online delivery?**  
**Insight:** **2,355 restaurants** offer online delivery, while **5,048 do not**.  
**Business Value:** Shows delivery adoption is still limited.

**Q5️⃣ What percentage of restaurants support online delivery?**  
**Insight:** Only **31.8%** of restaurants provide online delivery.  
**Business Value:** Highlights strong growth opportunity for delivery expansion.

**Q6️⃣ What is the overall rating distribution of restaurants?**  
**Insight:**  
- Average: **3,737**  
- Good: **2,100**  
- Very Good: **1,079**  
- Excellent: **301**  
- Poor: **186**  
**Business Value:** Most restaurants fall in mid-rating categories.

**Q7️⃣ How many restaurants are rated “Excellent”?**  
**Insight:** Only **301 restaurants** are rated “Excellent”.  
**Business Value:** These are premium outlets ideal for promotions and partnerships.

**Q8️⃣ Are mid-rated restaurants dominant on Zomato?**  
**Insight:** **5,837 restaurants** fall under “Average” and “Good” ratings combined.  
**Business Value:** Quality improvement here can impact most users.

**Q9️⃣ Do most restaurants operate without online delivery?**  
**Insight:** Yes, **68.2%** of restaurants do not offer delivery.  
**Business Value:** Large untapped opportunity for Zomato’s delivery ecosystem.

**Q🔟 What does India’s restaurant concentration indicate?**  
**Insight:** India’s high restaurant count indicates intense market competition.  
**Business Value:** Zomato can differentiate via ratings, visibility, and recommendations.

**Q1️⃣1️⃣ Are highly rated restaurants common on the platform?**  
**Insight:** “Excellent” restaurants make up **~4%** of total listings.  
**Business Value:** Premium discovery features become critical.

**Q1️⃣2️⃣ Which rating category dominates Zomato?**  
**Insight:** The **“Average”** rating category dominates with **3,737 restaurants**.  
**Business Value:** Indicates customer experience is acceptable but improvable.

**Q1️⃣3️⃣ How does rating distribution affect customer trust?**  
**Insight:** Limited “Excellent” ratings suggest customers rely heavily on reviews and votes.  
**Business Value:** Reinforces importance of trust-building mechanisms.

**Q1️⃣4️⃣ What does delivery availability suggest about growth strategy?**  
**Insight:** Delivery is under-penetrated compared to dine-in listings.  
**Business Value:** Expansion of delivery partners can directly increase order volume.

**Q1️⃣5️⃣ Which segment should Zomato prioritize for growth?**  
**Insight:** Mid-rated, non-delivery restaurants form the largest segment.  
**Business Value:** Converting these into delivery-enabled outlets offers maximum ROI.

**Q1️⃣6️⃣ What does the data suggest about customer satisfaction levels?**  
**Insight:** Majority of restaurants are neither poor nor excellent.  
**Business Value:** Incremental improvements can significantly improve platform perception.

**Q1️⃣7️⃣ How competitive is the Zomato marketplace?**  
**Insight:** High restaurant density in India implies strong competition.  
**Business Value:** Data-driven ranking becomes essential.

**Q1️⃣8️⃣ What role do premium restaurants play?**  
**Insight:** Premium restaurants are few but influential.  
**Business Value:** Useful for brand image and high-value customers.

**Q1️⃣9️⃣ How balanced is Zomato’s global presence?**  
**Insight:** Zomato is heavily skewed toward India with limited international spread.  
**Business Value:** Indicates scope for international scaling.

**Q2️⃣0️⃣ What overall business strategy emerges from the data?**  
**Insight:** Zomato is a **high-volume, mid-quality, delivery-underpenetrated platform** dominated by India.  
**Business Value:** Clear focus areas: delivery expansion, quality uplift, and premium discovery.


## 🚀 Future Enhancements

- City-level and cuisine-level analysis
- Rating prediction and restaurant segmentation
- Delivery adoption modeling
- Dashboard development using Power BI or Tableau
- Integration of order and revenue data (if available)

---

## 👤 Author

**Pralhad Balaji Jadhav**  
Aspiring Data Analyst | Python | Data Analytics  

📌 GitHub Repository:  
https://github.com/parlhad

---

## 📎 Note

This project is created for **learning, portfolio, and demonstration purposes** using a publicly available Zomato dataset.


