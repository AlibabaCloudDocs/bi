# Horizontal bar charts {#concept_zm3_422_vdb .concept}

This topic describes the overview, examples, and deletion of a horizontal bar chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_zh5_5ll_xgb .section}

A horizontal bar chart shows comparisons between categories. You can use a horizontal bar chart to visualize data changes over a period of time or comparisons between categories. For example, you can show the working progress of employees in a project group.

Similar to a [line chart](reseller.en-US/User Guide/Create dashboards/Create charts/Line charts.md#), a horizontal bar chart is based on the category axis and the value axis.

## Samples {#section_jgl_gml_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15640460881695_en-US.png)

## Notes {#section_df5_hml_xgb .section}

You can set a minimum of one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Color Legend \(Dimensions\) section can take only one dimension.

**Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

## Examples {#section_omf_nml_xgb .section}

Scenario: compares the shipping costs of products in multiple cities.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **Horizontal Bar Chart** icon and an empty chart appears on the dashboard.
5.  On the Dimensions list, locate the **city** field and add it to the Filters section.

    Municipalities are filtered from cities by using the filter as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15640460881691_en-US.png)

6.  Click the **Filter** icon and select **Filter by Value** in the dialog box that appears.
7.  Select four municipalities from the list or enter four municipality names manually and click **OK** as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/156404608911402_en-US.png)

8.  Add the **city** and **product\_type** fields to the Category Axis \(Dimensions\) section in sequence.

    **Note:** Make sure that you have converted the dimension type of the city field from String to Geo.

9.  On the Measures list, locate the **shipping\_cost** field and add it to the Value Axis \(Measures\) section.
10. Add the **product\_type** field to the Color Legend \(Dimensions\) section.

    **Note:** You can add dimensions to the Color Legend \(Dimensions\) section when only one measure is added to the Value Axis \(Measures\) section. Otherwise, you are not allowed to add dimensions to the Color Legend \(Dimensions\) section.

11. Click **Update** and the chart is updated.
12. On the Style tab page, you can configure the basic information, chart type, axes, functionality, and series settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15640460891693_en-US.png)

13. Click **Save** to save the dashboard.

## Configure the style {#section_d1c_qml_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses **Dark** as the background color.

    **Note:** 

    -   To jump to a report or an external page, select **Show Hyperlink** and enter a name and address.
    -   In the Basic Information section, you can change the chart type to a stacked horizontal bar chart or 100% stacked horizontal bar chart.
-   In the Chart Type section, you can configure labels, alignment, legend position, dual y-axis, and chart type \(stacked horizontal bar chart and 100% stacked horizontal bar chart\). This example uses **Stacked**.
-   In the Axes section, you can configure axis titles and units. This example uses **Show Scale** for the bottom axis.
-   In the Functionality section, you can configure whether to show a scroll bar and the display mode.
-   In the Series Settings section, you can set measures' aliases, boundary values, and data display formats.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15640460881695_en-US.png)

**Note:** For more information about Style, see [Configure a chart](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

## Delete a chart {#section_adc_xml_xgb .section}

To delete a chart, move the pointer over the upper-right corner of a chart, click the More Actions icon that appears, and select **Delete** from the drop-down list.

