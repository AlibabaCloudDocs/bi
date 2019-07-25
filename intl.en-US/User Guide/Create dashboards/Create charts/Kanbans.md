# Kanbans {#concept_k5j_cr2_vdb .concept}

This topic describes the overview, examples, and deletion of a kanban.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_dt4_lbn_xgb .section}

A kanban provides an overview of data such as sales performance. Using kanbans enables you to rapidly respond to sales status and management situations. Kanbans help you to discover and solve problems.

A kanban is composed of labels and measures. Labels are based on data dimensions such as regions. Measures are based on data measures such as order numbers and order amounts.

## Samples {#section_wyx_4bn_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/156404660139650_en-US.png)

## Notes {#section_r32_sbn_xgb .section}

You can select a maximum of one dimension for the labels of a kanban. You can select a minimum of one and a maximum of 10 measures for the metrics of a kanban.

## Examples {#section_k4h_5bn_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the **Kanban** icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, locate the **province** field and add it to the Labels \(Dimensions\) section. In the Measures list, select the **order number**, **order\_amt**, **shipping\_cost**, and **profit\_amt** fields and add them to Metrics \(Measures\) as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/15640466011760_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title name, template types, and number of columns.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/156404660144654_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_ehg_wbn_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses Dark as the background color.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Card Settings section, you can configure the template type, number of columns, and alignment. This example uses 3 as the number of columns.
-   In the Series Setting section, you can configure the aliases for dimensions, units, and numbers of decimal places.

Click Update and the chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/156404660239651_en-US.png)

## Delete a chart {#section_u4r_wbn_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

