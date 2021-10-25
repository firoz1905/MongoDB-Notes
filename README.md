# MongoDB-Notes
Understanding MongoDB

What is MongoDB ?
MongoDB is an open-source NoSQL database written in C++ language. It uses JSON-like documents with optional schemas. 
It provides easy scalability and is a cross-platform, document-oriented database.
MongoDB works on the concept of Collection and Document.
"A Document is an ordered set of keys with associated values. It is represented by a map,hash , or dictionary.
Example : {"Greeting" : "Hello World!"}"
"A Collection is a group of documents. If a document, is the MongoDB analog of a row in a relational database , then collection can be thought of as the analog to a table. Example : {"greeting" : "Hello World!" , "views" :3 } {"signOff" : "Good Bye"}" --- > Collections have dynamic Schemas
"MongoDB groups collections into databases. Reserved Database names - config , local , admin"
Mongo Shell - It is a JS shell that allows to interact with MongoDB instance from the command line. 
It combines the ability to scale out with features such as secondary indexes, range queries, sorting, aggregations, and geospatial indexes


What are some features of MongoDB ?

Indexing - It supports generic secondary indexes and provide unique , compound , geospatial and full-text indexing capabilities as well. 
Aggregation - It supports an aggregation framework based on the concept of data processing pipelines
Special COllection and index types : It supports time-to-live (TTL) collections for data that should expire at a certain time.
File Storage : supports an easy-to-use protocol for storing large files and file metadata
Sharding : process of splitting up data across machines

CRUD operations in MongoDB ?


UPDATE Methods : updateOne , updateMany , replaceOne , updateOne , updateMany . Each of this method takes a filter document as their first parameter and a amodifier document , which describes changes to make as a the second paramter. 
DELETE Methods : deleteOne and deleteMany
find Method is used to perform queries in MongoDB. 
