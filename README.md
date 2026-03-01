# Flight Data Warehouse Design

## Project Overview

This project focuses on the **design and implementation of a data warehouse** for flight analysis based on provided source datasets.  

The system enables analysis of:
- Flight delays  
- Punctuality
- Flights frequency

---

## Technical Requirements

- **Environment:** Databricks Community Edition  
- **Implementation Languages:** SQL, Python (PySpark)  
- **Architecture:** Two-layer architecture  
  - `staging` layer  
  - `curated` layer  
- **Data Model:** Star schema or Snowflake schema
- **Support for Slowly Changing Dimensions (SCD)**  
- **Incremental data loading**  
- **Documentation:**  
  - ERD (Entity-Relationship Diagram)  
  - Data workflow diagram  
---

## Implementation Stages

### 1️. Source Data Analysis and Model Design

- Creation of an **ERD diagram**
- Identification of **fact and dimension tables**
- Selection and justification of schema (**star** or **snowflake**)
- Definition of **SCD strategy** for dimension tables

---

### 2️. Staging Layer Implementation

- Creation of **staging tables**
- Implementation of **source data ingestion**
- Data **validation and cleansing**

---

### 3️. Curated Layer Implementation

- Creation of **dimension tables**
- Creation of **fact tables**
- Implementation of **SCD logic**
- Implementation of **incremental loading process**

---

### 4️. Analytical Reports Implementation

- Creation of **analytical views**
- Implementation of **aggregations (daily granularity)**
- Preparation of **example analyses with data visualizations**
