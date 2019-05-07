# LBS bubble maps {#concept_glz_t4f_vdb .concept}

**Note:** LBS bubble maps are available only to **Quick BI Enterprise Standard** users.

This topic describes how to create an LBS bubble map. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create an LBS bubble map. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_bfv_wss_xgb .section}

Similar to [Bubble maps](reseller.en-US/User Guide/Create dashboards/Create charts/Bubble maps.md#), an LBS bubble map is a map that uses the sizes of bubbles distributed across the map to reflect data sizes. It provides multiple basemaps for you to choose from, such as AMAP, Google Map, and GeoQ. LBS bubble maps allow you to understand the distribution and values of metrics across countries and regions in an easy and visual way. For example, LBS bubble maps can display the number of visitors at different tourist attractions or the per capita incomes across different regions.

An LBS bubble map consists of regions with bubbles of various sizes. Regions are determined by data dimensions, or the latitude and longitude values of the location such as the province. Bubble sizes are determined by data measures, such as the transportation cost and order quantity.

## Example of an LBS bubble map {#section_ysx_zss_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/155722184039683_en-US.png)

## Precautions {#section_xyq_1ts_xgb .section}

Only one dimension can be set for the region of an LBS bubble map and it must be a geographical dimension or the latitude and longitude values of the location, such as the region, province, or city. One to five measures can be set for the bubble size.

For more information about the administrative divisions of China, see [Administrative divisions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Scenario: Compare the order amounts and profit amounts across provinces {#section_qnb_cts_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  Click the **LBS Bubble Map** icon. The blank LBS bubble map is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimensions.

    In the Dimensions section, double-click **province**, or drag and drop it to the Geo \(Location\) section. In the Measures section, double-click **order amt** and **profit amt**, or drag and drop them to the Bubble Size \(Measures\) section, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15572218401870_en-US.png)

6.  Click **Update**. The system automatically updates the map.
7.  On the Style tab, you can change the title and layout of the map, and the formats of specific fields, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15572218401871_en-US.png)

8.  Click **Save** to save the dashboard.

    Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.


## Configure a style {#section_c5d_rrs_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend, Map, Zoom, and Map Center. Set Map Center to Google Map in this example.
-   In the Series Settings section, you can set Alias, AutoFit Mode, and Decimal Places.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/155722184039685_en-US.png)

## Delete a map {#section_bqk_hts_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

