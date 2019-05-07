# Treemaps {#concept_q2y_4gf_vdb .concept}

This topic describes how to create a treemap. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a treemap. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_z1y_rdn_xgb .section}

Treemaps can be used to compare the proportions between variables easily.

A treemap consists of nested rectangles of different sizes and labels. The label of each rectangle is determined by data dimensions, such as the package design. The size of each rectangle is determined by data measures, such as the transportation cost.

## Example of a treemap {#section_sst_b2n_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9137/155721139739652_en-US.png)

## Precautions {#section_k1y_d2n_xgb .section}

Only one dimension can be set for the labels of rectangles. This dimension can have a maximum of 12 dimension values. Only one measure can be set for the sizes of rectangles.

## Scenario: Compare the order quantities of different products {#section_pb4_p2n_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Treemap icon. The blank treemap is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimension.

    In the Dimensions section, double-click **product type**, or drag and drop it to the Rectangle Labels \(Dimensions\) section. In the Measures section, double-click **order number**, or drag and drop it to the Rectangle Size \(Measures\) section, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9137/15572113971803_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can change the title and legend of the treemap, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9137/15572113971804_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure a style {#section_e1q_r2n_xgb .section}

-   In the Basic Settings section, you can set Show Title.
-   In the Design section, you can set Show Tooltip, AutoFit Mode, and the number of decimal places.

## Delete a map {#section_cyc_s2n_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current map.

