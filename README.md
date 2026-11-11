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

2.0: Data Acquisition and Preparation
- 2.2 Given a scenario, perform data exploration to identify possible inconsistencies with a dataset
- 2.3 Given a scenario, perform appropriate data transformation and cleansing techniques

---

### Data Inconsistencies

Each data source has unique quality issues and associated inconsistencies. When designing an extract, transform and load (ETL) 
process, you need to deal with these issues.

**Data Duplication:** occurs when the same data is entered twice, often as a result of human error.

**Data Redundancy:** Happens when the same data elements exist in multiple places within a system.

**Invalid Data:** Values outside of a valid range for a given attribute.

**Nonparametric Data:** Categorical data. Categories may only distinguish groups, or they may have a meaningful rank order (order matters, not the raw label values).

**Data Outliers:** Values that differ significantly from other observations in the dataset.

**Specification Mismatch:** Occurs when an individual component's characteristics are beyond the range of acceptable values.

**Data Type Validation:** Ensures that values in a dataset have a consistent data type.

**Data Completeness:** The minimum amount of information needed to fulfill a business objective. 

---

### Data Transformation Techniques

**String Manipulation:** Programmatically modifying text to improve data consistency.
- **Regular Expressions (RegEx):** Match text patterns
  - *Anchors:* The position in the string
  - *Boolean:* Allows for matching more than one value (example: neighbor | neighbour matches both neighbor and neighbour
  - *Character Classes:* Ability to match multiple values for a given character
  - *Literals:* Match exactly the characters in a text string
  - *Quantifiers:* Specify the number of time to match a pattern
  - *Wildcards:* Matches any character
- **Conversion:** Change data from one unit of measurement to another.
- **Augmentation:** Adding attributes not found within your original dataset.
- **Scaling:** Changing the range of a numeric variable to ensure consistent measurement and improved ability to compare across variables.
- **Grouping Techniques:** Two common approaches
  - *Clustering:* Forms groups of similar data points using shared attributes.
  - *Binning:* Grouping continuous numerical data into categories (bins). Example: U.S. Census Bureau's Age Categories
- **Reduction:** Shrinking an extensive dataset without negatively impacting its analytical value.
- **Dimensionality Reductions:** Remove attributes from a dataset.
- **Numerosity Reductions:** Reduces the overall volume of data.
- **Aggregation:** Summarization of raw data for analysis.
- **Transposition:** When you want to change rows into columns.
- **Exploding:** Take complex data from a single row and transform it into multiple rows.
- **Standardization:** Converting data into a consistent format to ensure uniformity and comparability.
- **Imputation:** Technique for dealing with missing values by replacing them with substitutes.
  - Remove missing data
  - Replace it with zeros
  - Replace it with overall average
  - Replace it with the most frequent occurence (mode)
  - Replace it with the closest (or neighboring) value average
- **Parsing:** Separating composite data into their component parts
- **Merging:** Combine multiple datasets with different structures into one dataset.
- **Appending:** Combines multiple datasets with the same structure.
- **Recording Data:** Maps old values to new values to facilitate analysis.
- **Derived Variables:** New variables resulting from calculations on existing variables.
- **Deletion:** Removing data from a dataset.
- **Data Blending:** Combines multiple sources of data into a single dataset at the reporting level.

---

### Managing Data Quality

As an analyst you need to recognize situations that cause data quality issues.

**Circumstances to check:** Every step along the lifecycle creates opportunities for data quality issues
- **Data Acquisition:** Source system inconsistencies can result in missing or invalid values.
- **Data Manipulation:** Errors can occur when data is reshaped to fit your structure.
- **Final Product Preparation:** Errors when packaging data into reports and dashboards. 

**Automated Validation:** can be used to prevent mistakes and perform data validation checks.

**Data Quality Dimensions:** There are six dimensions to consider:
- **Accuracy:** How close an attribute matches its intended use.
- **Completeness:** All data is present.
- **Consistency:** Reliability of an attribute.
- **Timeliness:** Is it available when needed.
- **Uniqueness:** Whether or not an attribute exists in multiple places.
- **Validity:** Attributes value is within range.

**Data Quality Rules and Metrics:** Conformity or nonconformity of data

**Methods to validate quality:** Can be done by seeing if the data passes your reasonable expectations or by various statistical methods that look 
for irregularities.
- **Reasonable Expectations:** Is the data being processed at the rate expected? Does the output match your expected results?
- **Data Profiling:** Statistical approach that looks for discrepancies including missing values that occur infrequently, too frequently, or should be eliminated.
- **Data Audits:** Help you understand whether or not you have the data your business needs to operate.
- **Cross-validation:** A statistical technique that evaluates how well predictive models perform. 

---

### Exam Essentials
- Spot common inconsistencies: duplication, redundancy, invalid values, outliers, type mismatches, incompleteness.
- Explain why **missing data** and **outliers** matter and how they affect analysis.
- Apply transformation/cleansing: string work (including RegEx ideas), conversion, scaling, binning/clustering, aggregation, transposition, explode, standardize, impute, parse, merge/append, recode, derive, delete.
- Contrast **dimensionality reduction** (fewer attributes) vs **numerosity reduction** (less volume/rows).
- Contrast **merging** vs **appending** vs **data blending**.
- Name the six quality dimensions: accuracy, completeness, consistency, timeliness, uniqueness, validity.
- Describe ways to check quality: reasonable expectations, profiling, audits, cross-validation; use rules/metrics and automated validation where possible.

---

### Cliff Notes – Objectives Covered in Chapter 5

**2.2 Given a scenario, perform data exploration to identify possible inconsistencies**
- **Duplication** — same data entered more than once  
- **Redundancy** — same elements stored in multiple places  
- **Invalid data** — outside allowed range  
- **Outliers** — values far from other observations  
- **Specification mismatch** — component outside acceptable limits  
- **Data type validation** — values match the expected type  
- **Completeness** — enough information for the business need  
- **Quality dimensions:** accuracy, completeness, consistency, timeliness, uniqueness, validity  
- **Where issues arise:** acquisition, manipulation, final report/dashboard prep  
- **Checks:** reasonable expectations, data profiling, audits, cross-validation; rules/metrics; automated validation  

**2.3 Given a scenario, perform appropriate data transformation and cleansing**
- **String manipulation / RegEx** — anchors, alternation (Boolean), character classes, literals, quantifiers, wildcards  
- **Conversion** — change units  
- **Augmentation** — add attributes not in the source  
- **Scaling** — change numeric range for comparability  
- **Grouping** — clustering (similar points); binning (continuous → categories)  
- **Reduction** — dimensionality (drop attributes); numerosity (reduce volume)  
- **Aggregation** — summarize raw data  
- **Transposition** — rows ↔ columns  
- **Exploding** — one complex row → multiple rows  
- **Standardization** — consistent format  
- **Imputation** — handle missing values (drop; zero; mean; mode; neighbor/closest average)  
- **Parsing** — split composite fields  
- **Merging** — combine different structures; **appending** — same structure; **blending** — combine at reporting layer  
- **Recoding** — map old values → new values  
- **Derived variables** — calculated from existing fields  
- **Deletion** — remove data

---

**End of Chapter 5**

</details> <!-- Ends Chapter 5 -->

---

<details>
<summary><strong>Chapter 6: Data Analysis and Statistics</strong></summary>

## Chapter 6: Data Analysis and Statistics

### Domains 

3.0: Data Analysis
- 3.1 Given a set of requirements, determine the appropriate communication approach for data analysis.
- 3.2 Given a scenario, select the appropriate statistical method or function.
- 3.3 Given a scenario, troubleshoot basic issues using the appropriate tool or method. 

---

### Communication Approaches

Effective communication combines art and science.

**Audience:** The group of people your data is for. 

**User persona types:** The typical audience member
- **Individual contributors:** Need sufficient data to perform their role.
- **Nontechnical Managers:**Need operational data to make tactical decisions.
- **Technical Managers:** Need operational data, source data, and analytical method.
- **Product Leadership:** Data about products they own, market size, customer desires, production details, and distribution information.
- **C-Suite:** (CEO, CFO, CTO, COO...) Insights that enable strategic decision-making. Less likely to understand methods.

**Constituents:** consider if you have internal or external constituents. This impacts the sensitivity of data.
- **Information Sensitivity:** Not all data is approved for all people.

**Key Performance Indicators (KPIs):** are metrics that leaders agree are crucial to understanding how an organization is performing.

- **Chief Finance Officer (CFO)**
  - Gross Profit Margin
  - Cost of Goods Sold
  - Net Profit Margin
  - Working Capital
  - Operating Cash Flow
  - Debt-to-Equity Ratio
  - Burn Rate
  - Accounts Receivable
  - Accounts Payable
- **Chief Marketing Officer**
  - Brand Awareness
  - Churn
  - Customer Satisfaction Customer Lifetime Value
  - Cost per Click
  - Net Promotor Score (NPS)
  - Return on Market Investment
- **Human Resource (HR)**
  - Employee Satisfaction
  - Turnover
  - Cost per Hire
  - Time to Hire

**Mock-up:** A simplified visual prototype to show the audience. 

**Accessibility:** Presents the data in a way they can understand regardless of any physical disabilities (colors, contrast, fonts).

### Fundamentals of Statistics

Knowledge of statistics is the foundation for modern data analysts.
- **Population:** All the data points you want to study.
- **Sample:** A subset of a population.
- **Variable:** A unique attribute about a data subject.
- **Observation:** Individual record in a dataset corresponding to a tabular row.
  - **Sample Size:** Number of observations from the population.
  - **Statistic:** Numeric representation of a property of a sample.
  - **Parameter:** Numeric representation of a property for the population.

**Statistical Functions and Measures**
- **Mathematical:** Measure the frequency, central tendency, dispersion, and position of data.
  - **Count:** Straight forward way to understand how much data
  - **Percentage:** Identifies the proportion of a given value (occurrence / total) * 100.
  - **Frequency:** How often a specific value for a variable occurs.
- **Measures of Central Tendency:** Identify the central or most typical, value in a dataset.
  - **Mean:** Average, sum / total
  - **Median:** Midpoint value for all observations of a variable.
    1) Sort the data numerically
    2) Find the middle value
       a) Odd count is the middle value (1,3,4,6,9) 4 would be the median.
       b) Even count, take the mean of the middle two values. (1,3,4,5,6,9) middle values are 4 & 5 median would be 4.5
  - **Mode:** A variable's most frequently occurring value.

