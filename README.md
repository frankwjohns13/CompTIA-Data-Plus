# CompTIA Data+ DAO-002 Notes
This is where my notes for the CompTIA Data+ exam will be kept.
<details>
<summary><strong></strong>CompTIA Data+ Study Guide Exam DAO-002</summary>

by Mike Chapple and Sharif Nijim  
Copyright 2025 by John Wiley & Sons, Inc.  
ISBN: 9781394320912

</details>

---
<details>
<summary><strong>Exam Objectives Summary</strong></summary>

---

<details>
<summary><strong>Data Concepts and Environments (20%)</strong></summary>

**Explain Data Concepts:**
- Database types
- Data structures
- File extensions
- Data types

**Identify Data Sources:**
- Databases
- APIs
- Website data
- Files
- Logs
- Repositories

**Recognize Infrastructure Concepts:**
- Cloud
- On-premise
- Storage
- Containerization

**Identify Data Tools:**
- Coding environments
- BI Software
- Analysis platforms

**Understand AI Concepts:**
- Identify AI models
- Natural language processing
- Robotic automation

</details> <!-- Ends Data Concepts and Environments -->

---

<details>
<summary><strong>Data Acquisition and Preparation (22%)</strong></summary>

**Use Data Acquisition Methods:**
- Data integration and queries to gather and combine data

**Perform Data Exploration:**
- Find missing values
- Duplication
- Redundancy
- Outliers

**Apply Data Transformation:**
- Cleansing
- Merging
- Parsing
- Formatting data

</details> <!-- Ends Acquisition and Preparation -->

---

<details>
<summary><strong>Data Analysis (24%)</strong></summary>

**Communicate Analysis Results:**
- Select methods for different audiences

**Select Statistical Methods:**
- Apply basic statistical techniques to data.

**Troubleshoot Analysis Issues:**
- Use tools and resources to resolve problems.

  
</details> <!-- Ends data Analysis -->

---

<details>
<summary><strong>Visualization and Reporting (20%)</strong></summary>

**Create Effective Visuals:**
- Use charts
- Maps
- Table
- Design elements

**Deliver Reports:**
- Provide dashboards or summaries using appropriate methods.

**Validate Reporting Accuracy:**
- Apply validation and review to solve reporting issues
  
</details> <!-- Ends Visualization and Reporting -->

---

<details>
<summary><strong>Data Governance (14%)</strong></summary>

**Explain Data management Practices:**
- Documentation
- Versioning
- Data lineage

**Summarize Compliance Requirements:**
- Retention
- Audits
- Regulation

**Compare Privacy and Protection Strategies:**
- Access control
- Encryption
- Masking

**Implement Quality Assurance:**
- Profiling
- Monitoring
- Testing for data quality

  
</details> <!-- Ends Data Governance -->


</details> <!-- Ends the Objectives Summary -->

---

<details>
<summary><strong>Chapters</strong></summary>

Notes listed by chapters. 

---

<details>
<summary><strong>Chapter 1: Today's Data Analyst</strong></summary>

## Chapter 1: Today's Data Analyst

### Domains

**1.0: Data Concepts and Environments**
- 1.5 Identify artificial intelligence (AI) concepts

**3.0: Data Analysis**
- 3.2 Given a scenario, select the appropriate statistical method or function

---

### Key Terms and Main Idea

**Data** is any information that is collected no matter the format (text, pictures, graphs, spreadsheets...)

**Data Analysts** are professionals who possess the skills required to understand how an organization can acquire, clean, and transform data to meet the needs of the organization.

---

### The Analytics Process

**Data Acquisition → Cleaning and Manipulation → Analysis → Visualization → Reporting and Communication**

**Data Acquisition**  
Data can come from *internal sources* (e.g., sales reports) or *external sources* (e.g., census data).

**Cleaning and Manipulation**  
After data is collected, a large share of time goes to finding errors or missing values and transforming the data into a usable form.

