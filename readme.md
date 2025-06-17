# Databricks Data + AI Summit 2025

## Key Announcements

The Databricks Data + AI Summit 2025, held in San Francisco between June 9-12, emphasised Databricks' vision of a **fully-integrated data + AI ecosystem** within its platform, aiming to simplify complex challenges and drive real-world AI innovation. The overarching theme highlighted an accelerated push in AI agent integration, developer experience, and platform governance. These announcements underscore Databricks’ commitment to unifying disparate data and GenAI systems at scale and enabling faster business insights.

### AI/ML Development & Operations

#### [Agent Bricks: Auto-Optimised Agents Using Your Data](https://www.databricks.com/blog/introducing-agent-bricks)
A new **auto-optimised agent builder** designed for creating high-quality, domain-specific AI agents. It simplifies the process by building agents based on task descriptions and automatically handling evaluation and tuning through LLM judges. Features include information extraction, knowledge assistance, multi-agent supervision, and custom LLM agents, with the ability to assess output quality versus cost. [Watch the live demo](https://www.youtube.com/watch?v=ul8cRLIP_Vk&t=6315s)

#### [General Availability of Databricks Apps](https://www.databricks.com/blog/announcing-general-availability-databricks-apps?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
This provides a **verticalised app builder** that streamlines the development and deployment of intelligent applications. It abstracts stack decisions by managing everything through Unity Catalog, enabling developers to quickly build and operationalise GenAI-powered applications using familiar languages like Python and JavaScript in a serverless model. Ideal use-cases include data visualisation, AI applications, self-service analytics and data quality monitoring. [Watch the live demo](https://www.youtube.com/watch?v=ul8cRLIP_Vk&t=4155s)

#### [MLflow 3.0: Build, Evaluate, and Deploy Generative AI with Confidence](https://www.databricks.com/blog/mlflow-30-unified-ai-experimentation-observability-and-governance?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
Unifies AI experimentation, observability, and governance across traditional ML, deep learning, and GenAI development within a single platform, aiming to eliminate the need for separate specialised tools. Capabilities include production tracing, version tracking, quality measurement via LLM judges and production monitoring.

#### [Databricks One](https://www.databricks.com/blog/introducing-databricks-one?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
A new, **code-free and visually redesigned experience** tailored for business users. It provides a unified user experience layer built on the Data Intelligence Platform, allowing non-technical users to explore and query data using natural language (e.g., via the "Genie" feature in AI/BI dashboards). [Watch the live demo](https://www.youtube.com/watch?v=0pys27kA67U&t=7574s)

### Data Engineering & Operations

#### [Lakebase Public Preview](https://www.databricks.com/blog/announcing-lakebase-public-preview?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
Announced as the **first fully-managed, Postgres-compatible transactional database engine** built specifically for developers and AI agents. Lakebase adds an operational database layer to the Databricks Data Intelligence Platform, unifying transactional (OLTP) and analytical (OLAP) data storage. It offers fully independent storage and ßcompute, continuous autoscaling, low latency (sub-10 ms), high concurrency (over 10K QPS), high availability, and **"branching" capabilities** for low-risk AI development and experimentation. [Watch the live demo](https://www.youtube.com/watch?v=ul8cRLIP_Vk&t=2800s)

#### [Lakeflow Designer: No-Code ETL, Powered by the Data Intelligence Platform](https://www.databricks.com/blog/announcing-lakeflow-designer-no-code-etl?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
This is a visual, no-code pipeline builder featuring drag-and-drop functionality and natural language support for creating ETL pipelines. Databricks is also donating its **declarative ETL framework to the Apache Spark open-source project. [Watch the live demo](https://www.youtube.com/watch?v=0pys27kA67U&t=4479s)

#### [Databricks Lakeflow (General Availability)](https://www.databricks.com/blog/announcing-general-availability-databricks-lakeflow?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
Provides a unified approach to data engineering for ingestion, transformation, and orchestration. [Watch the live demo](https://www.youtube.com/watch?v=0pys27kA67U&t=3835s)

#### [Lakebridge: Free, Open Data Migration to Databricks SQL](https://www.databricks.com/blog/introducing-lakebridge-free-open-data-migration-databricks-sql?scid=701Vp00000DUbu0IAD&utm_source=databricks&utm_medium=email)
A **free, AI-powered migration tool** that automates intricate aspects of transitioning from legacy data warehouses to Databricks, including schema translation, optimisation, and data validation. This is intended to significantly reduce the risks and expenses associated with data modernisation.

### Core Platform & Governance Advancements

#### Unity Catalog Enhancements
* Unity Catalog, central to the Databricks Data Intelligence Platform, now offers **complete support for both Apache Iceberg™ and Delta Lake**. This aims to eliminate format silos, allowing **seamless reading (Generally Available) and writing (Public Preview) of Unity Catalog-managed Iceberg tables** through the Iceberg REST Catalog API. This is a significant differentiator, providing full interoperability across various engines.
* Introduced **business metrics as first-class assets in the lakehouse**, establishing a single semantic layer for all data and AI workloads. Metrics can be defined once and reused across dashboards, AI models, and data engineering jobs via SQL, ensuring consistent definitions.

#### Advanced Governance Capabilities (Beta)
*   **Attribute-based access control (ABAC)** allows flexible access policies using tags at the catalog, schema, or table level for **row and column-level security**.
*   **Tag policies** enforce consistent tag creation and usage.
*   **Data classification** intelligently detects and tags sensitive data (e.g., PII) within 24 hours, automatically applying protection when used with ABAC.
*   **Automated data quality monitoring** checks data freshness and completeness, offering health indicators, root cause analysis, and alerts for proactive issue resolution.

## Implications for Optiver

These announcements are particularly relevant due to their emphasis on **real-time data processing, robust governance, and advanced AI application development**. The operationalisation of AI through **Agent Bricks and Databricks Apps**, coupled with simplified data engineering via Lakeflow, can accelerate the development and deployment of intelligent trading strategies, risk management tools, and compliance monitoring systems. The ability to unify transactional and analytical data on a single platform also promises to break down silos and enable faster, more coherent insights for critical decision-making. **Lakebase's low-latency transactional capabilities** and the advancements in Unity Catalog's governance (ABAC, data classification, quality monitoring) are critical for ensuring data integrity and compliance in a high-stakes, regulated environment.