**Measures of Dispersion:** Creates context around data spread
- **Range:** The difference between the Maximum and Minimum values.
- **Distribution:** A function that illustrates probable values for a variable and the frequency with which they occur.
  - **Normal Distribution:** Symmetrically dispersed around the mean.
  - **Central Limit Theorem (CLT):** As a sample size increases it becomes increasingly likely that the sampling distribution of all those means will be normally distributed.
  - **Skewed:** Occurs when the mean and median are far apart.
  - **Skewed Distribution:** Asymmetrical shape with one peak and a long tail on one side.
    - A right skew is positive
    - A left skew is negative
  - **Bimodal Distribution:** Has two distinct modes.
  - **Variance:** How far from the mean value each other data point is. How spread out the dataset is.
  - **Standard Deviation:** Statistic that measures dispersion in terms of how far the values of a variable are from its mean. It is the average distance of values from the mean (spread around the mean).
  - **Quartile:** Dividing a sorted dataset into four groups.
  - **Interquartile Range (IQR):** Combines the second and third quartile and consists of the middle 50% of the sorted dataset.
- **Logical:** Logical functions evaluate if a condition is true or false.
  | **Operator** | **Description** |
  |--------------|-----------------|
  | `IS NULL`    | Tests if the entry is blank |
  | `IS NOT NULL` | Checks if the variable has an entry |
  | `OR`          | Checks whether either of the conditions are true |
