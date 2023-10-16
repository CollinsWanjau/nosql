# NOSQL DATABASES

## Types of NoSQL Databases

### Key-Value Stores

- Emaphasize simplicity and are very useful in accelerating an app to support high
speed read and write processing of non-transactional data.Stored values can be any type
of binary object(text, images, JSON documents, etc.) and are accessed via a key.

- The app has complete control over what is stored in the value, making the flexible
NoSQL databases.

- Data is partitioned and replicated across a cluster to get scalibility and availability.
For this reason, key-value stores are often used to store user profile information, session and do not support transactions.

- Examples: Redis, Riak, Voldemort, and DynamoDB.

### Document Databases

- Store data in documents that are grouped together in collections. Each document contains
self-describing JSON, XML, BSON, or other binary-encoded format.

- A value is a single document that stores all data required for a single key.

- Popular fields in the document can be indexed to provide fast retruieval of data without knowing the key.

- Document databases are often used to store user profile information, session information, catalog information, and product information.

- Examples: MongoDB, CouchDB, and DynamoDB.

### Column Family Stores

- Store data in a table that consists of a set of rows. Each row has a primary key that uniquely identifies the row.Wide-column NoSQL databases store data in tables with rows and columns similar to relational databases, but names and formats of columns can vary from row to row in the same table.

- Wide-column dbs group columns of related data together.A query can retrieve related data in a single operation because only the columns associated with the query need to be read.

### Graph Databases

- Store data in nodes and edges. Nodes are entities such as people, products, and events. Edges are the relationships between nodes.A graph db uses graph structures to store, map, and query relationships.

- The provide index-free adjacency, so that adjacent elementsa are linked together without using an index.

## Benifits of NoSQL Databases

- Scalability: NoSQL databases are designed to scale out by using distributed clusters of hardware instead of scaling up by using more powerful hardware.NoSQL dbs use a horizontal scaling approach that adds more machines to increase capacity and non-disruptive load balancing to distribute load across the machines.

- Performance: NoSQL databases are designed to be efficient at scale. They use a distributed data architecture that provides horizontal scalability, and they are optimized for a particular data model and specific data access patterns.

- High Availability: NoSQL databases are designed to be highly available and avoid the complexity that comes with a typical RDBMS architecture that relies on primary and secondary servers.

- Global Availablity: NoSQL databases are designed to be globally available and can be deployed in multiple regions around the world.

- Flexible Data Modeling: NoSQL  offers the ability to implement flexbile and fluid data models that can evolve over time.App developers can leverage the data types and query options that are the most natural fit to specific application requirements rather than those that are forced by the database.