# LBS heat maps {#concept_brr_dnf_vdb .concept}

**Note:** LBS heat maps are available only to **Quick BI Enterprise Standard** users.

This topic describes how to create an LBS heat map. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create an LBS heat map. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mcg_3qs_xgb .section}

Similar to [Colored maps](reseller.en-US/User Guide/Create dashboards/Create charts/Colored maps.md#), an LBS heat map shows the size and distribution of data by using shades of color.

An LBS heat map consists of regions with different colors. Regions are determined by data dimensions or the latitude and longitude values of the location, such as the province. Colors are determined by data measures, such as the order amount and profit.

## An example of an LBS heat map {#section_fl2_mqs_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/155722104839681_en-US.png)

## Precautions {#section_xkd_nqs_xgb .section}

Only one dimension can be set for the region of an LBS heat map and it must be a geographical dimension. One to five measures can be set for the heat intensity.

For more information about the administrative divisions of China, see [Administrative divisions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Scenario: Compare the transportation costs and order quantities across provinces {#section_eyh_4qs_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the **LBS Heat Map** icon. The blank LBS heat map is automatically displayed in the display section.
5.  Click the Data tab and select the required measures and dimension.

    In the Dimensions section, double-click **province**, or drag and drop it to the Geo Location section. In the Measures section, double-click **order number** and **shipping cost**, or drag and drop them to the Heat Intensity \(Measures\) section.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

6.  Click **Update**. The system automatically updates the map.
7.  On the Style tab, you can change the title and layout of the map, and the formats of specific fields, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15572210481866_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure a style {#section_c5d_rrs_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend, Map, Zoom, and Map Center. Set Map Center to Google Map in this example.
-   In the Series Settings section, you can set the alias and color of the measure.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/155722104839682_en-US.png)

## Delete a map {#section_j1k_qqs_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

