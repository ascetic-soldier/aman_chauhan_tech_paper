# NoSQL
![NoSQL](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.OtCl-xXBm41hNobE5iGosQHaDt%26pid%3DApi&f=1 "NoSQL")

As a software developer, we'll always need a database to  gather data from or to save data in, for our projects. 
> ### What is a database ? 
> Databases can be considered as one of the important component entity for technology and applications. Data need to be stored in a specific structure and format to retrieve it whenever required.
> A database is a collection of information, stored on a computer, that can be accessed in a variety of ways. The two main types of databases are _relational_ and _non-relational_ databases.



As we have seen, that two major databases are -

* __Relational__ - A relational database, or relational database management system (RDMS), stores information in tables. Often, these tables have shared information between them, causing a relationship to form between tables. This is where a relational database gets its name from.  
![Relational vs Non-Relational](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.sod01hENrZ4YGn2P79yb0QHaEJ%26pid%3DApi&f=1 "Relational vs Non-Relational")
* __Non-Relational__ - A non-relational database, sometimes called NoSQL (Not Only SQL), is any kind of database that doesn't use the tables, fields, and columns structured data concept from relational databases. Non-relational databases have also been designed with the cloud in mind, making them great at horizontal scaling. 

Now, as we  are aware, _"what is a non-relational database? "_, we are well-equipped to understand __NoSQL__.

__NoSQL__ can be defined as an approach to database designing, which holds a vast diversity of data such as __key-value, multimedia, document, columnar, graph formats, external files,__ etc.

It is purposefully developed for handling specific data models having flexible schemas to build modern applications.

It is pretty famous for its high functionality, ease of development with a performance at scale. Because of such diverse data handling feature, NoSQL is called a non-relational database. It does not follow the rules of Relational Database Management Systems (RDBMS), and hence do not use traditional SQL statements to query data. 

NoSQL systems are also sometimes called Not only SQL to emphasize the fact that they may support SQL-like query languages.





## Types of NoSQL Databases
NoSQL databases generally fall under any one of these four __categories__:

![icon_types](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.Vu-aGs7t04XT0z_l6ROZwAHaHa%26pid%3DApi&f=1 'types')

1. __Key-value stores:__ is the most straightforward type, where every item of database gets stored in the form of an attribute name (i.e., "key") along with the value.
2. __Graph databases:__ are used for storing information about networks, like social connections.
3. __Wide-column stores:__ accumulate data collectively as a column rather than rows, which are optimized for querying big datasets.
4. __Document databases:__ couple every key with a composite data structure termed as a document. These documents hold a lot of different key-value pairs, as well as key-array pairs or sometimes nested documents.

___




## Some Famous NoSQL Databases -

### __1.  Mongo_DB__