- **Date:** Date functions help you work with and manipulate dates.
- **String:** String functions are used to improve data quality by cleaning and transforming text data.
  | **Function** | **Description**                                           |
  |--------------|-----------------------------------------------------------|
  | `UPPER()`    | Converts the string to all uppercase                      |
  | `LOWER()`    | Converts the string to all lowercase                      |
  | `INITCAP()`  | Converts only the first letter of the string to uppercase |
  | `TRIM()`     | Removes leading or trailing white space                   |

**Standard deviation on the exam:**  
Know what it is and how to interpret it (larger SD = more spread). You are not expected to grind the full formula by hand. 
Same for variance. You should be able to find mean, median, mode, range, and read a simple normal vs skewed picture.

---

### Troubleshooting

**Validate Data Sources**

Validating data sources is essential to troubleshooting: 
- **Header Record:** Check column names.
- **Footer Record:** Check to see if there are the correct number of entries.
- **Checksum:** Check the size of the file.
- **Network Rules:** Ensure no firewall rules interfere with migrating data. 

---

### Analysis Techniques

**Determine Type of Analysis:** Type is driven by the business objectives and desired outcomes.

**Types of Analysis:**
- **Trend Analysis:** Identify patterns by comparing data over time.
- **Performance Analysis:** Measures performance against defined goals.
- **Link Analysis:** Measures the relationships between two data points to discover patterns.

