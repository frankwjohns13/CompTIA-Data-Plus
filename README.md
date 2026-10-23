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

### Cliff Notes – Objectives Covered in Chapter 1

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

**1.0 Data concepts and Environments**
- 1.1 Explain data concepts

---

### Data Building Blocks

**Data Element**  
An element is an attribute about a person, place, or thing. They also describe characteristics of activities: 
orders, transactions, and events. Element names are usually column headings and their values make up the rows for that element.

**Data Type**  
Data types limit the values a data element can have.

---

### Exploring Data Types

**Tabular Data**  
Data that is organized into tables made up of columns and rows. Columns are fields and rows are records.

**Strings**  
Strings are the most widely used data type for storing character-based data.

**Numeric**  
If the element will deal exclusively with number values.
- **Integers:** store whole numbers (..., -2, -1, 0, 1, 2, ...)
- **Float:** (Floating Point, Decimals) store numbers that contain a decimal. (-1.5, 3.25, 6.0)

**Boolean**  
Hold a single bit (1 or 0). Often used for True/False calculations

**Date and Time**  
Hold date, day of the year, and time of day values. 

**Spatial Values**  
Used for geographic and geometric data.
-  **Geographic:** holds locations and shapes on Earth's surface. (Typically Latitude and Longitude)
-  **Geometric:** describe shapes and objects in a two-dimensional space.

**Unique Identifiers**  
Used to ensure every record, object, or resource can be distinctly recognized.

**Currency**  
Formats numerical values so it can be displayed in a specific way easily identifiable as that country's currency.

**Binary**  
Most common for storing unstructured data called Binary Large Objects (BLObs)

**Large Text**  
Classified as unstructured due to the need to detect nuance, humor, sarcasm, and inferential meaning.

---

### Common Data Structures

Data can be classified into three categories:
- **Structured:** Stored in a consistent, defined manner, organized into columns and rows. 
- **Unstructured:** Characteristics about an event or object (Images, phrases, audio, video, and descriptive text)
- **Semi-Structured:** Data that has structure but not tabular. (example: emails)

**Dimensional Data**  
Contains groupings of individual attributes about a given subject and organizes data into **Fact Tables** and **Dimension Tables**. 
- Fact Tables store measurement data.
- Dimensions tables contain data about the fact.

---

### Classifications

**Quantitative vs. Qualitative**  
- Quantitative data consists of numeric values that answer the questions, "How many? or How much?"
- Qualitative data frequently consists of text and answers the questions, "Why? What?" (characteristics, traits, and attributes)

**Discrete vs. Continuous**
- Discrete uses whole numbers and is used for things that cannot be divided. (Example: Number of children in a classroom)
- Continuous can contain decimal and is used for things measured on a scale. (Examples: Height, weight, averages)

**Categorical**  
Text data that has a known finite number of categories. (Examples: Departments (HR, IT, Admin...) or Status (Up, Down, Suspended...))  
*These categories can be expanded through table modifications.*

---

### Common File Formats

**Text Files**  
Text files contain plain text and are limited to alphanumeric values
- delimiter is a character that separates fields
- Comma-Separated Values(CSV) uses a comma

**JavaScript Object Notation (JSON)**  
Open standard used to add structure to a text file without adding significant overhead.

**Extensible Markup Language (XML)**  
Facilitates adding structure to a text file with more overhead than JSON.

**Hypertext Markup Language (HTML)**  
Used to format documents that are designed to be displayed in a web-browser.

---

### Exam Essentials
- Choose a data type based on the values you will store (and their limits).
- You can often format values for display later; storage type still matters for accuracy and operations.
- Structured = rows/columns; unstructured = free-form (text, images, audio, video); semi-structured = some structure but not fully tabular (e.g., email, JSON-ish content).
- Quantitative = numeric (“how many / how much”); qualitative = descriptive (“what / why”).
- Discrete = countable whole values; continuous = measurable values that can include decimals.
- Categorical = limited set of labels/categories (can grow over time).
- Dimensional models use fact tables (measurements) and dimension tables (context about the facts).
- Know common file formats: delimited text/CSV, JSON (light structure), XML (heavier structure), HTML (web display).

