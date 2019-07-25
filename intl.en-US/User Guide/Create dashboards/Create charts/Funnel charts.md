# Funnel charts {#concept_u3s_1q2_vdb .concept}

This topic describes the overview, examples, and deletion of a funnel chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_lcj_nxm_xgb .section}

Funnel charts are suitable for analyzing business processes that involve a sequence of activities and span over a long period. By comparing the business data during different stages, you can easily identify potential problems in the business process. Funnel charts can be used to show the conversion rates during different stages of the business process. For example, you can easily see the percentage of visitors who became paying customers in a funnel chart.

A funnel chart consists of a number of tiers with different labels and widths. The labels of tiers are determined by data dimensions, such as area. The widths of tiers are determined by data measures, such as the order amounts.

## Samples {#section_fvq_sxm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/156404656539640_en-US.png)

## Notes {#section_nj4_txm_xgb .section}

You can select a maximum of one dimension for tier labels and a maximum of one measure for tier areas.

## Examples {#section_eqr_5xm_xgb .section}

Scenario: compares the order amounts across multiple areas. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the Funnel Chart icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select a dimension and a measure.

    In the Dimensions list, locate the **area** field and add it to the Tier Labels \(Dimensions\) section. In the Measures list, locate the **order\_amt** field and add it to Tier Area \(Measures\).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/15640465651752_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, and legend as shown in the following figure.
8.  Click **Save** to save the dashboard.

## Configure the style {#section_rzg_zym_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses Dark as the background color.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the Layout section, you can configure the legend position, label style, and display mode.
-   In the Measures section, you can configure the measure's alias, data format, and the number of decimal places.
-   In the Blocks section, you can configure the dimension's alias and area colors.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/156404656539648_en-US.png)

## Delete a chart {#section_nnx_zym_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

