#NoSQL Databases
##MongoDB
###Description:
NoSQL Database

###Strengths:
* MongoDB is document-oriented and schema-free, enabling it to store less or non-structured data.[1]
* MongoDB supports JSON and JavaScript, supports range queries and dynamic queries which is almost as good as SQL queries.[1]
* MongoDB provides auto-sharding and full index support.[2]
* MongoDB serializes JSON files to BSON( binary JSON), making it more efficient than other JSON files storage databases including CouchDB.[3]

###Weaknesses:
*MongoDB does not support some query operations such JOIN, though it can be accomplished by making multiple queries.[4]

###References:
[1]http://en.wikipedia.org/wiki/MongoDB

[2]http://www.tutorialspoint.com/mongodb/mongodb_advantages.htm

[3]http://www.quora.com/How-does-MongoDB-compare-to-CouchDB-What-are-the-advantages-and-disadvantages-of-each

[4]http://makble.com/the-advantages-and-disadvantages-of-mongodb
<br></br>


##MongoLab
###Definition:
MongoDB as a Service

###Strengths:
* service provide MongoDB services over mainstream cloud platforms including AWS, Anzure and Google Cloud Platform.[1]
* MongoLab offers features like slow query analyzer, automatic monitoring and alerting.[1]

###References:
[1]https://mongolab.com/
<br></br>

##CouchDB
###Description:
NoSQL Database

###Strengths:
* CouchDB stores data in JSON files, and allows using JavaScript for querying.[1]
* CouchDB is ACID complaint and implements MVCC.[1]
* CouchDB has no read lock, because it always appends changed data in the end, achieving great performance in concurrency.[2]

###Weaknesses:
* CouchDB shares similar weaknesses to many other NoSQL databases, like limited query operations compared to SQL.[3]
* CouchDB has no built in full-text search.[3]

###References:
[1]http://en.wikipedia.org/wiki/CouchDB

[2]http://willconant.com/posts/2013-06-02/4-good-things-about-couchdb

[3]http://www.quora.com/How-does-MongoDB-compare-to-CouchDB-What-are-the-advantages-and-disadvantages-of-each
<br></br>

##AWS SimpleDB
###Definition:
Amazon NoSQL Database

###Strengths:
* SimpleDB has new query operations, e.g. conditional put and delete.[1]
* SimpleDB is compatible with other AWS products and services.[2]
* SimpleDB stores data in domain(corresponding to MongoDB collection), which offers SimpleDB indexing flexibility.[3]

###Weaknesses:
* SimpleDB only provides eventual consistency, which is a lower form of consistency.[1]
* SimpleDB users also have to face storage limitation as well as query limitation.[1]

###References:
[1]http://en.wikipedia.org/wiki/Amazon_SimpleDB

[2]http://aws.amazon.com/simpledb/

[3]http://www.masonzhang.com/2013/06/2-reasons-why-we-select-simpledb.html
<br></br>

##AWS DynamoDB
###Definition:
 Cloud-based NoSQl database
###Strengths:
* DynamoDB is compatible with other AWS products and services.[1]
* DynamoDB has no database size limitation.[2]    

###Weaknesses:
* Fairly small row size, table size and query size.[3]
* DynamoDB is not ACID guaranteed.[3] 
* DynamoDB has indexing restrictions. Users must set indexing fields before creating the database.[4]
* DynamoDB has limited data types, it doesn’t support binary data.[5]
* DynamoDB has limited query operations.[5]

###References:
[1] http://en1.wikipedia.org/wiki/Amazon_DynamoDB

[2] http://www.masonzhang.com/2013/06/2-reasons-why-we-select-simpledb.html

[3] http://www.slideshare.net/saniyakhalsa/dynamo-db-pros-and-cons

[4] http://www.masonzhang.com/2013/06/2-reasons-why-we-select-simpledb.html

[5] http://whynosql.com/my-disappointments-with-amazon-dynamodb/
<br></br>
##Cloudant

###Definition:
Cloud-based NoSQL Database as a service, based on CouchDB

###Strength: 
* Cloudant supports mobile applications well with cross data center availability.[1][2]

###References:
[1]https://www.ibm.com/developerworks/community/blogs/5things/entry/cloudant_blog_post_solution_guide?lang=en

[2]http://www.redbooks.ibm.com/abstracts/tips1187.html?Open
<br></br>

##Azure DocumentDB
###Definition:
NoSQL document database system

###Strengths: 
* DocumentDB supports JSON and JavaScript directly inside database engine, which makes it suitable for web and mobile applications.[1]
* DocumentDB supports SQL syntax for querying.[1]

###Weaknesses: 
*  having SQL like query syntax, DocumentDB has limited query operations than SQL, these functions include ORDER BY and WHERE.[2]

###References:
[1] http://azure.microsoft.com/en-us/services/documentdb/

[2] https ://social.msdn.microsoft.com/Forums/sqlserver/en-US/7a4d7874-a5c9-4aab-a5f7-5a9569afc224/what-are-the-azure-document-db-limitations-how-is-it-better-than-azure-sql?forum=AzureDocumentDB
<br></br>	

##RavenDB
###Description: 

NoSQL Database using .NET
###Strengths:
* RavenDB is open source.[1]
* RavenDB has features like alternate spelling suggestions and relative document search.[2]
* RavenDB meets strict OLTP criteria, which makes it suitable for OLTP applications.[3]

