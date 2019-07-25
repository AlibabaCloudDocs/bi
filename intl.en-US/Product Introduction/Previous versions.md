# Previous versions {#concept_gkr_bdb_5db .concept}

## V2.4.0 {#section_xjt_2rq_k2b .section}

Quick BI V2.4.0 China site \(aliyun.com\) supports the following features:

-   Dashboard layouts are improved.
-   You can now use hyperlinks and filter interaction in cross tables.
-   You can drag items to add components and create charts.
-   Quick BI Enterprise Standard now supports these user-created data sources: Vertica and IBM DB2 LUW.
-   Quick BI Enterprise Standard can detect second or minute-based data and filter time-based data by second.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V2.3.0 {#section_eh1_ccr_32c .section}

Quick BI V2.3.0 International site \(alibabacloud.com\) supports the following features:

-   Page layouts are improved.
-   Quick BI Enterprise Standard now supports more data sources including Hive and Oracle.
-   The data modeling feature of Quick BI Enterprise Standard supports connecting databases across different data sources: MaxCompute, MySQL, and Oracle.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V2.0 {#section_sxs_kgb_5db .section}

Layout

The layout of Quick BI V2.0 contains these sections: Home, Workspace, Guide, and Subscriptions.

-   Home: Visitors can find related reports from shared with me and favorites. New users can quickly view resources in workspaces by installing cases and applying for workspaces.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15640441601054_en-US.png)

-   Workspace: you can create data sources, datasets, dashboards, and workbooks. Dashboards components are better displayed and filter bars are optimized.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15640441601055_en-US.png)

-   Guide: the workflow provides you with an overview of the product process to familiarize you with Quick BI.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15640441601056_en-US.png)

-   Subscriptions: you can create, manage, and monitor email tasks.

Quick BI Basic new features

-   Quick BI Basic now supports more data sources including PostgreSQL, PPAS, and Oracle.
-   Supports image components \(URLs\).

Quick BI Pro new features

-   Workbook

    Added new data analysis methods for workbooks. Supports retrieving data from workbook cells, and displaying and processing data from different data sources. Supports more than 200 data processing functions that are similar to those in Excel.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15640441611057_en-US.png)

-   Subscriptions

    You can manage email subscriptions and quickly create email tasks in the dashboards.

-   Protected mode

    Members in the same workspace can edit the same dashboard or workbook.

-   Apply for and approve permissions

    You can apply for permission to access dashboards, workbooks, and BI portals. Quick BI will send you notifications when you receive permission requests or approvals. This helps you obtain permissions.


\(Testing\) Modify embedded reports