![icon](https://www.developersfeed.com/wp-content/uploads/2016/10/mongodbicon-1.png "mongo db")

MongoDB is currently the most popular and widely used NoSQL database. This general purpose database has been used by many large companies such as Facebook, eBay, Forbes, and many others. MongoDB implements a document store data model which stores data in BSON documents similar to JSON files. 

It is best fit for use-cases when we are planning to integrate hundreds of different data sources. Even when we are expecting read and write operations, we can use MongoDB. The database allows us to store clickstream data and use it for behavioural analysis. 

__It has following additional advantages -__
* Easily scalable
* Powerful document-based query language
* Fast processing
* Load balancing
* Schema-less design
* High availability
* JavaScript stored procedures
* Simple database administration
* Replication and sharing
* Security/encryption


### __2. Apache Cassandra__
![icon](https://cassandra.apache.org/_/_images/blog/casseye.jpg "apache_cassandra")

This database solution was first built by Facebook. Cassandra is among the most scalable, as it can handle petabytes of information and thousands of concurrent requests. 

Apache Cassandra is an open source NoSQL database. Cassandra is a distributed database management system that is massively scalable. What makes Cassandra more appealing as a database system is its ability to _Scale Horizontally_, and it's one of the few database systems that can process data in real time and generate high performance and maintain high availability. The mixture of a column-oriented database with a key-value store means not all rows require a column, but the columns are grouped, which is what makes them look like tables. Cassandra offers _no single point of failure_ if a data node goes down.
Apache Casandra is employed by the of __Instagram, Netflix, and Apple__. The combination of the wide column store data model and emphasis on performance makes  Apache Cassandra one of the fastest NoSQL database available. 

__Some great benefits of Apache Cassandra are -__

- Ability to manage large amounts of structured,  semi-structured, and unstructured data.
- Automatic replication
- Continuous(100%) availability
- High performance
- Highly scalable
- Flexible Data Model
- Decentralized
- Large Developer/Support Community


### __3. Redis__
![icon](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.05JV0NhPgGVRo0ACpT8g5AHaD3%26pid%3DApi&f=1 "redis")


By far the most popular key-value store database, Redis uniquely uses an in-memory data store for __superfast performance and very low latency__.  

__Some of the most notable benefits and features of Redis are -__

- High performance/ low latency
- Simple asynchronous replication
- Different persistence/durability options
- Lua scripting
- Pub/sub support
- Multiple programming language support

### __4. Neo4j__

![icon](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.vbs-yP6PB4id55syTwETTgHaC9%26pid%3DApi&f=1 'neo4j')

Neo4j is an open source NoSQL ''graph-based database'. Neo4j is the front-runner of the graph-based model. As a graph database, it manages and queries highly connected data reliably and efficiently. It allows developers to store data more naturally from domains such as social networks and recommendation engines. The data collected from sites and applications are initially stored in nodes that are then represented as graphs.


### __5. DynamoDB__

![icon](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.Rxw0xXAbhpzaUrXiDn0W5gHaD5%26pid%3DApi&f=1 'dynamo')

Amazon's NoSQL database is known for its scalability. If our solutions require a database that can handle simple key-value queries in a large number, DynamoDB is the best choice. 

DynamoDB allows users to create databases capable of storing and retrieving any amount of data, and serving any amount of traffic. It automatically distributes data and traffic over servers to dynamically manage each customer's requests, and also maintains fast performance.

The two main advantages of DynamoDB are scalability and flexibility. It does not force the use of a particular data source and structure, allowing users to work with virtually anything, but in a uniform way.


## NoSQL Databases have a lot of advantages over SQL for Software Developers, which includes : -

- __Flexible and Agile data models -__ NoSQL databases typically have very flexible schemas. A flexible schema allows you to easily make changes to your database as requirements change. You can iterate quickly and continuously integrate new application features to provide value to users faster. 

    They are flexible for any type of changes in not only the genre of data but also the architecture of data-storage, allowing comparative agility like the addition of new columns with no significant alterations or breakdown.

-  __Horizontal scaling -__  NoSQL databases allow you to scale-out horizontally, meaning you can add cheaper, commodity servers whenever you need to.
-  __Fast queries -__ Queries in NoSQL databases can be faster than SQL databases because, data in SQL databases is typically normalized, so queries for a single object or entity requires us to join data from multiple tables. As your tables grow in size, the joins can become expensive. However, data in NoSQL databases is typically stored in a way that is optimized for queries. The rule of thumb is  _Data that is accessed together should be stored together._ Queries typically do not require joins, so the queries are very fast.
-  **It's cheaper -**
  NoSQL databases are intended for utilizing inexpensive commodity hardware for constructing clusters of the server, which helps in managing huge data volumes and transaction of data. On the other hand, traditional RDBMSs systems want expensive storage and original servers; this means they pose a higher cost per volumes for storing the data.
- **High availability -**
Auto replication feature in NoSQL databases makes it highly available because in case of any failure data replicates itself to the previous consistent state.

- __Cloud compatibility -__ Modern NoSQL databases have also been designed for the cloud, making them naturally good for horizontal scaling where, lots of smaller servers can be spun up to handle increased load.
    - Modern application paradigms like microservices and real-time streaming
- It also helps to develop good statistical models and group  data, something which is very difficult in SQL.


___



## Reference Links

- https://www.mongodb.com/compare/relational-vs-non-relational-databases
- https://www.mongodb.com/nosql-explained
https://www.w3schools.in/definition/what-is-nosql/
- https://hub.packtpub.com/top-5-nosql-databases/


