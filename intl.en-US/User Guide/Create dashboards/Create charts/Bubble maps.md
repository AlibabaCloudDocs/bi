# Bubble maps {#concept_zrl_kk2_vdb .concept}

This topic describes the overview, examples, and deletion of a bubble map.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mxl_g4l_xgb .section}

A bubble map displays data by using a map with bubbles of different sizes. You can view the values and distribution of data based on a country or a region. For example, you can use a bubble map to display tourist traffic of multiple tourist attractions or the average income in multiple regions.

A bubble map is based on geographic locations and bubble sizes. Geographic locations are based on dimensions such as provinces. Color scales are based on measures such as order amounts and profit amounts.

## Samples {#section_lbh_rhm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15640461711715_en-US.png)

## Notes {#section_x1q_thm_xgb .section}

You can select a maximum of one dimension for geographic locations. The dimension type is required to be Geo. You need to select a minimum of one and a maximum of five measures for bubble sizes.

## Examples {#section_ynh_vhm_xgb .section}

Scenario: compares the order numbers and profit amounts in multiple provinces. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard** as the display mode.

4.  Click the Bubble Map icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select a dimension and measures.

    On the Dimensions list, locate the **province** field and add it to the Geo Location \(Dimensions\) section. On the Measures list, locate the **order\_number** and **profit\_amt** fields and add them to the Bubble Size \(Measures\) section respectively.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province field. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15640461711713_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, legend, and value ranges.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15640461711714_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_qy2_yhm_xgb .section}

-   In the Basic Information section, you can configure the title, font color, and background color. This example uses **Dark** as the background color.
-   In the Layout section, you can configure the legend position and whether to show tooltips. This example uses **Show Geo Names**.
-   In the Series Settings section, you can configure value ranges and the number of decimal places.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15640461711715_en-US.png)

## Delete a chart {#section_kjf_c3m_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

