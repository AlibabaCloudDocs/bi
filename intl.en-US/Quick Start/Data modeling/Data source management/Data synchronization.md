# Data synchronization {#concept_glq_12r_5db .concept}

In the personal workspace, the Quick BI supports synchronizing data sources of MaxCompute and MySQL to the explore space.

1.  In the Data Sources page, click **Import Data** button.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9089/15342220021315_en-US.png)

2.  Click drop-down arrow, and select a data source \(MaxCompute or MySQL\).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9089/15342220021316_en-US.png)

    **Note:** 

    -   You must add the following IP addresses to the RDS whitelist when synchronizing the MySQL data source.

        10.152.69.0/24,10.153.136.0/24,10.143.32.0/24,120.27.160.26,10.46.67.156,120.27.160.81,10.46.64.81,121.43.110.160,10.117.39.238,121.43.112.137,10.117.28.203,118.178.84.74,10.27.63.41,118.178.56.228,10.27.63.60,118.178.59.233,10.27.63.38,118.178.142.154,10.27.63.15,100.64.0.0/8,10.151.99.0/24

    -   You must switch to the classic network to synchronize the MySQL data sources. The VPC network does not support the synchronization.
    -   This function is a one-time synchronization. If the data source is updated, you must synchronize the data source again.

