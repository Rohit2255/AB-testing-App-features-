# 🧪 A/B Testing for App Feature Optimization

This project demonstrates how A/B Testing can be used to statistically evaluate the impact of product or UI changes on user conversion. It simulates a real-world scenario where two versions of a fintech app interface are tested to determine which one drives more user conversions.

---

## 📌 Project Overview

**A/B Testing** is a method of comparing two versions of a web page, app feature, or product strategy to determine which one performs better based on a measurable outcome — in this case, **conversion rate**.

- **Group A**: 490 users, 53 conversions → **10.82%**
- **Group B**: 510 users, 86 conversions → **16.86%**

We performed a **Z-Test for Proportions** to statistically validate whether the observed difference is significant.

---

## 🧠 Objectives

- Understand the concept of A/B Testing
- Use statistical hypothesis testing (Z-Test) to determine significance
- Visualize conversion metrics and uplift
- Make business decisions based on data, not assumptions

---

## 🔍 Key Steps

1. **Data Setup**: Simulated conversion data for Group A and B  
2. **Conversion Rate Calculation**  
3. **Statistical Hypothesis Testing (Z-Test)**  
4. **Visualizations**:
   - 📊 Bar Chart for Conversion Rate
   - 🧱 Stacked Bar for Converted vs Non-converted
   - 🎯 Z-Score Distribution (Normal Curve)
   - 🚀 Conversion Lift Analysis

---

## 📊 Results

- **Z-Statistic**: -2.76  
- **P-Value**: 0.0057  
- ✅ **Conclusion**: Statistically significant difference. Group B performs better. We reject the null hypothesis.

---

## 🧰 Tech Stack

- **Language**: Python  
- **Libraries**: Pandas, Matplotlib, Seaborn, SciPy  
- **Concepts**: Hypothesis Testing, Z-Test, Visualization, A/B Testing

---

## 🧪 What is A/B Testing?

A/B Testing is a user experience research methodology. It consists of a randomized experiment with two variants (A and B). It is a way to compare two versions of a single variable to determine which one performs better in a controlled setting.


---
## 🤝 Connect with Me

📌 I'm exploring 100 Days of Finance Data Science — and this was Day 11!

- 💼 LinkedIn: [Rohit Kumar Yadav](https://www.linkedin.com/in/rohit-kumar-yadav-b97360194/)
- 🐦 Twitter/X: [@ashwathama56](https://x.com/ashwathama56)
- 📧 Email: ry661432@gmail.com

Feel free to connect for collaboration, feedback, or to just geek out on Data Science in Finance 🚀

---

## 🏷️ Tags

`A/B Testing` `Conversion Optimization` `Z-Test` `Data Science` `Product Analytics` `Fintech` `Python` `100DaysOfDataScience`

---

## 🚀 Getting Started

```bash
git clone https://github.com/Rohit2255/AB-testing-app-features.git
cd ab-testing-app-features
jupyter notebook AB testing App features.ipynb



