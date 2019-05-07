# Kanbans {#concept_k5j_cr2_vdb .concept}

This topic describes how to create a kanban. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_dt4_lbn_xgb .section}

A kanban provides an overview of data such as sales performance. Using kanbans enables you to rapidly respond to sales status and management situations. Kanbans helps you to discover and solve problems.

A kanban is composed of labels and measures. Labels are based on data dimensions such as regions. Measures are based on data measures such as order numbers and order amounts.

## Examples {#section_wyx_4bn_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/155721098639650_en-US.png)

## Notes {#section_r32_sbn_xgb .section}

You can select a maximum of one dimension for the labels of a kanban. You can select a minimum of one and a maximum of 10 dimensions for the measures of a kanban.

## Example scenario: comparison of order numbers, order amounts, shipping costs, and profit amounts among provinces {#section_k4h_5bn_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode manually. The following example uses **Standard**.

4.  Click the **Kanban** icon and an empty kanban chart appears in the dashboard.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, locate the **province** field and ad it to the Labels \(Dimensions\) section. In the Measures list, locate the **order\_number**, **order\_amt**, **shipping\_cost**, and **profit\_amt** fields and add them to the Metrics \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type of the province field form String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/15572109861760_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, modify the kanban title, template, and column number.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/15572109861761_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_ehg_wbn_xgb .section}

-   In the Basic Settings section, you can configure the chart title, hyperlinks for page jumping, and the background color. This example uses Dark as the background color.
-   In the Card Settings section, you can configure the template type and card style. In this example, the column number is set to three.
-   In the Series Settings section, you can configure aliases, the unit, formats, and the number of decimal places for dimensions.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/155721098739651_en-US.png)

## Delete a chart {#section_u4r_wbn_xgb .section}

Click the **More Actions** icon in the upper-right corner of the chart and select **Delete** from the drop-down list to delete a chart.

