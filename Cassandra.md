@Author : Adi

# Notes from the Apache Cassandra DSE 220 Course 
## What is Data Modelling? 

Data Modelling is process/language/tool agnostic 

Steps required for data modelling include: 

* Analyze requirements of the domain
* Identify entities and relatinoships - Conceptual Data Model
* Identify queries-Workflow and Access Patterns
* Specify the schema - Logical Data Model 
* Get somethign wokring with CQL- Physical Data Model 
* Optimize and Fine tuning 

Cassandra is highly query driven and when designing Cassandra, it really pays off to understand the applications's workflow and understand the types of queries the application will support.


## Relational DB vs Cassandra 

Note: 
Cassandra differs quite a bit from normal relational data modelling. 
 
 Main differences are: 
 * Cassandra uses distributed architecture whereas relational db(RDB) have a single point of failure 
 * In RDM, primary keys used for uniqueness. In Cassandra, primary keys are used for that and much much more. 
 * Cassandra can't do joins due to multiple nodes