**Exploratory Data Analysis**  
An exploratory data analysis (EDA) uses descriptive statistics to summarize the main characteristics of a dataset, identify outliers, and give you context.
- Steps:
  - Check the data structure
  - Check the data representation
  - Check for missing data
  - Identify outliers
  - Summarize statistics
  - Check assumptions

---

### Exam Essentials

- Match communication to **audience** (individual contributors, nontechnical managers, technical managers, product leadership, C-suite) and sensitivity (internal vs external).
- Use **KPIs** appropriate to the role (finance, marketing, HR examples).
- Distinguish **population / parameter** vs **sample / statistic**; know observation, variable, sample size.
- Calculate/interpret **central tendency**: mean, median (odd/even rules), mode.
- Describe **dispersion**: range, variance, standard deviation, quartiles, IQR; normal vs skewed (right/positive, left/negative) vs bimodal; idea of CLT.
- Choose analysis type: **trend**, **performance**, **link**; use **EDA** steps (structure, representation, missing data, outliers, summary stats, assumptions).
- Use logical vs string (and date) functions for validation/cleaning.
- Troubleshoot sources with header/footer checks, checksums, and network/path issues.

---

### Cliff Notes

**3.1 Given a set of requirements, determine the appropriate communication approach**
- Know the **audience** and **persona** (individual contributor → C-suite).
- **C-suite** wants strategic insight, not method detail; technical managers want methods + sources.
- **Internal vs external** constituents → data sensitivity.
- **KPIs** = agreed metrics of performance (examples by CFO / CMO / HR).
- Support understanding with **mock-ups** and **accessibility** (color, contrast, fonts).

**3.2 Given a scenario, select the appropriate statistical method or function**
- **Population** vs **sample**; **parameter** (population) vs **statistic** (sample).
- **Central tendency:** mean (average), median (middle after sort), mode (most frequent).
- **Dispersion:** range (max − min), variance, standard deviation (spread from mean), quartiles, IQR (middle 50%).
- **Distribution:** normal (symmetric about mean), skewed (mean ≠ median; right = positive, left = negative), bimodal (two peaks).
- **CLT:** larger samples → sampling distribution of the mean tends toward normal.
- **Count, percentage, frequency** for basic magnitude/proportion.
- **Logical** (IS NULL, IS NOT NULL, OR…), **date**, **string** (UPPER, LOWER, INITCAP, TRIM) functions.
- Analysis types: **trend** (over time), **performance** (vs goals), **link** (relationships).
- **EDA:** structure → representation → missing data → outliers → summary stats → assumptions.

**3.3 Given a scenario, troubleshoot basic issues using the appropriate tool or method**
- Validate **data sources**: header (column names), footer (row counts), checksum (file integrity/size), network rules (delivery blocked?).
- Use logical/string/date checks to find blanks, bad formats, and inconsistent text.
- EDA steps double as troubleshooting when results look wrong.

---

**End of Chapter 6**
 
</details> <!-- Ends Chapter 6 -->


---