---

### Cliff Notes – Objectives Covered in Chapter 3

**1.1 Explain data concepts**

**Data building blocks**
- **Data element:** attribute of a person, place, thing, or activity (often a column); values fill the rows
- **Data type:** restricts what values an element can hold

**Common data types**
- **String** — character data (most common text type)
- **Numeric** — integers (whole numbers) and floats/decimals (fractional)
- **Boolean** — true/false (often 1/0)
- **Date/time** — dates, times, timestamps
- **Spatial** — geographic (Earth locations) vs geometric (2D shapes)
- **Unique identifiers** — distinctly identify records/objects
- **Currency** — numeric values formatted as money
- **Binary / BLOB** — unstructured binary (files, images)
- **Large text** — long free-form text (nuance/meaning; often treated as unstructured)

**How data is organized**
- **Structured** — consistent rows/columns (tabular)
- **Unstructured** — images, audio, video, free descriptive text
- **Semi-structured** — some structure, not fully tabular (e.g., email)

**How data is classified**
- **Quantitative** — numbers (“how many / how much?”)
- **Qualitative** — text/traits (“what / why?”)
- **Discrete** — countable whole values (e.g., number of children in a class)
- **Continuous** — measured on a scale; can include decimals (height, weight, averages)
- **Categorical** — finite set of categories/labels (set can expand)
- **Dimensional** — fact tables (measurements) + dimension tables (attributes about the facts)

**Common file formats**
- **Text / CSV** — plain text; delimiter separates fields (CSV uses commas)
- **JSON** — lightweight structure on text
- **XML** — structure with more overhead than JSON
- **HTML** — documents meant for web browsers


---

**End of Chapter 3**


</details> <!-- Ends Chapter 3 -->


---

<details>
<summary><strong>Chapter 4: Databases and Data Acquisition</strong></summary>

## Chapter 4: Databases and Data Acquisition

### Domains

Domain 1.0 Data Concepts and Environments
- 1.1 Explain data concepts
- 1.2 Identify types of data sources

Domain 2.0 Data Acquisition and Preparation
- 2.1 Given a scenario, use data acquisition methods

---

### Exploring Databases

**Two Categories:**
- **Relational:** Structured database
  - **Entity:** Contains data for a single subject
  - **Entity Instance:** A specific example of an entity
  - **Entity Relationship Diagram (ERD):** Visual artifact of the data modeling process
  - **Cardinality:** Refers to a relationship between two entities
  - **Unary Relationship:** Entity has a connection with itself
  - **Binary Relationship:** Connects to two entities
  - **Ternary Relationship:** Connects three entities
  - **Associative Table:** Is junction/bridge for many-to-many relationships
  - **Primary Key:** Unique identifier (can be numeric or other types)
  - **Synthetic Primary Key:** Attribute whose only purpose is to contain unique values for each row in a table
  - **Foreign Key:** One or more columns in one table that point to corresponding columns in a related table
  - **Referential Integrity:** Enforces consistency in related tables
  - **Composite Primary Key:** A primary key with more than one column
  - **Database Administrator:** Highly trained person who understands how database software interacts with computer hardware
- **Nonrelational Databases:** No predefined structure. Highly flexible approach to storing data.
  - **Key-Value:** Is one of the simplest ways of storing data. It is a collection of keys and their corresponding values. Example: Song title => audio file of the song
  - **Document:** Similar to a Key-Value except the value is restricted to a specific structure format. Example: JSON
  - **Column Family:** Uses an index to identify data in groups
  - **Graph:** Specialized in exploring relationships between pieces of data.

---

### Database Use Cases

**Major Categories:**
- **Online Transactional Processing (OLTP):** Handles everyday transaction. Example: Flight reservations, online orders...
  - **Normalization:** The process for structuring a database to minimize duplication of data
    - **First Normal Form (1NF):** Each column holds atomic (single) values; no repeating groups; rows uniquely identifiable
    - **Second Normal Form (2NF):** 1NF plus all non primary key values must depend on the entire primary key
    - **Third Normal Form (3NF):** Builds upon 2NF by adding a rule that all columns must depend on only the primary key.
