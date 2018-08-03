# Version history {#concept_gkr_bdb_5db .concept}

## Quick BI v2.4.0 {#section_xjt_2rq_k2b .section}

The Quick BI Chinese version features are updated as follows:

-   Dashboard layout updates.
-   Table and pivot table support jump and linkage functionality.
-   Support dragging to add query components and charts.
-   Professional Edition: Add the support for external database Vertica and IBM DB2 LUW.
-   Professional Edition: Minutes and seconds in time data are recognized, and the filtering of time data is accurate to seconds.

## Quick BI v2.3.0 {#section_eh1_ccr_32c .section}

The Quick BI international version features are updated as follows:

-   The UI of Quick BI has updated.
-   Professional Edition: Add support for Hive, Oracle database as data source.
-   Advanced/Professional Edition: Data Modeling supports cross-source database connections for MaxCompute, MySQL, and Oracle data sources.

## Quick BI v2.0 Edition {#section_sxs_kgb_5db .section}

1. Product interaction process

The quick Bi interaction is upgraded to support the use of full links, and it is divided into Home, Workspace, Guide, and Subscription.

-   Home: The Home page includes the areas of Shared with Me and Favorites. A new user can quickly view resources in the workspace through the Report demos, and they also can join a workspace to view the resources in that workspace.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15332654511054_en-US.png)

-   Workspace: You can manage the data source, dataset, dashboard, and workbook, meanwhile, the display style of dashboard component is optimized, and the function of widgets is enhanced.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15332654511055_en-US.png)

-   Guide: The Guide provides a product process through a process chart.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15332654511056_en-US.png)

-   Subscription: You can create, manage, and monitor appropriate mail tasks through the Subscription function.

New Standard Edition

-   Added PostgreSQL, PPAs, and Oracle data sources
-   Add an image widget

New in advanced Edition

-   Workbook

    Added a data analysis method for a workbook. The workbook supports cell-level counting, displaying data from different data sources, and processing them at the same time. It also supports more than 200 data processing functions.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/15332654511057_en-US.png)

-   Subscription

    Added mail subscription management lists to support mail task in dashboard.

-   Supports collaboration within a team

    Allows other members of the workspace to work together to edit a dashboard or spreadsheet.

-   New permission request and approval flow

    Support for dashboard, spreadsheet, portal permission requests, and message approval, helps users to take the initiative to obtain report permissions.


Four, the trial function embedded report changes

The Quick BI pro supports 20 reports embedded, and the Quick BI Basic closes third-party embedded entry, but the reports which are already embedded still can be edited.

## Quick BI v1.12  {#section_yd5_fhb_5db .section}

The features are updated as follows:

