# Polar diagrams {#concept_wby_whf_vdb .concept}

This topic describes how to create a polar diagram. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a polar diagram. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_clr_shn_xgb .section}

A polar diagram can be used to display data changes over a period of time or compare metric values. It is suitable for data of the enumerated type. For example, compare data across different regions.

Similar to [Pie charts](reseller.en-US/User Guide/Create dashboards/Create charts/Pie charts.md#), a polar diagram consists of sectors of labels and arc radiuses. Labels are determined by data dimensions, such as the area and product type. Arc radiuses are determined by data measures, such as the order number and order amount.

## Example of a polar diagram {#section_ttz_13n_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/155721180639657_en-US.png)

## Precautions {#section_ol1_23n_xgb .section}

Only one dimension can be set for labels. This dimension must contain 3 to 12 variables. Only one measure can be set for arc radiuses.

## Scenario: Compare the order quantities across multiple areas {#section_khj_h3n_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Polar Diagram icon. The blank polar diagram is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimension.

    In the Dimensions section, double-click **area**, or drag and drop it to the Label \(Dimensions\) section. In the Measures section, double-click **order number**, or drag and drop it to the Arc Radius \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15572118061816_en-US.png)

6.  Click **Update**. The system automatically updates the diagram.
7.  On the Style tab, you can set Show Title, Layout, Show Legend, Measures, and Series Settings, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15572118061817_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure a style {#section_vhf_l3n_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to **Light** in this example.
-   In the Layout section, you can set Show Legend, Show Tooltip, Label Style, Leaders, and Radius. In this example, set Show Legend to **Right** and Label Style to **Name, Value \(Percentage\)**.
-   In the Measures section, you can set AutoFit Mode and decimal places. In this case, enter **2**.
-   In the Series Settings section, you can set the alias of the measure and the color of the alias.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/155721180633800_en-US.png)

## Delete a chart {#section_yzh_p3n_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.

