# Colored maps {#concept_vsg_jl2_vdb .concept}

This topic describes the overview, examples, and deletion of a colored map.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_wfv_p3m_xgb .section}

Similar to a [Bubble map](reseller.en-US/User Guide/Create dashboards/Create charts/Bubble maps.md#), a colored map shows the size and distribution of data by using shades of color.

A colored map consists of color scales and geographic locations. Geographic locations are based on dimensions such as provinces. Color scales are based on measures such as order amounts and profit amounts.

## Samples {#section_mmc_s3m_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/156404624139618_en-US.png)

## Notes {#section_ojc_53m_xgb .section}

You can select a maximum of one dimension for geographic locations. The dimension type is required to be Geo. You need to select a minimum of one and a maximum of five measures for color scales.

## Examples {#section_swl_v3m_xgb .section}

Scenarios: compares the shipping costs, order amounts, and profit amounts in multiple areas. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the Colored Map icon and an empty chart appears.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, select **area** and add it to Geo Location \(Dimensions\). In the Measures list, select **order\_amt**, **profit\_amt**, and **shipping\_cost**, and add them to Colorscale \(Measures\), as shown in the following figure:

    **Note:** Make sure that you have converted the dimension type from String to Geo for the area dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15640462421720_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, legend, and value-based colors.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15640462421721_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_gnp_1jm_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses **Dark** as the background color.

    **Note:** To jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Layout section, you can configure the legend position, whether to show tooltips, and whether to show geo names. This example uses Top as the legend position shows geo names.
-   In the Series Settings section, you can configure measures' aliases, data display formats, and value ranges.

Click Update and the updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/156404624239620_en-US.png)

## Delete a chart {#section_ebx_bjm_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

