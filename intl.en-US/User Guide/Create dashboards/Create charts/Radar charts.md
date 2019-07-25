# Radar charts {#concept_xkk_b42_vdb .concept}

This topic describes the overview, examples, and deletion of a radar chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_gfn_hpm_xgb .section}

Radar charts display numbers and ratios obtained from data analysis. You can view the changing trends of indicators by using radar charts. For example, sales of all areas are represented by numbers and ratios in radar charts.

A radar chart is based on labels and lengths. Labels are based on dimensions such as product types. Lengths are based on measures such as shipping costs.

## Notes {#section_xdk_jqm_xgb .section}

You can select a minimum of one and a maximum of two dimensions for the labels of a radar chart. The number of dimension values must be greater than or equal to three and less than or equal to 12. You need to select a minimum of one dimension for the length.

## Samples {#section_nfs_mqm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/156404643039630_en-US.png)

## Examples {#section_x4k_4qm_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the Radar Chart icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, locate the **area** field and add it to Labels \(Dimensions\). In the Measures list, locate the **order\_number** and **order\_amt** fields and add them sequentially to Length \(Measures\).

    **Note:** Make sure that you have converted the dimension type of the area field from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/15640464301744_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the **Style** tab page, you can configure the title name, layout, and legend.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/156404643044656_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_o5g_rqm_xgb .section}

-   In the Basic Information section, you can configure the title name, hyperlink, and background color. This example uses **Domestic data** as the title name and uses **Dark** as the background color.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the Layout section, you can configure the legend position and whether to show tooltips, areas, and labels.
-   In the Series Settings section, you can configure aliases for dimensions, data formats, and numbers of decimal places. This example uses red as the line color for the **order\_number** field.

Click Update and the chart is updated as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/15640464301747_en-US.png)

## Delete a chart {#section_nx5_1tm_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

