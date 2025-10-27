# 🎬 Data Quality — Unit 2 Labs

**Date:** October 23, 2025  
**Author:** Max Matteucci  

---

## 🧩 Colab Notebooks (In case preview is not working.)
-All Colab files run, but when uploading to GitHub, I am having issues getting it to display.  It also was not displaying on the Professor's GitHub, so it's either on my side or a glitch in Colab.  I also included raw colab links below.

Lab 4: ((https://drive.google.com/file/d/1JFTkBlylTe7CdYWk97OoP8814VW4thyx/view?usp=sharing))  
Lab 5 Part 1: (https://drive.google.com/file/d/1yGvaKl-4k4mfKe6wcx2Hyx97x5umwUNq/view?usp=sharing)  
Lab 5 Part 2: (https://drive.google.com/file/d/1R3Zj4V_nzoxTP-q1Dkxs5iIq01IKNb4d/view?usp=sharing)  
Lab 5 Part 3: (https://drive.google.com/file/d/16zpjB3_p-XceZEfosLwK3v_bzxdaDMnZ/view?usp=sharing)  
Lab 6: (https://drive.google.com/file/d/1GfQwX0TjoK29xSDVskmFLDvdbup9Bjb9/view?usp=sharing)

(I also included BrightSpace labs in the similarly named folder, as those instructions were different and I did not want to miss anything.)
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

Comprehensive Reflection — Labs 1–3

Lab 1 — Kaggle → GCS → BigQuery → Data Quality
This lab built the foundation for working in the Google Cloud ecosystem. I learned how to authenticate securely, manage Kaggle API keys, and stage datasets in GCS to ensure reproducibility and version control. Loading data into BigQuery with verification steps made me appreciate the importance of clean pipelines and proper project configuration. The data quality profiling section (missingness, duplicates, outliers) demonstrated how early data checks prevent costly downstream errors in analytics or modeling.

Lab 2 — Churn Modeling & Feature Engineering (BQML)
This lab transitioned from raw data to predictive modeling. I learned how to structure feature engineering workflows, create meaningful predictors, and run BigQueryML classification models efficiently in SQL. Experimenting with variable transformations and balance checks helped me understand how to improve model performance and interpretability. The integration of engineering, modeling, and evaluation steps in one cloud environment reinforced the importance of scalability and automation in production-ready analytics.

Lab 3 — Logistic Regression & Model Interpretation (BQML)
In the final lab, I focused on applying and interpreting logistic regression models in BigQueryML. I explored coefficient meaning, model fit metrics (AUC, precision, recall), and the practical implications of those values for decision-making. Seeing how small feature changes affected model accuracy helped strengthen my intuition for modeling tradeoffs. This lab tied together the previous two by emphasizing statistical rigor and explainability alongside cloud efficiency.

Overall Summary
Together, these labs built a complete cloud analytics pipeline: ingesting and staging data (Lab 1), engineering and modeling features (Lab 2), and interpreting and evaluating models (Lab 3). I now understand both the technical and conceptual flow from data acquisition to business insight, and how each stage connects in a reproducible, auditable way within Google Cloud.
