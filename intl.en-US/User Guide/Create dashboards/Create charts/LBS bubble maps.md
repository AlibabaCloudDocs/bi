# LBS bubble maps {#concept_glz_t4f_vdb .concept}

This topic describes the overview, examples, and deletion of an LBS bubble map.

**Note:** LBS bubble maps only apply to **Quick BI Enterprise Standard**.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_bfv_wss_xgb .section}

Similar to a [bubble map](reseller.en-US/User Guide/Create dashboards/Create charts/Bubble maps.md#), an LBS bubble map is a map that uses the sizes of bubbles distributed across the map to reflect data. It provides multiple base maps for you to choose from, such as AMAP, Google Maps, and GeoQ. LBS bubble maps allow you to understand the distribution and values of metrics across countries and regions in an easy and visual way. For example, LBS bubble maps can display the passenger numbers across tourist attractions or the per capita incomes across regions.

An LBS bubble map is based on bubble sizes and geographical locations. Geographical locations are determined by Geo type dimensions such as the province. Bubble sizes are determined by measures such as the shipping cost and order number.

## Samples {#section_ysx_zss_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/156404678239683_en-US.png)

## Notes {#section_xyq_1ts_xgb .section}

You can only select one dimension for the geographical locations and the dimension type must be Geo. For example, the area, province, and city fields. You can select a minimum of one and a maximum of five measures for bubble sizes.

For more information, see [Detailed information for regions](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Examples {#section_qnb_cts_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **LBS Bubble Map** icon and an empty chart appears.
5.  On the Data tab page, select dimensions and measures.

    On the Dimensions list, locate the **province** field to the Geo Location section. On the Measures list, locate the **order\_amt** and **profit\_amt** fields and add them to the Bubble Size \(Measures\) section respectively.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15640467821870_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, and data display formats.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15640467831871_en-US.png)

8.  Click **Save** to save the dashboard.

    In the upper-right corner of the chart, choose **More Actions** \> **Delete** to delete the chart.


## Configure the style {#section_c5d_rrs_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses Dark as the background color.

    **Note:** To configure a hyperlink used to jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Layout section, you can configure the legend position, base map, zoom settings, and map center. This example uses Google Map as the base map.
-   In the Series Settings section, you can configure the measures' aliases, data display formats, and numbers of decimal places.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/156404678339685_en-US.png)

## Delete a chart {#section_bqk_hts_xgb .section}

In the upper-right corner of the chart, choose **More Actions** \> **Delete** to delete the chart.

