# Vertical bar charts {#concept_bnq_fd2_vdb .concept}

This topic describes the overview, examples, and deletion of a vertical bar chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_a4v_1jl_xgb .section}

A vertical bar chart shows comparisons among discrete categories. You can use a vertical bar chart to visualize data changes over a period of time or comparisons among discrete categories. For example, you can show the comparison of the traffic flow of vehicles over different periods of time at a crossing.

Similar to a [line chart](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md#), a vertical bar chart is based on the category axis and value axis.

## Samples {#section_ywl_djl_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15640460081689_en-US.png)

## Notes {#section_oj5_fjl_xgb .section}

You can set at least one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Color Legend \(Dimensions\) section can take only one dimension.

**Note:** You can enable the color legend only when the value axis involves one measure.

## Examples {#section_vfq_hjl_xgb .section}

Scenario: compares the shipping cost for different products of provinces of East China. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **Vertical Bar Chart** icon and an empty chart appears on the dashboard.
5.  On the Dimensions list, locate the **area** field and add it to the Filters section.

    East China is filtered by using the area filter as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15640460081685_en-US.png)

6.  Click the **Filter** icon and select **Filter by Value** in the dialog box that appears as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/156404600911401_en-US.png)

7.  Select East China and click **OK**.
8.  Drag **province** and **product\_type** to the Category Axis \(Dimensions\) area in turn.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

9.  On the Measures list, drag **shipping\_cost** to the Value Axis \(Measures\) area.
10. Drag **product\_type** to the Colors \(Dimensions\) area.

    **Note:** You can enable the color legend only when the value axis involves one measure.

11. Click **Update** to update the chart.
12. On the Style tab page, you can configure the basic information, chart type, axes, functionality, and series settings.
13. Click **Save** to save the dashboard.

## Configure the style {#section_zdf_sjl_xgb .section}

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_okw_sjl_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

