# 📊 SuperStore Sales & Profit Analysis

## 🛠️ Data Preparation & Feature Engineering
- ✅ No **null values** or **duplicates** in the dataset.  
- Converted **Order Date** & **Ship Date** to datetime format.  
- Created new features:
  - **Shipping Days** → Delivery duration.  
  - **Order Year, Month, Year-Month** → Timeline analysis.  
  - **Discount Amount** = Discount × Sales.  
  - **COGS** = Sales − (Discount Amount + Profit).  
  - **Selling Price** = Sales ÷ Quantity.  

---

## 🛍️ Categories & Products
- **Top Sales Drivers:**  
  - *Furniture → Chairs*  
  - *Technology → Phones*  
- **Top Profit Drivers:**  
  - *Technology → Copiers*  

⭐ **Star Product:** Canon imageCLASS 2200 Advanced Copier → Appears in both *Top Sales* and *Top Profit*.  
⚠️ **Loss Leaders:** Chairs, GBC Ibimaster → High sales but low profit.  

📌 **Recommendation:** Focus on star products, optimize pricing for low-margin items.  

---

## 👥 Customer Segments
- **Consumers** deliver the highest total profit.  
- **Home Office** customers are the most profitable per order.  

📌 **Insight:** Different segments contribute differently — one drives volume, the other margin.  

---

## 🌍 Regional & Geographic Insights
- **Best Region:** West → highest sales & profit.  
- **Weakest Regions:** Central (profit), South (sales).  
- **Top State:** California.  
- **Top City:** New York.  
- **Lowest Performers:** Texas (state), Philadelphia (city).  

📌 **Recommendation:** Optimize strategy in Central, South, and underperforming states/cities.  

---

## 💸 Discounts & Profitability
- Weak negative correlation (**-0.21**) → Higher discounts slightly reduce profit.  
- **Furniture** suffers the most (**-0.49**).  
- **Tables** sub-category heavily impacted (**-0.67**).  

📌 **Recommendation:** Limit discounts in Furniture/Tables, but consider promotions in Technology/Office Supplies.  

---

## 🚚 Shipping Modes
- **Most Used & Profitable:** Standard Class.  

📌 **Insight:** Customers prefer Standard Class → Keep as core offering, test premium services carefully.  

---

## ⏳ Trends Over Time
- **Yearly:** Sales and orders show steady growth.  
- **Monthly:** Demand peaks in year-end months; profit follows seasonal patterns.  

📌 **Recommendation:** Run aggressive campaigns during seasonal peaks.  

---

## 🏆 Customers (Pareto Principle)
- **Top 20% of customers generate ~80% of sales & profit.**  

📌 **Recommendation:** Retain high-value customers through loyalty programs and personalized offers.  

---

## 📦 Order Quantity vs Profit Margin
- No significant relationship between **quantity ordered** and **profit margin**.  

📌 **Insight:** Bigger orders don’t guarantee higher margins → Pricing strategy matters more than volume.  

---

# 🎯 Final Key Insights
1. **Technology (especially Copiers)** is the strongest profit driver.  
2. **Consumers** generate volume; **Home Office** generates higher per-order profitability.  
3. **West Region + California/New York** dominate profitability.  
4. **Discounts erode profit**, especially in Furniture/Tables.  
5. **Canon Copier** is a flagship product → maintain stock & visibility.  
6. **Customer concentration risk:** Top 20% drive majority of revenue → Retention is crucial.  

---
