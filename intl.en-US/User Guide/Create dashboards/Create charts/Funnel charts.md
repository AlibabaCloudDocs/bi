# Funnel charts {#concept_u3s_1q2_vdb .concept}

This topic describes how to create a funnel chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_lcj_nxm_xgb .section}

Funnel charts apply to the analysis of the standardized business process that has long cycles and multiple links. By using funnel charts, you can discover problems and locate the causes rapidly. Funnel charts are also used to present the conversion rate of each step. For example, you can view the conversion rates throughout the process from a user entering a website to completing purchases.

A funnel chart is based on the tier label and tier area. The tier label is based on the dimension such as the region. The tier area is based on the measure such as the order amount.

## Examples {#section_fvq_sxm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/155721065239640_en-US.png)

## Notes {#section_nj4_txm_xgb .section}

You can select a maximum of one dimension for the tier labels of a funnel chart. You can select a maximum of one measure for the tier area of a funnel chart.

## Scenarios: order amounts in multiple areas {#section_eqr_5xm_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset. Click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode manually. The following example uses **Standard**.

4.  Click the Funnel chart icon and an empty chart appears in the dashboard.
5.  On the Data tab page, select dimensions and measures as needed.

    In the Dimensions list, select the **area** field and add it to the Tier Labels \(Dimensions\) section. In the Measures list, select the **order\_amt** field and add it to the Tier Area \(Measures\) section.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/15572106521752_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, modify the name, layout, and legend of the funnel chart.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/15572106521753_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_rzg_zym_xgb .section}

-   In the Basic Settings section, you can configure the chart name, hyperlinks for page jumping, and the background color. This example uses Dark as the background color.
-   In the Layout section, you can configure the legend position, label style, and display mode.
-   In the Measures section, you can configure the alias, format, and the number of decimal places of the measure.
-   In the Blocks section, you can configure the colors and aliases of dimension values.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/155721065239648_en-US.png)

## Delete a chart {#section_nnx_zym_xgb .section}

Click the **More Actions** icon in the upper-right corner of the chart and select **Delete** from the drop-down list to delete a chart.

