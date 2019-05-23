# Version history {#concept_gkr_bdb_5db .concept}

## Quick BI v2.4.0 {#section_xjt_2rq_k2b .section}

The Chinese version of Quick BI v2.4.0 supports the following features:

-   Dashboard layouts are improved.
-   You can now use hyperlinks and filter interaction in cross tables.
-   You can drag items to add components and create charts.
-   Quick BI Enterprise Standard now supports these user-created data sources: Vertica and IBM DB2 LUW.
-   Quick BI Enterprise Standard can detect second or minute-based data and filter time-based data by second.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v2.3.0 {#section_eh1_ccr_32c .section}

The international version of Quick BI v2.3.0 supports the following features:

-   Page layouts are improved.
-   Quick BI Enterprise Standard now supports more data sources including Hive and Oracle.
-   The data modeling feature of Quick BI Enterprise Standard supports connecting databases across different data sources: MaxCompute, MySQL, and Oracle.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v2.0 {#section_sxs_kgb_5db .section}

Layout

The layout of Quick BI v2.0 contains these sections: Home, Workspace, Guide, and Subscriptions.

-   Home: you can find a specified report on the Shared with Me or Favorites tab. New users can install case reports and apply to join the workspace to view resources in the workspace.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15585827011054_en-US.png)

-   Workspace: you can create data sources, datasets, dashboards, and workbooks. Dashboards components are better displayed and filter bars are optimized.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15585827011055_en-US.png)

-   Guide: the workflow provides you with an overview of the product process to familiarize you with Quick BI.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15585827011056_en-US.png)

-   Subscriptions: you can create, manage, and monitor email tasks.

Quick BI Basic new features

-   Quick BI Basic now supports more data sources including PostgreSQL, PPAS, and Oracle.
-   Supports image components \(URLs\).

Quick BI Pro new features

-   Workbooks

    Workbooks support a new data analysis method. This method can retrieve data from a specified cell. Different data sources can be displayed and processed at the same time. The Microsoft Excel-like workbooks also support over 200 functions that can help you process data.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15585827011057_en-US.png)

-   Subscriptions

    You can manage email subscriptions and quickly create email tasks in the dashboards.

-   Protected mode

    Members in the same workspace can edit the same dashboard or workbook.

-   Apply for and approve permissions

    You can apply for permission to access dashboards, workbooks, and BI portals. Quick BI will send you notifications when you receive permission requests or approvals. This helps you obtain permissions.


\(Testing\) Modify embedded reports

