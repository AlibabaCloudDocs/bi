# Hierarchy charts {#concept_esg_blf_vdb .concept}

This topic describes how to create a hierarchy chart. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a hierarchy chart. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_ajy_t3s_xgb .section}

A hierarchy chart uses the tree structure to display and organize hierarchical data. It is an implementation of the enumeration method. For example, when you view the revenues of the prefecture-level cities within a province, the relationships between the province and prefecture-level cities can be displayed in parent-child structures. Hierarchy charts are used to analyze organizational structures, such as the staff structure of a company or the department structure of a hospital.

A hierarchy chart consists of node metrics and node labels. Each node label is determined by data dimensions, such as the area and product type. Each node metric is determined by data measures, such as the order quantity and order amount.

## Example of a hierarchy chart {#section_ykn_w3s_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/155721468239666_en-US.png)

## Precautions {#section_im2_x3s_xgb .section}

At least two dimensions must be set for node labels. These two dimensions must have a parent-child relationship. At least one measure must be set for the node metric.

## Scenario: Compare the order quantities of different products across provinces and areas {#section_udg_y3s_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Hierarchy Chart icon. The blank hierarchy chart is automatically displayed in the display section.
5.  Click the Data tab and select the required measures and dimensions.

    In the Dimensions section, double-click **area**, **province**, and **product type**, or drag and drop them to the Node Labels \(Dimensions\) section in order. This order determines their hierarchical relationships in the chart. In the Measures section, double-click **order number**, or drag and drop it to the Node Metrics \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/15572146821844_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set Show Title, Layout, and Design.
    -   Hierarchy charts support three layouts. You can select the expansion mode \(root nodes are merged by default\) and display mode of parent and child nodes as needed.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/15572146821847_en-US.png)

    -   In the Design section, you can manually enter the number of hierarchy levels displayed in the chart. You can select a primary path from the corresponding drop down list. The primary path is displayed in a different color from other paths. You can load the filter bar to the chart so that you can edit the chart in the preview mode or on the dashboard, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/15572146821848_en-US.png)

8.  Click **Save** to save the dashboard.

## Delete a chart {#section_iwt_1js_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.

