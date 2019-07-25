# Pie charts {#concept_gwq_4f2_vdb .concept}

This topic describes the overview, examples, and deletion of a pie chart.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_jh4_4nf_xgb .section}

A pie chart displays a data series. Each data series has a unique color or texture. Pie charts show data distribution and proportions. For example, you can use a pie chart to show the proportion of five social insurances and one housing fund in a person's income. You can also use a pie chart to show the sales proportion of an auto brand in total sales of all brands.

A pie chart consists of slices. The label of a sector is determined by a dimension such as the area field and the product\_type field. The degree of an angle is determined by a measure such as order\_amt and profit\_amt.

## Samples {#section_w15_tnf_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15640461331700_en-US.png)

## Notes {#section_brb_b4f_xgb .section}

You can set at least one dimension such as area and product\_type. In addition, you can set at least one measure for the Arc Angle \(Measures\) area such as order\_amt and profit\_amt.

## Examples {#section_cmv_qf2_vdb .section}

Scenario: compares shipping costs for multiple areas. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the Pie Chart icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    On the Dimensions list, locate the **area** field and add it to the Labels \(Dimensions\) section. On the Measures list, locate the **shipping\_cost** field and add it to the Central Angle \(Measures\) section as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the area dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15640461331698_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, legend, display mode, radius, and aliases of dimension's values.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/156404613333798_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_m5d_pqf_xgb .section}

-   In the Basic Information section, you can configure the title, font color, hyperlink, and background color. This example uses **Dark** as the background color.

    **Note:** To jump to a report or an external page, select **Show Hyperlink** and enter a name and address.

-   In the Layout section, you can configure the legend, display mode, label style, leaders, and radius. This example uses **Name, Value \(Percentage\)** as the label style and uses Top as the legend position.
-   In the Measures section, you can configure the unit and number of decimal places. This example uses **2** as the number of decimal places.
-   In the Series Settings section, you can configure aliases for dimension's values and colors for corresponding slices. In this example, the color for **Northeast** is set to grey.

Click Update and the updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15640461331700_en-US.png)

## Delete a chart {#section_zv5_n4f_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