###Weaknesses:
* RavenDB only support .NET which means it only supports Mirosoft platforms this moment.[4]
* RavenDB doesn't have good reporting system.[5]

###References:
[1]http://ravendb.net/

[2]http://code972.com/blog/2014/01/801-ravendbs-hidden-features

[3]http://nosqlguide.com/document-store/mongodb-vs-couchdb-vs-ravendb-a-nosql-comparison/

[4]http://nosqlguide.com/document-store/mongodb-vs-couchdb-vs-ravendb-a-nosql-comparison/

[5]http://ayende.com/blog/136196/when-should-you-use-ravendb
<br></br>
##CouchDB: 
###Description:
NoSQL Database
###Strengths: 
* CouchDB stores data in JSON files, and allows using JavaScript for querying.
* CouchDB is ACID complaint and implements MVCC.[1]
* CouchDB has no read lock, because it always appends changed data in the end, achieving great performance in concurrency.[2]

###Weaknesses: 
* CouchDB shares similar weaknesses to many other NoSQL databases, like limited query operations compared to SQL.
* CouchDB has no built in full-text search.[3]

###References:
[1]http://en.wikipedia.org/wiki/CouchDB

[2]http://willconant.com/posts/2013-06-02/4-good-things-about-couchdb

[3]http://www.quora.com/How-does-MongoDB-compare-to-CouchDB-What-are-the-advantages-and-disadvantages-of-eac
<br></br>
##RethinkDB
###Description:
NoSQL Database

###Strengths:
* RethinkDB is open source.[1]
* RethinkDB offers SQL-like JOIN operations, and enables chaining complex commands for complicated queries.[2] 


###Weaknesses:
* RethinkDB doesn't support Microsoft system.[3]
* RethinkDB has CID properties at all time, but not Atomic.[4]

###References:
[1]http://rethinkdb.com/

[2]http://www.quora.com/What-is-the-advantage-of-RethinkDB-over-MongoDB

[3]http://rethinkdb.com/docs/comparison-tables/

[4]http://rethinkdb.com/faq/#when-is-rethinkdb-not-a-good-choice
<br></br>

##CouchBase
###Description:
Enterprise-level NoSQL database.
###Strengths:
* CouchBase offers easy management GUI.[1]
* CouchBase includes Memcached capabilities which many mainstream NoSQL databases don’t have.[2]

###Weaknesses:
* CouchBase doesn’t support range sharding.[2]

###References:
[1] http://www.couchbase.com/

[2] http://www.javaworld.com/article/2078750/open-source-tools/nosql-showdown--mongodb-vs--couchbase.html

<br></br>	

##Oracle NoSQL: 
###Description: 
Oracle distributed NoSQL database.

###Strengths:
* Oracle supports simple key/value store and is ACID complaint.[1]
* Oracle supports JSON file storage, and will have table-structure value abstraction soon.
* Oracle uses replication for concurrency management.[2]

###References:
[1] http://www.oracle.com/us/products/database/nosql/overview/index.html

[2] http://www.oracle.com/technetwork/database/database-technologies/nosqldb/documentation/nosql-vs-mongodb-1961723.pdf

<br></br>
##HBase
###Description:
Apache NoSQL database.
###Strengths:
* HBase is open source.[1]
* HBase is based on HDFS, which is good for sparse data storage and maintenance.[1]
* HBase supports XML storage, and automatic table sharding.[2]
* HBase provides user-friendly Java API.[2]

###Weaknesses:
* HBase is not a complete replacement substitute for HDFS, and doesn’t support in-database analytics.[3]
* HBase is an in-memory focused database, which should have advantage of sparse I/O, however HBase is dependent on Map/Reduce is I/O bound which is conflict with HBase features.[4]

###References:
[1] http://en.wikipedia.org/wiki/Apache_HBase

[2] http://hbase.apache.org/

[3] http://www.infoworld.com/article/2610656/database/big-data-showdown--cassandra-vs--hbase.html?page=4

[4] http://blog.cloudera.com/blog/2011/04/hbase-dos-and-donts/

##Cassandra
###Description:
Apache NoSQL DBMS
###Strengths:
* Cassandra is open source as well as free. [1]
* Since Cassandra is an Apache product, it’s compatible with other Apache products and services such as Apache Hive and Pig.[1]
* Instead of Master-Slave architecture, Cassandra runs  a peer to peer architecture, which means we can add and remove a single server without causing functionality problems, since they are in equal level.[1]
* Cassandra is column oriented, enabling quick slicing.[1]

###Weaknesses:
* Cassandra provides node-level replication, which is not as good as MongoDB query-level ad-hoc controls.[2]

###References:
[1] http://www.edureka.co/blog/apache-cassandra-advantages/

[2] http://vikaskumar9.blogspot.com/2012/03/cassandra-vs-mongodb.html
<br></br>
##FatDB
###Definition:
 NoSQL Database

###Strengths:
* FatDB is well integrated with SQL server, enabling unstructured as well as structured data management.[1]
* FatDB enables both in-memory and on-disk storage.[2]

###Weaknesses:
* FatDB is built on .NET language, limiting its functionalities beyond Microsoft platforms.[2]

###References: 
[1] http://nosql.findthebest-sw.com/l/23/FatDB

[2] http://nosql.findthebest-sw.com/compare/1-23/MongoDB-vs-FatDB

