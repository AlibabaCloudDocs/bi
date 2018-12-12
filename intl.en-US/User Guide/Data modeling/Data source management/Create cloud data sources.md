# Create cloud data sources {#concept_tlv_gn5_mfb .concept}

Operations on datasets, workbooks, dashboards, and portals are based on data sources. This topic describes how to build a cloud data source.

Go to the data source creation page to create a cloud data source.

1.  Log on to the Quick BI console.
2.  Click **Data Sources** to go to the data source management page.
3.  Click **Create Data Source** and select a data source.
4.  Click the Cloud Database tab.

## MaxCompute {#section_inm_5p5_mfb .section}

1.  Click the **MaxCompute** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13878_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=qPDr4PFHDAZfzQILpz3Dabe7KiQ%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: You do not need to modify the default address. If you want to modify it, see [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/34951.htm).

        **Note:** The database endpoint varies with region. For example, in a classic network, the database endpoints of Hong Kong region and Singapore region are http://service.cn-hongkong.maxcompute.aliyun-inc.com/api and http://service.ap-southeast-1.maxcompute.aliyun-inc.com/api respectively. For more information, see [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/34951.htm).

    -   Project: The project name.
    -   Access ID: The AccessKey ID.
    -   Access Key: The AccessKey Secret.
    **Note:** The value of the Access Key must be valid. The corresponding account is that of the project administrator or owner, or a common user who has permissions to list, select, and create instances.

3.  Click **Test Connection**.

    **Note:** If the connection works properly, a message indicating connection success will be displayed.

4.  Click **Add** to add a data source.

    After the data source is added, the **Data Sources** tab page is automatically displayed, and all data tables under the data source are displayed in the right-side pane.

    MaxCompute data sources are asynchronously loaded and updated. If you create a MaxCompute data source for the first time, wait up to five minutes for the data synchronization.


## MySQL {#section_l1b_pq5_mfb .section}

Due to the limitations imposed by the whitelist policy of ApsaraDB for RDS, before adding an ApsaraDB for RDS data source, you must manually add related IP addresses to whitelists on the ApsaraDB for RDS console.

For more information about how to add and set a whitelist, see [Access domains and data centers](https://www.alibabacloud.com/help/doc-detail/26198.htm?spm=a2c63.p38356.a3.1.4a0c1ce4v8Eznb).

1.  Click the **MySQL** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13887_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=vYAC%2B9uJnPT7tx0Yy8Ug%2BYNBulg%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Username: The username of the database.
    -   Password: The password of the database.
    If you do not know the username or the password, contact your data warehouse administrator.

3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

    If a data source with the same configuration already exists, a prompt message will be displayed. Do not add a data source repeatedly.


## SQL Server {#section_rws_vq5_mfb .section}

You can add a data source from RDS for SQL Server in a similar way you add a data source from RDS for MySQL. The differences are that you need to add the configuration item **schema** for data sources from ApsaraDB for RDS \(SQL Server\), and the default port number of the SQL server is **1433**.

1.  Click the **SQL Server** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13888_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=hHjSGUmeYTdiGOSW2MYINZ1RCxA%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Schema: dbo.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## Analytic DB {#section_v4y_dr5_mfb .section}

1.  Click the **Analytic DB** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13889_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=5NFxdSc%2FHhrUOGQGCswvcplYcYE%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Access ID: The AccessKey ID.
    -   Access Key: The AccessKey Secret.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## HybridDB for MySQL {#section_h4s_hr5_mfb .section}

You can add a data source from HybridDB for MySQL in a similar way you add a data source from RDS for MySQL.

1.  Click the **HybridDB for MySQL** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13890_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=Lqcwl3FH4SjDgp7nBgc601yNFhE%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The default value is 3306.
    -   Database: The name of the database.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## HybirdDB for PostgreSQL {#section_xjg_nr5_mfb .section}

You can add a data source from HybridDB for PostgreSQL in a similar way you add a data source from RDS for SQL Server. The default port is the port specific to HybridDB for PostgreSQL.

1.  Click the **HybridDB for PostgreSQL** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13891_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=nT4VENDycTE1phIUKz9GVYgBpzk%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Schema: public.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## PostgreSQL {#section_zmk_rr5_mfb .section}

1.  Click the **PostgreSQL** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13892_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=9AeCsnhEzHkFi%2FBa3KWFF%2FMVrZA%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Schema: public.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## PPAS {#section_s12_vr5_mfb .section}

You can add a data source from RDS for PPAS in a similar way you add a data source from HybridDB for PostgreSQL.

1.  Click the **PPAS** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13893_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=ntgMMuiTdFnZPWrw3iM9idpibOo%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Schema: public.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

## Hive \(for Quick BI Professional\) {#section_ngp_ts5_mfb .section}

If you have purchased **Quick BI Professional**, you can add a Hive data source.

1.  Click the **Hive** icon.
2.  Specify the parameters required for data source connection as follows:

    ![](http://icms-static-translation.oss-cn-hangzhou.aliyuncs.com/SP_78/DNQBI11855835/images/13894_zh-CN.png?Expires=1541233986&OSSAccessKeyId=LTAIJfoPL6wmrirR&Signature=4pDhf%2FDJnAas92CKqnjnq%2F9tg4A%3D)

    -   Name: The display name in the data source list.
    -   Database Endpoint: The host name or IP address.
    -   Port: The port number.
    -   Database: The name of the database.
    -   Username: The username of the database.
    -   Password: The password of the database.
3.  Click **Test Connection**.
4.  Click **Add** to add a data source.

