# Line charts {#concept_mrr_y1z_5db .concept}

This topic describes how to create a line chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_zmq_jrf_xgb .section}

A line chart presents the changing trend of data through broken lines and shows continuous data that changes over time. Line charts are useful for analyzing and showing data trends at equal intervals. Line charts are also used for analyzing the interactions among multiple groups of data that change over time. For example, analyzing the sales volume of a certain product or related products for the prediction of future sales.

A line chart is based on the category axis and the value axis. The category axis is the horizontal axis. The categories are required to be dimensions such as dates, provinces, and product types. The value axis is the vertical axis. The values are required to be measures such as performance indicators and order numbers.

Dimensions and measures are automatically used for the category axis and the value axis respectively in the dashboards. You only need to select fields from the Dimensions and Measures lists.

## Examples {#section_smq_qrf_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/155710965844560_en-US.png)

## Notes {#section_nvf_vrf_xgb .section}

You need to select at least one dimension for the category axis and at least one measure for the value axis. The color legend supports up to one dimension.

**Note:** You can enable the color legend only when the value axis involves one measure.

## Scenarios: order numbers and unit prices of multiple products {#section_jb5_wrf_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon for the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the **Line Chart** icon and an empty line chart appears on the dashboard.
5.  Select dimensions and measures.

    In the Dimensions list, locate **product\_type** and add it to the Category Axis \(Dimensions\) section. In the Measures list, locate **order\_number** and **price** and add them to the Value Axis \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [EN-US\_TP\_9077.md\#](reseller.en-US/Quick Start/Create a report/Create dashboards.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/15571096581589_en-US.png)

6.  On the Style tab page, you can configure the basic settings, style, layout, axes, and series settings for a chart.
7.  Click **Save** to save the dashboard.

## Configure the style {#section_okn_fsf_xgb .section}

For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_t4w_ssf_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

