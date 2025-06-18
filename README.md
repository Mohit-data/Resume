\documentclass[11pt]{article}
\usepackage{geometry}
\geometry{letterpaper, margin=0.6in}
\usepackage{enumitem}
\usepackage{xcolor}
\usepackage[
    colorlinks=true,
    urlcolor=blue,
    linkcolor=blue
]{hyperref}
\usepackage{times}
\usepackage{titlesec}
\usepackage{fancyhdr}

\linespread{0.95}  % slightly tighten line spacing
\pagestyle{empty}

\titlespacing*{\section}{0pt}{6pt}{4pt}  % improve section spacing

% Define section vertical gap
\newcommand{\sectiongap}{\vspace{6pt}}

% Global item spacing
\setlist[itemize]{leftmargin=*, noitemsep, topsep=1pt, parsep=0pt, partopsep=0pt}

\begin{document}

\begin{center}
    {\Large \textbf{Mohith Kasturi}} \\[0.1cm]
    \href{mailto:mohithk.data@gmail.com}{mohithk.data@gmail.com} \textbullet\ (331) 303-6476 \textbullet\ 
    \href{https://www.linkedin.com/in/-mohit-b219b7296/}{linkedin.com/in/-mohit-b219b7296} \textbullet\ 
    \href{https://github.com/mohithk}{github.com/mohithk}
\end{center}

\vspace{0.1cm}
\hrule
\vspace{0.2cm}

% Professional Summary
\section*{Professional Summary}
Data Engineer with 5+ years of experience designing cloud-native systems that process millions of records daily across AWS, Azure, and GCP. Specialized in building event-driven, microservices-based real-time and batch pipelines using Python, SQL, Spark, dbt, and Snowflake to support analytics, machine learning, and regulatory reporting. Experienced in collaborating with engineering, product, and compliance teams in Agile/SAFe environments to reduce latency, improve pipeline reliability, and deliver scalable data solutions using orchestration and governance tools such as Airflow, dbt, and Amundsen across finance and healthcare domains.

% Education
\sectiongap
\section*{Education}
\textbf{M.S. in Computer Science} \hfill \textbf{Governors State University}, Chicago, IL \\
GPA: 3.9/4.0 \hfill Jan 2022 -- Dec 2023 \\
\vspace{0.1cm}
\textbf{B.E. in Electrical Engineering} \hfill JNTU, Hyderabad, India

% Skills
\sectiongap
\section*{Technical Skills}
\begin{itemize}
    \item \textbf{Programming:} Python (Pandas, PySpark, pytest, unittest), PL/SQL, Java, Bash, Scala
    \item \textbf{Cloud \& Big Data:} AWS (S3, Redshift, Glue, Lambda), Azure (ADF, Synapse, Event Hubs), GCP (BigQuery, Dataflow, Pub/Sub), Databricks, Hadoop (Hive, HDFS, Pig, Sqoop, MapReduce, Oozie, Zookeeper), Ab Initio (GDE, Metadata Hub), Snowflake
    \item \textbf{ETL/ELT \& Orchestration:} Apache Spark, dbt, Apache Airflow, SSIS, Talend, SnowPipe
    \item \textbf{Storage \& Warehousing:} Redshift, Synapse, BigQuery, PostgreSQL, Delta Lake, Hive, HDFS
    \item \textbf{Streaming \& APIs:} Kafka, Kinesis, REST, GraphQL, MQTT, Event Hubs
    \item \textbf{Data Visualization:} Power BI, Tableau, Looker, Excel
    \item \textbf{DevOps \& IaC:} Docker, Kubernetes, Terraform, Jenkins, GitHub Actions
    \item \textbf{Governance \& Security:} RBAC, RLS, PII masking, Amundsen, DataHub, encryption, audit logging
    \item \textbf{Project Tools:} Jira, Confluence, Azure Boards, Agile/Scrum
\end{itemize}

% Professional Experience
\sectiongap
\section*{Professional Experience}
\vspace{2pt}
\textbf{Azure Data Engineer}, First Horizon Bank \hfill Germantown, TN \\
Apr 2023 – Present
\begin{itemize}[itemsep=3pt]
    \item Led scalable Azure and Snowflake data pipelines for regulatory reporting and fraud detection, reducing latency by 25\%.
    \item Built Java API for real-time Cassandra access integrated with Hadoop, Solr, PySpark, Kafka, and Storm.
    \item Developed event-driven fraud detection workflows using Event Hubs, Databricks, Spark ML (XGBoost, scikit-learn).
    \item Optimized batch ETL from PostgreSQL, MongoDB, SQL Server, improving throughput by 40\%.
    \item Automated infrastructure provisioning with Docker, Kubernetes, and Terraform, halving deployment time.
    \item Integrated real-time APIs and Kafka streams into Databricks, enhancing fraud feature generation.
    \item Refactored PySpark pipelines with dbt test coverage and pytest, reducing processing time by 30\%.
    \item Implemented RBAC, audit logging, and Section 19 privacy controls in Synapse and Databricks.
    \item Collaborated with cross-functional teams to define data requirements for credit and fraud analytics.
\end{itemize}

\vspace{2pt}
\noindent
\textbf{AWS Data Engineer}, Optum \hfill Eden Prairie, MN \\
Apr 2022 – Mar 2023
\begin{itemize}[itemsep=3pt]
    \item Engineered and optimized multi-terabyte ETL pipelines on AWS and Databricks, supporting 25K+ Medicare claims daily.
    \item Built secure ETL workflows with IAM, encryption, and audit logging for HIPAA compliance.
    \item Built pipelines ingesting 1M+ records daily from JSON, XML, and REST APIs via Glue, Redshift, Lambda.
    \item Developed cross-cloud workflows with PySpark integrating BigQuery, Snowflake, Redshift.
    \item Tuned Databricks Spark clusters for real-time transformations via Spark DataFrame API.
    \item Used Ab Initio (GDE, Metadata Hub) to manage metadata-driven workflows and orchestration.
    \item Refactored legacy Informatica ETLs into Spark and Snowflake, improving speed by 40\%.
    \item Reverse-engineered SQL/C# APIs and integrated logic into dbt and PySpark with unit testing.
    \item Delivered real-time analytics via SSIS, Spark, Snowflake, cutting dashboard load time by 50\%.
    \item Built PySpark-based monitoring pipelines reducing incident response time.
    \item Created Tableau dashboards transforming risk metrics into actionable visuals.
\end{itemize}

\vspace{2pt}
\noindent
\textbf{GCP Data Engineer}, Takeda Pharmaceutical \hfill Mumbai, India \\
Jan 2020 – Dec 2021
\begin{itemize}[itemsep=3pt]
    \item Built real-time and batch ELT pipelines using Apache Beam, Dataflow, BigQuery for clinical analytics.
    \item Migrated legacy pipelines to GCP with PySpark, Hive, and DataFrame APIs.
    \item Designed ingestion for structured/semi-structured data across on-prem and cloud.
    \item Used Hadoop tools (Hive, HDFS, Pig, Sqoop, MapReduce, Oozie, Zookeeper) for scalable ETL.
    \item Implemented monitoring pipelines with Airflow, Cloud Functions, and Python.
    \item Orchestrated vitals ingestion using Pub/Sub, Event Hubs, and visualized via Power BI.
    \item Developed Git-driven Airflow DAGs deployed via Terraform and Azure DevOps CI/CD.
    \item Standardized schemas across OLAP/OLTP systems with schema validation for Power BI.
    \item Enforced secure and repeatable deployments with CI/CD and Terraform under DevSecOps.
\end{itemize}

\vspace{2pt}
\noindent
\textbf{Data Engineer}, Amazon \hfill Mumbai, India \\
Jul 2019 – Dec 2019
\begin{itemize}[itemsep=3pt]
    \item Developed predictive models using scikit-learn, XGBoost to forecast customer churn and risk.
    \item Built ELT pipelines with Glue, Lambda, Redshift integrating third-party customer data.
    \item Engineered cloud-native data lakes with BigQuery, Snowflake, Redshift, and S3.
    \item Analyzed 2.5M Prime member records, improving retention by 15\%, revenue by \$15M/month.
    \item Optimized Kafka-S3 pipelines and Redshift/Hive queries for better performance.
    \item Applied Jenkins and Terraform for CI/CD and infrastructure automation.
    \item Conducted ETL performance testing with JMeter, cutting latency by 20\%.
    \item Streamed real-time behavior via Kinesis and EMR to drive targeted marketing.
    \item Defined data quality rules and delivered Power BI dashboards on customer churn.
\end{itemize}

% Certifications
\sectiongap
\section*{Certifications}
\begin{itemize}[itemsep=2pt]
    \item Microsoft Azure Fundamentals (AZ-900)
    \item Google Cloud Practitioner
    \item AWS Certified Cloud Developer Associate
    \item Databricks Certified Data Engineer Associate (in progress)
\end{itemize}

\end{document}
