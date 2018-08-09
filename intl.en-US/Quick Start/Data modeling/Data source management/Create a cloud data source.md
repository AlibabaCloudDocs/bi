# Create a cloud data source {#task_wfz_mbq_5db .task}

Data sources must be used as the basis to operate datasets, worksheets, dashboards, data portals, and others. This section describes how to create a cloud data source.

1.   Log on to the Quick BI console. 
2.   Click **Data Sources**. The data source management page is displayed. 
3.   Click **Create** to select a data source. 

## MaxCompute {#task_opx_tbq_5db}

1.   Click From Cloud Database tab. 
2.   Click **MaxCompute**. 
3.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591292_en-US.png)

    -   Name: The name of the data source configuration list.
    -   Database address: There is a default address here, which is generally not subject to modification; if you need to modify, please refer to maxcompute for access to domain names and datacenters.

        **Note:** Database addresses change by region. For example, in the classic network, the database address in HongKong region is http://service.cn-hongkong.maxcompute.aliyun-inc.com/api, the database address in Singapore region is http://service.ap-southeast-1.maxcompute.aliyun-inc.com/api. For more information, refer to: [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/34951.htm).

    -   Project: The name of the project.
    -   Access Id: Access Key ID of the Alibaba Cloud console.
    -   AccessKey: The AccessKey Secret of the Alibaba Cloud console.
    **Note:** The value of AccessKey must be valid. The corresponding account can be that of the project administrator, project owner,  or a common user who has permissions to list, select, and create instances.

4.   Click Connect tests to perform a data source connectivity test. 

    If the connectivity is normal, a prompt message is displayed.

5.   Click **Add**, then the data source is added. 

    After the data source is added, the Data Source tab is automatically displayed, and all data tables under the data source are displayed in the right pane.

    MaxCompute data sources are asynchronously loaded and updated. If it is your first time to create a data source, you must wait one to five minutes for data synchronization.


## MySQL {#task_zs4_5cq_5db}

Due to the limitation of the whitelist policy of ApsaraDB for RDS, you must manually add the following whitelists on the ApsaraDB for RDS console before adding an ApsaraDB for RDS data source: 10.152.69.0/24, 10.152.163.0/24, or 139.224.4.0/24.

To add and set up whiteable lists, see setting up whiteable access domains and data centers.

1.   Click **MySQL**. 
2.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591294_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   User Name: The user name of the database.
    -   Password: The password of the database.
    If you do not know the user name and password, contact your data warehouse administrator.

3.   Click Connect tests to perform a data source connectivity test. 
4.   Click Add to complete the data source add. 

    If a data source with the same configuration already exists, a message indicating a conflict is displayed. Do not add a duplicate data source.


## SQL Server {#task_fgn_jfq_5db}

The method for adding a data source from ApsaraDB for RDS \(SQL Server\) is similar to that from ApsaraDB for RDS \(MySQL\).  The differences are that the configuration item schema is added for data sources from ApsaraDB for RDS \(SQL Server\), and the default port is set to port 1433 of the SQL server.

1.   Click **SQL Server**. 
2.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591296_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: dbo
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.   Click Connect tests to perform a data source connectivity test. 
4.   Click Add to complete the data source add. 

## Analytic DB {#task_h3r_sfq_5db}

1.   Click **Analytic DB**. 
2.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591297_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Access Id: The AccessKey ID of the Alibaba Cloud console.
    -   AccessKey: The AccessKey Secret of the Alibaba Cloud console.
3.   Click Connect tests to perform a data source connectivity test. 
4.   Click Add to complete the data source add. 

## Hybrid DB for MySQL {#task_h1f_1gq_5db}

The method for adding a data source from Hybrid DB for MySQL is similar to that from MySQL. 

1.   Click **Hybrid DB for MySQL**. 
2.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591298_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port: Default 3306
    -   Database: Connection database name
    -   User name: corresponding user name
    -   Password: The password of the database.
3.   Click **Test Connection** to perform the data source connectivity test. 
4.   Click Add to complete the data source add. 

## HybirdDB for PostgreSQL {#task_owt_ggq_5db}

The method for adding a data source from Hybrid DB for PostgreSQL is similar to that from SQL Server.  The default port becomes a specific port of  PostgreSQL.

1.   Click **Hybrid DB for PostgreSQL**. 
2.   Enter the required data source connection information, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591299_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.   Click **Test Connection** to perform the data source connectivity test. 
4.   Click Add to complete the data source add. 

## PostgreSQL {#task_fks_4gq_5db}

1.   Click **PostgreSQL**. 
2.   Enter the required information for connecting to a data source. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591300_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.   Click **Test Connection** to perform the data source connectivity test. 
4.   Click Add to complete the data source add. 

## PPAS {#task_uwk_tgq_5db}

The method for adding a data source from PPAS is similar to that from PostgreSQL. 

1.   Click **PPAS**. 
2.   Enter the required information for connecting to a data source, as shown in the following figure. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9084/15338019591301_en-US.png)

    -   Display name: list of data sources display name
    -   Database Endpoint: Enter the host name or IP address.
    -   Port: Enter the correct port number.
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.   Click **Test Connection** to perform the data source connectivity test. 
4.   Click **Add**. The data source is added. 

