# Line charts {#concept_mrr_y1z_5db .concept}

Assume that you have read [Dashboard overview](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create a line chart. If you want to edit a dataset or create a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A line chart displays information as a series of data points connected by straight line segments. You can use a line chart to analyze and visualize a trend in data over equal intervals of time. In addition, you can use a line chart to analyze the correlation between multiple groups of data that changes over time. For example, you can analyze the sales volume of a group of products or multiple groups of products that change over time to obtain a forecast of sales trends.

A line chart consists of the category axis and the value axis. The category axis appears as a horizontal axis and oriented to the right. You can only add dimensions to the category axis such as date, province, and product\_type. The value axis appears as a vertical axis and oriented upwards. You must add measures to the value axis such as metrics for analyzing objects including order\_amt.

In a dashboard, fields have been automatically sorted into dimensions and measures as shown in the following figure. When you create a line chart, you can drag fields from the Dimensions list and the Measures list to the corresponding category axis and value axis as required.

## Precautions {#section_tvz_dbz_5db .section}

Select at least one dimension on the category axis and select at least one measure on the value axis. The Colors \(Dimensions\) area can take only one dimension at most.

**Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

The following scenario is based on the company\_sales\_record dataset.

**Scenario: Visualize the number of orders and price for each product category.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.
4.  Click the **Line** icon, a line chart appears in the display area of the dashboard.
5.  Select required dimensions and measures.

    On the Dimension list, drag **product\_type** to the Category Axis \(Dimensions\) area. On the Measures list, drag **order\_amt** and **price** to the Value Axis \(Measures\) area in turn as shown in the following figure.

    **Note:** You must ensure that you have changed the province field from the string type to the location type. For more information about how to change data types of a dimension, see [EN-US\_TP\_9077.md\#](intl.en-US/Quick Start/Create a report/Create dashboards.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/15566035031589_en-US.png)

6.  On the Style tab, you can change some items such as the title, layout, legend, and axis format of a chart.

    **Note:** For more information about the Style tab, see [EN-US\_TP\_9114.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

7.  Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the upper-right corner of the chart and select **Delete** to delete the current chart.

