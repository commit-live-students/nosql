![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# Introduction to NoSQL

“A NoSQL (originally referring to “non SQL” or “non relational”) database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relation databases (RDBMS). It encompasses a wide variety of different database technologies that were developed in response to a rise in the volume of data stored about users, objects and products, the frequency in which this data is accessed, and performance and processing needs. Generally, NoSQL databases are structured in a key-value pair, graph database, document-oriented or column-oriented structure.

Over decades and decades of software development, we have been using databases in form of SQL (Structured Query Language) where we store our data in relational tables. However, in recent years with the tremendous rise in use of internet and Web 2.0 applications, the databases have grown into thousands and thousands of terabytes. Applications such as Facebook, Google, Amazon, Watsapp, etc. gave rise to an entire new era of database management which follows approach of simple design, speed and faster scaling than the traditional databases. Such databases are used in big data, massive real time applications and analytics.

As an example, consider that you have a blogging application that stores user blogs. Now suppose that you have to incorporate some new features in your application such as users liking these blog posts or commenting on them or liking these comments. With a typical RDBMS implementation, this will need a complete overhaul to your existing database design. However, if you use NoSQL in such scenarios, you can easily modify your data structure to match these agile requirements. With NoSQL you can directly start inserting this new data in your existing structure without creating any new pre-defined columns or pre-defined structure.

### Benefits of NoSQL over RDBMS
* ***Schema Less:*** NoSQL databases being schema-less do not define any strict data structure.
* ***Dynamic and Agile:*** NoSQL databases have good tendency to grow dynamically with changing requirements. It can handle structured, semi-structured and unstructured data.
* ***Scales Horizontally:*** In contrast to SQL databases which scale vertically, NoSQL scales horizontally by adding more servers and using concepts of sharding and replication. This behavior of NoSQL fits with the cloud computing services such as Amazon Web Services (AWS) which allows you to handle virtual servers which can be expanded horizontally on demand.
* ***Better Performance:*** All the NoSQL databases claim to deliver better and faster performance as compared to traditional RDBMS implementations.

Talking about the limitations, since NoSQL is an entire set of databases (and not a single database), the limitations differ from database to database. Some of these databases do not support ACID transactions while some of them might be lacking in reliability. But each one of them has their own strengths due to which they are well suited for specific requirements.

### Types of NoSQL Databases
#### Document Oriented Databases
Document oriented databases treat a document as a whole and avoid splitting a document in its constituent name/value pairs. At a collection level, this allows for putting together a diverse set of documents into a single collection. Document databases allow indexing of documents on the basis of not only its primary identifier but also its properties. Different open-source document databases are available today but the most prominent among the available options are MongoDB and CouchDB. In fact, MongoDB has become one of the most popular NoSQL databases.

#### Graph Based Databases
A graph database uses graph structures with nodes, edges, and properties to represent and store data. By definition, a graph database is any storage system that provides index-free adjacency. This means that every element contains a direct pointer to its adjacent element and no index lookups are necessary. General graph databases that can store any graph are distinct from specialized graph databases such as triple-stores and network databases. Indexes are used for traversing the graph.

#### Column Based Databases
The column-oriented storage allows data to be stored effectively. It avoids consuming space when storing nulls by simply not storing a column when a value doesn’t exist for that column. Each unit of data can be thought of as a set of key/value pairs, where the unit itself is identified with the help of a primary identifier, often referred to as the primary key. Bigtable and its clones tend to call this primary key the row-key.

#### Key Value Databases
The key of a key/value pair is a unique value in the set and can be easily looked up to access the data. Key/value pairs are of varied types: some keep the data in memory and some provide the capability to persist the data to disk. A simple, yet powerful, key/value store is Oracle’s Berkeley DB.


### Popular NoSQL Databases

* ***Document Oriented Databases*** – MongoDB, HBase, Cassandra, Amazon SimpleDB, Hypertable, etc.
* ***Graph Based Databases*** – Neo4j, OrientDB, Facebook Open Graph, FlockDB, etc.
* ***Column Based Databases*** – CouchDB, OrientDB, etc.
* ***Key Value Databases*** – Membase, Redis, MemcacheDB, etc