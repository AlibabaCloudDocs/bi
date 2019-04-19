# Basic concepts {#concept_ndj_1vv_tdb .concept}

## Key procedures {#section_nq4_kvv_tdb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9063/155563787137889_en-US.png)

## Basic objects {#section_jgv_qvv_tdb .section}

-   Data source
-   Dataset
-   Workbooks \(for Quick BI Pro\)
-   Dashboard
-   Portal \(for Quick BI Pro\)

**Note:** For more information about the difference of editions, see the following figure.

## Data source {#section_cgt_vvv_tdb .section}

When you use Quick BI for data analysis, you must first specify the data source of the raw data. A data source stores your raw data. You can use multiple methods to add data sources:

-   Add data sources from cloud database services
-   Add data sources from user-created database systems
-   Upload local files \(only available for Personal Space\)

For more information about creating data sources, see [Create a cloud data source](../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from external database](../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

## Dataset {#section_l5h_rwv_tdb .section}

You can create datasets by using tables from different data sources. You can edit, move, or delete a dataset in the dataset list.

For more information about datasets, see [Create a dataset](../../../../reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Workbook {#section_qvj_b5p_b2b .section}

Workbooks are available for Workspace. You can obtain a workbook by analyzing and processing a dataset. You can use it to reference individual cells, leverage a rich range of functions, and create sophisticated business reports.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9063/15556378716895_en-US.png)

For more information about creating workbooks, see [../../../../dita-oss-bucket/SP\_78/DNQBI11869867/EN-US\_TP\_9106.md](../../../../reseller.en-US//Create a workbook.md).

## Dashboard {#section_uf2_1yv_tdb .section}

Dashboard provides you a more flexible tile layout to create interactive reports with visual analytics. Dashboard supports data filtering, data query, and multiple data display modes to highlight the key fields of data.

Dashboards support two display modes.

-   Full-screen mode \(only for Quick BI Enterprise Standard\)

The standard mode supports multiple charts and five layout widgets.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9063/15556378716896_en-US.png)

The standard mode supports multiple charts and five layout widgets.

For more information, see [Create charts in a dashboard](../../../../reseller.en-US/User Guide/Create dashboards/Create charts/Create charts in a dashboard.md).

## Portals {#section_e51_jyv_tdb .section}

The data portal is also known as the data product. and reporting products that use a menu structure. You can use a portal as part of a management analysis system, for it supports to be referenced by external links.

For more information about portals, see [Create portals](../../../../reseller.en-US/Quick Start/Create a report/Create portals.md#).

## Product architecture {#section_ptc_sz4_mgb .section}

The product architecture of Quick BI is shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9064/15556378711012_en-US.png)

Modules and functions of Quick BI:

-   Data connection module

    Quick BI accesses data from multiple supported data sources, including MaxCompute, ApsaraDB for RDS \(MySQL, PostgreSQL, SQL Server\), Analytic DB, and HybridDB \(MySQL, PostgreSQL\). Quick BI provides an encapsulation of the standard APIs that are used for querying the schema and data of these data sources.

-   Data processing module
    -   QUERY engine: You can use the QUERY engine to perform queries and retrieve data from data sources.
    -   Data pre-processing: This feature provides lightweight solutions to extract, transform, and load data \(ETL processing\). Currently, only the custom MaxCompute SQL queries are supported, with more data sources to be supported in the future.
    -   Data modeling: This module provides data modeling features for online analytical processing \(OLAP\). It converts data sources to multi-dimensional analysis models. Data modeling supports common semantic objects, such as dimensions \(such as date and location\), measures, and star schema. This module supports calculated fields. Additionally, it allows you to edit dimensions and measures using the SQL syntax supported by the current data source.
-   Data visualization module
    -   Workbook: Provides operations related to online electronic spreadsheet \(webexcel\), including data analysis \(such as row and column filtering, common/advanced filtering, classified aggregation, AutoSum, and conditional formatting\), data export, text processing, sheet processing, and other operations.
    -   Dashboard: In Quick BI, you can easily author dashboards with widgets and rich visuals. Quick BI provides 33 charts and diagrams, including line charts, pie charts, bar charts, funnel charts, tree diagrams, geo bubble maps, geomaps, and card charts. Supported widgets include Filter Bar, TAB, IFrame, Image, and Text Area. Quick BI supports filter interactions that allow you to filter data across multiple charts.
    -   Portal: You can drag and drop components on a dashboard to assemble a portal. Quick BI supports embedded links \(linked dashboards\) and basic settings of the template and the menu bar.
    -   Share/Publish: You can share workbooks, dashboards, and portals with other logged-in users, and publish dashboards on the Internet for non-logged-in users to access the dashboards.
-   Permission management module
    -   Organizational unit management and authorizations: Manages authorizations in a three-layer hierarchy: organization - workspace - role, to control access permission of each report.
    -   Row-level permission management: Control access to data at row-level, enables different roles to have row-level access to data stored in a table.