Quick BI Pro allows you to embed a maximum of 20 third-party reports. However, you cannot embed third-party reports into Quick BI Basic. The reports that you have already embedded remain editable, but no new reports can be added.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.12 {#section_yd5_fhb_5db .section}

Quick BI V1.12 supports the following features:

-   Quick BI now supports more data sources including HybridDB for MySQL.
-   Added the management page where reports of third-party systems can be embedded for personal workspaces.
-   Quick BI V1.12 allows you to use views in the SQL Server data source.
-   You can now add descriptions to the calculated fields.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.11 {#section_izg_vhb_5db .section}

Quick BI V1.11 supports the following features.

-   The following widgets are available in the dashboards:

    -   Five chart widgets: polar diagrams, word clouds, tornado-leaned funnel charts, hierarchy charts, and flow analysis.
    -   One content widget: iFrame.
    You can use more methods to create dashboards.

-   New filtering rules for cross tables in dashboards: you can use visualization methods such as foreground colors, background colors, and icon sets to highlight values within a specified value range. Business data is better displayed.
-   New filtering criteria for charts in the dashboards: The measure of the criteria now supports filtering based on both the clustered data and distributed data. Supports more filtering methods.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.10 {#section_b4t_f3b_5db .section}

The new dashboard \(testing\) is released and supports the following features:

-   The new dashboard uses the popular tile layout in the industry. You can easily adjust the size and location of the chart block.
-   The new dashboard provides 12 charts and 2 widgets to optimize the chart functionality. Scatter charts now support up to 1000 dimensions. Date widgets can be combined into filter bars. The chart color scheme is visually enhanced.
-   The interaction of the new dashboard caters to user habits. You can configure charts based on the chart logic. It is easier for you to learn and use the dashboard.
-   The new dashboard supports filtering dimensions and measures in chart blocks. This allows you to filter data more flexibly.
-   The filter bars of the new dashboard support associating datasets from the same or different data sources.
-   The filter interaction of the new dashboard allows you to cancel the interaction.
-   The new dashboard allows you to report data while editing the report. This increases development efficiency.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.9 {#section_t1v_l3b_5db .section}

Quick BI V1.9 supports the following features.

-   Quick BI now supports more data sources including SQL Server databases running on Elastic Compute Service \(ECS\) instances.
-   You can now upload local Excel files, including XLS and XLSX files. You can use these Excel files to create reports.
-   The user space now supports more update operations. You can add fields to the table schema, update tables, append files to tables, and delete specified files from tables.
-   Watermarks are optimized. Previously, dashboards were watermarked with your baseId. Dashboards now can be watermarked with your username that directly displays the author information.
-   Enhanced calculated field: A calculated field is a new column that meets the SQL column syntax of the current data source. The field is created by existing fields and SQL supported functions. If you need to create a new field that is calculated based on existing data in the data source, add another calculated field. Calculated fields help you analyze data based on different conditions, such as user attribute groups and price ranges.
-   Quick BI Basic release. Features: Connecting to multiple data sources, using classic workbooks for data analysis, and creating dashboards that support multiple charts. Creating portals and downloading data. Sharing classic workbooks, dashboards, and portals. You can embed dashboards to third-party systems \(number <= 2 per account and monthly visiting time <= 10 thousand per dashboard\). Uploading local files to the Explore space \(capacity <= 100 MB per account\).

    **Note:** The workbook feature is in beta testing and will be soon unavailable. Workbooks do not support adding custom grouping fields, data type conversion, dataset snowflake model association, database cross-source association, and other features.

-   Quick V1.9 allows you to download dashboard data. You can download data corresponding to the chart widgets in the dashboard in the XLSX format.
-   Data row-level permission settings are optimized: redundant columns displayed on the row-level permission settings area in the earlier versions are removed. Operations of query member values are added to each selected controlled field. The interaction optimization makes operations of row-level permissions more smooth and convenient.
-   Added the analyst role to the group workspace. Analyst is a role between developer and reader. It can use the data sources and datasets to create new data applications, but it cannot create data sources or datasets. This feature was developed based on user proposals and is a role feature developed from production scenarios.
-   In the Org Units page, you can now upload multiple accounts: Earlier versions only allowed administrators to manually add group members. For organizations that have a large number of members to manage, multiple uploading is a required feature. This feature allows the organization managers to fill in the workbooks containing Alibaba Cloud accounts and account names based on the template to add multiple users, with a maximum of 3,000 users at a time.
-   Supports using a drop-down list to select users to share reports with or transfer reports to. In earlier versions, when you share or transfer reports, you use the fuzzy search feature to locate users. Only when the keywords are hit, the user list appears. The current version supports selecting users from the drop-down list, which is more user-friendly.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.8 {#section_r34_s3b_5db .section}

Quick BI V1.8 supports the following features.

-   Data modeling is optimized: Previously, dataset maintenance can only be conducted on worksheets. Multiple worksheets affect each other and can easily cause errors. The new version removes dataset maintenance from worksheets and provides central dataset maintenance. Multiple datasets can be created from a fact table, and the dataset modification interface is more easy-to-use.
-   Unified the terms of various data objects with common terms in the industry. Renamed metric to measure. Renamed drilling group to hierarchy.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.7 {#section_ccl_v3b_5db .section}

Quick BI V1.7 supports the following features.

-   Quick BI V1.7 now supports more data sources including CSV files. You can upload CSV files to the user space to analyze data.
-   The main navigation pane is optimized. Data Sources and Datasets are moved to separate tabs.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.6 {#section_sf1_y3b_5db .section}

Quick BI V1.6 supports the following features.

-   The fast dataset function is released. Based on the Quick BI built-in acceleration engine, you can transfer MaxCompute tables to fast datasets by creating fast datasets, greatly improving the query speed.
-   Greenplum data sources are added. ApsaraDB HybridDB incorporates some in-depth extensions by Alibaba Cloud based on Greenplum Open Source Database program, and supports features including OSS storage, JSON data type, and HyperLogLog approximating analysis. Supports flexible hybrid analysis by using the standard and pre-released query syntax of SQL 2008 and Online Analytical Processing \(OLAP\) aggregate functions.
-   Optimized share feature: in earlier versions, you can only share objects with users under the same organization. The new feature makes it easier to collaborate and share objects with other users.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.5 {#section_enp_bjb_5db .section}

Quick BI V1.5 supports the following features.

-   You can publish dashboards.
-   Scenario analysis: the log analysis template for net.cn is available.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.4 {#section_pzm_cjb_5db .section}

Quick BI V1.4 supports the following features.

-   The distributed execution layer framework is optimized.
-   You can delete data sources.
-   Quick BI V1.4 supports more data sources including SQL Server.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.3 {#section_vf4_cjb_5db .section}

Quick BI V1.3 supports the following features.

-   User demos are available.
-   The procedure to create works is optimized.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.2 {#section_ex4_cjb_5db .section}

Quick BI V1.2 supports the following features.

-   Tenant models, data source management, work sharing areas, and the authorization and application processes are simplified.
-   You can embed Quick BI dashboards to third-party systems.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.1 {#section_orh_kjb_5db .section}

Quick BI V1.1 supports the following features.

-   Network connection errors of data sources are fixed.
-   You can share objects with other users.

------------------------------------------------------------------------------------------------------------------------------------------------------

## V1.0 {#section_fhv_kjb_5db .section}

Quick BI V1.0 supports the following features.

-   Quick BI V1.0 supports basic BI features, such as creating datasets, workbooks, and dashboards.

