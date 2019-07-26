# Configure the collection of metrics {#concept_183307 .concept}

You need to configure the collection of metrics on the Edit page of a dashboard. Only metrics with hourly, daily, and monthly granularities can be collected.

1.  On the Edit page of a dashboard, select the kanban that displays the metric to be monitored.
2.  Click the **More Actions** icon in the right corner of the kanban and select **Collect Metric** from the More drop-down list.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/157090/156410586244312_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/157090/156410586244313_en-US.png)

3.  In the **Configure Metric Collection** dialog box, enter a name, update time, and date/time dimension for the monitored metric. Update time is when an email notification is sent.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/157090/156410586244314_en-US.png)

    **Note:** 

    -   If the type of a kanban dimension is not date/time, you can associate the kanban with a filter bar. Fields with hourly, daily, and monthly granularities in the filter bar can be set as date/time dimensions that are used for metric collection.
    -   If the type of a kanban dimension is date/time, the dimension is used for metric collection by default. If the type of a kanban dimension is not date/time and the kanban is associated with a filter bar, then a date/time field is used for metric collection by default. The date/time field with the smallest granularity is used when multiple date/time fields are in the filter bar.
    -   Do not change the date/time dimension that is displayed by default.
4.  Click **OK**.

After configuring the collection of metrics, the Metrics page is redirected.

