This repository contains different code samples & other examples related to the Databricks platform & Spark:

* [pyspark-snippets](pyspark-snippets) - functions that simplify development of PySpark code for Databricks
* [dbconnect-maven](dbconnect-maven) - skeleton of the Maven project for simple Spark job, and instructions on how to run it via databricks-connect.
* [dbconnect-sbt](dbconnect-sbt) - skeleton of the SBT project for simple Spark job, and instructions on how to run it via databricks-connect.
* [simba-jdbc-aad-token](simba-jdbc-aad-token) - example of querying data on Databricks using JDBC protocol.  Authentication to Databricks is performed using Azure Active Directory tokens issued for Azure Service Principal.
* [dbsql-with-aad-token](dbsql-with-aad-token) - example of querying data on Databricks using [python-sql-connector](https://docs.databricks.com/dev-tools/python-sql-connector.html) library.  Authentication to Databricks is performed using Azure Active Directory tokens issued for Azure Service Principal.
* [dbconnect-package-versions-check](dbconnect-package-versions-check) - tool to checks compatibility of local Databricks connect environment with Databricks cluster.
* [database-diagram-builder](database-diagram-builder) - tool to generate UML diagram(s) for tables in Databricks/Spark database.

You can also find more examples of Spark code in the other repositories:
* [spark-playground](https://github.com/alexott/spark-playground) - general Spark code
* [cassandra-dse-playground](https://github.com/alexott/cassandra-dse-playground) - Spark code specific for use with Cassandra/DataStax Enterprise (DSE)


