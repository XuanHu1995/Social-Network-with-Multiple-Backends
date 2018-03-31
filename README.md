# Social Networking website with multiple backends.

This project incorporates three types of databases (MySQL, HBase, MongoDB). To implement a social networking website, heterogeneity of data, functionality, and requirements are needed. Therefore, applications usually require developers to incorporate a number of different databases, making use of their respective advantages to achieve better efficiency and performance. As a result, in a network of databases, even a single request made by the front-end of will trigger requests to many internal back-end services to retrieve fresh information.

Databases:
1. MySQL
- RDS(DBaaS)
We will be using Amazon's RDS MySQL, which is a Database-as-a-Service(DBaaS). In DBaaS, cloud providers offer packaged database services which users can #configure and deploy# while the cloud provider performs the #traditional database administration and maintenance functions#. The database can seamlessly scale based on load. They are maintained, upgraded, and backed-up by the cloud provider.

2. HBase
HBase is based on HDFS.

3. MongoDB
MongoDB is a Document Oriented Database. They are weakly typed while RDBMS are strongly typed. Document Stores are schema-free; most columns or fields are optional and can be added or removed at any time. A Document Store is a subtype of key-value stores, but while the value content may be opaque to a key-value store (remember that you cannot create an index on any HBase column), fields in a document store can be indexed. 


Use of Terraform
Terraform is a middleware which we can use to configure, deploy and resources on Cloud. It supports multiple cloud providers such as AWS, gcloud, Azure.
