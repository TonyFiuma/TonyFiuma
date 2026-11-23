[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Google+Sans\&weight=500\&size=32\&pause=1000\&color=81A1C1\&background=2E343F00\&vCenter=true\&repeat=false\&width=435\&lines=%F0%9F%91%8B%F0%9F%8F%BB+Hi%2C+I'm+Antonio+Fiumanò!)](https://git.io/typing-svg)

## Welcome to Antonio Fiumanò's GitHub page! 🔥

👋 I'm a passionate **Data Engineer** with several years of experience and a strong foundation in Java development and enterprise data integration.

I specialize in building and optimizing scalable data pipelines and data platforms using technologies such as:

* **Databricks**
* **PySpark**
* **Azure**
* **Informatica Intelligent Cloud Service (IICS)**
* **Informatica PowerCenter**
* **Oracle Database**
* **Snowflake**
* **SQL**
* **Python**

🤖 I'm currently expanding my Data Engineering background into **Agentic AI**, exploring how LLMs, RAG and agentic workflows can be applied to real Data Engineering and migration problems.

🚀 My focus is on transforming raw data into valuable insights, modernizing legacy data platforms, integrating diverse data sources and building reliable, scalable and governed data solutions.

💡 Continuously exploring new technologies across **Data Engineering, Cloud, Big Data and AI**.

## 🌐 Socials:

[![LinkedIn: TonyFiuma](https://img.shields.io/badge/-Antonio_Fiumanò-blue?style=flat-square\&logo=Linkedin\&logoColor=white\&link=https://www.linkedin.com/in/antonio-f-68aab419a/)](https://www.linkedin.com/in/antonio-f-68aab419a/)
[![GitHub Tony Fiuma](https://img.shields.io/github/followers/TonyFiuma?label=follow\&style=social)](https://github.com/TonyFiuma)

---

# 🚀 Projects

### 🏗️ Data Architecture Builder [📄 Repo](https://github.com/TonyFiuma/data-architecture-builder) · [▶️ Try the MVP](https://tonyfiuma.github.io/data-architecture-builder/)

An interactive **cloud data architecture MVP** that turns project requirements into a design proposal. The guided questionnaire uses data sources, volumes, freshness requirements and consumption patterns to recommend an architecture, a technology stack and a data model, with a rationale for each choice.

**Tech Stack:**

* **HTML**
* **CSS**
* **JavaScript**
* **GitHub Pages**

**Key Features:**

* **Architecture Recommendations**: Evaluates data warehouse, lakehouse and hybrid designs based on project requirements
* **Technology Selection**: Recommends services for ingestion, storage, processing and orchestration
* **Storage Sizing**: Estimates capacity from data volumes, retention and replication assumptions
* **Diagrams and Exports**: Generates an SVG data flow diagram and Word documents for the architecture proposal and implementation guide
* **Sample Scenarios**: Includes ERP replication on Azure Databricks and telemetry processing on AWS

---

### 🤖 PowerCenter to Databricks Migration Agent [📄 Repo](https://github.com/TonyFiuma/powercenter-to-databricks-agent)

An **Agentic AI migration framework** designed to assist the migration of **Informatica PowerCenter mappings to Databricks / PySpark**.

The project combines deterministic PowerCenter XML parsing with **LangGraph, dual RAG knowledge bases, LLM-based migration planning, PySpark generation, deterministic validation and automatic repair loops**.

Instead of relying on an LLM to directly translate raw PowerCenter XML into code, the system follows a controlled migration workflow where structured mapping metadata remains the source of truth and LLM outputs are validated before being accepted.

**Tech Stack:**

* **Python**
* **LangGraph**
* **LangChain**
* **RAG**
* **Chroma Vector Database**
* **Sentence Transformers**
* **LLMs**
* **PySpark**
* **Databricks**
* **Groq**
* **OpenRouter**
* **Ollama**

**Key Features:**

* **PowerCenter XML Parser**: Extracts mappings, transformations, fields, expressions, instances and connectors
* **Dual RAG**: Dedicated PowerCenter and Databricks technical knowledge bases
* **Migration Planner**: Uses structured mapping metadata and retrieved documentation to design migration strategies
* **Plan Validation**: Detects unsupported assumptions and speculative migration decisions
* **Automatic Plan Repair**: Repairs migration plans that fail deterministic validation
* **PySpark Generation**: Generates migration code from validated plans
* **Code Validation**: Python syntax, semantic and structural completeness checks
* **Automatic Code Repair**: Repairs only mappings that fail validation
* **Persistent Caching**: Reuses successful migration plans and generated code
* **Migration Artifacts**: Produces migration reports and generated `.py` files
* **Synthetic Examples**: Public PowerCenter XML examples for testing the end-to-end workflow

> 🚧 **Status:** Working MVP under active development. Source Qualifier and Expression transformations are currently supported, with Aggregator, Joiner, Lookup and workflow/session parsing planned next.

---

### 🚀 Sell-Out Analytics Pipeline [📄 Repo](https://github.com/TonyFiuma/sellout_databricks_pyspark)

This project implements an end-to-end **Sell-Out Data Engineering pipeline** on **Azure Databricks**, designed to integrate and harmonize heterogeneous sales data from multiple legacy sources.

The solution follows the **Medallion Architecture (Bronze, Silver, Gold)** and uses **PySpark, Delta Lake and Unity Catalog** to transform raw source data into governed, business-ready datasets for analytics and reporting.

The project includes **78 legacy importers**, multiple source-specific parsers, reference-data management, FX normalization, Data Quality controls, Sell-In/Sell-Out enrichment and a business-oriented Gold layer.

> This repository is a sanitized portfolio reconstruction of a real-world Data Engineering project. Confidential data, customer identities and production environment information have been removed or replaced with synthetic values.

**Tech Stack:**

* **Azure Databricks**
* **PySpark / Apache Spark**
* **Delta Lake**
* **Microsoft Azure**
* **Unity Catalog**
* **Spark SQL**
* **Python**
* **Databricks Asset Bundles**
* **Medallion Architecture**

**Key Features:**

* **Bronze Layer**: Multi-source ingestion and source-specific parsing
* **Silver Layer**: Data standardization, reference mappings, FX normalization and harmonization
* **Data Quality**: Validation of mappings, mandatory fields, measures and business rules
* **Sell-In / Sell-Out**: Business enrichment and normalization logic
* **Submission Management**: Latest-submission selection to prevent duplicate reporting
* **Gold Layer**: Business-ready Sell-Out datasets and KPI aggregations
* **Analytics**: Company, product and market/channel performance KPIs
* **Governance**: Unity Catalog, column masking, constraints and least-privilege patterns
* **Deployment**: Databricks Asset Bundle job configuration

---

### 🌎 Bank Rating Engine [📄 Repo](https://github.com/TonyFiuma/bank_rating_engine)

The **Rating Engine Bank Pipeline** project is a robust Data Engineering solution designed to streamline and enhance the processing of financial data for a banking environment.

**Tech Stack:**

* **Informatica PowerCenter**
* **PL/SQL / Oracle**
* **Linux**

**Key Features:**

* Enterprise ETL processes using Informatica PowerCenter
* Complex data transformations using PL/SQL
* Integration of multiple data flows
* Linux-based operational execution
* Data processing for banking workloads

---

### 🌐 Python ETL Project [📄 Repo](https://github.com/TonyFiuma/electric_cars_python_etl)

In this **Python ETL Project**, I focused on building an ETL process that extracts data from a specified URL, transforms it and loads it into a CSV file or Google BigQuery.

This project was developed to strengthen my Python skills applied to Data Engineering.

**Tech Stack:**

* **Python**
* **Pandas**
* **Google BigQuery**

**Key Features:**

* **Extraction**: Retrieves data from a given URL using Python's `requests` library
* **Transformation**: Uses `pandas` to clean, filter and process the data
* **Loading**: Supports CSV output or loading transformed data into Google BigQuery

---

# 💫 About Me

🎂 Born and raised in **Italy** 🇮🇹
🐛 Solving bugs since **2019** 🔍
💼 Currently working as a **Data Engineer**
⚡ Building solutions with **Databricks & PySpark**
🤖 Exploring **Agentic AI, RAG, LangGraph and LLM applications for Data Engineering**
🌱 Always learning new technologies related to **Big Data, Cloud and AI**
🎯 Passionate about building scalable data architectures, modernizing legacy systems and turning data into actionable insights

## 💻 Tech Stack

### Data Engineering & Cloud

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge\&logo=databricks\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Informatica](https://img.shields.io/badge/Informatica-DD0031?style=for-the-badge\&logo=Informatica\&logoColor=white)
![Oracle](https://img.shields.io/badge/oracle-%23F00000.svg?style=for-the-badge\&logo=oracle\&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-%2300C8FF.svg?style=for-the-badge\&logo=Snowflake\&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-%23FF7300.svg?style=for-the-badge\&logo=oracle\&logoColor=white)

### AI & Agentic Systems

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic%20AI-1C3C3C?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-6C63FF?style=for-the-badge)
![Chroma](https://img.shields.io/badge/Chroma-Vector%20Database-orange?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector%20Database-000000?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLMs-black?style=for-the-badge)

### Development

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=java\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge\&logo=spring-boot\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge\&logo=git\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge\&logo=css3\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=TonyFiuma&theme=nord&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TonyFiuma&layout=compact&theme=nord&hide_border=true" />
</p>
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Google+Sans\&weight=500\&size=32\&pause=1000\&color=81A1C1\&background=2E343F00\&vCenter=true\&repeat=false\&width=435\&lines=%F0%9F%91%8B%F0%9F%8F%BB+Hi%2C+I'm+Antonio+Fiumanò!)](https://git.io/typing-svg)

## Welcome to Antonio Fiumanò's GitHub page! 🔥

👋 I'm a passionate **Data Engineer** with several years of experience and a strong foundation in Java development and enterprise data integration.

I specialize in building and optimizing scalable data pipelines and data platforms using technologies such as:

* **Databricks**
* **PySpark**
* **Azure**
* **Informatica Intelligent Cloud Service (IICS)**
* **Informatica PowerCenter**
* **Oracle Database**
* **Snowflake**
* **SQL**
* **Python**

🤖 I'm currently expanding my Data Engineering background into **Agentic AI**, exploring how LLMs, RAG and agentic workflows can be applied to real Data Engineering and migration problems.

🚀 My focus is on transforming raw data into valuable insights, modernizing legacy data platforms, integrating diverse data sources and building reliable, scalable and governed data solutions.

💡 Continuously exploring new technologies across **Data Engineering, Cloud, Big Data and AI**.

## 🌐 Socials:

[![LinkedIn: TonyFiuma](https://img.shields.io/badge/-Antonio_Fiumanò-blue?style=flat-square\&logo=Linkedin\&logoColor=white\&link=https://www.linkedin.com/in/antonio-f-68aab419a/)](https://www.linkedin.com/in/antonio-f-68aab419a/)
[![GitHub Tony Fiuma](https://img.shields.io/github/followers/TonyFiuma?label=follow\&style=social)](https://github.com/TonyFiuma)

---

# 🚀 Projects

### 🏗️ Data Architecture Builder [📄 Repo](https://github.com/TonyFiuma/data-architecture-builder) · [▶️ Try the MVP](https://tonyfiuma.github.io/data-architecture-builder/)

An interactive **cloud data architecture MVP** that turns project requirements into a design proposal. The guided questionnaire uses data sources, volumes, freshness requirements and consumption patterns to recommend an architecture, a technology stack and a data model, with a rationale for each choice.

**Tech Stack:**

* **HTML**
* **CSS**
* **JavaScript**
* **GitHub Pages**

**Key Features:**

* **Architecture Recommendations**: Evaluates data warehouse, lakehouse and hybrid designs based on project requirements
* **Technology Selection**: Recommends services for ingestion, storage, processing and orchestration
* **Storage Sizing**: Estimates capacity from data volumes, retention and replication assumptions
* **Diagrams and Exports**: Generates an SVG data flow diagram and Word documents for the architecture proposal and implementation guide
* **Sample Scenarios**: Includes ERP replication on Azure Databricks and telemetry processing on AWS

---

### 🤖 PowerCenter to Databricks Migration Agent [📄 Repo](https://github.com/TonyFiuma/powercenter-to-databricks-agent)

An **Agentic AI migration framework** designed to assist the migration of **Informatica PowerCenter mappings to Databricks / PySpark**.

The project combines deterministic PowerCenter XML parsing with **LangGraph, dual RAG knowledge bases, LLM-based migration planning, PySpark generation, deterministic validation and automatic repair loops**.

Instead of relying on an LLM to directly translate raw PowerCenter XML into code, the system follows a controlled migration workflow where structured mapping metadata remains the source of truth and LLM outputs are validated before being accepted.

**Tech Stack:**

* **Python**
* **LangGraph**
* **LangChain**
* **RAG**
* **Chroma Vector Database**
* **Sentence Transformers**
* **LLMs**
* **PySpark**
* **Databricks**
* **Groq**
* **OpenRouter**
* **Ollama**

**Key Features:**

* **PowerCenter XML Parser**: Extracts mappings, transformations, fields, expressions, instances and connectors
* **Dual RAG**: Dedicated PowerCenter and Databricks technical knowledge bases
* **Migration Planner**: Uses structured mapping metadata and retrieved documentation to design migration strategies
* **Plan Validation**: Detects unsupported assumptions and speculative migration decisions
* **Automatic Plan Repair**: Repairs migration plans that fail deterministic validation
* **PySpark Generation**: Generates migration code from validated plans
* **Code Validation**: Python syntax, semantic and structural completeness checks
* **Automatic Code Repair**: Repairs only mappings that fail validation
* **Persistent Caching**: Reuses successful migration plans and generated code
* **Migration Artifacts**: Produces migration reports and generated `.py` files
* **Synthetic Examples**: Public PowerCenter XML examples for testing the end-to-end workflow

> 🚧 **Status:** Working MVP under active development. Source Qualifier and Expression transformations are currently supported, with Aggregator, Joiner, Lookup and workflow/session parsing planned next.

---

### 🚀 Sell-Out Analytics Pipeline [📄 Repo](https://github.com/TonyFiuma/sellout_databricks_pyspark)

This project implements an end-to-end **Sell-Out Data Engineering pipeline** on **Azure Databricks**, designed to integrate and harmonize heterogeneous sales data from multiple legacy sources.

The solution follows the **Medallion Architecture (Bronze, Silver, Gold)** and uses **PySpark, Delta Lake and Unity Catalog** to transform raw source data into governed, business-ready datasets for analytics and reporting.

The project includes **78 legacy importers**, multiple source-specific parsers, reference-data management, FX normalization, Data Quality controls, Sell-In/Sell-Out enrichment and a business-oriented Gold layer.

> This repository is a sanitized portfolio reconstruction of a real-world Data Engineering project. Confidential data, customer identities and production environment information have been removed or replaced with synthetic values.

**Tech Stack:**

* **Azure Databricks**
* **PySpark / Apache Spark**
* **Delta Lake**
* **Microsoft Azure**
* **Unity Catalog**
* **Spark SQL**
* **Python**
* **Databricks Asset Bundles**
* **Medallion Architecture**

**Key Features:**

* **Bronze Layer**: Multi-source ingestion and source-specific parsing
* **Silver Layer**: Data standardization, reference mappings, FX normalization and harmonization
* **Data Quality**: Validation of mappings, mandatory fields, measures and business rules
* **Sell-In / Sell-Out**: Business enrichment and normalization logic
* **Submission Management**: Latest-submission selection to prevent duplicate reporting
* **Gold Layer**: Business-ready Sell-Out datasets and KPI aggregations
* **Analytics**: Company, product and market/channel performance KPIs
* **Governance**: Unity Catalog, column masking, constraints and least-privilege patterns
* **Deployment**: Databricks Asset Bundle job configuration

---

### 🌎 Bank Rating Engine [📄 Repo](https://github.com/TonyFiuma/bank_rating_engine)

The **Rating Engine Bank Pipeline** project is a robust Data Engineering solution designed to streamline and enhance the processing of financial data for a banking environment.

**Tech Stack:**

* **Informatica PowerCenter**
* **PL/SQL / Oracle**
* **Linux**

**Key Features:**

* Enterprise ETL processes using Informatica PowerCenter
* Complex data transformations using PL/SQL
* Integration of multiple data flows
* Linux-based operational execution
* Data processing for banking workloads

---

### 🌐 Python ETL Project [📄 Repo](https://github.com/TonyFiuma/electric_cars_python_etl)

In this **Python ETL Project**, I focused on building an ETL process that extracts data from a specified URL, transforms it and loads it into a CSV file or Google BigQuery.

This project was developed to strengthen my Python skills applied to Data Engineering.

**Tech Stack:**

* **Python**
* **Pandas**
* **Google BigQuery**

**Key Features:**

* **Extraction**: Retrieves data from a given URL using Python's `requests` library
* **Transformation**: Uses `pandas` to clean, filter and process the data
* **Loading**: Supports CSV output or loading transformed data into Google BigQuery

---

# 💫 About Me

🎂 Born and raised in **Italy** 🇮🇹
🐛 Solving bugs since **2019** 🔍
💼 Currently working as a **Data Engineer**
⚡ Building solutions with **Databricks & PySpark**
🤖 Exploring **Agentic AI, RAG, LangGraph and LLM applications for Data Engineering**
🌱 Always learning new technologies related to **Big Data, Cloud and AI**
🎯 Passionate about building scalable data architectures, modernizing legacy systems and turning data into actionable insights

## 💻 Tech Stack

### Data Engineering & Cloud

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge\&logo=databricks\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Informatica](https://img.shields.io/badge/Informatica-DD0031?style=for-the-badge\&logo=Informatica\&logoColor=white)
![Oracle](https://img.shields.io/badge/oracle-%23F00000.svg?style=for-the-badge\&logo=oracle\&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-%2300C8FF.svg?style=for-the-badge\&logo=Snowflake\&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-%23FF7300.svg?style=for-the-badge\&logo=oracle\&logoColor=white)

### AI & Agentic Systems

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic%20AI-1C3C3C?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-6C63FF?style=for-the-badge)
![Chroma](https://img.shields.io/badge/Chroma-Vector%20Database-orange?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector%20Database-000000?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLMs-black?style=for-the-badge)

### Development

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=java\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge\&logo=spring-boot\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge\&logo=git\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge\&logo=css3\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=TonyFiuma&theme=nord&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TonyFiuma&layout=compact&theme=nord&hide_border=true" />
</p>
