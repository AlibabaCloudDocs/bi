# Area charts {#concept_rvx_tyd_vdb .concept}

This topic describes the overview, examples, and deletion of an area chart.

See [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. To create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_i4z_mcg_xgb .section}

Similar to a [line chart](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md), an area chart displays the data trend and proportions.

An area chart consists of the category axis and the value axis. The category axis is the horizontal axis. The categories must be dimensions such as dates, provinces, and product types. The value axis is the vertical axis. The values must be measures such as performance indicators and order numbers.

Dimensions and measures are automatically used for the category axis and the value axis respectively in the dashboards. You only need to select fields from the Dimensions and Measures lists.

## Samples {#section_qs1_qcg_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15640459681682_en-US.png)

## Notes {#section_m23_tcg_xgb .section}

You can set at least one dimension for the category axis, and set at least one measure for the value axis. The Colors field can take only one dimension.

**Note:** You can enable the color legend only when the value axis involves one measure.

## Examples {#section_jfn_5cg_xgb .section}

Scenario: visualizes the number of orders for each product type of each province. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon for the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **Area Chart** icon and an area chart appears on the dashboard.
5.  Select dimensions and measures.

    On the Dimensions list, drag the province and product\_type fields to the Category Axis \(Dimensions\) section respectively. On the Measures list, drag the order\_amt field to the Value Axis \(Measures\) section as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15640459681679_en-US.png)

6.  Drag the **product\_type** field to the Colors \(Dimensions\) area and click **Update**.

    **Note:** You can enable the color legend only when the value axis involves one measure.

7.  On the **Style** tab page, you can configure the basic information, chart type, axes, functionality, and series settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15640459681680_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_xgp_13l_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses **Dark** as the background theme.

    **Note:** 

    -   In the Basic Information section, you can configure the chart type, such as line chart, stacked area chart, and 100% stacked area chart.
    -   To configure a hyperlink used to jump to a report or an external page, select **Show Hyperlink** and enter a name and address.
-   In the Chart Type section, you can configure whether to show labels, the position of legend, whether to display dual Y-axis, and whether to switch to a stacked area chart or a 100% stacked area chart. This example uses **100% Stacked**.

    **Note:** Select **Show Labels** to show all measure labels. Labels support Smart Display and Full Display. Assume that a chart involves many dimension values and the scroll bar is not shown in the chart. In Smart Display mode, only partial labels are displayed. In Full Display mode, all labels are displayed.

-   In the axis, you can set the title and unit of the Axis. In this example, set the title of the horizontal axis to **Province**.
-   In the Functionality section, you can configure whether to show a scroll bar.
-   In the Series Settings section, you can set measure aliases, the axis style, boundary values, and the data display format. In Series settings, change the color of the **Office** field to orange.

Click Update and the updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15640459681682_en-US.png)

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_esy_dc2_vdb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

