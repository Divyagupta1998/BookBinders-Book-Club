# Bookbinders Book Club - Direct Mail Campaign Optimization

---

## Project Summary
Bookbinders Book Club (BBBC), a direct marketing company specializing in specialty books, faced challenges in optimizing customer engagement and improving response rates to direct mail campaigns.  
With changing consumer behaviors and increased competition, BBBC aimed to enhance the effectiveness of its direct mail marketing by **predicting customer purchasing decisions**.

---

## Problem
- Optimize customer engagement for direct mail campaigns.  
- Predict purchasing decisions using customer attributes such as:  
  - Gender  
  - Book category  
  - Purchase frequency  
  - Recency of purchase  
  - Spending behavior  

---

## Approach
To address this challenge, we applied **three predictive modeling techniques**:

1. **Ordinary Linear Regression**  
   - Identified key factors influencing customer purchases.  

2. **Binary Logit Model**  
   - Predicted purchase probabilities based on spending, gender, recency, and product preferences.  

3. **RFM Segmentation (Recency, Frequency, Monetary)**  
   - Segmented customers into high, medium, and low-value groups for targeted marketing.  

**Validation:**  
- Training dataset: 1,600 customers  
- Holdout sample: 2,300 customers  
- Best performance: **Binary Logit Model** with **82.34% accuracy**  

---

## Solution
Based on model insights, recommendations include:  
- Focus marketing efforts on **females** and customers interested in **art books**.  
- Prioritize **recent buyers** and **high monetary value customers** from RFM segmentation.  
- Use the **Binary Logit Model** to refine targeting strategies and improve campaign efficiency.  

**Expected Outcomes:**  
- Improved targeting will increase customer engagement and sales.  
- Direct mail response rates projected to boost profit from **$23,875 → $95,500**.  

---

## Future Recommendations
- Explore **dynamic modeling techniques** such as:  
  - Time-series analysis for evolving customer trends.  
  - Cross-selling opportunities for long-term growth.  
- Continuously adapt models to keep pace with **changing consumer behaviors**.  

---
