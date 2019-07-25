# Polar diagrams {#concept_wby_whf_vdb .concept}

This topic describes the overview, examples, and deletion of a polar diagram.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_clr_shn_xgb .section}

A polar diagram compares multiple data values. It is used for comparing enumerated data, such as data based on multiple regions.

Similar to a [pie chart](reseller.en-US/User Guide/Create dashboards/Create charts/Pie charts.md#), a polar diagram consists of slices. Labels of slices are determined by the dimension, such as the area and product type. Arc radiuses are determined by the measure, such as order numbers and order amounts.

## Samples {#section_ttz_13n_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/156404664939657_en-US.png)

## Notes {#section_ol1_23n_xgb .section}

You can select a maximum of one dimension for labels. The minimum number of dimension values is three. The maximum number of dimension values is 12. You can select a maximum of one measure for arc radiuses.

## Examples {#section_khj_h3n_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the Polar Diagram icon and an empty chart appears on the dashboard.
5.  On theData tab page, select a dimension and a measure.

    In the Dimensions list, locate the **area** field and add it to the Label \(Dimensions\) section. In the Measures list, locate the **order\_number** field and add it to the Arc Radius \(Measures\) section, as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the area dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15640466491816_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, legend, measures, and series settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15640466491817_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_vhf_l3n_xgb .section}

-   In the Basic Information section, you can configure the title name, title color, description, hyperlink, and background color. This example uses **Dark** as the background color.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the Layout section, you can configure the legend position, whether to show tooltips, label style, leaders, and radiuses. The example uses **Name, Value \(Percentage\)** as the label style and uses **Right** as the legend position.
-   In the Measures section, you can configure the data format and the number of decimal places. This example uses **2** as the number of decimal places.
-   In the Series Setting section, you can configure aliases for the dimensions and slice colors.

Click Update and the chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/156404664933800_en-US.png)

## Delete a chart {#section_yzh_p3n_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

