# Customer Segmentation Using RFM Analysis

This project demonstrates how to apply **RFM (Recency, Frequency, Monetary)** analysis for customer segmentation using order transaction data. The objective is to understand customer purchasing behaviors and group them into segments that can be targeted with personalized marketing strategies.

## 📊 Project Objectives

- Calculate Recency, Frequency, and Monetary metrics for each customer.
- Assign RFM scores based on business rules.
- Segment customers based on RFM scores.
- Provide actionable insights to improve customer engagement and retention.

## 📁 Dataset

The dataset contains customer order information including:
- Customer ID
- Frequency of purchases
- Recency (days since last purchase)
- Total monetary value of purchases

## ⚙️ Tools Used

- Python (pandas, numpy)
- Microsoft Excel
- RFM scoring logic
- Documentation in Word format

## 🔍 Methodology

1. Preprocessed the transaction data to extract R, F, and M metrics.
2. Applied percentile-based segmentation to assign scores (1-3 scale).
3. Calculated the RFM score by combining individual scores.
4. Segmented customers into groups (e.g., high value, loyal, at-risk).
5. Derived key business insights.

## 🧠 Key Insights

- 33% of customers purchased within the last 49 days.
- Customers with RFM scores like `333`, `331`, etc. are highly engaged and valuable.
- Customers with scores like `111`, `112` may need win-back strategies.

## 📌 Project Files

- `Orders.xlsx` – Source dataset with RFM calculation.
- `RFM_Analysis_Project_Documentation.docx` – Full project report.
- `README.md` – Project overview and instructions.

## 📈 Potential Extensions

- Add customer segmentation visualizations (bar charts, heatmaps).
- Build dashboards using Tableau or Power BI.
- Deploy customer segmentation model using Streamlit or Flask.

---

**Author:** Ayan Jawaid  

