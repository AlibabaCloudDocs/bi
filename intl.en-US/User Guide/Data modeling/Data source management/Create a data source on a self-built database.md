# Create a data source on a self-built database {#concept_fqx_5lq_5db .concept}

This section describes how to create a data source on a self-built database.

## MySQL {#section_g4w_zlq_5db .section}

1.  Log on to the Quick BI console.
2.  Click **Data Source** to enter the Data Sources page.
3.  Select**Create Data Sources** \> **Self-built data source** \> **MySQL**
4.  Enter the connection information of a data source as the following figure shows.

    **Note:** If the data source that you add is created by yourself on an ECS instance in a VPC network, you must select the Ecs \(vpc\) self-built data source check box.

    ![](images/11380_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 3306.
    -   Database: the name of a database that you connect to.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
    -   Buyer accessId: the accessId of a user that purchases the instance.
    -   Buyer accessKey: the accessKey that is associated with the accessId.
    -   Ecs instance id: the ID of the instance.
    -   Ecs area: the region that hosts the instance.
5.  Click **Test Connection** to perform a data source connectivity test.
6.  Click **Add** to add a data source.

You need to open a port on the firewall of a host to allow external users to access your self-built MySQL database on the host.

1.  Open the configuration file of a firewall by executing the following command.

    `vi /etc/sysconfig/iptables`

2.  Add the following command to the configuration file.

    ```
    -A RH-Firewall-1-INPUT -m state –state NEW -m tcp -p tcp –dport 3306 -j
                ACCEPT
    ```

3.  Restart the iptables service after the configuration.

    `service iptables restart`


## SQL Server {#section_u4k_lmq_5db .section}

1.  Click the **SQL Server** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    **Note:** If the data source that you add is created by yourself on an ECS instance in a VPC network, you must select the Ecs \(vpc\) self-built data source check box.

    ![](images/11381_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 1433.
    -   Database: the name of a database that you connect to.
    -   Schema: dbo.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
    -   Buyer accessId: the accessId of a user that purchases the instance.
    -   Buyer accessKey: the accessKey that is associated with the accessId.
    -   Ecs instance id: the ID of the instance.
    -   Ecs area: the region that hosts the instance.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## PostgreSQL {#section_y3k_rmq_5db .section}

1.  Click the **PostgreSQL** icon.
2.  Enter the required connection information of a data source as the following figure shows.

     

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 5432.
    -   Database: the name of a database that you connect to.
    -   Schema: public.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## Oracle {#section_hjb_wmq_5db .section}

1.  Click the **Oracle** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](images/11383_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 1521.
    -   Database: the name of a database that you connect to.
    -   Schema: public.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## Hive \(Quick BI Enterprise\) {#section_gbh_1nq_5db .section}

If you are using **Quick BI Enterprise**, you can add a Hive data source.

1.  Click the **Hive** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](images/11384_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: a proper port number.
    -   Database: the name of a database that you connect to.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
    -   hiveMetastoreUri: the URI that is used to store Hive metadata.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## Vertica \(Quick BI Enterprise\) {#section_vmf_kh5_j2b .section}

If you are using **Quick BI Enterprise**, you can add a Vertica data source.

1.  Click the **Vertica** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15502170906839_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 5433.
    -   Database: the name of a database that you connect to.
    -   Schema: public.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## IBM DB2 LUW \(Quick BI Enterprise\) {#section_j2w_xk5_j2b .section}

If you are using **Quick BI Enterprise**, you can add an IBM DB2 LUW data source.

1.  Click the **IBM DB2 LUW** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15502170906841_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: The default value is 50000.
    -   Database: the name of a database that you connect to.
    -   Schema: DB2INST1.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## SAP IQ \(Sybase IQ\) \(Quick BI Professional Edition） {#section_frd_2mf_1fb .section}

If you are using **Quick BI Professional Edition**, you can add an SAP IQ \(Sybase IQ\) data source.

1.  Click the **SAP IQ\(Sybase IQ\)** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](images/11189_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: 2638.
    -   Database: the name of a database that you connect to.
    -   Schema: sybase.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

## SAP HANA \(Quick BI Professional Edition\) {#section_vwz_cnf_1fb .section}

If you are using **Quick BI Professional Edition**, you can add an SAP HANA data source.

1.  Click the **SAP HANA** icon.
2.  Enter the required connection information of a data source as the following figure shows.

    ![](images/11190_en-US.png)

    -   Name: the name of a data source.
    -   Database Endpoint: a hostname or an IP address.
    -   Port: 30015.
    -   Database: the name of a database that you connect to.
    -   Schema: public.
    -   Username: the username that is used to access a database.
    -   Password: the password that is associated with the username.
3.  Click **Test Connection** to perform a data source connectivity test.
4.  Click **Add** to add a data source.

