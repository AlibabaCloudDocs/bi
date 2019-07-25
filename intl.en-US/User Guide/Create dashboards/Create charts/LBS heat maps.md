# LBS heat maps {#concept_brr_dnf_vdb .concept}

This topic describes the overview, examples, and deletion of an LBS heat map.

**Note:** LBS heat maps only apply to **Quick BI Enterprise Standard**.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mcg_3qs_xgb .section}

Similar to a [colored map](reseller.en-US/User Guide/Create dashboards/Create charts/Colored maps.md#), an LBS heat map represents the size and distribution of data by using different shades of location dots.

An LBS heat map is based on geographic locations and heat intensity. Geographic locations are determined by Geo type dimensions such as the province. Heat intensity is determined by measures such as the order amount and profit amount.

## Samples {#section_fl2_mqs_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/156404674539681_en-US.png)

## Notes {#section_xkd_nqs_xgb .section}

You can only select one dimension for the geographical locations and the dimension type must be Geo. You can select a minimum of one and a maximum of five measures for the heat intensity.

For more information, see [Detailed information for regions](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Examples {#section_eyh_4qs_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **LBS Heat Map** icon and an empty chart appears.
5.  On the Data tab page, select a dimension and measures.

    On the Dimensions list, locate the **province** field and add it to the Geo Location section. On the Measures list, locate the **order\_number** and **shipping cost** fields and add them to the Heat Intensity \(Measures\) section respectively.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, and measures' aliases.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15640467451866_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_c5d_rrs_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses Dark as the background color.

    **Note:** To configure a hyperlink used to jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Layout section, you can configure the legend position, base map, zoom setting, and map center. This example uses Google Map as the base map.
-   In the Series Settings section, you can configure measures' aliases and legend colors.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/156404674539682_en-US.png)

## Delete a chart {#section_j1k_qqs_xgb .section}

In the upper-right corner of the chart, choose **More Actions** \> **Delete** to delete the chart.