<details>
<summary><strong>Chapter 7: Data Visualization with Reports and Dashboards</strong></summary>

## Chapter 7: Data Visualization with Reports and Dashboards

### Domains

Domain 3.0: Data Analysis
- 3.1 Given a set of requirements, determine the appropriate communication approach for data analysis
- 3.2 Given a scenario, select the appropriate statistical method or function
- 3.3 Given a scenario, troubleshoot basic issues using the appropriate tool or method

---

### Exploring Visualization Elements

**Charts:** Fundamental method to visualize both quantitative and qualitative data.
- **Line:** Trends over time.
- **Pie:** Parts of a whole (few slices).
- **Bar:** Compare categories.
- **Stack Bar:** Category totals split by subcategory.
- **Scatter:** Relationship between two numeric variables.
- **Bubble:** Scatter + third variable as size.
- **Histogram:** Distribution of one numeric variable.
- **Waterfall:** Cumulative increase/decrease.

**Maps** 
- **Geographic Maps** Excellent for location-related data.
- **Heat Maps:** Uses color and location to visually illustrate significance.
- **Tree Maps:** Uses rectangles whose area depicts a proportional representation of hierarchical data.

**Pivot Tables:** Use aggregation functions (SUM, COUNT, AVERAGE, MAX, and MIN) to reshape and summarize data.

**Infographics:** Information graphics minimize text in favor of visual elements to display data in an easy to understand way.

**Word Cloud:** A visualization that uses shapes, font size, and color to signify the relative importance of words. 

---

### Understanding Business Requirements

**Key Terms**
- **Report:** Electronic or physical document that reflects information at a given time.
- **Dashboard:** An interactive visualization that encourages people to explore data dynamically. 

To create proper and effective reports and dashboards you must know who your audience is.

Electronic reports can be handled in one of three ways.
- **Pull Approach:** You publish a report on a regular basis to a location where the audience can access it. They can retrieve it as needed. 
- **Push Approach:** Report is generated and automatically sent to an audience list.
- **Blended Approach:** You store the report in a central location and notify the list of people it is ready.

---

### Understanding Design Elements

When creating reports or dashboards use the five Cs of design principles
- **Control:** Focus the attention of your audience. Make it quick and easy to find the data they need.
- **Correctness:** Make sure that your information is accurate and free of spelling errors.
- **Clarity:** Select the right visualization tool for communicating your message.
- **Consistency:** Use the same design and elements throughout your report and dashboard.
- **Concentration:** Using visuals to focus your audience's attention on the most relevant information without overwhelming them with details.

**Cover Page:** This is the first thing people see. Therefore, it should have a concise title describing the report's contents.

**Executive Summary:** Following the cover page is the executive summary which provides an overview of the reports contents.

**Branding:** Always adhere to the corporate branding standards

**Color Schemes:** Limited selection of colors used when creating a report or dashboard. 
- **Monochromatic** palette limits you to working with shades of a single color.
- **Complementary** palette starts with two contrasting colors. 

**Layouts:** When designing reports and dashboards it is crucial to think about approachability. Begin with a summary before diving into details. 
For long multipage reports, use a Table of Contents, short paragraphs, and bullet points.
- **Parallel Construction:** Use the same style bullet point through!!

**Fonts:** Avoid ornate fonts. Instead, use easy to read fonts like: 
- serif (Times New Roman, Garamond, Courier New) for printed reports
- sans serif (Arial, Helvetica, Geneva) for digital reports

**Graphics:** In reports and dashboards, displaying summary information graphically is a practical choice. "A picture is worth a thousand words." Clearly labeled graphics and charts can deliver a lot of information quickly. 

**Corporate Reporting Standards:** Comply with your organization's style guide (logos, color schemas...)

**Documentation Elements:** To help build trust incorporate versions numbers, reference data sources, and reference data. 
- **Version numbers:** Numeric value that refers to a specific report.
- **Reference Data sources:** List where and when the information is from adds validity and a time frame.

**Frequently Asked Questions (FAQ):** Having a section that answers commonly asked questions is a good practice. 

---

### Understanding Dashboard Development Methods

