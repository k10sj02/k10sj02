# Hi, I’m Stann 👋🏽

I build end-to-end data systems that turn messy real-world data into decisions about where to focus, who to prioritize, and how to allocate resources.

> Previously built systems used across:  
> → $15B+ modeled fundraising portfolios  
> → 40K+ lead scoring pipelines  
> → 500K+ voter outreach interactions across 13 U.S. states and 5 Canadian provinces

Most of my work lives at the intersection of:  
→ analytics engineering  
→ applied modeling  
→ product thinking  

Often in environments where the data is incomplete, biased, or operationally messy (fundraising, civic tech, campaigns).

---

## 🚀 Featured Projects

### 🗳️ Voter Engagement Targeting & Analytics System  
End-to-end data pipeline and targeting system for a national voter outreach campaign across 13 U.S. swing states, uncovering previously unknown outreach locations and driving targeting and deployment across 15,000+ outreach locations.

→ designed and operationalized the geospatial targeting pipeline (Google Places → Census enrichment → BigQuery)  
→ partnered with messaging analytics pipeline (ThruText → S3 → GCS → BigQuery) to enable downstream reporting

→ developed a **service density KPI** to quantify outreach coverage vs real-world infrastructure  
→ identified **400K+ locations** and prioritized high-impact communities for outreach  
→ informed targeting and deployment strategy across **15,000+ engagement sites**

🔗 https://github.com/k10sj02/barbershop-voter-engagement-analytics  

---

### 💸 Donor Retention & Propensity System
Production-style donor scoring system modeled on real fundraising workflows, prioritizing high-probability and dormant donors to improve allocation of fundraising effort.

→ engineered RFM features from transactional donation data to reflect donor lifecycle behavior  
→ trained logistic regression model (AUC ~0.82) to predict likelihood of repeat giving
→ designed segmentation framework (Low / Medium / High) to support prioritization and outreach strategy

→ deployed as an interactive application for scoring, filtering, and operational use by fundraising teams

🔗 https://github.com/k10sj02/nonprofit-donor-scoring  

---

### 🧠 Behavioral Modeling: Gender Norms  
Predictive modeling and validation study on how social norms shape behavior, highlighting the limits of prediction in complex, real-world data.

→ trained classification models (Random Forest, Logistic Regression) on attitudinal survey data  
→ identified a **hard performance ceiling (~0.65 AUC)** and investigated underlying causes of limited predictability  
→ traced constraints to survey design, measurement limitations, and noise in self-reported attitudes  

→ paired modeling with a literature review to contextualize results within social science research  

→ deployed an interactive app to surface predictions and feature-level drivers  

🔗 https://github.com/k10sj02/gender-norms-predictor  

---

## 🧪 What I Focus On

- building **systems**, not one-off analysis  
- turning data into **decisions, not dashboards**  
- designing **metrics that actually reflect reality**  
- working in **imperfect, real-world data environments**  

---

## ⚙️ Tech

**Core:** SQL, Python  
**Warehousing:** BigQuery, Snowflake, PostgreSQL, dbt  
**Apps & Viz:** Streamlit, Tableau, Power BI, Looker  
**Infra:** GCP, AWS, Docker, Git  

---

## 🌐 Elsewhere

Portfolio: https://stannomarjones.com  
LinkedIn: https://linkedin.com/in/stannomarjones  
