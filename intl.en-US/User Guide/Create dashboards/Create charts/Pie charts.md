# Pie charts {#concept_gwq_4f2_vdb .concept}

This topic describes how to create a pie chart. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_jh4_4nf_xgb .section}

A pie chart displays a data series. Each data series has a unique color or texture. Pie charts show data distribution and proportions. For example, you can use a pie chart to show the proportion of five social insurances and one housing fund in a person's income. You can also use a pie chart to show the sales proportion of an auto brand in total sales of all brands.

A pie chart is composed of slices. Labels are based on dimensions such as areas and product types. Central angles are based on measures such as order numbers and order amounts.

## Examples {#section_w15_tnf_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15571937111700_en-US.png)

## Notes {#section_brb_b4f_xgb .section}

You can set a maximum of one dimension such as the area and product type for labels. The number of dimension values is required to be less than or equal to 12. You can set a maximum of one measure such as the order number and profit amount for central angles

## Scenarios: shipping costs in multiple areas {#section_cmv_qf2_vdb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the Pie Chart icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    On the Dimensions list, locate **area** and add it to the Labels \(Dimensions\) section. On the Measures list, locate **shipping\_cost** and add it to the Central Angle \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type of the area field from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15571937111698_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, layout, legend, display mode, radius, and dimension names. For more information, see.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/155719371133798_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_m5d_pqf_xgb .section}

-   In the Basic Settings section, you can configure the chart title, title color, hyperlinks for page jumping, and background color. This example uses **Dark** as the background color.
-   In the Layout section, you can configure the legend location, display mode, label style, leaders, and radius. In this example, Label Style is set to **Name, Value \(Percentage\)**. The legend is displayed on the **Right** of the chart.
-   In the Measures section, you can configure the value format and number of decimal places. In this example, the number of decimal places is set to **2**.
-   In the Series Settings section, you can configure dimension aliases and colors. In this example, the color of the **Northeast** slice is set to grey.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15571937111700_en-US.png)

## Delete a chart {#section_zv5_n4f_xgb .section}

Click the **More Actions** icon and select **Delete** from the drop-down list to delete a chart.