**Analysis**  
With prepared data, processing often starts with *exploratory data analysis* (EDA) to spot patterns, relationships, and anomalies. 

**Visualization**  
A picture is worth a thousand words. Charts and graphs help others grasp what the data shows quickly—often more effectively than tables of numbers alone. 

**Reporting and Communication**  
Results are usually shared through reports and dashboards. Reports capture a point-in-time view; dashboards can show near real-time data. 

---

### Analytics Techniques

**Descriptive Analytics**  
Data is displayed using statistics (e.g., sums, totals, percentages, frequencies). 

**Inferential Analytics**  
Uses a sample of a given population to make general inferences about the population as a whole. 

**Predictive Analytics**  
Estimates the probability of future events from existing data. 

**Prescriptive Analytics**  
Seeks optimization by simulating many scenarios. 

---

### Machine Learning, Artificial Intelligence, and Deep Learning

**Artificial Intelligence (AI)**  
*AI* is when you attempt to get a computer to act like a human.

**Machine Learning**  
*Machine learning* a subset of AI that uses algorithms to learn patterns from data.
- Understanding customers and what appeals to different groups.
- Searching log files for anomalies that could indicate cyber attacks.
- Sales predictions based on the market.

**Deep Learning**  
*Deep learning* is highly specialized subdivision of machine learning most commonly used for image, video, and sound analysis.

**Generative AI**  
*Generative AI* foundational models are the large models trained on huge datasets; LLMs are the common type used for text. 
They use *Large Language Models* called *foundational models* that are trained on massive datasets. 

---

### Robotic Process Automation

The process of automating repetitive, rule-based tasks is called *Robotic Process Automation* (RPA). The systems that use this software are called robots or "bots".
The bots can streamline data collection by accessing multiple sources and consolidating the data into a central database. Then, perform data analysis on it. They can 
pull data from various systems, organize it, and generate a report formatted to meet the organizations needs. 

---

### Data Governance

*Data governance* sets the organizations quality and control standards for data collection. This process ensures the data is accurate and secure.

---

### Analytics Tools

*Analytics tools* are used to automate much of the heavy data analytics process. 
- Tools like Microsoft Excel and Google Sheets are used to create spreadsheets. 
- Rstudio to help program in the R programming language

---

### Summary – Objectives Covered in Chapter 1

**1.5 Identify artificial intelligence (AI) concepts**
- **Artificial intelligence (AI):** systems designed to perform tasks that typically require human intelligence
- **Machine learning (ML):** subset of AI; algorithms learn patterns from data (customer segmentation, log anomaly detection, sales forecasting)
- **Deep learning:** specialized ML, often used for image, video, and audio analysis
- **Generative AI:** creates new content (text, images, music, video); examples include ChatGPT, Claude, Midjourney
- **Foundational models / large language models (LLMs):** large models trained on massive datasets that power many generative AI tools
- **Robotic process automation (RPA):** software “bots” that automate repetitive, rule-based tasks (collect data, consolidate sources, format reports)

**3.2 Given a scenario, select the appropriate statistical method or function**  
*(Chapter 1 introduces the analytics types that drive method choice; deeper stats come later.)*
- **Descriptive analytics:** summarize what happened (sums, totals, percentages, frequencies)
- **Inferential analytics:** use a sample to draw conclusions about a larger population
- **Predictive analytics:** estimate likelihood of future outcomes from historical data
- **Prescriptive analytics:** recommend or simulate actions to optimize outcomes

**Related concepts (supporting context)**
- **Analytics process:** Acquisition → Cleaning & Manipulation → Analysis (often starts with EDA) → Visualization → Reporting & Communication
- **Data sources:** internal (e.g., sales reports) vs external (e.g., census data)
- **Data governance:** organizational standards for data quality, control, accuracy, and security
- **Common tools:** spreadsheets (Excel, Google Sheets); programming environments (e.g., RStudio for R)

---

**End of Chapter 1**

</details> <!-- Ends Chapter 1 -->

---

