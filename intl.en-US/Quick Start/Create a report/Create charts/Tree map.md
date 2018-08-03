# Tree map {#concept_q2y_4gf_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a tree map. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A matrix tree describes the relative proportions of multiple data indicators of a specific object.

A matrix tree consists of color block labels and the color block size. Color block labels are determined by the data dimension, such as the product packaging box. The color block size is determined by the data measurement, such as the transportation costs.

## Notice on creating a tree map {#section_byf_rgf_vdb .section}

Rectangle labels of a tree map can have only one dimension, and the dimension value must be smaller than or equal to 12. The rectangle size can have only one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity of different types of products.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click tree map icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **product\_type** option and add it to the rectangle label area. In the measurement list, locate the **order\_number** option and add it to the rectangle size area, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9137/15332646651803_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and legends of the tree map.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

