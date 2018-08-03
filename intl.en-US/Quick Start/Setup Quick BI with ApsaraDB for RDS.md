# Setup Quick BI with ApsaraDB for RDS {#concept_q2b_y2d_5db .concept}

This chapter shows how to configure Quick BI to render data from ApsaraDB for RDS. The following information uses a MySQL database as an example.

Assume that you already have an existing MySQL database running and data to render.

The configuration includes the following three parts.

-   Configure Quick BI
-   Create a dashboard
-   Publish a dashboard

## Prerequisites { .section}

-   Obtain MySQL credentials.

    For more information, see  [Create account and database for MySQL 5.7 High-availability Edition/5.5/5.6 instances](https://www.alibabacloud.com/help/doc-detail/26129.htm?spm=a2c63.p38356.a3.1.26854bd3feeGKO),  [Create account and database for MySQL 5.7 Basic Edition](https://www.alibabacloud.com/help/doc-detail/49015.htm?spm=a2c63.p38356.a3.2.26854bd3feeGKO), and  [Create master account](https://www.alibabacloud.com/help/doc-detail/26130.htm?spm=a2c63.p38356.a3.3.26854bd3feeGKO) .

-   Obtain a free trial Quick BI or a purchased version.

    For more information, see [Purchase, upgrade, and renew](../../../../intl.en-US/Pricing/Purchase, upgrade, and renew.md#).


## Configure Quick BI {#section_gd5_ffd_5db .section}

**Copy IP ranges from the Quick BI**

1.  Log on to the Quick BI console.
2.  Select **Workbench** \> **Data sources**, to enter the data source management page
3.  Select **Create** \> **From Cloud Database** \> **MySQL**, to create a new data source from the Cloud database.
4.  Copy IP ranges, which are displayed in the blue area. See the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610681134_en-US.png)


**Obtain database endpoint from the RDS**

1.  Log on to the RDS console.
2.  Select the region where the target instance is located.
3.  Click the name of the target instance to go to the Basic Information page. 

    The Internet Address is the database endpoint.


**Set whitelist on RDS**

1.  Select **Security** in the left-side navigation pane to visit the Security page.
2.  On the Whitelist Settings tab page, click **Modify**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610691137_en-US.png)

3.  Click **Clear** to delete the IP address 127.0.0.1.
4.  Click **Add a Whitelist Group** to add a new whitelist group.
5.  Enter a new group name and paste IP ranges in the whitelist area.
6.  Click **OK** to complete the whitelist settings.

    For more information, see [Set whitelist](https://www.alibabacloud.com/help/doc-detail/26198.htm?spm=a2c63.p38356.a3.5.26854bd3feeGKO) .


**Verify the data source connection**

1.  Go back to the Quick BI data sources management page.
2.  Select **Create** \> **From Cloud Database** \> **MySQL**.
3.  Enter the required information for connecting to a data source, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610691140_en-US.png)

    -   Name: The name of the data source.
    -   Database Endpoint: Enter the host name or Internet address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   User Name: The user name of the database.
    -   Password: The password of the database.
4.  Click **Test Connection** to perform the data source connectivity test.

    If the connection goes well, a successful information is displayed.

5.  Click **Add**.  The data source is added.

    For more information, see [Create a cloud data source](intl.en-US/Quick Start/Data modeling/Data source management/Create a cloud data source.md#) and [Upload local files](intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#).


## Create a dashboard {#section_w2n_phd_5db .section}

1.  Select a data table in the data source management page.
2.  Click **Create Dataset** next to the data table.
3.  Click **Dashboards** to enter the dashboard management page.
4.  Select **Create \> Dashboard** to enter the dashboard editing page.
5.  Select or search for the dataset that you want to analyze, as shown in following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610691150_en-US.png)

    For more information about dashboard basic operations, see [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#).

6.  Double-click a chart icon, for example, the line chart.   The line chart sample is displayed.
7.  Select required dimension fields and measurement fields. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610691152_en-US.png)

8.  Click **Update** to complete the line chart creation.
9.  Click **Save** to save current dashboard.

## Make public a dashboard {#section_ns4_g3d_5db .section}

1.  Select a dashboard in the dashboard management page.
2.  Click **Make Public** icon next to the selected dashboard. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15332610691158_en-US.png)

3.  Select an expiration date, and select Regenerate URL.
4.  Copy the generated URL to your browser to view the dashboard contents.

## Further reading {#section_ug2_43d_5db .section}

You can get further detailed information from the following addresses.

-   [ApsaraDB for RDS](https://www.alibabacloud.com/product/apsaradb-for-rds?spm=a2c63.p38356.a3.10.26854bd3feeGKO)
-   [Quick BI](https://www.alibabacloud.com/product/quickbi?spm=a2c63.p38356.a3.11.26854bd3feeGKO)

