#Relational DBMS
##Oracle Database
###Definition: Object-relational DBMS
###Strengths:
* Oracle is World’s biggest RDBMS vender, Oracle Database supports all mainstream systems and platforms, and various programming languages including Java, .NET and PHP.[1][2]
* Oracle Database is good at super large data storage.[1]
* Oracle Database can be used for all level enterprise purposes.[3]
* Oracle Database is fully ACID-complaint, it has Flashback technology which supports online backup and recovery.[1][3]
* Oracle Database supports cursor for programming simplification.[4]
    
###Weaknesses
* Oracle Database is complex and harder for DBAs to handle.[2]
* Oracle Database, when handling small datasets, is not as cost-effective as other mainstream SQL database including MySQL.[2]

###References
[1] http://en.wikipedia.org/wiki/Oracle_Database

[2] http://www.ehow.com/list_7614878_advantages-oracle-database-management-system.html

[3] http://www.ehow.com/list_7684620_advantages-oracle-databases.html

[4] http://www.erpgreat.com/oracle-database/advantage-of-oracle-database.htm
<br></br>


##SQLite
###Definition:
SQL database

###Strengths:
* SQLite doesn’t need any configuration, including installation and administration. [1]
* A SQLite database in stored in a cross-platform disk file, which makes it appropriate for a website database.[1]
* SQLite supports multiple platforms, including mobile OS such as iOS and Android. [1]

###Weaknesses:
* SQLite doesn’t support multi-client concurrency. [2]
* SQLite is not good at handling high write volumes data, and also has limited potential of additional functionalities.[2]

###References:
[1] http://www.sqlite.org/features.html

[2] https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems
<br></br> 


##PostgreSQL, EnterpriseDB
###Definition: 
Object-relational DBMS
PostgreSQL based NoSQL DBMS

###Strengths: 
* PostgreSQL supports concurrency using MVCC.[1]
* PostgreSQL is open source.[2]

* PostgreSQL supports XML data storage, its newest edition supports JSON file storage.[3]

* PostgreSQL owns strong third party support and community.[4]

###Weaknesses:
* PostgreSQL has limited read speed.[5]

###References:
[1] http://en.wikipedia.org/wiki/PostgreSQL

[2] http://www.enterprisedb.com/products-services-training/products/postgresql-overview

[3] http://en.wikipedia.org/wiki/PostgreSQL

[4] https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

[5] https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems


<br></br>

##Postgres-XL

###Definition:
PostgreDB based database

###Strength: 
* OLTP write scalability and massive parallel processing.[1]

###Definition:
[1]http://www.postgresql.org/about/news/1523/
<br></br>

##VFabric Postgres: Availability ended in Sept 2014.

<br></br>

##MySQL
###Definition:
Relational DBMS

###Strenghs:
* MySQL is open source, and the world second widest used Relational DBMS.[1]
* MySQL enables graphical design and administer databases, while supports command line operations.[1]
* MySQL has powerful SQL functionality.[2]
* MySQL can achieve high performance will storing and maintaining large volume of data.[2]
* MySQL supports various platforms, including many mobile OS.[3]
* MySQL can achieve high performance will storing and maintaining large volume of data.[3]

###Weaknesses: 
* MySQL is not strictly SQL complaint since it does not intend to achieve full SQL functionalities.[4]
* MySQL can execute concurrent read operations well, but not read-write operations.[4]

###Definitions:
[1] http://en.wikipedia.org/wiki/MySQL


[2] https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

[3] http://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems

[4]https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

##MariaDB: A community developed fork of MySQL for free of charge purpose, share similar features as MySQL.
##MariaDB Enterprise: Extended version of MariaDB for enterprise level use.
###Strengths:
* MariaDB Enterprise implements a user friendly query editor.[1]
* MariaDB in addition supports a fully backup engine.[1]

###References:
[1] https://mariadb.org/

<br></br>
##Firebird
###Definition:
Relational DBMS

###Strengths: 
* Firebird is open source.[1]
* Firebird implement concurrency using MVCC.[1]

