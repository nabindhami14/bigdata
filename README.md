![](https://devopsideas.com/wp-content/uploads/2018/11/Elasticsearch_component_relation.png)

> CLUSTER  
> NODE (single server in the cluster, identified by the unique name)  
> SHARD (indexes are broken up into shards, shard is essentially piece of an index)  
> DOCUMENT (baisc unit of the information expressed in the JSON)

### ADVANTAGE OF THE NO SQL DATABASE (SHARDS)

- Scalability (Horizontal Scaling)
- Flexibility (Schema-less Data Models)
- High Performance (Efficient Storage and Retrieval)
- Distributed Architecture (Fault Tolerance and High Availability)
- Real Time Processing (Stream Processing)
- Handling Unstructured Data (Variety of Data Type)
- Specialized Use Cases (Tailored Solutions)

### NO SQL DATABASES

#### KEY VALUE PAIR

Store data as a collection of key-value pairs, where the key is a unique identifier. Caching, session management, user preferences.

> REDIS DYNAMODB

#### DOCUMENT

Store data as documents, typically in JSON, BSON, or XML format. Each document contains a set of key-value pairs, where values can be nested.

> MONGODB

#### COLUMN

Store data in columns rather than rows. Columns are grouped into families, and each column family is stored together.

> APACHE CASSANDRA, HBASE

#### GRAPH

Store data as nodes, edges, and properties. Nodes represent entities, edges represent relationships, and properties are attributes of nodes and edges.

> Neo4j

### HADOOP

**_Open source framework distributed storage(hdfs) and distributed processing(map-reduce)._**

#### HADOOP COMPONENTS

![](https://media.geeksforgeeks.org/wp-content/uploads/20200621102239/Hadoop-componants.png)

##### MAP REDUCE (DISTRIBUTED PROCESSING)

##### HDFS (HADOOP DISTRIBUTED FILE SYSTEM | DISTRIBUTED STORAGE)

##### YARN (YET ANOTHER RESOURCE NEGOTIATOR)

##### HADOOP COMMON

#### HADOOP ARCHITECTURE

![](https://media.geeksforgeeks.org/wp-content/uploads/20200621121240/Namenode-and-Datanode.png)

##### HDFS (NAME NODE AND DATA NODE)

### ROLES OF DISTRIBUTED SYSTEM IN BIG DATA ANALYTICS

- Scalability (HORIZONTAL SCALING)
- Parallel Processing (DIVIDED INTO SMALLER SUB TASKS)
- Fault Tolerance (ONE SYSTEM FAILS, OTHER FUNCTIONS)
- Data Locality (COMPUTATION IS PERFORMED AS CLOSE AS DATA, REDUCES DATA TRANSFER TIME)
- Data Replication and Distribution (DATA DISTRIBUTED ACROSS MULTIPLE NODES, LOAD BALANCE, REPLICATION INTO MULTPLE NODES ENSURES FAULT TOLERANCE)
- Data Partitioning (LARGER DATA PARTIONING INTO SMALLER, MANAGABLE CHUNKS, RESOURCE UTILIZATION)
- Distributed File System (GFS, HADOOP)
- Resource Management (HADOOP (YARN) allocate resource dynamically)
- Real Time Processing (APACHE KAFKA)

### GOOGLE FILE SYSTEM

#### GFS CLIENTS

> **_Computer programs or applications which may be used to request file, requets may be to access or modify already-existing file or add new files._**

#### GFS MASTER SERVERS

> **_NAMESPACE, METADATA_**

#### GFS CHUNK SERVERS

> **_Data linux file system, 64 Sized chunks, (3 copies)._**

### FULL TEXT SEARCHING

Full text indexing is the process of creating a data structure, known as index that stores information about the words or terms found in the locations. The primary goal of full-text indexing is to speed up search operations by pre-processing and organizing textual data, allowing for quick and efficient retrieval of relevant documents. During indexing, the text is typically tokenized, breaking it into individual words or terms. Common words (stop words) and punctuation may be excluded to reduce index size and improve search performance.

Searching involves querying the full-text index to identify and retrieve documents that match certain criteria or contain specific keywords.
Search queries can be formulated using query languages that allow users to express complex search criteria, including Boolean operators, proximity searches, and wildcard characters. Many search systems use algorithms to rank the relevance of documents based on factors such as keyword frequency, document length, and other relevance metrics.

### DATA SCIENTIST ROLES (P2D4C)

#### PROBLEM FORMULATION

#### DATA COLLECTION AND EXPLORATION

#### DATA CLEANING AND PREPROCESSING

#### DATA ANALYSIS AND MODELING

#### PROGRAMMING AND SCRIPTING

#### DATA VISUALIZATION

#### COMMUNICATION AND COLLABRATION

### BIG DATA

#### VOLUME

> **_Size of data._**

#### VARIETY

> **Structured(RDBMS), Unstructured(XML, JSON) and semi structured(AUDIO, VIDEO, FILES).\_**

#### VELOCITY

> **_Speed of generation of the data._**

#### VARIABLILITY

> **_Inconsistency in the data._**

#### VARACITY

> **Quality on the data collected.\_**

#### VISUALIZATIONS

> **_Non technical understandable_**
