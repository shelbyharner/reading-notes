# Mongo and Mongoose

## SQL vs NoSQL
  - SQL databases are referred to as relation databases
  - NoSQL databases are referred to as non-relational or distributed
  - SQL - table based database, predefined schema that must be adhered to
  - NoSQL - document based, key-value pairs, graphs or wide-column stores, dynamic schema for unstructured data
  - SQL databases are vertically scalable, NoSQL databases are horizontally scalable
  - SQL databases are good for complex queries and NoSQL databases are not
  - SQL is not good for hierarchical data storage
  - NoSQL is good for hierarchical data storage and is similar to JSON data
  - Better, large scale support for SQL compared to NoSQL
  - SQL databases are either open or closed source, NoSQL can be classified based on the type of data storage (key-value, document, graph)
  - SQL database examples:
    - MySQL community edition: open source database stacked with apache and PHP, can also be stacked with nginx and server side JS using Node.js
    - MS-SQL server express edition: powerful, user friendly, with stable, reliable and scalability support from Microsoft
    - Oracle express edition: limited edition of Oracle Enterprise Edition server, with certain limitaions. Free for development and deployment
  - NoSQL database examples:
    - MongoDB: document based database that stores data in JSON like documents, non-relational and dynamic, written in C++
    - CouchDB: also a document based database that stores data in JSON like documents
    - Redis: open source and lightening fast, written in ANSI C language

## NOSQL DATA MODELING TECHNIQUES
  - SQL data model was designed a long time ago and with the end user in mind
    - the end user typically wants aggregated reporting information that is not in separate data items
  - NoSQL data modeling includes key-value, document based, and graph models
  - NoSQL data modeling is typically driven by application specific access patterns like the types of queries to be supported
  - Denormalization is the copying of the same data into multiple docs or tables in order to simplify a query process
  - Aggregates are soft schema capabilities for all major genres of NoSQL
  - Application side joins are a many to many relational model (scaffolding, hierarchy)
  - Atomic aggregates allow one to store a single source of data as a document, row or key-value pair and update atomically
  - Enumerable keys are an unordered key-value data model that can be partitioned and stored across multiple servers by hashing the key
  - Dimensionality reduction is a technique that allows one to map multidimensional data to a key-value model or other non-multidimensional model
  - Index table is a technique that allows storing of indexes in a place that does not support indexes internally
  - Composite key index allows a store with ordered keys to be sorted and built into multidimensional indexes
  - Aggregation with composite keys is used for indexing and grouping of large arrays of data
  - Inverted search - direct aggregation is a data processing pattern instead of data modeling, uses an index to find data that meets a criteria
  - Tree aggregation is a hierarchy graph of a record of a document
  - Adjacency list is a way of graph modeling that shows a record of arrays of direct ancestors or descendants
  - Materialized paths help to avoid recursive traversals of tree-like structures
  - Nested sets is a technique for modeling tree-like structures, used in relational databases
  - Nested document flattening is making a document a flat list of fields and values

Save for reference: https://mongoosejs.com/docs/api.html#Model