- **Online Analytical Processing (OLAP):** Focuses on an organization's ability to analyze data.
  - Denormalized design
  - More efficient for analytical queries to read large amounts of data in a single table.
- **Schema Concepts:** The schema is the structure and depends on the purpose of the database.
  - **Star:** Facilitates analytical processing. Named after its appearance. Uses denormalized dimensions.
    - The *Fact Table* is in the center.
    - *Dimensional Tables* connect to the Fact Table.
  - **Snowflake:** Similar to star it has a central fact table. Uses normalized dimensions (subcategories)
    - Dimensions have subcategories.
    - Less denormalized than star.
  - **Dimensionality:** Refers to the number of attributes a table has. The greater the number of attributes, the higher the dimensionality.
  - **Handling Dimensionality:** There are many ways to design dimensions (start and end date, indicator flags, effective date...).

---

### Data Acquisition Concepts

Data can come from sources you own (internal) or it can be obtained from a third-party source (external).

The data acquisition process: 
- **Ingestion:** receiving, reshaping, and inserting data. Also known as Extracting, Transforming, and Loading (ETL).
  - **Extracting:** Pulling data from the source system
  - **Transforming:** Reformatting the data to fit your analytical design
  - **Loading:** Ensuring the data is put into the analytical system.
    - **Initial Load:** The first time data is put into the system.
    - **Delta/Incremental Load:** Additional data added later.
  - **Data Source and Collection Methods:** Data is the life blood of an organization.
    - **External Data:** Offers benchmarks or evaluates areas for expansion
    - **Internal Data:** Shows how a company can grow.
  - **Application Programming Interface (API):** Structured method for computer systems to exchange information. API's hide how they do things and focus on what to show the user.
  - **Web Services:** Smartphone applications may not have all the data they need saved on the phone. It connects via Hypertext Transfer Protocol (HTTP).
  - **Web Scraping:** The programmatic retrieval of data from a website. Programming languages like Python and R make this easy.
  - **File:** Common way to integrate and obtain data.
  - **File Types:** CSV, XLS, and JSON.
  - **Logs:** Log files are another common source of data.
    - Dates & Times, IP Addresses, Request Method, URL/Path, HTTP, Status Codes, Bytes Sent, User-Agent
  - **Data Repositories:** Store data in preparation for Analysis.
    - **Data Silo:** Repository controlled by one department or organization
    - **Data Warehouse:** Database containing data from many transactional systems
    - **Data Marts:** Subset of a warehouse that focuses on the needs of a particular department.
    - **Data Lake:** Stores raw data in its native form.
    - **Data Lakehouse:** Combines the warehouse structure with the lake style of data.
  - **Human-in-the-Loop:** When the data you need is found only in the minds of people.
    - **Survey:** You can tailor questions based on your goals and your audience.
    - **Observation:** You can watch people or machines and collect primary Quantitative or Qualitative data.
    - **Sampling:** Collecting data from a smaller group and assuming it is representative of the population. 


---

### Working with Data

To turn a database into an operational database you use the Data Definition Language (DDL). DDL lets you CREATE, ALTER, and DROP tables. 
Once the database is built, you use the Data Manipulation Language (DML) to INSERT, UPDATE, SELECT, and DELETE data in the table. 

- **Filtering:** An entire table gives an overall picture. Filtering provides data on a subset of that table
- **Sorting:** Organizes data in an order in which you find helpful
- **Date Functions:** Often used to narrow a scope of data.
- **Logical Functions:** Can make data substitutions when retrieving data.
- **Aggregate Functions:** Summarizes data to help answer questions.
- **Concatenation:** Merges separate variables into one.
- **Nested Queries:** One query embedded within another query.
- **Working with Multiple Tables:** It is common to pull data from multiple related tables.
  - **Inner Join:** Use columns whose values exist in two tables (first tables foreign key to second tables primary key)
  - **Outer Join:** eturns all rows from one table (LEFT/RIGHT) even without matches; full outer returns all from both
  - **Cross Join:** Creates a cartesian product matching every row of table one with every row of table two.
