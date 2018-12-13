# Synchronize data sources {#concept_glq_12r_5db .concept}

In the Personal Space of Quick BI, you can synchronize MaxCompute and MySQL data sources to Exploration Space.

1.  On the Data Sources page, click **Import Data**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9089/15446676841315_en-US.png)

2.  Select a MaxCompute data source or a MySQL data source.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9089/15446676841316_en-US.png)

    **Note:** 

    -   You must add the following IP addresses to the RDS whitelist before synchronizing the MySQL data source.

        11.193.158.0/24,11.193.162.0/24,47.74.161.0/24,47.74.162.0/24

    -   You must switch to a classic network to synchronize MySQL data sources. A VPC network does not support the synchronization of MySQL data sources.
    -   This function is a one-time synchronization. If the data source is updated, you must synchronize the data source again.

