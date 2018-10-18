# Create a cloud data source {#concept_tlv_gn5_mfb .concept}

Data sources must be used as the basis to operate datasets, worksheets, dashboards, data portals, and others. This section describes how to create a cloud data source.

Before you create a cloud data source, you need to go to the data source creation page:

1.  Log on to Quick BI console.
2.  Click **Data Sources**. The data source management page is displayed.
3.  Click **Create Data Sources** to select a data source.
4.  Click Cloud database tab.

## MaxCompute {#section_inm_5p5_mfb .section}

1.  Click **MaxCompute**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985317713878_en-US.png)

    -   Name: The name of the data source configuration list.
    -   Database address: There is a default address here, which is generally not subject to modification; if you need to modify, please refer to [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/34951.htm).

        **Note:** Database addresses change by region. For example, in the classic network, the database address in HongKong region is http://service.cn-hongkong.maxcompute.aliyun-inc.com/api, the database address in Singapore region is http://service.ap-southeast-1.maxcompute.aliyun-inc.com/api. For more information, refer to: [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/34951.htm).

    -   Project: The name of the project.
    -   Access Id: Access Key ID of the Alibaba Cloud console.
    -   AccessKey: The AccessKey Secret of the Alibaba Cloud console.
    **Note:** The value of "Access Key" must be valid. The corresponding account can be that of the project administrator or owner or a common user who has the list, select, and create instance permissions.

3.  Click **Test Connection** to perform the data source connectivity test.

    **Note:** If the connectivity is normal, a prompt message is displayed.

4.  Click **Add**, then the data source is added.

    After the data source is added, the **Data Source** tab is automatically displayed, and all data tables under the data source are displayed in the right pane.

    MaxCompute data sources are asynchronously loaded and updated. If it is your first time to create a data source, you must wait one to five minutes for data synchronization.


## MySQL {#section_l1b_pq5_mfb .section}

Due to the limitation of the whitelist policy of ApsaraDB for RDS, you must manually add the whitelists on the ApsaraDB for RDS console before adding an ApsaraDB for RDS data source.

To add and set up whiteable lists, see [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/26198.htm?spm=a2c63.p38356.a3.1.4a0c1ce4v8Eznb).

1.  Click **MySQL**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985317813887_en-US.png)

    -   Display name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: Connection database name
    -   User Name: The user name of the database.
    -   Password: The password of the database.
    If you do not know the user name and password, contact your data warehouse administrator.

3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

    If a data source with the same configuration already exists, a message indicating a conflict is displayed. Do not add a duplicate data source.


## SQL Server {#section_rws_vq5_mfb .section}

The method for adding a data source from ApsaraDB for RDS \(SQL Server\) is similar to that from ApsaraDB for RDS \(MySQL\). The differences are that the configuration item **schema** is added for data sources from ApsaraDB for RDS \(SQL Server\), and the default port is set to port **1433** of the SQL server.

1.  Click **SQL Server**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985317813888_en-US.png)

    -   Name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: Connection database name
    -   Schema: dbo
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

## Analytic DB {#section_v4y_dr5_mfb .section}

1.  Click **Analytic DB**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985319113889_en-US.png)

    -   Name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: Connection database name
    -   Access Id: The AccessKey ID of the Alibaba Cloud console.
    -   AccessKey: The AccessKey Secret of the Alibaba Cloud console.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

## Hybrid DB for MySQL {#section_h4s_hr5_mfb .section}

The method for adding a data source from Hybrid DB for MySQL is similar to that from MySQL. 

1.  Click **Hybrid DB for MySQL**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985319113890_en-US.png)

    -   Name: Display name in the data source list
    -   Database address: Just fill in the host name or IP address.
    -   Port: Default 3306
    -   Database: Connection database name
    -   User name: Corresponding user name
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

## HybirdDB for PostgreSQL {#section_xjg_nr5_mfb .section}

The method for adding a data source from Hybrid DB for PostgreSQL is similar to that from SQL Server.  The default port is the port specific to HybridDB for PostgreSQL.

1.  Click **Hybrid DB for PostgreSQL**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985319113891_en-US.png)

    -   Name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

## PostgreSQL {#section_zmk_rr5_mfb .section}

1.  Click **PostgreSQL**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985319113892_en-US.png)

    -   Name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add** to complete the data source add.

## PPAS {#section_s12_vr5_mfb .section}

The method for adding a data source from PPAS is similar to that from PostgreSQL. 

1.  Click **PPAS**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/153985319213893_en-US.png)

    -   Name: Display name in the data source list
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add**. The data source is added.

