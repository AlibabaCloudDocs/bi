# Radar chart {#concept_xkk_b42_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a radar chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A radar chart can be used to show analyzed numbers or ratios. People can intuitively know the changes and trend of each indicator. For example, you can use a radar chart to show the sales of each region.

A radar chart consists of branch labels and the branch length. Radius labels are determined by the data dimension, such as the product type. The radius is determined by the data measurement, such as the shipping costs.

## Notice on creating a radar chart {#section_xbs_d42_vdb .section}

Branch labels of a radar chart have one to two dimensions, and a dimension value must be greater than three and smaller than or equal to 12. The branch length must have at least one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity and order amount of different regions.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click radar chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area** option and add it to the radius label area. In the measurement list, locate the **order\_amt** and **order\_number** options, and add them to the radius area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/15332643311744_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the **Style** tab, you can edit the title, layout, and legends of the radar chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

