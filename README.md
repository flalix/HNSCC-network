---
# title: "GraphDB"
# author: "Raquel L. Costa"
# date: "11/14/2017"
output: html_document
---


# HNSCC Graph Network

### Introduction

Head-neck-squamous cell carcinoma is heterogeneous cancer which affects around 300,000 people in the word per year. Among the risk factors are smoking, alcohol and HPV infections.
The TCGA (The Cancer Genome Atlas) is paramount of data collection of more than 30 cancer types. The diversity of omic layers, such as RNA-seq, methylation, miRNA, proteomic, clinical, copy number variation and mutation, can be analyzed in different aspects including mathematical models, machine learning, and data model. 

The manuscript was submitted to `GigaScience`. The preprint version can be read in [Arxiv:](). We chose the graph data model (in `Neo4j` database) to put and store your results. This model consists mainly of nodes, edges, and properties.  


### Data model of HNSCC


### How to use

#### Install local `Neo4j` (version 2.3.4).

Visit the site: (https://neo4j.com/release-notes/neo4j-2-3-4/) and get the instruction how to download Neo4j.


#### Put the database

The database directory `hdscc.db` can be moved to `neo4j-community-xxx/data/`

#### Change the configuration:

You need change the configuration. 

* Open the archive `/conf/neo4j-server.properties`
* Change the line: `org.neo4j.server.database.location=data/graph.db` to `org.neo4j.server.database.location=data/hpv.db`
* Save and close

#### Start and use the database

* Start Neo4j in: `./bin/neo4j start` 
* Open the browser and write the locahost in 7474 port. (http://localhost:7474)


### Simple queries
There are many possibilities of queries in a graph database. Here we show a possible query.


### Contact
If you have any consideration for this work which can improve the quality, please let us know! Thanks ;-)
Contact quelopes@gmail.com by email. 
<!-- Ask questions and please report any bug you find. -->
