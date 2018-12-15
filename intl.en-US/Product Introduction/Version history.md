# Version history {#concept_gkr_bdb_5db .concept}

## Quick BI V2.4.0 {#section_xjt_2rq_k2b .section}

Feature updates of Quick BI China are as follows:

-   Dashboard layout updates.
-   Table hyperlinks and filter interaction.
-   Drag to add components and charts.
-   Quick BI Professional: Existing data source now supports Vertica and IBM DB2 LUW.
-   Quick BI Professional: Data in date data type can be recognized in minutes and seconds. Filter data in date data type accurate to seconds.

## Quick BI V2.3.0 {#section_eh1_ccr_32c .section}

Feature updates of Quick BI International are as follows:

-   The visualization of Quick BI is upgraded.
-   Quick BI Professional: Supports more data source types including Hive and Oracle.
-   Quick BI Professional: Data modeling supports database connections among three different data sources, which are MaxCompute, MySQL, and Oracle.

## Quick BI V2.0 {#section_sxs_kgb_5db .section}

Product interaction process

The Quick BI interaction is updated to support all features. The Quick BI navigation bar is divided into Home, Workspace, Guide, and Subscriptions.

-   Home: Visitors can find related reports from shared with me and favorites. New users can quickly view resources in workspaces by installing cases and applying for workspaces.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15448454911054_en-US.png)

-   Workspace: Supports data sources, datasets, dashboards, and workbooks. Provides optimized visual styles of dashboard components and enhanced features of filter bars.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15448454911055_en-US.png)

-   Guide: A workflow that provides you with an overview of the production process and a quickstart guide.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15448454911056_en-US.png)

-   Subscriptions: Create, manage, and monitor related mail tasks.

Updates for the Quick BI Basic

-   Data source now supports PostgreSQL, PPAS, and Oracle Data.
-   Supports image components \(URL\)

Updates for the Quick BI Pro

-   Workbook

    Added new data analysis methods for workbooks. Supports retrieving data from workbook cells, and displaying and processing data from different data sources. Supports more than 200 data processing functions that are similar to those in Excel.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15448454911057_en-US.png)

-   Subscriptions

    Supports managing mail subscriptions and quickly creating mail tasks in the dashboards.

-   Supports team collaboration

    Allows other members of the workspace to collaborate on editing a dashboard or workbook.

-   Added the workflow of applying for and approving permission requests

    Supports applying for the permission of dashboards, workbooks, and portals. Supports approving messages. Helps you take the initiative to obtain report permissions.


\(Testing\) Supports embedding report changes

Quick BI Pro supports a limit of 20 reports to be embedded. Quick BI Basic has disabled third-party embedding. The embedded reports remain editable, but no new reports can be added.

## Quick BI V1.12 {#section_yd5_fhb_5db .section}

Feature updates are as follows:

