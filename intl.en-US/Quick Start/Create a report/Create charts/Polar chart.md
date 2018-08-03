# Polar chart {#concept_wby_whf_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a polar chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A polar chart can be used to show data changes in a period of time or comparison between multiple items. Polar charts apply to enumerated values, for example, comparison between data of different regions.

Similar to a Pie chart, a polar chart consists of multiple slices. The label of each slice is determined by the data dimension, such as the region or product type. The length of each slice is determined by the data measurement, such as the order quantity or order amount.

## Notice on creating a polar chart {#section_p5q_yhf_vdb .section}

Slice labels of a polar chart can have only one dimension, and the number of dimension members must be greater than 3 and smaller than or equal to 12. The slice length can have only one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity of different regions. \(The number of regions must be greater than three and smaller than or equal to 12.\)**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click polar chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area** option and add it to the slice label area. In the measurement list, locate the **order\_number** option, and add it to the arc radius area, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15332647451816_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can change the title and legends of the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

