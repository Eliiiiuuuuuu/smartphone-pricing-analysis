# 📱 Smartphone Pricing Analysis

This project investigates what drives smartphone pricing on Amazon — is it technical specifications (like RAM and storage) or brand influence?

---

## 🔍 Business Question

- How much do hardware specs influence smartphone prices?
- Is there a clear brand premium beyond specs?
- Are high-rated phones mainly from well-known brands?

---

## 📊 Dataset

- Source: Amazon Cell Phone Listings from Kaggle
- Sample Size: 1,000+ phones (Nov 2005 – May 2025)
- Key variables: RAM, Storage, Screen Size, Brand, Rating, Price

---

## 🧠 Methods

- Binning & Averaging (specs vs. price trends)
- Multivariate Regression (evaluate individual contribution)
- Value Score Construction: `(rating / price) * log(review_count + 1)`

---

## 📌 Key Findings

- RAM and rating show some correlation, but low explanatory power (R² = 0.019)
- After adding **brand dummy**, R² increases to 0.34 → brand matters much more
- Top “value-for-money” phones tend to be low-cost, niche brands
- High-rated phones are predominantly from Xiaomi, Samsung, Huawei → brand trust matters

---

## 🖼️ Key Visuals

<img src="charts/amazon_data_snapshot.png.png" width="400"/>  
<img src="charts/high_rating_brands.png.png" width="400"/>  
<img src="charts/regression_comparison_withbrand.png.png" width="400"/>
<img src="charts/regression_without_brand.png.png" width="400"/>
<img src="specs_vs_price.png.png" width="400"/>
<img src="charts/value_score_ranking.png (2).png" width="400"/>
img src="charts/value_score_ranking.png.png" width="400"/>

---

## 📁 Project Structure

