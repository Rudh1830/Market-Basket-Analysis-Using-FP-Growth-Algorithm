# 🛒 Market Basket Analysis Using FP-Growth Algorithm

## 📌 Overview
This project applies the **FP-Growth algorithm** to a Market Basket Optimization dataset to discover **frequently purchased item combinations** and generate **association rules**.

FP-Growth is a fast and memory-efficient algorithm widely used in retail analytics and recommendation systems to uncover hidden patterns in transactional data.

---

## 📂 Dataset
- Market_Basket_Optimisation.csv
- Each row represents a customer transaction
- Each column represents an item purchased in that transaction

---

## ⚙️ Algorithm Used
### FP-Growth (Frequent Pattern Growth)
- No candidate generation (unlike Apriori)
- Uses FP-Tree structure for fast mining
- Efficient for large datasets

---

## 🧪 Methodology
1. Load transaction dataset
2. Convert transactions into list format
3. One-hot encode using TransactionEncoder
4. Apply FP-Growth with `min_support = 0.03`
5. Generate association rules using lift metric
6. Analyze frequent itemsets and strong rules

---

## 🛠️ Technologies Used
- Python
- Pandas
- mlxtend
- Jupyter Notebook / Kaggle

---

## 🚀 How to Run

### Install dependencies
pip install mlxtend

---
📈 Results

Identified frequent itemsets (1-item, 2-item, 3-item)

Discovered strong association rules using lift and confidence

Useful for:

Product bundling

Cross-selling strategies

Recommendation systems

Store layout optimization

🔍 Example Insights

Certain food items are frequently bought together

Strong rules reveal cross-selling opportunities

High-lift item pairs indicate strong customer behavior patterns

---

# 📄 requirements.txt
pandas
mlxtend

---
# **Conclusion**

FP-Growth provides a scalable and efficient solution for market basket analysis, helping businesses make data-driven decisions in retail and e-commerce.

---