-   Add the HybridgeDB for MySQL data source.
-   The management control page of third-party embeddable system reports is added to the personal space. You can add and embed third-party system reports for easy use. For more information, see  [Help](https://help.aliyun.com/knowledge_detail/55768.html).
-   Add View function in SQL server data sources.
-   You can add notes for fields.

## Quick BI v1.11 {#section_izg_vhb_5db .section}

The features are updated as follows:

-   Added the following widgets in dashboard:

    -   Five charts: Polar chart, Cloud chart, Tornado chart, Hierarchy chart, and Conversion chart.
    -   The one content control is the iFrame control.
    Quick BI supports more dashboard creation methods.

-   Added new rules in Table chart: You can use different colors and marks to display specified values or value ranges. Display of business data is clearer.
-   New dashboard chart filter new detail filter feature: Metric filter in chart, not only support, filter by after-aggregation metric, filtering is now also supported based on the fine-grained metric of the pre-aggregation details. Quick BI supports more filtering methods.

## Quick BI  V1.10 {#section_b4t_f3b_5db .section}

The new dashboard product is released, and features are updated as follows:

-   The new dashboard uses the mainstream tile layout, users can easily adjust the size and location of the chart.
-   The new dashboard provides 12 charts and 2 widgets to optimize chart functionality. For example, the scattered chart supports to 1000 dimension values, the date widget is combined into the Filter, chart color is more beautiful and so on.
-   The new dashboard interaction logic is updated according to the user's habits, and the chart configuration is configured according to the chart elements. Users easy to learn and easy to use.
-   The new dashboard supports setting dimension and measurement filtering at the chart level, and the query condition is more flexible.
-   The Filter bar of the new dashboard supports both Single-Dataset and Multi-Dataset. The functions are more powerful.
-   The new dashboard's chart supports canceling the association between charts.
-   The new dashboard supports searching data during the report editing.

## Quick BI  v1.9 {#section_t1v_l3b_5db .section}

The features are updated as follows:

-   SQL Server data sources of ECS are supported.
-   Local Excel file uploading is supported: Quick BI supports upload of XLS and XLSX files. This function meets users' requirements of uploading and creating reports through Excel files.
-   Table schema updating and data content updating of the exploration space are supported: The new version supports adding fields to the table schema and updating of table data content. You can add data files to the table and delete existing data files from the table.
-   Dashboard watermark display is optimized: BaseID of the user is displayed in the watermark of the earlier version, which has no intuitive meanings for users. The new version uses the logon name as the watermark.
-   The calculated field function is strengthened: A calculated field is a new column that is constructed by a user using the existing fields and functions supported by SQL and meets the definition syntax rules of the SQL column of the current data source. If you want to perform calculation based on existing data in the data source, you can add calculated fields. The calculated field function can provide flexible data analysis, such as user attribute group analysis and price range analysis.
-   Quick BI Basic version release: The Basic edition supports the following features: Connect to multiple data sources; use a worksheet for data analysis; create a dashboard with a variety of data charts; create data portals; data downloads, share a worksheet, dashboard, portal, dashboard that can be embedded in a third-party system.\( Number <=2 of visits per account month <= 10 thousand per dashboard \), local files are uploaded to exploration space \(capacity <= 100 m per account \).
-   Dashboard data download is supported: Data corresponding to chart controls of the dashboard can be downloaded as XLSX files.
-   Data row-level permission setting interface is optimized: The extra column display box on the row-level permission setting interface in the earlier version is removed. Operations of query member values are added to each selected controlled field. The interaction optimization makes operations of row-level permissions more smooth and convenient.
-   Added Analyst roles in the workspace: The analyst is a role between the developer and the viewer. This role can use data sources and datasets to create reports, but the analyst cannot create or edit data sources and datasets. The requirement comes from the user's proposal, it is a role requirement that is refined from the user's real usage scenario.
-   Batch upload of users in organizational unit management is supported: Earlier versions only allow the organizational unit administrator to manually add members. The batch user upload function is required for organizational unit that has a large number of members. This function enables the organizational unit administrator to add users in batches by filling in the workbook with Alibaba Cloud accounts and nicknames according to the template requirements. A maximum of 3000 users can be added at a time.
-   Users who choose to share and transfer in a drop-down box in support of cluster space: previous versions used to share and transfer reports in cluster space when selecting users through a fuzzy search. way, only the match to keyword displays a list of the corresponding users, and currently supports the selection of users in the form of a drop-down box, it is easier for users to use.

## Quick BI v1.8 {#section_r34_s3b_5db .section}

The features are updated as follows:

-   Data modeling optimization: Previous maintenance of the data set can only be performed in the worksheet, multiple work sheets affect each other and are error prone, the new release centrally manages the maintenance of the data set from the worksheet, supporting a table of facts. from a fact table. It makes the dataset editing is easier to use.
-   Terms of data objects and use general terms in the industry are unified. Metering is changed to measurement, and drilling group is changed to layer schema.

## Quick BI v1.7 {#section_ccl_v3b_5db .section}

The features are updated as follows:

-   CSV file data sources are supported. CSV files can be uploaded to exploration spaces, so that users can freely analyze their data.
-   The main navigation bar is optimized. Data sources and datasets are integrated into a single data tag.

## Quick BI v1.6 {#section_sf1_y3b_5db .section}

The features are updated as follows:

-   Publishing datasets speed-up function: Based on Quick  Bi built-in Acceleration Engine allows users to create extreme-speed data sets in the form, make the tables in maxcompute into extreme-speed data sets, and greatly increase the query speed.
-   Add greenplum Data source Database open source database project, features such as OSS storage, JSON data types, hyperloglog Prediction and Analysis are supported by the Ali cloud depth extension. Complying with SQL 2008 standard query syntax and OLAP aggregate functions, ApsaraDB HybridDB offers a flexible hybrid analyzing capability.
-   The function of sharing works to any member is provided. The original share function can only share a work with members in the same organizational unit. The updated function helps easy collaboration and share.

## Quick BI v1.5 {#section_enp_bjb_5db .section}

The features are updated as follows:

-   The dashboard release function is provided.
-   The scenario analysis - HiChina log analysis template goes live.

## Quick BI v1.4 {#section_pzm_cjb_5db .section}

The features are updated as follows:

-   The distributed execution layer framework is optimized and upgraded.
-   Deletion of data sources is supported.
-   SQLServer is supported.

## Quick BI v1.3 {#section_vf4_cjb_5db .section}

The features are updated as follows:

-   User demos are added.
-   The process of creating a file is optimized.

## Quick BI v1.2 {#section_ex4_cjb_5db .section}

The features are updated as follows:

-   Tenant models, management of data sources, file share area, authorization, and application are simplified.
-   Dashboards can be embedded into a third-party system.

## Quick BI  v1.1 {#section_orh_kjb_5db .section}

The features are updated as follows:

-   The problem about user's data source network connection is solved.
-   Implement the sharing function.

## Quick BI v1.0 {#section_fhv_kjb_5db .section}

The features are updated as follows:

-   Basic BI functions are provided. Quick BI supports developing and creating datasets, worksheets, and dashboards.

