# Create a user-created data source {#concept_fqx_5lq_5db .concept}

This topic describes how to create a user-created data source. You can access all data sources that are created in Quick BI Enterprise Standard by using SSH tunnels.

## MySQL {#section_g4w_zlq_5db .section}

1.  Log on to the Quick BI console.
2.  Click **Data Sources** to go to the Data Sources page.
3.  Choose **Create Data Source** \> **User-created Data Sources** \> **MySQL**
4.  Enter the fields for connecting to the data source as shown in the following figure.

    **Note:** Select ECS \(VPC\) User-created Data Source and enter the required fields when you connect to an ECS \(VPC\) user-created data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511380_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 3306.
    -   Database: the database name.
    -   Username: the database username.
    -   Password: the database password.
    -   AccessKey ID: the AccessKey ID for the account that purchased the ECS instance for housing the database.
    -   AccessKey Secret: the AccessKey Secret.
    -   Instance ID: the ECS instance ID.
    -   ECS Instance Region: the region location ID of the ECS instance.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
5.  Click **Test Connection** to perform a data source connectivity test.
6.  Click **Add** to add the data source.

You need to remove the firewall of the user-created database for allowing users to access MySQL through the Internet.

1.  Run the following command to open the configuration file for the firewall.

    `vi /etc/sysconfig/iptables`

2.  Add the following command to the configuration file.

    ```
    -A RH-Firewall-1-INPUT -m state –state NEW -m tcp -p tcp –dport 3306 -j
                ACCEPT
    ```

3.  Restart iptables.

    `service iptables restart`


## SQL Server {#section_u4k_lmq_5db .section}

1.  Click the **SQL Server** icon.
2.  Enter the fields for connecting to the data source as shown in the following figure.

    **Note:** Select ECS \(VPC\) User-created Data Source and enter the required fields when you connect to an ECS \(VPC\) user-created data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511381_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 1433.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is dbo.
    -   Username: the database username.
    -   Password: the database password.
    -   AccessKey ID: the AccessKey ID for the account that purchased the ECS instance for housing the database.
    -   AccessKey Secret: the AccessKey Secret.
    -   Instance ID: the ECS instance ID.
    -   ECS Instance Region: the region location ID of the ECS instance.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## PostgreSQL {#section_y3k_rmq_5db .section}

1.  Click the **PostgreSQL** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511382_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 5432.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    **Note:** After you select ssh, interactive query services that are provided by MaxCompute Lightning are supported.

3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## Oracle {#section_hjb_wmq_5db .section}

1.  Click the **Oracle** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511383_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 1521.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## Hive \(Quick BI Enterprise Standard\) {#section_gbh_1nq_5db .section}

If you use **Quick BI Enterprise Standard**, you can add a Hive data source.

1.  Click the **Hive** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511384_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number.
    -   Database: the database name.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## Vertica \(Quick BI Standard\) {#section_vmf_kh5_j2b .section}

If you use **Quick BI Enterprise Standard**, you can add a Vertica data source.

1.  Click the **Vertica** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15566125256839_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 5433.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## IBM DB2 LUW \(Quick BI Enterprise Standard\) {#section_j2w_xk5_j2b .section}

If you use **Quick BI Enterprise Standard**, you can add an IBM DB2 LUW data source.

1.  Click the **IBM DB2 LUW** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15566125256841_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 50000.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is DB2INST1.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## SAP IQ \(Sybase IQ\) \(Quick BI Enterprise Standard） {#section_frd_2mf_1fb .section}

If you use **Quick BI Enterprise Standard**, you can add an SAP IQ \(Sybase IQ\) data source.

1.  Click the **SAP IQ\(Sybase IQ\)** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511189_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 2638.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is sybase.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

## SAP HANA \(Quick BI Enterprise Standard\) {#section_vwz_cnf_1fb .section}

If you use **Quick BI Enterprise Standard**, you can add an SAP HANA data source.

1.  Click the **SAP HANA** icon.
2.  Enter the fields for connecting to the data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/155661252511190_en-US.png)

    -   Name: the data source name.
    -   Database Address: the IP address or hostname of the database.
    -   Port Number: the port number. The default port number is 30015.
    -   Database: the database name.
    -   Schema: the database schema. The default schema is public.
    -   Username: the database username.
    -   Password: the database password.
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
    -   \[DO NOT TRANSLATE\]
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add the data source.

