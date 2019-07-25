# Scatter charts {#concept_w3v_cp2_vdb .concept}

This topic describes how to create a scatter chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_yjv_lvm_xgb .section}

Scatter charts present the distribution and aggregation of data.

A scatter chart is composed of the X-axis and Y-axis. The color legend is based on the data dimension such as the product type. The scales of the X-axis and Y-axis are based on the data measures.

## Examples {#section_asp_4vm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/156404650039634_en-US.png)

## Notes {#section_gz3_pvm_xgb .section}

You can select a maximum of one dimension for the color legend. You can set a maximum of 1,000 dimension values.

X-axis: supports a minimum of one and a maximum of three dimensions.

Y-axis: supports one measure.

## Scenarios: unit prices and order numbers of multiple product types {#section_bvr_qvm_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode manually. The following example uses **Standard**.

4.  Click the Scatter Chart icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, locate the **product\_type** field and add it to the Color Legend \(Dimensions\) section. In the Measures list, locate the **price** and **order\_number** fields and add them to the X Axis \(Measures\) and Y Axis \(Measures\) sections separately.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/15640465001750_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can modify the chart name, layout, and legend as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/15640465001751_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_mds_2wm_xgb .section}

-   In the Title section, you can configure the title.
-   In the Design section, you can choose whether to show axis titles. This example shows the axis titles.
-   In the Layout section, you can set the legend position and choose whether to show tooltips.

The updated chart is as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/156404650039638_en-US.png)

## Delete a chart {#section_br2_dwm_xgb .section}

Click the **More Actions** icon in the upper-right corner of the chart and select **Delete** from the drop-down list to delete a chart.

