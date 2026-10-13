<!-- fetched 2026-10-13 from https://learn.microsoft.com/en-us/azure/cosmos-db/postgresql/introduction by sweep-shape-compat.py; text extracted from the provider's own page -->

Introduction/Overview - Azure Cosmos DB for PostgreSQL | Microsoft Learn 
 Skip to main content
 Skip to Ask Learn chat experience
 This browser is no longer supported.
 Upgrade to Microsoft Edge to take advantage of the latest features, security updates, and technical support.
 Download Microsoft Edge
 More info about Internet Explorer and Microsoft Edge
 Table of contents 
 Exit editor mode 
 Ask Learn 
 Ask Learn 
 Reading mode 
 Table of contents 
 Read in English 
 Add 
 Add to Plans 
 Edit 
 Copy Markdown 
 Print 
 Note 
 Access to this page requires authorization. You can try signing in or changing directories .
 Access to this page requires authorization. You can try changing directories .
 What is Azure Cosmos DB for PostgreSQL?
 Applies to: ✅ PostgreSQL
 Feedback 
 Summarize this article for me
 In this article
 Important
 Azure Cosmos DB for PostgreSQL is on a retirement path and no longer recommended for new projects. Instead, use one of these two services:
 For PostgreSQL workloads, use the Elastic Clusters feature of Azure Database For PostgreSQL to take advantage of horizontal scale-out and distributed PostgreSQL features within the open source Citus extension. For migration guidance, see migrate to Azure Database for PostgreSQL with Elastic Cluster .
 For NoSQL workloads, use Azure Cosmos DB for NoSQL for a distributed database solution that includes a 99.999% availability service level agreement (SLA), instant autoscale, and automatic failover across multiple regions.
 Azure Cosmos DB for PostgreSQL is a managed service for PostgreSQL extended
with the Citus open source superpower of
 distributed tables . This superpower enables you to build highly scalable
relational apps. You can start building apps on a single node cluster, the
same way you would with PostgreSQL. As your app's scalability and performance
requirements grow, you can seamlessly scale to multiple nodes by transparently
distributing your tables.
 Real-world customer applications built on Azure Cosmos DB for PostgreSQL include software-as-a-service (SaaS) apps, real-time
operational analytics apps, and high throughput transactional apps. These apps
span various verticals such as sales and marketing automation, healthcare,
Internet of Things (IoT) data, finance, logistics, and search.
 Implementation checklist
 As you're looking to create applications with Azure Cosmos DB for PostgreSQL, ensure you've
reviewed the following articles:
 Learn how to build scalable apps .
 Connect and query with your app stack .
 See how the Azure Cosmos DB for PostgreSQL API extends PostgreSQL, and try useful diagnostic queries .
 Pick the best cluster size for your workload.
 Learn how to use Azure Cosmos DB for PostgreSQL as the storage backend for multiple microservices .
 Monitor cluster performance.
 Ingest data efficiently with Azure Stream Analytics 
and Azure Data Factory .
 Fully managed, resilient database
 As Azure Cosmos DB for PostgreSQL is a fully managed service, it has all the features for
worry-free operation in production. Features include:
 automatic high availability
 backups
 built-in pgBouncer
 read-replicas
 easy monitoring
 private endpoints
 encryption
 and more
 Try the quickstart > 
 Always the latest PostgreSQL features
 Azure Cosmos DB for PostgreSQL is powered by the
 Citus open source extension to
PostgreSQL. Because Citus isn't a fork of Postgres, the Citus extension always
supports the latest PostgreSQL major version within a week of release--with
support added to our managed service on Azure at most a few weeks later.
 Your apps can use the newest PostgreSQL features and extensions, such as
native partitioning for performance, JSONB support to store and query
unstructured data, and geospatial functionality via the PostGIS extension.
It's the speed you need, on the database you love.
 Start simply, scale seamlessly
 A database cluster can begin as a single node, while
having the superpower of distributing tables. At a few dollars a day, it's the
most cost-effective way to experience Azure Cosmos DB for PostgreSQL. Later, if your
application requires greater scale, you can add nodes and rebalance your data.
 Next steps
 Create a new account using the Azure portal.
 Connect to a cluster with psql.
 Use the Citus extension to distribute tables .
 Feedback
 Was this page helpful?
 Yes 
 No 
 No 
 Need help with this topic?
 Want to try using Ask Learn to clarify or guide you through this topic?
 Ask Learn 
 Ask Learn 
 Suggest a fix? 
 Additional resources
 Last updated on 
 2026-04-27
 In this article
 Was this page helpful?
 Need help with this topic?
 Want to try using Ask Learn to clarify or guide you through this topic?
 Ask Learn 
 Ask Learn 
 Suggest a fix? 
 en-us 
 Your Privacy Choices 
 Theme 
 Light 
 Dark 
 High contrast 
 AI Disclaimer 
 Previous Versions 
 Blog 
 Contribute 
 Privacy 
 Consumer Health Privacy 
 Terms of Use 
 Trademarks 
 © Microsoft 2026
