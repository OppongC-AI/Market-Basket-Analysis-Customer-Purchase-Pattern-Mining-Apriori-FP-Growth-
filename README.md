# Market-Basket-Analysis-Customer-Purchase-Pattern-Mining-Apriori-FP-Growth-
🚀 Overview

This project applies data mining and association rule learning techniques to uncover hidden purchasing patterns in retail transaction data.

Using Apriori and FP-Growth algorithms, the system identifies:

Frequently purchased item combinations
Strong association rules between products
Customer buying behavior patterns

The ultimate goal is to translate data into actionable business strategies like product bundling, cross-selling, and inventory optimization.

Dataset: UCI Online Retail dataset with 500,000+ transactions

🧠 Key Features
🛒 Market Basket Analysis
Identifies products frequently bought together
Generates association rules for business insights
⚡ Algorithm Comparison
Apriori vs FP-Growth
Same results, but FP-Growth is significantly faster
📊 Advanced Rule Evaluation

Analyzed rules using:

Support
Confidence
Lift
Leverage
Conviction
Kulczynski
Jaccard
🔍 Pattern Discovery
Strong relationships found in product variations (e.g., themed items like teacup sets)
High lift values (>20) indicate strong co-purchase behavior
🛠️ Tech Stack
Python
Pandas
mlxtend (Apriori, FP-Growth)
NumPy
Matplotlib
📂 Dataset
Source: UCI Machine Learning Repository
~500,000 transactions
Features include:
Invoice ID
Product Description
Quantity
Price
Customer ID
Country

Data preprocessing included:

Removing invalid transactions (negative/zero values)
Feature engineering (total spend, items per invoice)
Sampling for computational efficiency
⚙️ Methodology
Data Cleaning & Preparation
Transaction Encoding
Frequent Itemset Generation
Apriori
FP-Growth
Association Rule Mining
Rule Evaluation using multiple metrics
Business Insight Generation
📊 Key Results
Identified high-confidence rules (>80%) for product combinations
Discovered extremely strong associations (Lift > 20)
Example insight:
Customers buying one variation of a product (e.g., color variants) are highly likely to buy others

From the tables on pages 5–7, rules like:

Teacup product combinations showed:
Confidence: ~0.90
Lift: >22
Strong bidirectional relationships
💡 Business Recommendations
🎯 Product Bundling
Bundle highly associated products (e.g., color variants)
🛍️ Cross-Selling
Recommend complementary items during checkout
🏬 Product Placement
Group related items physically or digitally
📦 Inventory Optimization
Maintain stock for frequently co-purchased products
🎄 Seasonal Strategy
Leverage seasonal purchasing patterns for promotions
⚠️ Limitations
Apriori is computationally expensive (required sampling)
No real-time recommendation system implemented
No customer segmentation deployed in production
🔮 Future Improvements
Real-time recommendation engine
Integration into e-commerce platforms
Customer segmentation (clustering)
Deep learning-based recommendation systems
