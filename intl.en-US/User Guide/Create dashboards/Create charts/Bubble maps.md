# Bubble maps {#concept_zrl_kk2_vdb .concept}

This topic describes how to create a bubble map. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mxl_g4l_xgb .section}

A bubble map displays data by using a map with bubbles of different sizes. You can view the values and distribution of data based on a country or a region. For example, you can use a bubble map to display tourist traffic in multiple tourist attractions or average income in multiple regions.

A bubble map is based on geographic locations and bubble sizes. Geographic locations are based on dimensions such as provinces. Bubble sizes are based on measures such as shipping costs and order numbers.

## Examples {#section_lbh_rhm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15571950811715_en-US.png)

## Notes {#section_x1q_thm_xgb .section}

You can select a maximum of one dimension for geographic locations. The dimension type is required to be Geo. You need to select a minimum of one and a maximum of five measures for bubble sizes.

## Scenarios: order numbers and profit amounts in multiple provinces {#section_ynh_vhm_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon.

    **Note:** If you use Quick BI **Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode. The following example uses **Standard**.

4.  Click the Bubble Map icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    On the Dimensions list, locate **province** and add it to the Geo Location \(Dimensions\) section. On the Measures list, locate **order\_number** and **profit\_amt** and add them to the Bubble Size \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type of the province field from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15571950811713_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, layout, legend, and value ranges.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15571950811714_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_qy2_yhm_xgb .section}

-   In the Basic Settings section, you can configure the chart title, text color, and background color. This example uses **Dark** as the background color.
-   In the Layout section, you can configure the legend location and labels. In this example, the **Show Geo Names** check box is selected.
-   In the Series Settings section, you can configure value ranges and the number of decimal places.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15571950811715_en-US.png)

## Delete a chart {#section_kjf_c3m_xgb .section}

Click the **More Actions** icon and select **Delete** from the drop-down list to delete a chart.