-   Data source now supports HybridDB for MySQL.
-   An administration page that can be embedded in a third-party system report is added to the personal workspace. You can embed new third-party reports to make the system easier to use. For more information, see [Grant third-party report permissions to group workspaces](https://help.aliyun.com/knowledge_detail/55768.html).
-   The view is now available under the SQL server data source.
-   You can now add notes to the calculated fields.

## Quick BI V1.11 {#section_izg_vhb_5db .section}

Feature updates are as follows:

-   The following widgets are added to the dashboards:

    -   Five chart widgets: Radar, Word Cloud, Tornado, TreeMap, and Conversion Path.
    -   One content widget: The iFrame widget.
    More ways to create dashboards.

-   New filtering criteria for tables in the dashboards: It highlights the measures in a certain data interval by setting visual attributes such as foreground color, background color, and icon sets. The display of the business data is clearer.
-   New filtering criteria for charts in the dashboards: The measure of the criteria now supports filtering based on both the clustered data and distributed data. More ways to filter data.

## Quick BI V1.10 {#section_b4t_f3b_5db .section}

The new dashboard \(experimental\) release has the following features:

-   The new dashboard uses the popular tile layout in the industry. You can easily adjust the size and location of the chart block.
-   The new dashboard provides 12 charts and 2 widgets to optimize chart functionality. The scatterplot supports up to 1000 dimensions. Date widgets can be combined into filter bars. The chart color scheme is visually enhanced.
-   The interaction of the new dashboard caters to user habits. You can configure charts based on the chart logic. It's easier for you to learn and use the dashboard.
-   The new dashboard supports filtering dimensions and measures in chart blocks, and the filtering is more flexible.
-   The filtering criteria of the new dashboard supports the interaction of datasets in different sources or in the same source, and the widget is more powerful.
-   The filter interaction of the new dashboard allows you to cancel the interaction, which is more user-friendly.
-   The new dashboard supports querying report data during report editing and provides a higher development efficiency.

## Quick BI V1.9 {#section_t1v_l3b_5db .section}

Feature updates are as follows:

-   Added support for the SQL Server data source in ECS.
-   Supports uploading local Excel files: The supported file formats are .xls and .xlsx, which meet the requirements of uploading Excel files to create reports.
-   Schema updates and data updates for the Explore space. Supports adding new fields to tables, updating table data, appending data files to tables, and deleting specified data files that already exist in the tables.
-   Optimized display of the dashboard watermark. The watermark in previous versions displayed your baseId, of which the meaning was not clear. The current version displays your logon name instead of your baseId in the watermark.
-   Enhanced calculated field: A calculated field is a new column that meets the SQL column syntax of the current data source. The field is created by existing fields and SQL supported functions. If you need to calculate based on existing data in the data source to get a new value, you can choose to add a calculated field. By using calculated fields, you can implement flexible and dynamic data analysis, such as grouping user by attribution and price interval analysis.
-   Quick BI Basic release. Features: Connecting to multiple data sources, using classic workbooks for data analysis, and creating dashboards that support multiple charts. Creating portals and downloading data. Sharing classic workbooks, dashboards, and portals. You can embed dashboards to third-party systems \(number <= 2 per account and monthly visiting time <= 10 thousand per dashboard\). Uploading local files to the Explore space \(capacity <= 100 MB per account\).

    **Note:** The classic workbook is a beta feature and is not supported in future releases. The classic workbook does not support adding custom grouping fields, data type conversion, dataset snowflake model association, database cross-source association, and other features.

-   Supports downloading dashboard data: Downloading data corresponding to the chart widgets in the dashboards in xlsx format.
-   Optimized styles for the data line-level permission management: Removed the redundant column display in the permission management from earlier versions. Appended the filtering operations to each specified field. These optimizations for the interaction make granting line-level permissions more fluent and quicker.
-   Added the analyst role to the group workspace. Analyst is a role between developer and reader. It can use the data sources and datasets to create new data applications, but it cannot create data sources or datasets. This feature was developed based on user proposals and is a role feature developed from production scenarios.
-   In the Org Units page, you can now upload multiple accounts: Earlier versions only allowed administrators to manually add group members. For organizations that have a large number of members to manage, multiple uploading is a required feature. This feature allows the organization managers to fill in the workbooks containing Alibaba Cloud accounts and account names based on the template to add multiple users, with a maximum of 3,000 users at a time.
-   Supports using a drop-down list to select users to share reports with or transfer reports to. In earlier versions, when you share or transfer reports, you use the fuzzy search feature to locate users. Only when the keywords are hit, the user list appears. The current version supports selecting users from the drop-down list, which is more user-friendly.

## Quick BI V1.8 {#section_r34_s3b_5db .section}

Feature updates are as follows:

-   Data modeling optimization. In earlier versions, the maintenance for datasets can only be done in classic workbooks. Multiple classic workbooks may affect each other and may cause errors. The new version maintains the datasets centrally instead of working with classic workbooks. It supports creating multiple datasets from a fact table. The user interface for dataset editing is more friendly.
-   Unified the terms of various data objects with common terms in the industry. Renamed metric to measure. Renamed drilling group to hierarchy.

## Quick BI V1.7 {#section_ccl_v3b_5db .section}

Feature updates are as follows:

-   Data source now supports CSV files. CSV files can be uploaded to the Explore space and you are allowed to freely analyze your own data.
-   The main navigation is optimized to integrate data sources and datasets to a single data tag.

## Quick BI V1.6 {#section_sf1_y3b_5db .section}

Feature updates are as follows:

-   The high-speed dataset feature: The integrated Quick BI acceleration engine allows users to create high-speed datasets to create tables in MaxCompute into high-speed datasets, and significantly increase the query speed.
-   Added Greenplum data source: The cloud database Hybrid DB is based on the open-source Greenplum database project. Features such as OSS storage, JSON data, and HyperLogLog prediction and analysis are supported by the Alibaba Cloud in-depth extensions. Supports flexible hybrid analysis by using the standard and pre-released query syntax of SQL 2008 and Online Analytical Processing \(OLAP\) aggregate functions.
-   Supports sharing with members: In earlier versions, you can only share content with users under your organization. The new feature makes it easier to collaborate and share content without limit.

## Quick BI V1.5 {#section_enp_bjb_5db .section}

Feature updates are as follows:

-   Dashboard publishing features.
-   Scenario analysis - The log analysis template for net.cn is online.

## Quick BI V1.4 {#section_pzm_cjb_5db .section}

Feature updates are as follows:

-   Optimized the distributed execution layer framework.
-   Supports data source deletion.
-   Supports SQLServer.

## Quick BI V1.3 {#section_vf4_cjb_5db .section}

Feature updates are as follows:

-   Added user demos.
-   Optimized the workflow of creating new applications.

## Quick BI V1.2 {#section_ex4_cjb_5db .section}

Feature updates are as follows:

-   Simplified tenant models, data source management, work-sharing areas, and the process of authorizations and requests.
-   Supports integrating the dashboard to a third-party system for presentation.

## Quick BI V1.1 {#section_orh_kjb_5db .section}

Feature updates are as follows:

-   Resolved the issue of connecting user data sources.
-   Supports sharing with members.

## Quick BI V1.0 {#section_fhv_kjb_5db .section}

Feature updates are as follows:

-   Basic features are implemented. Supports the development and production of datasets, worksheets, and dashboards.

