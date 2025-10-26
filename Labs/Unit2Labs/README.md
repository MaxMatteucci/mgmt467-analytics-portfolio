# 🎬 Netflix Data Quality — Unit 2 Lab

**Date:** October 23, 2025  
**Author:** Max Matteucci  

---

## 🧩 Colab Notebooks (In case preview is not working.)
Lab 4: ((https://drive.google.com/file/d/1JFTkBlylTe7CdYWk97OoP8814VW4thyx/view?usp=sharing))  
Lab 5 Part 1: (https://drive.google.com/file/d/1yGvaKl-4k4mfKe6wcx2Hyx97x5umwUNq/view?usp=sharing)  
Lab 5 Part 2: (https://drive.google.com/file/d/1R3Zj4V_nzoxTP-q1Dkxs5iIq01IKNb4d/view?usp=sharing)  
Lab 5 Part 3: (https://drive.google.com/file/d/16zpjB3_p-XceZEfosLwK3v_bzxdaDMnZ/view?usp=sharing)  
Lab 6: (https://drive.google.com/file/d/1GfQwX0TjoK29xSDVskmFLDvdbup9Bjb9/view?usp=sharing)


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