###References:
[1]http://en.wikipedia.org/wiki/Firebird_(database_server)

##Percona
###Definition:
A MySQL support and consult company.
###Percona server: MySQL alternative 
###Strengths: 
* Percona server is open source.[1]
* Percona server has larger memory compared to MySQL, which is more suitable for cloud computing purposes.[1]
* Percona doesn’t only offer DBMS, but also other services as DB support, maintenance, consult etc, Percona is a Software as a service.[1]

###Definition:
[1]http://www.percona.com/software/percona-server

<br></br>
##Actian Ingres
###Definition:
Relational SQL DBMS

###Strengths: 
* Ingres is open source.[1] 
* Ingres well fits ACID properties.[2]
* Multi-Version Concurrency Control (MVCC)[2]

###Weaknesses:
 * Doesn’t support iOS, Android, and Symbian.[3]

###References:
[1] http://en.wikipedia.org/wiki/Ingres_(database)

[2] http://www.actian.com/products/operational-databases/

[3]http://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems
<br></br>

##SAP Sybase ASE
###Definition:
Relational DBMS

###Strengths:
* Enterprise level DBMS designed for large volume of data transaction.[1]
* Each data server is backed up by back server, reducing risk of data loss.[2]

###References:
[1] http://www.sap.com/pc/tech/database/software/adaptive-server-enterprise/index.html

[2] http://en.wikipedia.org/wiki/Adaptive_Server_Enterprise
<br></br>

##SAP Sybase SQL Anywhere

###Definition: 
Relational DBMS

###Strengths: 
* SQL Anywhere is designed for mobile devices, showing great performance in synchronization and self-maintenance.[1]

###Definitions:
[1]http://www.sap.com/pc/tech/database/software/sybase-sql-anywhere/index.html
<br></br>

##Oracle Database
###Definition:
Relational DBMS

###Strengths:
* Oracle database can be plugged into a multitenant container, while enables its cloud compatibility.[1]
* Oracle advanced compression compress all types of data with a 2-4 compression rate, reducing data size while optimizing the query speed.[2]
* Oracle database can retrieve unstructured data from XML and other resources.[3]

###Weaknesses: 
* Oracle Database doesn’t support mobile OS such as Android and iOS.[4]
* Oracle SQL is highly specialized query language, which makes it difficult to learn and master.[5]

###References:
[1] http://www.oracle.com/us/corporate/features/database-12c/index.html

[2] http://www.oracle.com/us/products/database/options/advanced-compression/overview/index.html

[3] http://www.oracle.com/technetwork/database/information-management/index.html

[4] http://en.wikipedia.org/wiki/Comparison_of_relational_database_management_systems

[5] http://www.ehow.com/list_6309384_advantages-disadvantages-oracle-sql.html
<br></br>

    
##Oracle Exadata
###Definition: 
Software and hardware integrated platform for Oracle database.

###Strengths: 
* Exadata supports both OLTP and OLAP database systems.[1]
* Exadata is advanced in architecture, it possesses technologies like state-of-the-art flash and high-speed InfiniBand internal fabric.[2]

###References:
[1] http://en.wikipedia.org/wiki/Oracle_Exadata

[2] https://www.oracle.com/engineered-systems/exadata/index.html
<br></br>

##IBM DB2
###Definition:
Relational DB

###Strengths: 
* Though DB2 starts as relational database, in recent years many of its products aim at less or non -structured data, particularly XML.[1]
* DB2 runs on various platforms.[2]
* DB2 has more powerful query language, which can be imbedded in code of other languages including Java.[2]

###Weaknesses:
* DB2 is considered difficult to master than other mainstream SQL databases.[3]

###References:
[1] http://en.wikipedia.org/wiki/IBM_DB2

[2] http://www.ehow.com/info_12106599_advantages-db2.html

[3] http://www.databaseskill.com/3941675/

<br></br>

##IBM PureData: Data analytical system:
###Strengths: 
* PureData uses FPGA for execution of analytic queries.[1]

