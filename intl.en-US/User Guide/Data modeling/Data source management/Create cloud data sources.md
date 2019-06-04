# Create cloud data sources {#concept_tlv_gn5_mfb .concept}

Operations on datasets, workbooks, dashboards, and BI portals are based on data sources. This topic describes how to create a cloud data source.

You need to go to the Add Data Source page before adding a cloud data source.

1.  Log on to the Quick BI console.
2.  Click **Data Sources** to go to the Data Sources page.
3.  Click **Create Data Source**.
4.  Click the Cloud Data Sources tab.

## MaxCompute {#section_inm_5p5_mfb .section}

1.  Click the **MaxCompute** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950613878_en-US.png)

    -   Name: the data source name.
    -   Database Address: the default address is displayed. For modification, see [Configure Endpoint](../../../../reseller.en-US/Prepare/Configure Endpoint.md#).

        **Note:** The database address is based on the region where the database instance is deployed. For example, if you choose a classic network as the network type for your database instance that is deployed in the Hong Kong region, the database address is http://service.cn-hongkong.maxcompute.aliyun-inc.com/api. If the database instance is deployed in the Asia Pacific SE 1 \(Singapore\) region, the database address is http://service.ap-southeast-1.maxcompute.aliyun-inc.com/api. For more information, see [Configure Endpoint](../../../../reseller.en-US/Prepare/Configure Endpoint.md#).

    -   Project: the project name.
    -   AccessKey ID: the AccessKey ID.
    -   AccessKey Secret: the AccessKey Secret.
    **Note:** Make sure that the AccessKey is valid. The corresponding account is an administrator of the project, the owner of the project, or a user that has List, Select, and CreateInstance permissions.

3.  Click **Test Connection** to perform a data source connectivity test.

    **Note:** If the connection is successful, a message that indicates success is displayed.

4.  Click **Add** to add the data source.

    After the data source is added, the **Data Sources** page is redirected automatically. All tables that are contained in the data source are listed in the right section.

    MaxCompute data sources use asynchronous loading. Creating a MaxCompute data source takes one to five minutes to synchronize data.


## MySQL {#section_l1b_pq5_mfb .section}

You need to add IP addresses or security groups to the whitelist of the RDS instance in the ApsaraDB for RDS console before you add an RDS data source.

For more information, see .

1.  Click the **MySQL** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950613887_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Username: the database username.
    -   Password: the database password.
    Contact the administrator of your data warehouse if you forget the username and password.

3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

    If a data source with the same configurations exists, a message that indicates conflict is displayed. You do not need to create the same data source again.


## SQL Server {#section_rws_vq5_mfb .section}

Adding an RDS \(SQL Server\) data source is similar to adding an RDS \(MySQL\) data source. However, you need to specify the **Schema** configuration item for an RDS \(SQL Server\) data source. The default port number for an SQL Server data source is **1433**.

1.  Click the **SQL Server** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950713888_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is dbo.
    -   Username: the database username.
    -   Password: the database password.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## AnalyticDB {#section_v4y_dr5_mfb .section}

1.  Click the **AnalyticDB** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950713889_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Access ID: the AccessKey ID.
    -   Access Key: the AccessKey Secret.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## HybridDB for MySQL {#section_h4s_hr5_mfb .section}

Adding a HybridDB for MySQL data source is similar to adding a MySQL data source.

1.  Click the **HybridDB for MySQL** icon.
2.  Enter the fields for connecting to the data source.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## HybirdDB for PostgreSQL {#section_xjg_nr5_mfb .section}

Adding a HybridDB for PostgreSQL data source is similar to adding a SQL Server data source. The default port number for a HybridDB for PostgreSQL database is displayed.

1.  Click the **HybridDB for PostgreSQL** icon.
2.  Enter the fields for connecting to the data source.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## PostgreSQL {#section_zmk_rr5_mfb .section}

1.  Click the **PostgreSQL** icon.
2.  Enter the fields for connecting to the data source.
    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## PPAS {#section_s12_vr5_mfb .section}

Adding a PPAS data source is similar to adding a PostgreSQL data source.

1.  Click the **PPAS** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950713893_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## Hive \(Quick BI Enterprise Standard\) {#section_ngp_ts5_mfb .section}

If you use **Quick BI Enterprise Standard**, you can add a Hive data source.

1.  Click the **Hive** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950713894_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Username: the database username.
    -   Password: the database password.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## Data Lake Analytics \(Quick BI Pro and Quick BI Enterprise Standard\) {#section_fxf_ct5_mfb .section}

If you use **Quick BI Enterprise Standard** or **Quick BI Pro**, you can add a Data Lake Analytics data source.

1.  Click the **Data Lake Analytics** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950713895_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port: 10000
    -   Database: the database name.
    -   Access ID: the AccessKey ID.
    -   Access Key: the AccessKey Secret.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## DRDS {#section_swl_vwk_5fb .section}

If you use **Quick BI Enterprise Standard**, you can add a DRDS data source.

1.  Click the **DRDS** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/23954/155961950731893_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or the hostname of the database.
    -   Port Number: the port number.
    -   Database: the name of a database that you connect to.
    -   Username: the database username.
    -   Password: the database password.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

