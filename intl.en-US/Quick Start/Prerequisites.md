# **Connect Quick BI to RDS for MySQL** {#concept_q2b_y2d_5db .concept}

This topic uses MySQL database as an example to describe how to connect Quick BI to RDS MySQL.

Assume that you already have a MySQL database running properly and the data in this database can be used.

## Prerequisites {#section_bjn_rb5_42b .section}

-   You have access permissions to the MySQL database. For more information, see [Create accounts and databases](../../../../intl.en-US/Quick Start for MySQL/Initial configuration/Create accounts and databases.md#).
-   Obtain a free trial for Quick BI or a purchased edition. For more information, see [Purchase, upgrade, and renew Quick BI services](../../../../intl.en-US/Pricing/Purchase, upgrade, and renew Quick BI services.md#).

## Configure Quick BI {#section_gd5_ffd_5db .section}

**Copy the IP address from Quick BI**

1.  Log on to the Quick BI console.
2.  Click**Workspace** \> **Data Sources**to go to the data source management page.
3.  Click**Create Data Source** \> **Cloud Database** \> **MySQL** to create a MySQL data source.
4.  Copy the IP address displayed in the blue area, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15447885581134_en-US.png)


**Obtain the endpoint of the MySQL database from RDS**

1.  Log on to the RDS console.
2.  Select the region where the target instance is located.
3.  Click the name of the instance to go to the Basic Information page.

    The IP address is the database endpoint.


**Set the IP address whitelists on RDS**

1.  In the left-side navigation pane, click **Data Security** to go to the data security management page.
2.  On the Whitelist Settings tab page, click **Modify**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15447885581137_en-US.png)

3.  Click **Clear** to delete the IP address 127.0.0.1.
4.  Click **Add Whitelist Group** to add a new whitelist group.
5.  Enter a new group name and paste the IP address in the whitelist area.
6.  Click **OK** to complete the whitelist settings.

    For more information, see [Set whitelists](https://www.alibabacloud.com/help/doc-detail/26198.htm?spm=a2c63.p38356.a3.5.26854bd3feeGKO).


**Verify the data source connection**

1.  Go back to the Quick BI data source management page.
2.  Click**Create Data Source** \> **Cloud Database** \> **MySQL**.
3.  Enter the data source connection information as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/15447885581140_en-US.png)

    -   Name: The display name of the data source.
    -   Database Endpoint: The IP address of the database.
    -   Port: The port number.
    -   Database: The database name.
    -   User Name: The name of the database user.
    -   Password: The database password.
4.  Click **Test Connection** to verify that the data source connection is functioning properly.

    If the connection functions properly, a prompt message is displayed.

5.  Click **Add**. The data source is added.

    For more information, see [Create a cloud data source](intl.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from external database](intl.en-US/User Guide/Data modeling/Data source management/Create a data source from external database.md#), and [Upload local files](intl.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).


## More information {#section_ug2_43d_5db .section}

You can obtain more detailed information about Quick BI and RDS from the following links.

-   [ApsaraDB for RDS](https://www.alibabacloud.com/product/apsaradb-for-rds?spm=a2c63.p38356.a3.10.26854bd3feeGKO)
-   [Quick BI](https://www.alibabacloud.com/product/quickbi?spm=a2c63.p38356.a3.11.26854bd3feeGKO)

