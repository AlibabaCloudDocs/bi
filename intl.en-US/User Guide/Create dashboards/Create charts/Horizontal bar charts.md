# Horizontal bar charts {#concept_zm3_422_vdb .concept}

This topic describes how to create a horizontal bar chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_zh5_5ll_xgb .section}

A horizontal bar chart shows comparisons between categories. You can use a horizontal bar chart to visualize data changes over a period of time or comparisons between categories. For example, you can show the working progress of employees in a project group.

Similar to [Line charts](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md#), a horizontal bar chart consists of the category axis and the value axis.

## Examples {#section_jgl_gml_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15571402271695_en-US.png)

## Notes {#section_df5_hml_xgb .section}

You can set a minimum of one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Color Legend \(Dimensions\) section can take only one dimension.

**Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

## Scenarios: shipping costs of products in multiple cities {#section_omf_nml_xgb .section}

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the **Horizontal Bar Chart** icon and an empty chart appears on the dashboard.
5.  On the Dimensions list, locate **city** and add it to the Filters section.

    You can search for municipalities from cities by using filters as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15571402271691_en-US.png)

6.  Click the **Filter** icon and select **Filter by Value** in the dialog box that appears.
7.  Select four municipalities from the list or enter the names of them manually, and click **OK** as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/155714022711402_en-US.png)

8.  Drag the **city** and **product\_type** fields to the Category Axis \(Dimensions\) section.

    **Note:** Makes sure that you have converted the dimension type of the province field from String to Geo.

9.  On the Measures list, drag **shipping\_cost** to the Value Axis \(Measures\) section.
10. Drag **product\_type** to the Color Legend \(Dimensions\) section.

    **Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

11. Click **Update** and the chart is updated.
12. On the Style tab page, you can configure the chart title, layout, legend, and axis style.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15571402271693_en-US.png)

13. Click **Save** to save the dashboard.

## Configure the style {#section_d1c_qml_xgb .section}

-   In the Basic Settings section, you can configure the chart title, hyperlinks, and background color. This example uses **Dark** as the background color.

    **Note:** In the Basic Settings section, you can change the chart type such as the stacked horizontal bar chart and 100% stacked horizontal bar chart.

-   In the Style section, you can configure the scroll bar and stacking style. This example uses **Stacking**.
-   In the Layout section, you can configure the legend location and choose whether to show labels and tooltips. In this example, the legend is displayed on the **Top** of the chart.
-   In the Axes section, you can configure axis titles and units. In this example, the **Show Scale** check box is selected on the Top Axis tab page.
-   In the Series Settings section, you can configure measure aliases, axis style, boundary values, and data display format.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15571402271695_en-US.png)

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_adc_xml_xgb .section}

If you want to delete the current chart, click More in the upper-right corner of the chart and select **Delete** to delete the current chart.

