# LBS flying line maps {#concept_pgm_jpv_k2b .concept}

**Note:** LBS flying line maps are available only to **Quick BI Enterprise Standard** users.

This topic describes how to create an LBS flying line map. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create an LBS flying line map. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

An LBS flying line map is a map that uses flying lines to display the relations between data across two or more regions.

An LBS flying line map consists of regions connected with routes. Regions are determined by data dimensions, such as the province or city. Routes are determined by data measures, such as the transportation cost or order quantity.

## Overview {#section_qw5_q5s_xgb .section}

An LBS flying line map is a map that uses flying lines to display the relations between data across two or more regions.

An LBS flying line map consists of regions connected with routes. Regions are determined by data dimensions, such as the province or city. Routes are determined by data measures, such as the transportation cost or order quantity.

## Example of an LBS flying line map {#section_hvp_55s_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/155722252339686_en-US.png)

## Precautions {#section_ny3_z5s_xgb .section}

A maximum of two dimensions can be set for the region of an LBS flying line map. These dimensions must be geographical dimensions such as the region, province and city. Only one measure can be set for the route.

For more information about the administrative divisions of China, see [Administrative divisions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Scenario: Display the costs of transportation from regions to provinces {#section_aqt_z5s_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the **LBS Flying Line Map** icon. The blank LBS flying line map is automatically displayed in the display section.
5.  Click the Data tab to select the required measure and dimensions.

    In the Dimensions section, double-click **area**, or drag and drop it to the Geo Location \(from\) section. Double-click **province**, or drag and drop it to the Geo Location \(to\) section. In the Measures section, double-click **shipping cost**, or drag and drop it to the Routes \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15572225236992_en-US.png)

6.  Click **Update**. The system automatically updates the map.
7.  On the Style tab, you can change the title and layout of the map, and configure Series Settings, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15572225236993_en-US.png)

8.  Click **Save** to save the dashboard.

    Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.


## Configure a style {#section_q2w_crt_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend, Map, Zoom, and Map Center. Set Map Center to Google Map in this example.

    **Note:** A dot is moving along each LBS route to indicate the direction of traffic. You can set Flying Time to adjust the speed of the dot. A greater value indicates a lower speed.

-   In the Series Settings section, you can set the alias and color of the measure.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/155722252339697_en-US.png)

## Delete a map {#section_yfs_fvs_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