- **System Functions:** Expose data about the database itself.
  - **Database Session:** Begins when you connect to the database and ends when you disconnect.
- **Query Optimization:** Write efficient queries to do what you intend to do.
- **Parametrization:** Minimize the number of times the database has to translate human readable requests into code the database understands.
- **Full Table Scan:** Reading every row looking for a match
- **Indexing:** Reduces the number of rows to search.
- **Data Subsets and Temporary Tables:** Help when dealing with large volumes of data.
  - **Temporary Tables:** Created to make data more manageable.
  - **Data Subsets:** Use temporary tables for ad hoc analysis
- **Execution Plan:** Shows the details of how a database runs a specific query. Helpful in troubleshooting

---

### Exam Essentials
- Contrast **OLTP** (day-to-day transactions, normalized) with **OLAP** (analysis, often denormalized).
- Explain **normalization** goals and the idea of 1NF / 2NF / 3NF (reduce duplication, depend on the key).
- Describe **star** vs **snowflake** schemas and the roles of fact vs dimension tables.
- Identify **relational** vs **nonrelational** models (key-value, document, column-family, graph).
- Know **primary key**, **foreign key**, **composite key**, **referential integrity**.
- Trace **ETL**: extract → transform → load (initial vs delta/incremental).
- Differentiate **internal** vs **external** sources and methods: APIs, web services, web scraping, files, logs, surveys/observation/sampling.
- Distinguish repositories: **silo**, **warehouse**, **mart**, **lake**, **lakehouse**.
- Use **DDL** (CREATE/ALTER/DROP) vs **DML** (SELECT/INSERT/UPDATE/DELETE).
- Apply filtering, sorting, joins (inner/outer/cross), aggregates, and basic query optimization (indexes vs full table scans).

---

### Cliff Notes – Objectives Covered in Chapter 4

**1.1 Explain data concepts**
- **Relational DB:** entities, instances, ERDs, cardinality (unary/binary/ternary)
- **Keys:** primary (unique row ID), synthetic PK, composite PK, foreign key, referential integrity
- **Associative table:** resolves many-to-many relationships
- **Nonrelational:** flexible, no fixed schema
  - Key-value, document (e.g. JSON), column-family, graph
- **OLTP:** transactional, normalized (1NF → 2NF → 3NF) to reduce duplication
- **OLAP:** analytical, often denormalized for fast reads
- **Schemas:** star (fact center + dimensions), snowflake (dimensions with subcategories)
- **Dimensionality:** number of attributes; design options (effective dates, flags, etc.)
- **DDL vs DML:** structure (CREATE/ALTER/DROP) vs data (SELECT/INSERT/UPDATE/DELETE)
- **Query tools:** filter, sort, date/logical/aggregate functions, concatenation, nested queries
- **Joins:** inner (matches only), outer (keep unmatched from one side), cross (Cartesian product)
- **Optimization:** parameterization, indexes (avoid full table scans), temp tables/subsets, execution plans

**1.2 Identify types of data sources**
- **Internal** (owned systems) vs **external** (third-party / benchmarks / expansion)
- **APIs** — structured system-to-system exchange
- **Web services** — often over HTTP for apps that need remote data
- **Web scraping** — programmatic site retrieval (e.g. Python, R)
- **Files** — CSV, XLS, JSON, etc.
- **Logs** — timestamps, IPs, methods, paths, status codes, bytes, user-agent
- **Repositories**
  - Data silo — department-controlled
  - Data warehouse — integrated from many transactional systems
  - Data mart — department-focused subset of a warehouse
  - Data lake — raw data in native form
  - Data lakehouse — lake flexibility + warehouse structure
- **Human-in-the-loop:** surveys, observation, sampling

**2.1 Given a scenario, use data acquisition methods**
- **Ingestion / ETL:** extract (from source) → transform (fit analytic design) → load (into analytic system)
- **Initial load** vs **delta/incremental load**
- Choose method by scenario: API, file drop, logs, scrape, survey/sample, warehouse/mart/lake feed


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




