Dashboards are dynamic tools that assist people explore data to inform their decision-making.

**Consumer Types:** It is crucial to identify who will be interacting with the dashboard. As you identify what your consumers want to see, you can locate where to get the relevant data. 
- **Service Level Agreement (SLA)** - may be desired when designing a dashboard for external customers.

**Data Source Considerations:** Next you need to decide whether or not you need live data.
  - **Static Data:** Data that refreshes at some regular intervals.
  - **Continuous Data (Live Data):** Comes from operational databases that people use to perform their daily duties.

**Data Type Considerations:** Regardless of whether you generate reports or use a dashboard, make sure your software can handle the data type of each attribute.

**Development Process:** Use wireframes and mockups to help build and refine the dashboard's design.
- **Wireframe:** is a blueprint for an application that defines basic design and functions.
- **Mockups:** Extend a wireframe with details about the visual elements. 

**Operational Considerations:** Obtain feedback while designing the dashboard. Clarify access permissions. 
- **Access Permissions:** define who can view the data.

---

### Delivery Considerations

As always, remember to identify your audience.

Static and Dynamic Delivery: Determining if your dashboard or report needs to be static or dynamic is imperative! It determines where and how you get your data.
- **Static:** reports and dashboards pull data from resources that reflect a specific point in time.
- **Dynamic:** reports and dashboards provide real-time access to information
- **Self-service Portals:** provide on-demand access to aggregated data. 

**Frequency:** One more thing to consider when designing reports and dashboards is how and how often the data will be refreshed. 
- **Subscription:** Allows people to opt in for notifications when data changes.
- **Scheduled Delivery:** Providing data at a specific time and frequency (Example: Close of Business reports)
- **Drill Down:** Showing an overview, but allowing the user to see more details as needed.
- **Ad Hoc:** One-time reports use existing data to meet a unique need.
- **Recurring Reports:** Provide a summary on a regularly scheduled basis.
- **Compliance reports:** Details how your organization meets compliance obligations
  - *Financial Compliance reporting:* Public U.S. companies need to report finances in accordance with the Sarbanes-Oxley Act.
  - *Safety Compliance reporting:* Shows compliance with the Occupational Safety and Health Act (OSHA).
  - *Health Compliance Reporting:* For companies that deal with medical records, they must comply with the Health Information Portability and Accountability Act (HIPAA).
  - *Risk Compliance Reports:* These reports are used to build trust and cover how the organization maintains its IT system.
  - *Regulatory Compliance Reports:* Demonstrates how the organization meets regulatory obligations like the Payment Card Industry and Data Security Standard (PCI DSS).

**Data Versioning Techniques:** By adding a unique version number to each change in data, you can ensure everyone is on the same page when comparing data. 

**Tactical and Research**
- **Tactical Reports:** Give information regarding short-term decisions.
- **Research Reports:** Provide information for strategic decisions.

---

### Report Validation Techniques

Organizations rely on reliable, accurate reports when making decisions. 

**Issues:**
- Untimely report delivery due to load times.
- Excessive time with ETL processing.
- Processing large amounts of data causes low refresh rates.
- Stale data pulled from old sources.

Combining techniques and operational experience will help mitigate, troubleshoot, and resolve problems.

**Data Filtering:** Creating a subset of data from existing data to make searching easier.

**Reviews:** During the development process it is important to resolve issues before they make it to productions.

**Source Validation:** Ensures the data used for the report is accurate, complete, and free of formatting anomalies. 

**Data Structure:** Changes to data structure resulting from changes to the data schema, may affect how the API behaves. 

**Monitoring Alerts:** Raise exceptions when the ETL or data refresh process fails. 

---

### Exam Essentials

### Exam Essentials
- Start visualization work by identifying **audience**, goals, and sensitivity (same idea as Ch. 6 communication).
- Contrast **report** (point-in-time document) vs **dashboard** (interactive exploration).
- Match **chart type** to the question (trend → line; parts of whole → pie; categories → bar; distribution → histogram; two numerics → scatter; etc.).
- Apply the **five Cs**: control, correctness, clarity, consistency, concentration.
- Know delivery modes: **push / pull / blended**; **static vs dynamic**; subscription, scheduled, ad hoc, recurring, compliance.
- Use design basics: cover/summary, branding, color schemes, layout, fonts (serif print / sans-serif screen), versioning, source citations.
- Dashboard process: consumers → data sources (live vs scheduled) → wireframe → mockup → access permissions.
- Validate reports: filtering, reviews, source checks, structure/API impacts, monitoring/ETL alerts; watch load time, stale data, slow refresh.

