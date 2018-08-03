# Scatter chart {#concept_w3v_cp2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a scatter chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A scatter chart shows distribution and convergence of data.

A scatter chart consists of the X axis and Y axis. Color legends of a scatter chart are determined by the data dimension, such as the product type. The X axis and Y axis are determined by the data measurements.

## Notice on creating a scatter chart {#section_nqt_2p2_vdb .section}

Color legends of a scatter chart can have only one dimension, and the maximum number of dimension members is 1000.

X axis: Has one to three measurements.

Y axis: Has only one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the unit price and order quantity of different types of product.Scenario example: unit price and order quantity for different types of products.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click scatter chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **product\_type** option, and add it to the color legend area. In the measurement list, locate the **price** and **order\_number** options, and add them to the Y axis and X axis in sequence, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/15332644081750_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title, layout, and legends of the scatter chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