<details>
<summary><strong>Chapter 2: Data Analytics Tools</strong></summary>

## Chapter 2: Data Analytics Tools

### Domains

**1.0: Data Concepts and Environments**
- 1.3 Identify infrastructure concepts
- 1.4 Identify common data analysis tools

---

### Spreadsheets

The most widely used tool in analytics. They organize data into rows and columns. They are great for mathematical calculations, creating graphs and charts, and communicating reports. 

MS Excel is one of the most common spreadsheet software. 

---

### Programming Languages

**R**  
Popular among analysts because it is focused on statistics and analytic applications. It often comes with an *Integrated Development Environment* (IDE).

**Python**  
Arguably the most popular programming language. It is a general-purpose language. 

**Anaconda**  
Open source distribution for python/R that simplifies packages, dependencies, and environments.

**Scala**  
Powerful language that blends object-oriented and functional programming paradigms. 

**SAS**  
Statistical package and programming language. Can be used to automate repetitive tasks.

---

### Databases and SQL

The *Structured Query Language* is used to interact with databases. It is divided into two parts: Data Definition Language (DDL) and Data Manipulation Language (DML).

**Major DDL commands:**  

| **Command** | **Purpose**                            |
|-------------|----------------------------------------|
| `CREATE`    | Create a new table within the database |
| `ALTER`     | Modifies a table's structure           |
| `DROP`      | Deletes an entire table                |


**Major DML commands:**

| **Command** | **Purpose**                           |
|-------------|---------------------------------------|
| `SELECT`    | Retrieves information from a database |
| `INSERT`    | Adds new records to a database        |
| `UPDATE`    | Modifies rows in a database           |
| `DELETE`    | Deletes rows from a database table    |


**Tools:**
- Azure Data Studio
- MySQL Workbench
- Compass
- DBeaver
- Toad
- Microsoft's SQL Server Management Studio

---

### Business Intelligence Software

"Allows analysts to ingest and clean data, perform statistical analysis, visualize data, produce models, make predictions, 
and communicate and report results."

