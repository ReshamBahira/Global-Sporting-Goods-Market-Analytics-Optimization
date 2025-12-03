# Global-Sporting-Goods-Market-Analytics-Optimization

## **📌 Introduction**

This project provides a comprehensive analysis of a global sporting goods retailer’s transactional dataset to uncover insights across three major domains:

* International **market segmentation**
* **Discount optimization**
* **Delivery risk prediction**

The findings support strategic decision-making in pricing, promotions, and supply chain operations.

---

## **🎯 Objectives**

### **1. Competitive Market Analysis by Country**

* Segment countries based on product preferences and pricing behavior
* Identify premium vs. price-sensitive markets
* Apply clustering to understand international demand patterns

### **2. Discount Effectiveness Analysis**

* Determine optimal discount ranges to maximize profitability
* Study how discounts impact revenue, sales volume, and margin
* Identify regions that respond better to promotional strategies

### **3. Supply Chain Risk Modeling**

* Predict late delivery probabilities using machine learning
* Identify key factors influencing supply chain delays
* Recommend improvements to shipping and logistics workflows

---

## **📊 Visualizations**

* Treemaps of category-wise sales by country
* Bar charts for average price comparisons
* Cluster maps for country segmentation
* Logistic regression coefficient plots for delivery risk factors

---

## **🧪 Methodology**

### **Data Processing**

* Data cleaned and transformed using **PySpark** for scalability
* Managed missing values and high-cardinality features (e.g., ZIP codes)
* Applied one-hot encoding, feature scaling, and dimensionality reduction

### **Modeling Techniques**

* **Regression Models:** Random Forest, XGBoost, Ridge Regression
* **Classification:** Logistic Regression
* **Clustering:** KMeans for international segmentation
* **Evaluation Metrics:** RMSE, R², Precision, Recall, F1-Score, ROC-AUC

---

## **📈 Results**

### **🔹 Market Segmentation & Clustering**

* KMeans clustered 35+ countries into **4 distinct market segments**:

  * **Premium Markets:** Western Europe, Oceania
  * **Mid-Tier Regions:** Central America, Southeast Asia
  * **Price-Sensitive Markets:** Eastern Europe, Africa, USCA
* Enabled targeted pricing strategies
* Achieved a **15% increase in ROI** from region-specific promotions

---

### **🔹 Sales Forecasting**

**Models Used:** Random Forest, XGBoost
**Best Model:** XGBoost

* **RMSE:** 0.43
* **R²:** 0.60
* Improved forecast accuracy by **33% over baseline**
* Enhanced pricing and supply chain planning

---

### **🔹 Discount Optimization**

* Identified optimal discount range of **10%–25%**
* Found that standardized discounts alone had **weak correlation** with sales
* Recommended **region-tailored discounting strategies**
* Helped preserve profit margins while improving campaign performance

---

### **🔹 Late Delivery Risk Modeling**

**Model Used:** Logistic Regression

* **Accuracy:** 93.29%
* **Precision:** 90.37%
* **Recall:** 94.37%
* **ROC-AUC:** 98.38%
* High recall ensured effective identification of risky shipments
* Supported logistics planning and improved customer satisfaction

---

## **🚧 Limitations**

* **Data Imbalance:** Sparse data from certain regions and product categories
* **High Cardinality:** ZIP codes and customer regions required careful encoding
* **Risk of Overfitting:** Especially with XGBoost on small segments
* **Missing Operational Data:** No real-time warehouse or courier metrics

---

## **🔮 Future Work**

* Integrate real-time logistics data for improved delivery risk prediction
* Deploy an interactive dashboard for stakeholder use
* Build a **dynamic discounting system** that adapts by region/category
* Add customer segmentation for improved personalization
* Explore deep learning models (LSTM, Transformers) for time-series forecasting

---

## **📈 Business Impact**

* **Revenue Optimization:** Improved pricing and promotion strategies
* **Operational Efficiency:** Better management of high-risk shipments
* **Margin Protection:** Smarter discount strategies reduced unnecessary spend
