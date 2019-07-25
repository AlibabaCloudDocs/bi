# Line charts {#concept_mrr_y1z_5db .concept}

This topic describes the overview, examples, and deletion of a line chart.

See [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. To create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_zmq_jrf_xgb .section}

A line chart presents the changing trend of data through broken lines and shows continuous data that changes over time. Line charts are useful for analyzing and showing data trends at equal intervals. Line charts are also used for analyzing the interactions among multiple groups of data that change over time. For example, analyzing the sales volume of a certain product or related products to predict future sales.

A line chart is based on the category axis and the value axis. The category axis is the horizontal axis. The categories must be dimensions such as dates, provinces, and product types. The value axis is the vertical axis. The values must be measures such as performance indicators and order numbers.

Dimensions and measures are automatically used for the category axis and the value axis respectively in the dashboards. You only need to select fields from the Dimensions and Measures lists.

## Samples {#section_smq_qrf_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/156404587844560_en-US.png)

## Notes {#section_nvf_vrf_xgb .section}

You need to select at least one dimension for the category axis and at least one measure for the value axis. The color legend supports up to one dimension.

**Note:** You can enable the color legend only when the value axis involves one measure.

## Examples {#section_jb5_wrf_xgb .section}

Scenario: displays order numbers and unit prices of multiple products. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon for the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **Line Chart** icon and an empty line chart appears on the dashboard.
5.  Select dimensions and measures.

    On the Dimensions list, locate the **product\_type** field and add it to the Category Axis \(Dimensions\) section. On the Measures list, locate the **order\_number** and **price** fields and add them to the Value Axis \(Measures\) section respectively.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/15640458781589_en-US.png)

6.  On the Style tab page, you can configure the basic information, chart type, axes, functionality, and series settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/15640458781592_en-US.png)

7.  Click **Save** to save the dashboard.

## Configure the style {#section_okn_fsf_xgb .section}

-   In the Basic Settings section, you can configure the chart title, enable the hyperlink for page jumping, change the chart background color, and switch the chart type. This example uses **Dark** as the background theme.

    **Note:** To configure a hyperlink used to jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Chart Type section, you can configure whether to show labels, line style, the position of legend, and whether to display dual Y-axis. This example uses **Dual Y-Axis** and shows labels.

    **Note:** Select **Show Labels** to show all measure labels. Labels support Smart Display and Full Display. Assume that a chart involves many dimension values and the scroll bar is not shown in the chart. In Smart Display mode, only partial labels are displayed. In Full Display mode, all labels are displayed.

-   You can set the titles and units for the axes. This example uses **Product Type** as the title for the horizontal axis.
-   In the Functionality section, you can configure whether to show a scroll bar.
-   In the Series Settings section, you can set measure aliases, the axis style, boundary values, and the data display format. This example uses blue as the line color for the **price** measure.

Click Update and the updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/15640458781594_en-US.png)

For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_t4w_ssf_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