**PowerBI "SaaS":** (Microsoft's cloud/Saas layer) Popular among organizations that use other Microsoft products.

Major Components:
- Power BI desktop
- Microsoft's Software as a Service (SaaS)
- Mobile works on iOS, Android, and Windows
- Report Builder - create paginated reports
- Report Server - organizations can host their own environment

**Tableau:** Most popular data visualization tool. Focuses on easy ingestion of data from a variety of sources

**Looker:** Popular SaaS with access to cloud-based analytics. Powered by Google.

---

### Cloud Infrastructure

Cloud computing is the delivery of services over a network

**Cloud Computing Reasons:**
- On-demand, self-service computing
- Scalability
  - Horizontal Scaling: Adding more servers
  - Vertical Scaling: Increasing capacity of existing servers
- Elasticity: The ability to increase and decrease capacity

**Cloud Service Concepts:**
- Software as a Service (SaaS): Provider delivers an entire application to the customer
- Infrastructure as a Service (IaaS): Provides basic computing resources
  - Computing Resources
    - Virtual Machines
    - Containers
  - Storage Resources
    - Object Storage: unstructured/blobs
    - Block Storage: fixed-size volumes (VMs/DBs)
    - File Storage: hierarchical structure
    - Local Storage: attached directly to a virtual machine
    - Shared Storage: allows VMs or Containers to access the same storage
-Platform as a Service (PaaS): A platform to run your own applications

**Cloud Deployment Models:**
- On-premises/private: The organization builds its own cloud
- Public: Uses multitenancy in which it builds a giant infrastructure and carves out pieces to customers
- Hybrid: Combines a private and public server

**Common Public Cloud Providers:**
- Amazon Web Services
- Microsoft Azure
- Google Cloud Platform

---

### Exam Essentials

**Role of spreadsheets:**  
Spreadsheets are productivity software designed to create documents that organize any data type into rows and columns

**How programming languages are used:**  
Programming languages are used to create analysis tools

**Know how analysts and developers interact with databases:**  
- They use SQL to interact with databases.
- Analysts lean on DML (SELECT/INSERT/UPDATE/DELETE);
- Schema work is DDL (CREATE/ALTER/DROP).
- Some materials also call SELECT DQL.

**Role of Business Intelligence:**  
Tools used to ingest and clean data, statistical analysis, visualization, produce models, make predictions, and communicate and report.

**Role of Cloud Providers:**  
Deliver scalability, on-demand infrastructure.

**Different cloud and on-premises models:**  
Private, public, and hybrid

**Types of data storage and use cases:**  
Cloud storage, object storage, file storage

---

### Cliff Notes – Objectives Covered in Chapter 2

**1.4 Identify common data analysis tools**
- **Spreadsheets:** rows/columns; calculations, charts, reports (e.g., Excel)
- **Programming languages / environments**
  - **R** — statistics and analytics; often used with an IDE
  - **Python** — general-purpose; very common in analytics
  - **Anaconda** — distribution/manager for Python/R packages and environments (not a language)
  - **Scala** — object-oriented + functional; often used in big-data stacks
  - **SAS** — statistical package/language; good for automating repetitive analytics tasks
- **SQL & database tools**
  - **DDL:** `CREATE`, `ALTER`, `DROP` (structure)
  - **DML:** `SELECT`, `INSERT`, `UPDATE`, `DELETE` (data)
  - Tools: Azure Data Studio, MySQL Workbench, Compass, DBeaver, Toad, SSMS
- **Business intelligence (BI)**
  - Ingest/clean → analyze → visualize → model/predict → report
  - **Power BI** (Desktop, service/SaaS, mobile, Report Builder, Report Server)
  - **Tableau** — strong visualization and multi-source ingestion
  - **Looker** — Google cloud/SaaS analytics

**1.3 Identify infrastructure concepts**
- **Cloud reasons:** on-demand self-service, scalability, elasticity
  - **Horizontal scaling** — add more servers
  - **Vertical scaling** — increase capacity of existing servers
- **Service models**
  - **SaaS** — full application delivered by provider
  - **IaaS** — basic compute/storage/network resources
  - **PaaS** — platform to build/run your own apps
- **Storage types**
  - **Object** — unstructured data
  - **Block** — fixed-size blocks (often VMs/databases)
  - **File** — hierarchical structure
  - Local vs shared storage for VMs/containers
- **Deployment models:** private/on-premises, public (multitenant), hybrid
- **Major public clouds:** AWS, Microsoft Azure, Google Cloud Platform

---

**End of Chapter 2**

</details> <!-- Ends Chapter 2 -->


---

<details>
<summary><strong>Chapter 3: Understanding Data</strong></summary>

## Chapter 3: Understanding Data

### Domains




































</details> <!-- Ends Chapter 3 -->


---

<details>
<summary><strong>Chapter 4: Databases and Data Acquisition</strong></summary>

## Chapter 4: Databases and Data Acquisition

### Domains
  



































</details> <!-- Ends Chapter 4 -->


---

<details>
<summary><strong>Chapter 5: Data Quality</strong></summary>

## Chapter 5: Data Quality

### Domains
  



































</details> <!-- Ends Chapter 5 -->


---

<details>
<summary><strong>Chapter 6: Data Analysis and Statistics</strong></summary>

## Chapter 6: Data Analysis and Statistics

### Domains




































</details> <!-- Ends Chapter 6 -->


---

<details>
<summary><strong>Chapter 7: Data Visualization with Reports and Dashboards</strong></summary>

## Chapter 7: Data Visualization with Reports and Dashboards

### Domains
  



































</details> <!-- Ends Chapter 7 -->


---

<details>
<summary><strong>Chapter 8: Data Governance</strong></summary>

## Chapter 8: Data Governance

### Domains
  



































</details> <!-- Ends Chapter 8 -->



































  
</details> <!-- Ends Chapters -->

---



























