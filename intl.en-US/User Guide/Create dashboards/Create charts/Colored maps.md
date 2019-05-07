# Colored maps {#concept_vsg_jl2_vdb .concept}

This topic describes how to create a colored map. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_wfv_p3m_xgb .section}

Similar to [Bubble maps](reseller.en-US/User Guide/Create dashboards/Create charts/Bubble maps.md#), a colored map uses colors with different shades to present the values and distribution of data.

A colored map is based on geographic locations and color scales. Geographic locations are based on dimensions such as provinces. Color scales are based on measures such as order amounts and profit amounts.

## Examples {#section_mmc_s3m_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/155719713539618_en-US.png)

## Notes {#section_ojc_53m_xgb .section}

You can select a maximum of one dimension for geographic locations. The dimension type is required to be Geo. You need to select a minimum of one and a maximum of five measures for color scales.

For more information, see [Detailed information for regions](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Scenarios: shipping costs, order amounts, and profit amounts in multiple areas {#section_swl_v3m_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the Colored Map icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    On the Dimensions list, locate **area** and add it to the Geo Location \(Dimensions\) section. On the Measure list, locate **order\_amt**, **profit\_amt**, and **shipping\_cost** and add them to the Colorscale \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type of the area field from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15571971351720_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, legend, and value-based colors.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15571971361721_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_gnp_1jm_xgb .section}

-   In the Basic Settings section, you can configure the title, hyperlinks, and background color. This example uses **Dark** as the background color.
-   In the Layout section, you can configure the location of the legend and choose whether to show tooltips and geographic names. In this example, the legend is shown on the top of the chart and the geographic names are displayed.
-   In the Series Settings section, you can configure measure aliases, data display formats, and value ranges.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/155719713639620_en-US.png)

## Delete a chart {#section_ebx_bjm_xgb .section}

Click the **More Actions** icon and select **Delete** from the drop-down list to delete a chart.

