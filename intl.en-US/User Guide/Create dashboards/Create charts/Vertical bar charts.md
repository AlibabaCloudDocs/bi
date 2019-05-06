# Vertical bar charts {#concept_bnq_fd2_vdb .concept}

This topic describes how to create a vertical bar chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_a4v_1jl_xgb .section}

A vertical bar chart shows comparisons among discrete categories. You can use a vertical bar chart to visualize data changes over a period of time or comparisons among discrete categories. For example, you can show the comparison of the traffic flow of vehicles over different periods of time at a crossing.

Like [Line charts](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md#), a vertical bar chart consists of the category axis and the value axis.

## Examples {#section_ywl_djl_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15571396931689_en-US.png)

## Notes {#section_oj5_fjl_xgb .section}

You can set at least one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Color Legend \(Dimensions\) section can take only one dimension.

**Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

## Scenarios: the shipping cost for different products of provinces of East China {#section_vfq_hjl_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the **Vertical Bar Chart** icon and an empty chart appears on the dashboard.
5.  On the Dimensions list, locate **area** and add it to the Filters section.

    You can search for the East China area by using filters as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15571396931685_en-US.png)

6.  Click the **Filter** icon. Select **Filter by Value** in the Set Filter dialog box that appears as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/155713969311401_en-US.png)

7.  Select East China and click **OK**.
8.  Drag **province** and **product\_type** to the Category Axis \(Dimensions\) section.

    **Note:** Makes sure that you have converted the dimension type of the province field from String to Geo.

9.  On the Measures list, drag **shipping\_cost** to the Value Axis \(Measures\) area.
10. Drag **product\_type** to the Color Legend \(Dimensions\) section.

    **Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

11. Click **Update** and the chart is updated.
12. On the Style tab page, you can configure the chart title, layout, legend, and axis style.
13. Click **Save** to save the dashboard.

## Configure the style {#section_zdf_sjl_xgb .section}

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_okw_sjl_xgb .section}

Click the **More Actions** icon and select **Delete** from the drop-down list to delete a chart.

