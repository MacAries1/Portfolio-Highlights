# 🧠 Portfolio Highlights
Welcome! This repo showcases my most impactful work across data engineering, orchestration, and performance optimization. Each project reflects my commitment to reproducibility, modularity, and clarity—whether tuning SQL pipelines, wiring Airflow DAGs, or visualizing data flows with D3.js.

---

## 🔧 Featured Projects

### Ironman API Sync Optimization
- **Problem:** Hourly syncs were slow and unreliable due to nested CTEs and ambiguous EventIDs.
- **Solution:** Refactored queries, replaced EventID with a stable surrogate key, and implemented retry logic.
- **Impact:** Reduced sync time by 60%, improved reliability, and enabled hourly updates without manual intervention.
- **Repo:** *(Coming soon)*
### SCDOT DataMart & Dashboard (2-week delivery)
- **Tools:** SQL Server, SSRS, T-SQL, Kimball methodology
- **Challenge:** Deliver a complete DataMart and dashboard for South Carolina Department of Transportation under tight deadlines.
- **Solution:** Designed a dimensional model using Kimball principles, implemented ETL pipelines, and built SSRS dashboards aligned with stakeholder KPIs.
- **Impact:** Delivered a fully functional reporting solution in 2 weeks, enabling clear visibility into transportation metrics and decision-making.
- **Highlights:** 
  - Modeled fact and dimension tables with clear grain and lineage
  - Tuned stored procedures for performance and maintainability
  - Documented schema and ETL flow for reproducibility
- **Repo:** *(Coming soon)*
- ### Constructing a Web Server Using Kafka (MIT xPro Project 24.2)
- **Tools:** Python, Flask, Kafka, Docker, REST APIs
- **Challenge:** Build a web server that receives HTTP requests, publishes messages to Kafka, and processes them asynchronously.
- **Solution:** Designed a Flask-based web server that publishes incoming requests to a Kafka topic. A separate consumer service processes the messages and returns structured responses.
- **Impact:** Demonstrated event-driven architecture principles, decoupled service design, and real-time message flow using Kafka.
- **Highlights:**
  - Used Docker Compose to orchestrate Kafka, Zookeeper, producer, and consumer services
  - Implemented robust error handling and logging for message delivery and processing
  - Validated end-to-end flow with test payloads and response tracking
- **Repo:** [Required_Project_24.2-Constructing_a_Web_Server_Using_Kafka](https://github.com/MacAries1/Required_Project_24.2-Constructing_a_Web_Server_Using_Kafka)
