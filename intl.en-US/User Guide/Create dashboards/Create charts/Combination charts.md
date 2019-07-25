# Combination charts {#concept_z1t_gsn_jhb .concept}

Combination charts are a new chart type that is used for combining basic charts. This topic describes how to use a combination chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_a4v_1jl_xgb .section}

A combination chart displays data of different magnitudes by using dual y-axis. Multiple chart types \(line chart, vertical bar chart, and area chart\) and stack modes \(stacked and 100% stacked\) can be displayed within a combination chart.

A combination chart is based on the category axis, primary value axis, and secondary value axis.

## Samples {#section_ywl_djl_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/156253/156404605144222_en-US.png)

## Notes {#section_oj5_fjl_xgb .section}

You can select a minimum of one dimension, such as report date \(year\), for the category axis. You can select a minimum of one measure, such as order\_amt and profit\_amt, for the primary value axis and secondary value axis. You can select a maximum of one dimension for the color legend.

**Note:** You can enable the color legend only when the value axis involves one measure.

## Scenario: compares the order amounts and profit amounts over multiple years. {#section_vfq_hjl_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **Combination Chart** icon and an empty chart appears on the dashboard.
5.  On the Dimensions list, locate the **report\_date \(year\)** field and add it to the Category Axis \(Dimensions\) section.
6.  On the Measures list, locate the **order\_amt** and **profit\_amt** fields and add them to the Primary Measures and Secondary Measures sections respectively.

    **Note:** You can select vertical bar chart, line chart, or area chart as the chart type for the primary value axis or secondary value axis by clicking the chart type icon.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/156253/156404605144220_en-US.png)

    You can select the stack mode by clicking the stack mode icon.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/156253/156404605144221_en-US.png)

7.  Click **Update** and the chart is updated.
8.  On the Style tab page, you can configure the basic information, chart type, axes, functionality, and series settings.
9.  Click **Save** to save the dashboard.

## Configure the style {#section_zdf_sjl_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses **Dark** as the background color.

    **Note:** To jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Chart Type section, you can configure the labels, chart direction, line style, and legend position.

    **Note:** Select **Show Labels** to show all measure labels. Labels support Smart Display and Full Display modes. Assume that a chart involves many dimension values and the scroll bar is not shown in the chart. In the Smart Display mode, only partial labels are displayed. In Full Display mode, all labels are displayed.

-   In the Axes section, you can configure axis titles and units. In this example, **Show Scale** is selected for the x-axis.
-   In the Functionality section, you can configure whether to show the scroll bar.
-   In the Series Settings section, you can set measures' aliases, boundary values, and data display formats.

Click Update and the updated chart is shown as follows.

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_okw_sjl_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

