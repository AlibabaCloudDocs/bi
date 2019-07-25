# LBS flying line maps {#concept_pgm_jpv_k2b .concept}

This topic describes the overview, examples, and deletion of an LBS flying line map.

**Note:** Only **Quick BI Enterprise Standard** supports LBS flying line maps.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

An LBS flying line map is a map that uses flying lines to display the relations between data across two or more locations.

An LBS flying line map consists of geographic locations and routes. Geographic locations are based on dimensions such as the province. Color scales are based on measures such as the order amount and order number.

## Overview {#section_qw5_q5s_xgb .section}

An LBS flying line map is a map that uses flying lines to display the relations between data across two or more locations.

An LBS flying line map consists of geographic locations and routes. Geographic locations are based on dimensions such as the province. Color scales are based on measures such as the order amount and order number.

## Samples {#section_hvp_55s_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/156404682139686_en-US.png)

## Notes {#section_ny3_z5s_xgb .section}

You can only select one dimension for each geographic location and the dimensions must be Geo type fields such as the area, province, and city. You can select a maximum of one measure for the routes.

For more information, see [Detailed information for regions](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

## Examples {#section_aqt_z5s_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the **LBS Flying Line Map** icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and a measure.

    On the Dimensions list, locate the **area** field and add it to the Geo Location \(From\) section. Locate the **province** field and add it to the Geo Location \(To\) section. On the Measures list, locate the **shipping\_cost** field and add it to the Routes \(Measures\) section as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province and area fields. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15640468216992_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, and series setting as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15640468216993_en-US.png)

8.  Click **Save** to save the dashboard.

    In the upper-right corner of the chart, choose **More Actions** \> **Delete** to delete the chart.


## Configure the style {#section_q2w_crt_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color. This example uses Dark as the background color.
-   In the Layout section, you can configure the legend position, base map, zoom settings, and map center. This example uses Google Map as the base map.

    **Note:** You can adjust the flying speed by moving the Flying Time slider. The bigger the slider value, the lower the flying speed.

-   In the Series Setting section, you can configure the measure's alias and line color.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/156404682239697_en-US.png)

## Delete a chart {#section_yfs_fvs_xgb .section}

In the upper-right corner of the chart, choose **More Actions** \> **Delete** to delete the chart.

