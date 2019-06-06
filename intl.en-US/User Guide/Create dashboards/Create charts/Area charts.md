# Area charts {#concept_rvx_tyd_vdb .concept}

This topic describes how to create an area chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_i4z_mcg_xgb .section}

Similar to [Line charts](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md), an area chart can display the trends in data over time and the proportion of data.

An area chart consists of the category axis and the value axis. The category axis is a horizontal axis and only supports dimensions such as dates, provinces, and product types. The value axis is a vertical axis and only supports measures such as sales indicators and order numbers.

Dimensions and measures are automatically used for the category axis and the value axis respectively in the dashboards. You only need to select fields from the Dimensions and Measures lists.

## Examples {#section_qs1_qcg_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15597860301682_en-US.png)

## Notes {#section_m23_tcg_xgb .section}

You can set at least one dimension for the category axis, and set at least one measure for the value axis. You can only select one dimension for the color legend.

**Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) section. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

## Scenarios: order numbers of multiple products in provinces {#section_jfn_5cg_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the **Area Chart** icon and an empty chart appears on the dashboard.
5.  Select dimensions and measures.

    On the Dimensions list, drag the province and product\_type fields to the Category Axis \(Dimensions\) section in turn. On the Measures list, drag the order\_amt field to the Value Axis \(Measures\) section.

    **Note:** Makes sure that you have converted the dimension type of the province field from String to Geo. For more information, see [Create dashboards](../../../../reseller.en-US/Quick Start/Create a report/Create dashboards.md).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15597860301679_en-US.png)

6.  Drag the **product\_type** field to the Color Legend \(Dimensions\) section and click **Update**.

    **Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) section. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

7.  On the **Style** tab page, you can configure the chart title, layout, legend, and axis style.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15597860301680_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_xgp_13l_xgb .section}

-   In the Basic Settings section, you can configure the chart title, hyperlinks, and background colors. This example uses **Dark** as the background color.

    **Note:** In the Basic Settings section, you can change the chart type such as the stacked area chart and 100% stacked area chart.

-   In the Style section, you can configure the scroll bar and stacking style. This example uses **100% Stacking**.
-   In the Layout section, you can configure the legend location and choose whether to show labels and tooltips. In this example, the legend is displayed on the **Right** of the chart.

    **Note:** Select **Show Labels** to show all labels. Show Labels supports Smart Display and Full Display. Assume that a chart involves many dimension values and the scroll bar is not shown in the chart. In Smart Display mode, only partial labels are displayed. In Full Display mode, all labels are displayed.

-   In the Axes section, you can configure axis titles and units. In this example, the X-Axis title is set to **Province**.
-   In the Series Settings section, you can configure measure aliases, axis style, boundary values, and data display format. In this example, the **Office** area is set to orange.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15597860301682_en-US.png)

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_esy_dc2_vdb .section}

Click the **More Actions** icon and select **Delete** from the drop-down list to delete a chart.

