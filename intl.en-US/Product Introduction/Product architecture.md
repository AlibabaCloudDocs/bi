# Product architecture {#concept_zlb_pyv_tdb .concept}

The product architecture of Quick BI is shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9064/15446912421012_en-US.png)

Modules and functions of Quick BI:

-   Data connection module

    Quick BI accesses data from multiple supported data sources, including MaxCompute, ApsaraDB for RDS \(MySQL, PostgreSQL, SQL Server\), Analytic DB, and HybridDB \(MySQL, PostgreSQL\). Quick BI provides an encapsulation of the standard APIs that are used for querying the schema and data of these data sources.

-   Data processing module
    -   QUERY engine: You can use the QUERY engine to perform queries and retrieve data from data sources.
    -   Data pre-processing: This feature provides lightweight solutions to extract, transform, and load data \(ETL processing\). Currently, only the custom MaxCompute SQL queries are supported, with more data sources to be supported in the future.
    -   Data modeling: This module provides data modeling features for online analytical processing \(OLAP\). It converts data sources to multi-dimensional analysis models. Data modeling supports common semantic objects, such as dimensions \(such as date and location\), measures, and star schema. This module supports calculated fields. Additionally, it allows you to edit dimensions and measures using the SQL syntax supported by the current data source.
-   Data visualization module
    -   Workbook: The data visualization module provides analytics functions for you to operate workbooks with ease. These functions include row filtering, column filtering, advanced filtering, subtotals, AutoSum, conditional formatting, data export, text processing, and table processing.
    -   Dashboard: In Quick BI, you can easily author dashboards with widgets and rich visuals. Quick BI provides 33 charts and diagrams, including line charts, pie charts, bar charts, funnel charts, tree diagrams, geo bubble maps, geomaps, and card charts. Supported widgets include Filter Bar, TAB, IFrame, Image, and Text Area. Quick BI supports filter interactions that allow you to filter data across multiple charts.
    -   Portal: You can drag and drop components on a dashboard to assemble a portal. Quick BI supports embedded links \(linked dashboards\) and basic settings of the template and the menu bar.
    -   Share/Publish: You can share workbooks, dashboards, and portals with other logged-in users, and publish dashboards on the Internet for non-logged-in users to access the dashboards.
-   Permission management module
    -   Organization permission management: This feature allows you to manage permissions at workspace level and organization level. It also supports role-based permissions in a workspace. With these mechanisms, you can assign users different levels of access to view different reports.
    -   Row-level permission management: This feature allows you to restrict access to individual rows in a table, and allows users who access a report to view different parts of the report.

