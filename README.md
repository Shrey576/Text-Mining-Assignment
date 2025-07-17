# Text-Mining-Assignment
- Got 85%

# How to Run
Open .ipynb in working Google browser that supports Colab notebook

# 📈 CTR Optimization & SEO Score Prediction Tool

This project implements a modular pipeline to **forecast and optimize Click-Through Rate (CTR)** over a 5-year horizon. Using **probabilistic forecasting, clustering, and SEO scoring**, the system predicts realistic performance targets and evaluates how closely actual performance aligns with those targets.

---

## 🔍 Project Overview

The goal of this tool is to assist SEO analysts, digital marketers, or research professionals in:

- Forecasting future CTR values using a **Gaussian (normal) distribution**
- Grouping predicted CTR values into **performance ranges** using **K-Means clustering**
- Selecting the most **realistic high-performance CTR target**
- Comparing that target with actual performance
- Calculating an **SEO Score** to assess alignment with ideal outcomes
- Visualizing the full process

---

## 🧠 Methodology

1. **CTR Forecasting**  
   Uses a Gaussian distribution to simulate a range of future CTR (%) values over a 5-year period.

2. **Clustering**  
   K-Means clustering is applied to the forecasted CTR values to identify meaningful performance groupings (e.g. low, average, high).

3. **Optimal CTR Selection**  
   The centroid (mean) of the best-performing cluster is chosen as the optimal forecasted CTR target.

4. **Evaluation & SEO Scoring**  
   The actual observed CTR is compared to the optimal forecasted value. The difference is used to compute an SEO Score (scaled 0–1).

5. **Visualization**  
   A line chart is generated showing:
   - Forecasted values
   - Clusters
   - Optimal CTR value
   - Actual CTR

---

## ⚙️ Features

- Fully modular design (forecasting, clustering, evaluation, visualization)
- Probabilistic CTR prediction over time
- SEO score generation for model alignment
- Clear and interpretable outputs
- Designed with explainability in mind for non-technical users

