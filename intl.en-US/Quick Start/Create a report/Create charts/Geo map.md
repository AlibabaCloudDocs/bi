# Geo map {#concept_vsg_jl2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a geo map.  If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

Similar to a [Geo bubble](intl.en-US/Quick Start/Create a report/Create charts/Geo bubble.md#), a geo map uses different colors to demonstrate the data values and ranges.

A Geo map consists of a geological region and a color saturation. The geological region is determined by the data dimension, such as a province. The color saturation is determined by the data measurement, such as an order amount or a profit amount.

## Notice on creating a geo map {#section_ilk_ll2_vdb .section}

You can set only one dimension for the geological region of a color map, and the dimension type must be of geological information. Set at least one color saturation and a maximum of five measurements.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the transportation costs, order amounts, and profit amounts of multiple regions.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click Geo map icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area** option and add it to the location area. In the measurement list, locate the **order\_amt**, **profit\_amount**, and **shipping\_cost** options and add them to the colorscale area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15332638481720_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and legend of the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

