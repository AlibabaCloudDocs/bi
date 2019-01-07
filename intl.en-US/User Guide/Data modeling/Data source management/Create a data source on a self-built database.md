# Create a data source from external database {#concept_fqx_5lq_5db .concept}

This section describes how to create a data source from external database.

## MySQL {#section_g4w_zlq_5db .section}

1.  Log on to Quick BI console.
2.  Click **Data Sources**. The data source management page is displayed.
3.  Click**Create data source** \> **From External Database** \> **MySQL**
4.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342851304_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port: Default 3306
    -   Database: Connection database name
    -   User name: corresponding user name
    -   Password: The password of the database.
5.  Click **Test Connection** to perform the data source connectivity test.
6.  Click Add to complete the data source add.

You must enable the ECS firewall to enable external accesses to MySQL.

1.  Run the following command to access the firewall configuration file:

    `vi /etc/sysconfig/iptables`

2.  Add the following command to the firewall configuration file.

    ```
    -A RH-Firewall-1-INPUT -m state –state NEW -m tcp -p tcp –dport 3306 -j
                ACCEPT
    ```

3.  After the configuration succeeds, restart iptable.

    `service iptables restart`


## SQL Server {#section_u4k_lmq_5db .section}

1.  Click **SQL Server**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342856169_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port: Default 1433
    -   Database: Connection database name
    -   Schema: dbo
    -   User name: corresponding user name
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click Add to complete the data source add.

## PostgreSQL {#section_y3k_rmq_5db .section}

1.  Click **PostgreSQL**.
2.  Enter the required information for connecting to a data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342856170_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port: Default 5432
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click Add to complete the data source add.

## Oracle {#section_hjb_wmq_5db .section}

1.  Click **Oracle**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342851307_en-US.png)

    -   Display name: list of data sources display name
    -   Database Address: Enter the host name or IP address.
    -   Port: Default 1521
    -   Database: Name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click **Add**. The data source is added.

## Hive \(Quick BI Pro\) {#section_gbh_1nq_5db .section}

If you are using the Quick BI professional, you can add Hive data source.

1.  Click **Hive**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342851308_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port: Just fill in the correct port number
    -   Database: Connection database name
    -   User name: Corresponding user name
    -   Password: Corresponding Password
3.  If you need to accelerate your Hive data source, enter the following data source acceleration information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342851309_en-US.png)

    -   hiveMetastoreUri: The address of Hive metadata.
4.  Click Connect tests to perform a data source connectivity test.
5.  Click Add to complete the data source add.

## Vertica \(Quick BI Pro\) {#section_vmf_kh5_j2b .section}

If you are using Quick BI professional, you can also add a Vertica data source.

1.  Click **Vertica**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342856839_en-US.png)

    -   Display name: List of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port Number: Default 5433
    -   Database: The name of the database to be connected to.
    -   Schema: public
    -   User Name: The user name of the database.
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click Add to complete the data source add.

## IBM DB2 LUW \(Quick BI Pro\) {#section_j2w_xk5_j2b .section}

If you are using Quick BI professional, you can also add an IBM DB2 LUW data source.

1.  Click **IBM DB2 LUW**.
2.  Enter the required data source connection information, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9085/15468342856841_en-US.png)

    -   Display name: list of data sources display name
    -   Database address: Just fill in the host name or IP address.
    -   Port Number: Default 50000
    -   Database: Connection database name
    -   Schema: DB2INST1
    -   User name: Corresponding user name
    -   Password: The password of the database.
3.  Click **Test Connection** to perform the data source connectivity test.
4.  Click Add to complete the data source add.

