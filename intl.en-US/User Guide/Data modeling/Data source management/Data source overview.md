# Data sources management overview {#concept_lpv_nxp_5db .concept}

Quick BI supports the following types of data sources:

## Cloud data sources: {#section_agw_qxp_5db .section}

-   MaxCompute
-   MySQL
-   SQL Server
-   Analytic DB
-   HybridDB for MySQL
-   HybridDB for PostgreSQL released
-   PostgreSQL
-   PPAS
-   Hive \(Quick BI Pro\)

## External database data sources {#section_kmm_sxp_5db .section}

-   MySQL
-   SQL Server
-   Oracle
-   PostgreSQL
-   Hive \(Quick BI Pro\)
-   Vertica \(Quick BI Pro\)
-   IBM DB2 LUW \(Quick BI Pro\)

## Exploration space {#section_q5v_txp_5db .section}

-   CSV file
-   Local Excel files
-   Data IDE

Uploaded local files are stored in the exploration space. The exploration space is a dedicated storage area of Quick BI, providing 1G space for each user currently.

When creating data sources, the Quick BI has the following requirements for the network type of data sources.

1.  The VPC RDS instance can access Quick BI by using an extranet domain name. MySQL and SQL Server instances can access Quick BI by using an intranet domain name, other VPC RDS instances can't access Quick BI by using an intranet domain name.
2.  The instances in the classic network can access Quick BI by using an extranet domain name and an intranet domain name. When you access Quick BI by using an extranet domain name, you should set the IP address whitelist on the RDS. For more information, see [Set whitelist](https://www.alibabacloud.com/help/doc-detail/26198.htm?spm=a2c63.p38356.a3.5.26854bd3feeGKO).
3.  Quick BI can be accessed by using the public network.
4.  MySQL and SQL Server built on a VPC ECs instance can access Quick BI by the internal network domain name.

