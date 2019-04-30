# Manage data sources {#concept_lpv_nxp_5db .concept}

Quick BI supports the following types of data sources.

## Cloud data sources {#section_agw_qxp_5db .section}

-   MaxCompute
-   MySQL
-   SQL Server
-   AnalyticDB
-   HybridDB for MySQL
-   HybridDB for PostgreSQL
-   PostgreSQL
-   PPAS
-   Hive \(Quick BI Enterprise Standard\)
-   Data Lake Analytics \(Quick BI Enterprise Standard and Pro）
-   OSS \(Quick BI Enterprise Standard\)
-   DRDS \(Quick BI Enterprise Standard\)

## User-created data sources {#section_kmm_sxp_5db .section}

-   MySQL
-   SQL Server
-   Oracle
-   PostgreSQL
-   Hive \(Quick BI Enterprise Standard\)
-   Vertica \(Quick BI Enterprise Standard\)
-   IBM DB2 LUW \(Quick BI Enterprise Standard\)
-   SAP IQ \(Sybase IQ\) \(Quick BI Enterprise Standard\)
-   SAP HANA \(Quick BI Enterprise Standard\)

## User space {#section_q5v_txp_5db .section}

-   CSV files
-   Excel files
-   Data IDE

Local files are uploaded and stored in the user space. Only Quick BI provides user spaces. Currently, each user has a user space of 1 GB.

## Network requirements for data sources { .section}

Quick BI has the following network requirements for data sources.

1.  Quick BI can connect to RDS instances in a VPC by using public IP addresses. MySQL and SQL Server instances can be connected by using private IP addresses.
2.  Quick BI can connect to instances in a classic network by using both public and private IP addresses. When Quick BI connects to RDS instances by using public IP addresses, set a whitelist of IP addresses that are allowed to access RDS instances in the RDS console. For more information, see .
3.  Quick BI can be accessed on the public network.
4.  Quick BI can connect to user-created MySQL and SQL Server databases on ECS instances in a VPC by using private IP addresses.

## More operations {#section_bxt_rds_pgb .section}

For more operations on data sources, see:

-   [Create cloud data sources](reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md)
-   [Create a data source on a self-built database](reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md)
-   [Upload local files](reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md)
-   [Edit, search, and delete data sources](reseller.en-US/User Guide/Data modeling/Data source management/Edit, search, and delete data sources.md)
-   [Search tables in a data source](reseller.en-US/User Guide/Data modeling/Data source management/Search tables in a data source.md)
-   [View table details in a data source](reseller.en-US/User Guide/Data modeling/Data source management/View table details in a data source.md)
-   [Synchronize data sources](reseller.en-US/User Guide/Data modeling/Data source management/Synchronize data sources.md)

