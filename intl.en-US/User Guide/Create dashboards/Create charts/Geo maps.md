# Geo maps {#concept_rp1_fvn_1fb .concept}

This topic describes how to create a geo map. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a geo map. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_i4q_fr5_xgb .section}

Similar to [Colored maps](reseller.en-US/User Guide/Create dashboards/Create charts/Colored maps.md#), a geo map shows the size and distribution of data by using shades of color. Compared with colored maps, geo maps provide a more detailed display of regions.

A geo map consists of regions with varied color scales. Geo Location \(Dimensions\) is determined by data dimensions such as the province. Colorscale \(Measures\) is determined by data measures such as the order quantity.

## Example of a geo map {#section_bsk_rr5_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20187/155728559839742_en-US.png)

## Precautions {#section_yxm_sr5_xgb .section}

Only one dimension can be set, and it must be a geographical dimension. Only one measure can be set for the color scale.

For more information about the administrative divisions of China, see [Administrative divisions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Example scenario: Compare order quantities among provinces in southern China {#section_r3d_5r5_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Geo Map icon. The blank geo map is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimension.

    In the Dimensions section, double-click **province**, or drag and drop it to the Geo Location \(Dimensions\) section. In the Measures section, double-click **order number** or drag and drop it to the Colorscale \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20187/155728559811278_en-US.png)

6.  Click **Update**. The system automatically updates the map.
7.  On the Style tab, you can set Display Scope and the legend color of each value range, as shown in the following figure.
8.  Click **Save** to save the dashboard.

## Configure a style {#section_j1v_j1v_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend, Show Tooltip, Show Geo Names, and Display Scope.
-   In the Series Settings section, you can set Alias, Data display format setting, and Set Value Ranges.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20187/155728559839750_en-US.png)

## Delete a map {#section_xfd_4t5_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