Quick BI Pro allows you to embed a maximum of 20 third-party reports. However, you cannot embed third-party reports into Quick BI Basic. The reports that you have already embedded remain editable, but no new reports can be added.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.12 {#section_yd5_fhb_5db .section}

Quick BI v1.12 supports the following features:

-   Quick BI now supports more data sources including HybridDB for MySQL.
-   You can embed third-party reports into your personal spaces..
-   Quick BI v1.12 allows you to use views in the SQL Server data source.
-   You can now add descriptions to the calculated fields.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.11 {#section_izg_vhb_5db .section}

Quick BI v1.11 supports the following features:

-   The following widgets are available in the dashboards:

    -   Five chart widgets: polar diagrams, word clouds, tornado-leaned funnel charts, hierarchy charts, and flow analysis.
    -   One content widget: iFrame.
    You can use more methods to create dashboards.

-   New filtering rules for cross tables in dashboards: you can use visualization methods such as foreground colors, background colors, and icon sets to highlight values within a specified value range. Business data is better displayed.
-   New filtering criteria for charts in the dashboards: you can filter data based on dimensions and measures before or after the data is processed by aggregate functions. Supports more filtering methods.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.10 {#section_b4t_f3b_5db .section}

The new dashboard \(testing\) is released and supports the following features:

-   The new dashboard uses the popular tile layout in the industry. You can easily adjust the size and location of the chart block.
-   The new dashboard provides 12 charts and 2 widgets to optimize the chart functionality. Scatter charts now support up to 1000 dimensions. Date widgets can be combined into filter bars. The chart color scheme is visually enhanced.
-   The interaction of the new dashboard caters to user habits. You can configure charts based on the chart logic. It is easier for you to learn and use the dashboard.
-   The new dashboard supports filtering dimensions and measures in chart blocks. This allows you to filter data more flexibly.
-   The filter bars of the new dashboard support associating datasets from the same or different data sources.
-   The filter interaction of the new dashboard allows you to cancel the interaction.
-   The new dashboard allows you to report data while editing the report. This increases development efficiency.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.9 {#section_t1v_l3b_5db .section}

Quick BI supports the following features:

-   Quick BI now supports more data sources including SQL Server databases running on Elastic Compute Service \(ECS\) instances.
-   You can now upload local Excel files, including XLS and XLSX files. You can use these Excel files to create reports.
-   The user space now supports more update operations. You can add fields to the table schema, update tables, append files to tables, and delete specified files from tables.
-   Watermarks are optimized. Previously, dashboards were watermarked with your baseId. Dashboards now can be watermarked with your username that directly displays the author information.
-   Enhanced capabilities for generating calculated fields. Calculated fields are generated based on SQL-supported functions and existing fields that meet the SQL syntax rules of the current data source. If you need to create a new field that is calculated based on existing data in the data source, add another calculated field. Calculated fields help you analyze data based on different conditions, such as user attribute groups and price ranges.
-   Quick BI Basic is released. It allows you to create multiple data sources and use workbooks to analyze data. You can create dashboards that support multiple types of charts. You can create BI portals, download data, share workbooks, dashboards, and BI portals, embed third-party dashboards \(maximum of 2 dashboards per account and maximum of 10,000 visits to each dashboard per month\), and upload local files to the user workspace \(maximum of 100 MB per account\).

    **Note:** The workbook feature is in beta testing and will be soon unavailable. Workbooks do not support adding custom grouping fields, data type conversion, dataset snowflake model association, database cross-source association, and other features.

-   Quick v1.9 allows you to download dashboard data. You can download data corresponding to the chart widgets in the dashboard in the XLSX format.
-   Data row-level permission settings are optimized: redundant columns displayed on the row-level permission settings area in the earlier versions are removed. Operations of query member values are added to each selected controlled field. The interaction optimization makes operations of row-level permissions more smooth and convenient.
-   You can add an analyst to a group space. An analyst is a role between a developer and a viewer. The analyst can use a data source and dataset to create works, but cannot create new data sources or datasets. The analyst cannot edit data sources or datasets. This role is created based on customer needs.
-   In the Org Units page, you can now upload multiple accounts. Earlier versions only allowed administrators to manually add group members. For organizations that have a large number of members to manage, uploading multiple members is a required feature. This feature allows the organization managers to fill in the workbooks that contain Alibaba Cloud accounts and account names based on the template to add multiple users, with a maximum of 3,000 users at a time.
-   You can use a drop-down list to select users to share reports with or transfer reports to. In earlier versions, when you share or transfer reports, you use the fuzzy search feature to locate users. The user list appears only when the keywords are hit. This version allows you to select users from the drop-down list for easy operations.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.8 {#section_r34_s3b_5db .section}

Quick BI v1.8 supports the following features:

-   Data modeling is optimized. In earlier versions, you need to maintain datasets in a workbook. Multiple workbooks may affect each other and cause errors. In this version, you do not need to maintain datasets in workbooks. It allows you to create multiple datasets from one fact table. This is easier for you to maintain datasets.
-   Unified the terms of various data objects with common terms in the industry. Renamed metric to measure. Renamed drilling group to hierarchy.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.7 {#section_ccl_v3b_5db .section}

Quick BI v1.7 supports the following features:

-   Quick BI v1.7 now supports more data sources including CSV files. You can upload CSV files to the user space to analyze data.
-   The main navigation pane is optimized. Data Sources and Datasets are moved to separate tabs.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.6 {#section_sf1_y3b_5db .section}

Quick BI v1.6 supports the following features:

-   The integrated Quick BI acceleration engine allows users to create high-speed datasets to create tables in MaxCompute into high-speed datasets, and significantly increase the query speed.
-   Quick BI v1.6 supports more data sources including Greenplum. HybridDB is based on Greenplum. Quick BI v1.6 is an open-source project whose features including OSS, the JSON data format, and HyperLogLog, are maintained by Alibaba Cloud. Supports flexible hybrid analysis by using the standard and pre-released query syntax of SQL 2008 and Online Analytical Processing \(OLAP\) aggregate functions.
-   Optimized share feature: in earlier versions, you can only share objects with users under the same organization. The new feature makes it easier to collaborate and share objects with other users.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.5 {#section_enp_bjb_5db .section}

Quick BI v1.5 supports the following features:

-   You can publish dashboards.
-   Scenario analysis: the log analysis template for net.cn is available.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.4 {#section_pzm_cjb_5db .section}

Quick BI v1.4 supports the following features:

-   The distributed execution layer framework is optimized.
-   You can delete data sources.
-   Quick BI v1.4 supports more data sources including SQL Server.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.3 {#section_vf4_cjb_5db .section}

Quick BI v1.3 supports the following features:

-   User demos are available.
-   The procedure to create works is optimized.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.2 {#section_ex4_cjb_5db .section}

Quick BI v1.2 supports the following features:

-   Tenant models, data source management, work sharing areas, and the authorization and application processes are simplified.
-   You can embed Quick BI dashboards to third-party systems.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.1 {#section_orh_kjb_5db .section}

Quick BI v1.1 supports the following features:

-   Network connection errors of data sources are fixed.
-   You can share objects with other users.

------------------------------------------------------------------------------------------------------------------------------------------------------

## Quick BI v1.0 {#section_fhv_kjb_5db .section}

Quick BI v1.0 supports the following features:

-   Quick BI v1.0 supports basic BI features, such as creating datasets, workbooks, and dashboards.

