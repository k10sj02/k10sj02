# Hi, I’m Stann 👋🏽

I build end-to-end data systems that turn messy real-world data into decisions about where to focus, who to prioritize, and how to allocate limited resources.

> Previously built systems used across:  
> → $16B+ in modeled fundraising portfolios  
> → 500K+ leads scored in production CRM pipelines  
> → 150K+ voter outreach interactions across 13 U.S. states and 5 Canadian provinces, spanning 1200+ communities

Most of my work lives at the intersection of:  
→ analytics engineering  
→ applied modeling  
→ product thinking  

Often in environments where the data is incomplete, biased, or operationally messy (fundraising, civic tech, campaigns, early-stage startups).  

In practice, much of my work involves building data systems that help organizations decide who to ask, how much to ask, and when to ask — whether the audience is donors, voters, or customers.

---

## 🚀 Featured Projects

### 🗳️ Voter Engagement Targeting & Analytics System  
End-to-end data pipeline and targeting system for a national voter outreach campaign across 13 U.S. swing states, uncovering previously unknown outreach locations and shaped targeting and deployment strategy across 15,000+ engagement sites.

→ designed and operationalized the geospatial targeting pipeline (Google Places → Census enrichment → BigQuery)  
→ partnered with messaging analytics pipeline (ThruText → S3 → GCS → BigQuery) to enable downstream reporting

→ developed a **service density KPI** to quantify outreach coverage vs real-world infrastructure  
→ identified **400K+ locations** and prioritized high-impact communities for outreach  

🔗 https://github.com/k10sj02/barbershop-voter-engagement-analytics  

---

### 💸 Donor Retention & Propensity System
Donor propensity scoring system for nonprofits modeled on real fundraising workflows, built to prioritize outreach toward highest value donors most likely to give again.  

→ engineered 15+ RFM and donor profile features from transactional data to capture giving lifecycle behavior  
→ trained Random Forest classifier (ROC-AUC 0.87, 2.5x lift at top 33%) to predict likelihood of repeat giving  
→ designed four-tier segmentation framework (High / Medium / Low / Very Low) with actionable outreach guidance per tier  

→ deployed as an interactive Streamlit app with CSV ingestion, column mapping, live filtering, and export for fundraising teams

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
- designing **metrics that actually reflect real-world behavior**  
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
