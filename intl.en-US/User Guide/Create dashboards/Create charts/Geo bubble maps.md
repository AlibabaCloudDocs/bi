# Geo bubble maps {#concept_cy4_cvn_1fb .concept}

This topic describes how to create a geo bubble map. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a geo bubble map. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_v45_db5_xgb .section}

Similar to [Bubble maps](reseller.en-US/User Guide/Create dashboards/Create charts/Bubble maps.md#), a geo bubble map uses a map profile as its background and attaches bubbles to the map to indicate data values. A geo bubble map shows the size and distribution scope of each metric by country, region, or city. Compared with bubble maps, geo bubble maps provide a more detailed display of regions.

A geo bubble map consists of regions with varied color scales. Geo Location \(Dimensions\) is determined by data dimensions such as the province. Colorscale \(Measures\) is determined by data measures such as the order quantity.

## Example of a geo bubble map {#section_dxf_gb5_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20186/155728672739738_en-US.png)

## Precautions {#section_vl1_hb5_xgb .section}

Only one dimension can be set, and it must be a geographical dimension such as the region, province, or city. Only one measure can be set for the color scale.

For more information about the administrative divisions of China, see [Administrative divisions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Example scenario: Compare order quantities among provinces in northern China {#section_u23_jb5_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Geo Bubble Map icon. The blank geo bubble map is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimension.

    In the Dimensions section, double-click **province** or drag and drop it to the Geo Locations \(Dimensions\) section. In the Measures section, double-click **order number**, or drag and drop it to the Colorscale \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20186/155728672711281_en-US.png)

6.  Click **Update**. The system automatically updates the map.
7.  On the Style tab, you can set Display Scope and the legend color of each value range, as shown in the following figure.
8.  Click **Save** to save the dashboard.

## Configure a style {#section_kkm_1c5_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend, Show Tooltip, Show Labels, Show Geo Names, and Display Scope.
-   In the Series Settings section, you can set Alias, Data display format setting, and Set Value Ranges.

## Delete a map {#section_fpb_bc5_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

