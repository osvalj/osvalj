# Hi, I'm Osval 👋

I'm a data scientist with a background in analytics, currently finishing a Master's in Data Science & AI. My work sits at the intersection of machine learning and business intelligence — I build things that are technically solid and actually useful to the people who need them.

What I've learned from working in analytics is that the hardest part is rarely the model. It's framing the right question, communicating the result clearly, and making sure something gets decided because of the work. I carry that mindset into everything I build.

---

## Projects

**Cardiovascular Disease Risk Predictor** *(in progress)*  
A web application for cardiovascular risk assessment, designed for both patients and primary care physicians. Built around a supervised ML model with SHAP-based explainability — so the predictions aren't just accurate, they're interpretable by clinicians and patients who need to trust them. Includes longitudinal tracking to monitor how risk evolves over time. Interface in Spanish.

I've been deliberate about the clinical framing before writing a single line of code. Getting the problem definition right matters more than getting to deployment fast.

---

**Windows Defender Malware Detection** — [view repository](#)  
Binary classification on Microsoft's Windows Defender telemetry dataset. The modeling part was straightforward; the real work was in the pipeline — hundreds of features with mixed types, high cardinality, and a lot of missing data that each needed a different treatment decision.

We built a custom `EDAInspector` class to track every preprocessing decision (what to drop, what to impute, and why), three separate sklearn pipelines for numeric, low-cardinality, and high-cardinality features, and tuned the classification threshold explicitly — because in malware detection, a false negative isn't the same cost as a false positive.

*Stack: Python · scikit-learn · Pandas · Decision Tree · RandomizedSearchCV*

---

**Ecommerce Performance Analysis with GA4** — [view repository](https://github.com/osvalj/ecommerce-ga4-business-analysis)  
An end-to-end business analysis of an ecommerce platform dealing with a specific problem: traffic was growing but revenue wasn't. I worked through funnel drop-offs, channel efficiency, and product performance to understand where the breakdown was happening — and structured the output as a decision-ready report for a growth or product team, not just a collection of charts.

*Stack: GA4 · BigQuery · SQL · Looker Studio*

---

## How I approach the work

I start with the business question and work backward from there. What decision does this need to support? What would "wrong" look like in practice? That framing shapes everything — what data to use, how to model it, and how to present it.

On the technical side, I'm strict about reproducibility: clean preprocessing pipelines, proper train/validation/test splits, no data leakage. And I put real weight on explainability — if a model influences something that matters to real people, the people using it need to understand why it's saying what it's saying.

---

## Stack

**Data Science & ML**  
Python · scikit-learn · Pandas · NumPy · Matplotlib · Seaborn  
SHAP · ydata-profiling · Sweetviz  
Supervised learning · Feature engineering · Pipeline design · Threshold tuning

**Analytics & BI**  
SQL · BigQuery (GCP) · MySQL  
Google Analytics 4 · Looker Studio · Power BI · Tableau  
Google Sheets / Excel

*Google Analytics (GA4) certified.*

---

## Contact

📧 hernandez.velez.oj@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/osvalhernandez)
