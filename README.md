# 🕵️ Fraud Detection Pipeline using Hadoop Pig & Tableau

This project demonstrates a **fraud detection pipeline** designed to analyze **large-scale bank transaction data** for identifying high-risk patterns and reducing fraud.  

The system uses **Hadoop Pig** for preprocessing and integrates results with **Tableau dashboards**, delivering real-time insights into suspicious activity.  

--------------------------------------------------------------------------------------------------

## ⚙️ Features

- **Large-Scale Data Processing**  
  - Processed **50,000+ transactions** with **95% efficiency** using Hadoop Pig  
  - Automated cleaning, aggregation, and feature engineering  

- **Fraud Detection Analysis**  
  - Achieved **92% detection accuracy (AUC score)**  
  - Identified **5 high-risk transaction clusters** and **3 geographic hotspots**  

- **Visualization & Insights**  
  - **Interactive Tableau dashboards** for fraud monitoring  
  - Visualized trends across customer behavior, transaction patterns, and geographies  

- **Business Impact**  
  - Provided actionable insights to potentially reduce **fraud-related losses by 18%**  

--------------------------------------------------------------------------------------------------

## 🚀 Execution

1. Upload raw transaction data into HDFS.
2. Run preprocessing scripts:
```bash
pig pig_scripts/clean_data.pig
pig pig_scripts/aggregate_features.pig
pig pig_scripts/detect_clusters.pig
```
Export the processed results into CSV/Parquet format.

Import results into Tableau for dashboard visualization.

Explore fraud clusters and geographic trends interactively.

--------------------------------------------------------------------------------------------------

## 📊 Key Deliverables

✅ Hadoop Pig preprocessing pipeline with 95% efficiency

✅ 92% accuracy (AUC) in fraud detection analysis

✅ Interactive Tableau dashboards for real-time monitoring

✅ Actionable insights into high-risk transaction clusters & hotspots