###References:
<br></br>
##Microsoft SQL server
###Definition:
Relational DBMS

###Strengths: 
* SQL server is easy to use, well supported and designed for enterprise level databases.[1]
* SQL server offers complete data recovery options.[1]
*SQL server offers good security performance.[2]

###Weaknesses:
* SQL server is costly than most other relational DBMS.[3]
* SQL server only support Windows.[4]

###References:
[1] http://www.ehow.com/list_6458544_microsoft-sql-server-advantages.html

[2] http://www.ehow.com/list_6458544_microsoft-sql-server-advantages.html

[3] http://www.quora.com/What-are-the-advantages-or-drawbacks-in-choosing-Microsoft-SQL-server-over-MySQL

[4] http://en.wikipedia.org/wiki/Microsoft_SQL_Server
<br></br>

##Microsoft SQL server PDW:
###Definition:
Parallel Data Warehouse, SQL server’s massive parallel processing edition.

###Strengths:
MPP allows PDW to run independent servers in parallel, which enables it to handle super large size of data.

###Reference:
[1]http://sqlpdw.com/2010/07/what-mpp-means-to-sql-server-parallel-data-warehouse/


<br></br>






##AWS RDS
###Definition:
Amazon Relational Database Service

###Strength:
* RDS runs on various relational databases including MySQL, PostgreSQL, and Amazon Aurora, provisioning them with General Purpose Storage, making it have features like fault tolerance and self-healing.[1] 
* RDS supports automatic backups as well as user-defined backup snapshot.[2]
* RDS provides PIOPS (Provisioned IOPS) for fast and consistent I/O performance which is good for online transaction processing (OLTP) databases or high I/O centric applications.[3] 
* RDS offers both vertical and horizontal scalability.[3]
* RDS offer Multi-AZ which handles database failover.[4]

###Weakness: 
* RDS has bad database visibility, requiring developers take more time to diagnose when the database is slowed down or run into problems.[4]

###References:
[1] http://aws.amazon.com/rds/

[2] http://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html

[3] https://www.scalebase.com/aws-rds-vs-self-hosted-mysql-availability-scalability-performance/

[4] http://www.quora.com/Is-Amazon-RDS-relational-database-service-good
<br></br>
##SolidDB
###Definition:
In-memory Relational DB

###Strengths:
* SolidDB both supports in-memory and on-disk storage, looks to me it’s a hybrid storage DB, which makes it have better overall performance over on-disk databases, and less cost and more stability than in-memory DB.[1]
* SolidDB is easy to deploy and administer.[2]

###Weaknesses:
* SolidDB has no instant deadlock detection, and it’s has limited production usage.[3]

###References:
[1] http://unicomsi.com/products/soliddb/

[2] http://en.wikipedia.org/wiki/SolidDB

[3] http://www.percona.com/blog/files/presentations/OSCON2007-Landscape-of-trx-engines.pdf
<br></br>

##Actian PSQL
###Definition:
DBMS developed by Pervasive.

###Strengths: 
* PSQL supports Relational DBMS as well as less structured key/value pair store.[1]
* Support various operating system including Windows, Linux and Mac OSX. [1]

* There are three editions of PSQL which supports various size of groups.[2]

###Weaknesses:
* Don’t support most mobile system, iOS, Android, etc.[3]

###References:
[1] http://en.wikipedia.org/wiki/Pervasive_PSQL

[2] http://www.actian.com/products/operational-databases/psql/
<br></br>



##Progress OpenEdge
###Definition:
Relational Database

###Strengths:
* OpenEdge is good at mobile applications.[1]

###References:
[1]https://www.progress.com/products/openedge/overview
<br></br>
##Rackspace Cloud Databases

###Definition:
MySQL cloud database

###Strengths: 
* Rackspace allows you to deploy relational databases such as MySQL, MariaDB, Percona server on cloud.[1]
* Cloud database provides built-in data redundancy, improving the reliability. [2]
* Cloud Database has easy configuration, administration and patching, saving customers’ operational costs for other purposes.[2]

