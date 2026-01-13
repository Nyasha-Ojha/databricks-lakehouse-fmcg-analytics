# databricks-lakehouse-fmcg-analytics
Production-ready Databricks Lakehouse project showcasing FMCG analytics, governed data pipelines, and parent–child enterprise reporting.

This project implements an enterprise-grade FMCG analytics platform using the Databricks Lakehouse architecture. It is designed to simulate how large organizations ingest, process, govern, and analyze data at scale, with a strong focus on real-world business reporting and decision-making. The solution follows modern data engineering principles and mirrors production systems used in FMCG, retail, and consumer analytics teams.

# Architecture Diagram
<img width="20005" height="11129" alt="project_architecture" src="https://github.com/user-attachments/assets/b1b7bd1a-439c-43ba-96ea-5513958c11c0" />
The data pipeline is built using a Bronze–Silver–Gold layered architecture, where raw sales data is ingested from Amazon S3 into Bronze tables, cleansed and standardized in the Silver layer, and transformed into analytics-ready Gold datasets. Each layer is purpose-driven, ensuring data reliability, scalability, and clear separation of concerns across ingestion, transformation, and reporting.


A key highlight of this project is the parent–child company analytics model, where individual child companies maintain their own Gold-level business metrics while a parent organization consumes consolidated analytics across all subsidiaries. This structure reflects real enterprise scenarios involving multi-brand or multi-region organizations and enables both decentralized data ownership and centralized reporting.

The platform leverages Databricks-native tools including Lakeflow Jobs for orchestration, Unity Catalog for governance and access control, and Databricks SQL for analytics delivery. Business insights are served through interactive SQL dashboards and enhanced with Databricks Genie, allowing stakeholders to query Gold tables using natural language without requiring SQL expertise.

Overall, this project demonstrates a production-ready data engineering workflow, combining scalable cloud storage, governed transformations, automated orchestration, and business-focused analytics. It showcases not only technical implementation but also architectural decision-making, data modeling, and analytics design aligned with how modern data teams operate in enterprise environments.

# Results:
![FMCG1](https://github.com/user-attachments/assets/3398bc10-379b-4258-afed-7adfc1f3da4b)

![FMCG2](https://github.com/user-attachments/assets/9364636d-66d6-4c4b-93c0-1899a54b98ab)

# Acknowledgement
This project was inspired by learning resources from the Databricks and data engineering community.
Conceptual guidance for the Lakehouse architecture and Bronze–Silver–Gold design pattern was derived from various YouTube tutorial but special thanks to by @Ansh_Lamba and @codebasics.