---

### Cliff Notes – Objectives Covered in Chapter 7

**Communication & design (ties to 3.1)**
- Know **who** the report/dashboard is for before choosing visuals or KPIs.
- **Report** = snapshot document; **dashboard** = interactive exploration.
- Delivery: **pull** (users fetch), **push** (auto-send), **blended** (store + notify).
- **Five Cs:** Control, Correctness, Clarity, Consistency, Concentration.
- Structure: cover page → executive summary → body; branding; limited color scheme (monochromatic / complementary).
- Fonts: **serif** for print; **sans-serif** for screen; avoid ornate type.
- Trust elements: version numbers, data sources/dates, FAQs.

**Choosing visuals (analysis communication)**
- **Line** — change over time  
- **Bar / stacked bar** — category comparison / composition  
- **Pie** — proportion of a whole (use sparingly)  
- **Scatter / bubble** — relationships (bubble adds a size variable)  
- **Histogram** — frequency distribution of numeric data  
- **Maps / heat maps / treemaps** — location, intensity, hierarchy  
- **Waterfall** — cumulative effect of gains/losses  
- **Word cloud** — relative word importance  
- **Pivot tables** — SUM, COUNT, AVERAGE, MAX, MIN summaries  
- **Infographics** — visuals over dense text  

**Dashboard development**
- Identify **consumers**; consider **SLA** for external users.
- **Scheduled/static** refresh vs **live/real-time** operational data.
- **Wireframe** (structure/function) → **mockup** (visual detail).
- Set **access permissions**; gather feedback during design.

**Delivery & report types**
- **Static** vs **dynamic** content.
- **Frequency:** subscription, scheduled delivery, drill-down, ad hoc, recurring.
- **Compliance examples:** SOX (financial), OSHA (safety), HIPAA (health), PCI DSS (card data), risk/IT controls.
- **Tactical** (short-term) vs **research/strategic** reports.
- **Versioning** so everyone compares the same snapshot.

**Validation / troubleshooting (ties to 3.3)**
- Problems: slow load, heavy ETL, low refresh, **stale** data.
- Mitigations: **filtering**, design **reviews**, **source validation**, watch **schema/API** changes, **monitoring alerts** on ETL/refresh failure.

---

**End of Chapter 7**

</details> <!-- Ends Chapter 7 -->


---

<details>
<summary><strong>Chapter 8: Data Governance</strong></summary>

## Chapter 8: Data Governance

### Domains

  5.0: Data Governance
  - 5.1 Explain data management concepts
  - 5.2 Summarize concepts related to data compliance
  - 5.3 Compare and contrast data privacy and protection practices
  - 5.4 Compare and contrast data quality assurance practices

---

### Data Management Concepts

**Data Management:** Collection of architectures, policies, practices, and procedures defining how an organization manages data over its lifetime.

**Data Governance:** Set of policies, procedure, and controls an organization develops to safeguard data. 

**Integration:** The practice of consolidating data from disparate sources to improve organizational decision making. 
- **Real-time Integration:** Provides the most current data available.
- **Batch Integration:** A snapshot of data at a specific time.

**Documentation:** Proper use of accurate documentation builds stability and confidence.

**Data Flow Diagram (DFD):** A visual drawing of how data moves through the system.

**Data Lineage:** Describes the complete lifecycle of data from creating to final destination.

**Data Dictionary:** A document detailing the specifics of objects within a relational database, including tables, indexes, and views.

**Hierarchy Structure:** Organizes data in a tree-like arrangement, representing parent-child relationships.

**Source of Truth:** The authoritative system of records for data within an organization. 

**Data Versioning:** Systematically tracks and manages dataset changes over time by uniquely identifying each version.

