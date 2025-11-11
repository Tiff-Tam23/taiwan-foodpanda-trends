# 🍱 Taiwan Foodpanda Trend Data Analysis

## 📘 Introduction
This project explores **Foodpanda Taiwan** order data to understand customer behavior and vendor performance.  
It combines multiple datasets containing order, product, and vendor information to identify trends such as popular cuisines, order times, and potential market opportunities.

---

## 🧭 Project Overview
The notebook analyzes customer order data from **Taiwan Foodpanda** to explore:
- Which cuisines are most popular  
- When customers order the most  
- Possible market gaps and customer behavior patterns  

The analysis combines **three datasets** and uses **Pandas** for data cleaning, merging, and descriptive analysis.

---

## 📂 Data Source
| File Name | Description |
|------------|-------------|
| `orders_tw.txt` | Contains order details such as order time, order day, and order ID |
| `products_tw.txt` | Contains product names, prices, and categories |
| `vendors_tw.txt` | Contains vendor information such as name, cuisine type, and location |

---

## 📦 Dataset Source
The data used in this project originates from the **[Delivery Hero Recommender Dataset](https://github.com/deliveryhero/dh-reco-dataset?tab=readme-ov-file)**,  
an open dataset released by **Delivery Hero** for research and educational purposes.  

This dataset contains anonymized order, vendor, and product information from the **Foodpanda** platform, which was adapted in this project to focus on the **Taiwan region (TW)**.

---

## 🧹 Data Preparation
1. Load datasets (`orders_tw.txt`, `products_tw.txt`, `vendors_tw.txt`)  
2. Merge them into a single DataFrame  
3. Remove duplicate order IDs  
4. Clean and organize columns for analysis  

---

## 📈 Summary of Key Insights

The **Foodpanda Taiwan market analysis** reveals actionable patterns in consumer behavior, vendor dynamics, and operational gaps — focusing mainly on **Taipei and surrounding areas**.

---

### 1️⃣ Cuisine Preferences & Underserved Markets
- **Dominant cuisines:** Taiwanese (38%), American (15%), Snacks (12.7%)  
- **Least ordered:** Exotic, Hong Kong-style, and Vegetarian  
- **Market gap:**  
  > Although around 14% of Taiwan’s population (~3.2 million people) are vegetarian, with over 6,000 vegetarian restaurants,  
  > Foodpanda partners with only **2% (116)** of them, capturing just **1.2% (23,132)** of potential orders.  

---

### 2️⃣ Peak Order Times & Cuisine Trends
- **Peak hours:** 12:00 → 19:00 → 13:00 (Lunch and Dinner peaks)  
- **Cuisine timing:**  
  - Taiwanese food: 11:00–13:00 & 18:00–20:00  
  - Snacks: 22:00–24:00 (late-night surge)  

---

### 3️⃣ Customer & Vendor Location Alignment
- **Top customer districts:** Zhongzheng (18.9%), Zhongshan (14.1%), Xinyi (12.4%)  
- **Top vendor districts:** Zhongzheng (13.9%), Zhongshan (12%), Sanchong (10.8%)  
- **Insight:** Vendors are concentrated in **affluent, high-traffic districts**, aligning well with strong purchasing power and consumer density.

---

### 4️⃣ Customer–Vendor Distance & Demand–Supply Balance
- **Order distribution:** 64.6% local (same district), 35.4% cross-region (average distance: 4.87 km)  
- **Top 3 cross-region order origins:** Zhongzheng District, Wanhua District, Zhongshan District  
- **Customer–vendor flow patterns:**  

| Customer District | Vendor Districts |
|-------------------|------------------|
| Zhongzheng | Xinyi |
| Wanhua | Xinzhuang, Zhongzheng |
| Zhongshan | Zhongzheng |

  These patterns indicate that customers in central Taipei often order from nearby commercial zones, possibly due to **commuting habits, workplace proximity, or popular dining areas**.  
- **Underserved areas (high demand–low supply):**
  - **Taoyuan:** Guishan, Nangang, Luzhu 
  - **New Taipei:** Shenkeng, Taishan, Shulin  
- **Balanced areas:** Zhongzheng, Songshan, Zhongshan


---

## 📝 Notes

This project is for educational and practice purposes only.
The dataset was used to demonstrate Python data analysis skills — not for commercial use.



