# Area charts {#concept_rvx_tyd_vdb .concept}

Assume that you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create an area chart. If you want to edit a dataset or create a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

An area chart displays graphically quantitative data. You can use an area chart to analyze and visualize a trend in data over identical intervals of time. In addition, you can use an area chart to analyze the interactions between multiple groups of data that changes over time. For example, you can analyze the sales volume of a group of products or multiple groups of products that change over time to obtain a forecast of sales trends.

An area chart consists of the category axis and the value axis. The category axis is depicted as horizontal and oriented to the right. You can only add dimensions to the category axis such as date, province, and product\_type. The value axis is depicted as vertical and oriented upwards. You can only add measures to the value axis such as metrics for analyzing objects including order\_amt.

In a dashboard, fields have been automatically grouped into dimensions and measures as the following figure shows. When you create a line chart, you can drag fields from the Dimensions list and the Measures list to the corresponding category axis and value axis as required.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15447735771677_en-US.png)

## Precautions {#section_esy_dc2_vdb .section}

You can set at least one dimension for the category axis, and set at least one measure for the value axis. The Colors field can take only one dimension.

**Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

The following scenario uses the company\_sales\_record dataset.

**Scenario: Visualize the number of orders for each product type of each province.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click the **Create Dashboard** icon next to the company\_sales\_record dataset.
4.  Click the **Area** icon, an area chart appears in the display area of the dashboard.
5.  Select required dimensions and measures.

    On the Dimensions list, drag the province and product\_type fields to the Category Axis \(Dimensions\) area in turn. On the Measures list, drag the order\_amt field to the Value Axis \(Measures\) area as the following figure shows.

    **Note:** You must ensure that you have changed the province field from the string type to the location type. For more information about how to change data types of a dimension, see [Example: Create a dashboard](intl.en-US/Quick Start/Example: Create a dashboard.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15447735771679_en-US.png)

6.  Drag the **product\_type** field to the Colors \(Dimensions\) area and click **Update**.

    **Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

7.  On the **Style** tab, you can change some items such as the title, layout, legend, and axis format of a chart as the following figure shows.

    **Note:** For more information about the Style tab, see [Configure a chart](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Configure a chart.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15447735781680_en-US.png)

    -   In General config, select **Dark** as the background color.
    -   In Style, select **Secondary Y Axis**.
    -   In Layout, select **Right** to show the legend.
    -   In Axis, enter **province** in the Axis title field.
    -   In Series settings, change the color of the **Office** field to orange.
    After you complete the configuration, the chart is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15447735781682_en-US.png)

8.  Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the upper-right corner of the chart and select **Delete**.