**Metadata:** Data that describes data. Provides business context you do not receive when examining the data itself.

**Data Governance Roles:**
- **Data Stewardship:** The act of developing policies and procedures for looking at an organization's data quality
- **Organizational Data Steward:** The person responsible for data stewardship.
- **Data Owner:** The senior business leader with overall responsibility for a specific data domain.
- **Data Domain:** Data about a particular operational division of the orgainzation.
- **Subject Area Data Steward:** Works in the owner's organization and handles the day-to-day governance activities.
- **Data Custodian:** Someone who implements technical controls that execute governance policies. 

---

### Data Compliance Concepts

Data compliance ensures that organizations handle, process, and store data while adhering to legal, regulatory, and industry standards.

**National Institute of Standards and Technology (NIST): A nonregulatory agency of the U.S. Department of Commerce that promotes innovation. They provide standards and guidelines on subject areas like cybersecurity, cryptography, and risk management. 

**Retention:** Policy-driven process that defines how long to hold data.

**Jurisdictional Requirements:** There are four regulatory and compicance obligations to consider. 
- **Criminal Law:** Used to discourage people from acting in a way that negatively impacts society.
- **Civil Law:** Used to resolve disputes between individuals, organizations, and goverments.
- **Administrative Law:** Allows government administrative agencies to create regulations.
- **Private Industry Regulations:** Aims to govern the activities of individuals and orgainzations without the force of law.

**Replication:** Copies date from one environment to another.

**Storage:** A durable location that holds data at rest.
- **Block Storage:** Directly accessible by the operating system.
- **Object Storage:** Stores data as individual objects.

**Data Ethics:** Moral principles guiding responsible collection, use, and sharing of data. 

**Payment Card Industry (PCI):** Nongovernmental body that governs car-based financial payments.

**PCI Data Security Standard (PCI DSS):** Core information security standard.
- Six principles:
  - Building and maintaining a secure netowrk.
  - Protecting cardholder data.
  - Maintaining a vulnerability management program.
  - Implementing strong access controls
  - Regularly monitoring and testing networks
  - Maintaining an information security policy.
- Two Primary Categories:
  - **Cardholder Data (CHD):** Data from the front of the card. (Name, primary account number, and expiration date)
  - **Sensitive Authorization Data (SAD):** Information from the back of the card. (Track data, Personal Identification Number (PIN), and Card Verification Value (CVV)).

**Personally Identifiable Information (PII):** Data that uniquely identifies an individual. NIST defines PII as:
- Full Name
- Date and Place of Birth
- Driver's License Number
- Passport Number
- Credit Card Numbers
- Addresses
- Telephone Numbers
- Email Addresses
- Login Credentials and Passwords

**Protected Health Information (PHI):** A broad category of data elements identifying an individual's health information. 
In the U.S., the **Health Insurance Portability and Accountability Act (HIPAA)** is the comprehensive law that regulates PHI.  
The 18 elements of PHI:
- Names
- Geographic Identifiers smaller than a state
- Dates other than years relating to an individual
- Telephone numbers
- Fax numbers
- Email address
- Social Security Number (SSN)
- Medica record numbers
- Health plan beneficiary numbers
- Account numbers
- Certificate or license numbers
- Vehicle identifiers
- Device identifiers and serial numbers
- Web Uniform Resource Locators (URL)
- Internet Protocol (IP) addresses
- Biometric identifiers
- Full-face photographs
- Any other unique identifying numbers, characteristics, or codes

**Audit:** Examines an organization's data management practices, security controls, and regulatory compliance.

**Classification:** Assigns a risk-based category to data based on its level of sensitivity, value, and relevant regulatory requirements.

**Incident Reporting:** Documents how to respond to security events that compromise data integrity, confidentiality, or availability. It generally includes the following steps:
1. Verify the breach
2. Stop the breach
3. Assess the impact of the breach
4. Notify the impacted parties
5. Correct the cause of the breach
6. Conduct a comprehensive review.

---

### Data Privacy and Protection


























</details> <!-- Ends Chapter 8 -->




  
</details> <!-- Ends Chapters -->

---




























