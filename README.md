# Krutarth Shah

Based in Pennsylvania, USA and open to opportunities across the US.

---

## About Me

I am a data professional with a Master of Information Systems Management 
from Carnegie Mellon University. My background sits at the intersection of 
engineering and analytics. I have built production data pipelines, deployed 
AI systems, run statistically rigorous experiments, and translated findings 
into decisions that leadership actually acted on.

I started in software engineering, moved into marketing analytics, and then 
deliberately pushed toward data, building systems at each step rather than 
just consuming them. That path gave me something most analysts don't have: 
I understand how data is generated, how it breaks, and how to fix it before 
it reaches a dashboard.

I work best when the problem is ambiguous, the data is messy, and the 
stakeholder needs an answer by Friday.

---

## What I Am Working Toward

I am deepening my expertise at the intersection of data engineering and 
analytics, specifically around building reliable data infrastructure that 
non-technical teams can actually trust and use independently.

Beyond the technical side, I am focused on developing the instinct to ask 
the right business question before writing the first query. The best analysis 
I have done started not with a dataset but with a conversation about what 
decision actually needed to be made.

Longer term, I want to work on problems where the data has real stakes, 
healthcare outcomes, financial decisions, operational efficiency, where 
getting the analysis wrong has consequences worth caring about.

---

## Projects
### [E-Commerce Data Platform](https://github.com/Kss6111/ecommerce-data-platform)
`Kafka` `Spark Structured Streaming` `PySpark` `Airflow` `AWS S3` `Delta Lake` `Snowflake` `dbt` `Great Expectations` `Terraform` `GitHub Actions` `Metabase` `Docker`

End-to-end data engineering platform handling both real-time streaming and batch ingestion in a single architecture. Kafka ingests order events, clickstream, and inventory updates into Spark Structured Streaming, landing in Delta Lake on AWS S3. PostgreSQL operational data is batch-extracted daily. Airflow orchestrates both pipelines. dbt transforms raw Snowflake data through 18 models with 106 passing tests into five mart tables. Great Expectations validates data quality at the raw layer. Metabase serves the analytics dashboard.

🔗 

---

### [Marketing Analytics Platform with A/B Testing](https://github.com/Kss6111/marketing-analytics-platform)
`Airflow` `PySpark` `BigQuery` `Python` `Tableau` `Docker`

End-to-end marketing data pipeline on real Google Analytics data (366 days, 12,221 records).
Conducted A/B test across 247,460 sessions finding CPC converts at 2x the rate of organic 
traffic with 168% higher revenue per session ($1.72 vs $0.64), all statistically significant 
(p < 0.000001).

🔗 [Live Tableau Dashboard](https://public.tableau.com/views/marketing_analytics_dashboard/MarketingAnalyticsDashboard)

---

### [E-Commerce Sales Analytics Pipeline - Olist Dataset](https://github.com/Kss6111/ecommerce-pipeline)
`Snowflake` `dbt` `Python` `Power BI` `VADER` `Prophet` `Scikit-learn`

ELT pipeline loading 100K+ orders into Snowflake across 14 dbt models.
Analyzed $15.42M in revenue via Power BI. Applied VADER NLP to 99K reviews,
K-Means RFM clustering, and Prophet time-series forecasting on 22 months of data.

📊 [Sales Overview Dashboard](https://github.com/Kss6111/ecommerce-pipeline/blob/main/visuals/dashboard_sales_overview.png) | [Customer Insights Dashboard](https://github.com/Kss6111/ecommerce-pipeline/blob/main/visuals/dashboard_customer_insights.png)

---

### [ResumeAI - AI-Powered Resume Screening System](https://github.com/Kss6111/ResumeAi-IAI-group-project)
`Python` `Gemini API` `Sentence-Transformers` `Streamlit` `FastAPI` `RapidFuzz`

Automated resume ranking system using two-stage semantic ranking
(bi-encoder + cross-encoder re-ranking) and LLM-based parsing via Gemini API.
Achieved 207% improvement in candidate identification accuracy over baseline keyword matching.
Processes 100 resumes in under 3 minutes with explainable score breakdowns.

---

### [Customer Churn Analysis](https://github.com/Kss6111/customer-churn-analysis)
`PostgreSQL` `Python` `Tableau` `Scikit-learn`

Identified month-to-month customers churn at 15x the rate of two-year subscribers,
flagging $139K monthly revenue at risk across 7,043 records.
Logistic regression model (89% accuracy) with actionable retention recommendations.

🔗 [Live Tableau Dashboard](https://public.tableau.com/views/CustomerChurnAnalysisTelecomDataset/Dashboard)

---

### Tech Stack

**Languages:** Python, SQL, Scala (basic), JavaScript, Java

**Data Engineering:** Kafka, Spark Structured Streaming, PySpark, Apache Airflow, dbt Core, Snowflake, BigQuery, AWS S3, Delta Lake, PostgreSQL, Docker, Docker Compose, Terraform, GitHub Actions, Great Expectations

**Analytics and BI:** Tableau, Power BI, Metabase, Looker Studio, Google Analytics

**Machine Learning and AI:** Scikit-learn, TensorFlow, PyTorch, Sentence-Transformers, VADER, Prophet, Gemini API, LangGraph

**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, RapidFuzz

**Tools:** Git, Streamlit, FastAPI, REST APIs, Jira

---

## Connect

📧 krutarts@alumni.cmu.edu
💼 [LinkedIn](https://linkedin.com/in/krutarthsshah)