###Weaknesses:
* Cloud database doesn’t provide good vertical scaling, and has limited features for its cloud services.[3]
* There are no options for external storage, al VMs can be stored in host own system.[3]
* To use this service, data must be stored and maintained in single data center, after that the account is tied up with that data center, and user won’t be able to utilize other data centers.[3]

###References:
[1] http://www.rackspace.com/cloud/databases

[2] http://www.rackspace.co.uk/cloud/databases

[3] http://www.quora.com/What-are-the-disadvantages-of-Rackspace-Cloud-Servers

<br></br>


##Anzure SQL database
###Definition:
Relational Database as a service

###Strengths:
* Anzure SQL needs no physical administration, [1]
* Anzure supports non-Microsoft technologies, which makes it a good complementary for SQL server.[1]
* Anzure SQL supports VM use.[1]

###Weaknesses:
* Anzure SQl implements most crucial parts of T-SQL, but not all of it.
* Charges for Anzure may be unpleasant, for reporting and data transfer where be charged in addition.

###References:
[1] http://searchsqlserver.techtarget.com/feature/The-pros-of-Windows-Azure-SQL-Database

[2] http://searchsqlserver.techtarget.com/feature/Why-you-should-think-twice-about-Windows-Azure-SQL-Database
<br></br>

##StormDB
###Definition:
Postgres-based database, recently purchased by translattice

###Strengths: 
* Supports various languates including Java, C#, Python, Ruby.[1]

###Weaknesses:
* StormDB has limited data size capability.[1]

###References:
[1]http://vschart.com/compare/sqlfire/vs/stormdb	
<br></br>

##Google BigQuery
###Definition:
Fast, SQL-like query language.

###Strengths: 
*BigQuery is able to handle huge size of data.[1]
*BigQuery enables real-time data analytical processing in database.  [1]
*BigQuery provides query caching, elevating query performance significantly.[1]

###Reference:
[1]http://googledevelopers.blogspot.com/2013/06/google-bigquery-new-features-bigger.html
<br></br>	

##Google Cloud Dataflow: 
###Definition:
Cloud service for data analysis and computation.
###Strengths:
*Dataflow enables real-time data analysis and computation on large scale on data.[1]
*Dataflow is designed and built for the Cloud.[1]
*Dataflow has java-based SDK, allowing developers to build their own data processing pipelines for various tasks, addressing Map/Reduce issues with pipelining.[2]

###References:
[1]https://cloud.google.com/dataflow/
http://www.tableau.com/pt-br/about/blog/2014/6/google-cloud-dataflow-31503

<br></br>
##Google Compute Engine
###Definition:
Infrastructure as a service, runs google search engine, Youtube, Gmail and many other Google products.

###Strengths:
*GCE allows users to launch VMs on demand, which are secure and available, and users don’t need to pay for unused computing time.[1]
*GCE’s load balancer doesn’t need pre-warming, and can operate on pike traffic instantly, gaining advantage over AWS.[2]
###References:
[1] https://cloud.google.com/compute/

[2] http://www.quora.com/What-are-the-advantages-of-Google-Compute-Engine-over-Amazons-cloud-offering

<br></br>

##HP Cloud RDB
###Definition:
HP’s cloud based Relational DB

##FathomDB
###Definition:
Database as a Service, MySQL database

<br></br>
##OpenStack Trove
###Definition: 
Database as a Service, DBaaS

###Strengths: 
* Trove is designed for OpenStack and only deployed for OpenStack data storage, which gives it pertinency.[1]
* Trove provides automated backup and data protection.[1]

###References:
[1]http://www.tesora.com/openstack/what-is-trove

<br></br>

##Oracle Timesten
###Definition:
In-memory Relational DB

###Strengths:
* In-memory means Timesten has no network latency or on-disk I/O, grant Timesten with great performance.[1]
* Timesten is imbedded with other Oracle products, including real-time data analytical system.[1]

###References:
[1]http://www.oracle.com/us/products/database/timesten/overview/index.html
<br></br>
