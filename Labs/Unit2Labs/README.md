# 🎬 Netflix Data Quality — Unit 2 Lab

**Date:** October 23, 2025  
**Author:** Max Matteucci  

---

## 🧠 What & Why
This project cleans and validates the `netflix` dataset hosted in Google BigQuery.  
It includes row-count verification, missingness checks, deduplication, outlier capping, and anomaly flag creation.  
All queries are designed for **reproducibility** so others can rerun and audit the process.

---

## ☁️ Environment Details
- **Project ID:** `database-project-467`
- **Region:** `US`
- **Bucket:** `netflix-lab-bucket`
- **Dataset:** `netflix`

---

## 📦 Current Table Row Counts
| Table Name | Row Count |
|-------------|------------|
| users | 30,000 |
| reviews | 85,000 |
| watch_history | 315,000 |
| watch_history_dedup | 100,000 |
| search_logs | 12,000 |
| recommendation_logs | 5,000 |
| movies | 3,120 |
