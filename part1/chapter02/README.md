# Part 1 - Chapter 02 - The Who, How, and What of Power BI

- [Part 1 - Chapter 02 - The Who, How, and What of Power BI](#part-1---chapter-02---the-who-how-and-what-of-power-bi)
  - [2.1 Highlighting who of Power BI](#21-highlighting-who-of-power-bi)
  - [2.2 How Data Comes to Life?](#22-how-data-comes-to-life)
  - [2.3 What - various type of data anlaystics](#23-what---various-type-of-data-anlaystics)

## 2.1 Highlighting who of Power BI

Data Related Job Roles:

![data-related-roles](img/data-related-roles.png)

Another refernece: [A map of data related roles](http://datavaluemap.com/a-map-of-data-related-roles/), with following matrix --

![data roles](img/DataRelateRoles-1024x1024.jpg)

Deeper look per role (thanks sharing from [Rajesh Pillai](https://www.linkedin.com/in/pillairajesh)):

| Role Name | Description | Responsibilities | Key Skills | Deliverables |
| --- | --- | --- | --- | --- |
| Data Analyst: The Insight Hunter | A Data Analyst focuses on interpreting raw data to uncover trends, patterns, and actionable insights for businesses. Think of them a storyteller who trun numbers into meaningful narratives. | <ul> <li>Collecting, cleaning, and organizing datasets</li> <li>Performing Exploratory Data Analysis (EDA) to uncover patterns</li> <li>Building dashboards and reports using tools like Tableau, Power BI, or Excel</li> <li>Identifying trends to guide business decisions.</li> </ul> | <ul> <li>Tools: SQL, Excel, Tableau, Power BI</li> <li>Programming: Python or R (basic to intermediate)</li> <li>Statistics: Basic knowledge to analyze and interpret data.</li> </ul> | Dashboards, business reports, and presentations that make complex data understandable. |
| Data Scientist: The Problem Solver | Data Scientists delve deeper into data, using advanced algorithms and predictive models to solve complex problems. They work at the intersection of mathematics, coding, and domain expertise. | <ul> <li>Cleaning and preprocessing large datasets</li> <li>Developing machine learning models for prediction or classification</li> <li>Performing A/B testing and hypothesis validation</li><li>Communicating findings through visualizations and storytelling.</li> </ul> | <ul> <li>Programming: Python, R, or Julia (advanced)></li> <li>Machine Learning: Scikit-learn, TensorFlow, PyTorch</li> <li>Mathematics and Statistics: Strong foundation in probability, linear algebra, and advanced statistics</li><li> Big Data Tools: Spark, Hadoop</li> </ul> | Predictive models, actionable insights, and recommendations for strategic decisions. |
| Machine Learning Engineer: The Deployer | Machine Learning Engineer bring models to life. They're responsible for deploying, scaling, and maintaining machine learning solutions in real-world systems. | <ul> <li>Building and optimizing machine learning pipelines</li> <li>Deploying models into production environments</li> <li>Monitoring model performance and managing retraining workflows</li> <li>Integrating ML models into applications or systems</li> </ul> | <ul> <li>Programming: Python, Java, Julia, C++, Mojo, or Scala (Python absolutely mandatory and pick others as required)</li> <li>Frameworks: TensorFlow, PyTorch, ONMX</li> <li>DevOps: Docker, Kubernates, CI/CD</li> <li>Cloud Platforms: Azure, AWS, GCP</li> </ul> | Production-ready ML systems that are scalable and reliable. |
| Data Engineer: The Architect | Data Engineers focus on creating robust data pipelines and infrastructures. They ensure dtaa is accessible, clean, and ready for analysis. | <ul> <li>Designing and building scalable data pipelines</li> <li>Ensuring data quality and availability</li> <li>Handling real-time and batch data processing</li> <li>Managing data warehousing and lakes<li> </ul> | <ul> <li>Programming: Python, Java, Scala</li> <li>Data Tools: Hadoop, Apache Spark, Kafka</li> <li>ETL Tools: Apache Airflow, Talend</li> <li>Databases: SQL and NoSQL</li> </ul> | Efficient, scalable systems that enable seamless data flow and storage. |
| Business Analyst: The Strategist | Business Analysts bridge the gap between business goals and technical solutions. While not always technical, they leverage data to align strategies with insights | <ul> <li>Gathering and decumenting business requirements</li> <li>Analyzing business metrics and performance</li> <li>Communicating with both technical and non-technical teams</li> </ul> | <ul> <li>Tools: Excel, SQL, Tableau, Qlik</li> <li>Domain Knowledge: Industry-specific experise</li> <li>Analytics: Basic statistical and predictive modeling</li> </ul> | Strategies and recommendations rooted in data. |
| AI Research Scientist: The Innovator | AI Researchers focus on advancing the field of machine learning and artificial intelligence through novel algorithms and techniques. | <ul> <li>Conducting research on cutting-edge AI methods</li> <li>Developing new machine learning architectures</li> <li>Publishing findings in academic journals and conferences</li> </ul> | <ul> <li>Programming: Python, R, MATLAB, Julia, Mojo (Python absolutely mandatory and pick others as required primarily for performance reasons)</li> <li>Mathematics: Optimization, advanced calculus, linear algebra</li> <li>Specialized ML Techniques: GANs, Transformers, Reinforcement Learning</li> </ul> | Research papers, patents, and novel algorithms that push the boundaries of AI. |

## 2.2 How Data Comes to Life?

| Steps | Explanation |
| --- | --- |
| 1. Prepare | Data preparation requires a business analyst to evaluate the business's needs and a data analyst to construct an appropriate data profile for cleansing and tranformation.|
| 2. Model | Data modeling can be seens as a process where all of raw pieces of data have been formalized and structured. The goal is to decide how the organized datasets can relate to each other. |
| 3. Visualize | Visualizing data helps organizations better understand business problems in ways that plain text can't convey. "A picture is worth a thousand words"! |
| 4. Analyze | Data analysis is the step in process when crafting data model and interpreting visualizations. | 
| 5. Manage | Power BI consists of lots of different apps, which reuqire variable ways for managing after the report is ready. |

## 2.3 What - various type of data anlaystics

Quick snapshot of data analytics work:

| Type | Question it answers | Common Techniques | Use Cases |
| --- | --- | --- | --- |
| Descriptive | What happended? | Dashboards, Reporting, Data Aggregation | KPI tracking, Sales performance |
| Diagnostic | Why did it happen? | Root cause analysis, drill paths | Customer churn analysis, campaign ROI |
| Predictive | What's likely to happen? | Forcasting, machine learning | Inventory planning, revenue forecasts |
| Prescriptive | What should we do next? | Optimization models, decision logic | Budget allocation, resource planning |
| Cognitive Analytics | | |

Source reference:

- [The 4 Types of Data Analytics Explained (Descriptive, Diagnostic, Predictive, and Prescriptive)](https://www.domo.com/learn/article/data-analytics-types)
---

Last updated at 2026-01-10