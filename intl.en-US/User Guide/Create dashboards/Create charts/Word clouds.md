# Word clouds {#concept_lnr_m3f_vdb .concept}

This topic describes the overview, examples, and deletion of a word cloud.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mx2_rjn_xgb .section}

A word cloud visualizes the frequency of words. It can be used in user profiles and user labels.

A word cloud is based on words and font sizes. Words are determined by dimensions, such as customer names and product names. Font sizes of words are determined by measures, such as profit amounts and unit prices.

## Samples {#section_bxd_tjn_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/156404669339658_en-US.png)

## Notes {#section_ns3_5jn_xgb .section}

You can select a maximum of one dimension for words and a maximum of one measure for font sizes.

## Examples {#section_pyb_gkn_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the Word Cloud icon and an empty chart appears.
5.  On the Data tab page, select a dimension and measure.

    In the Dimensions list, locate the province field and add it to the Word \(Dimensions\) section. In the Measures list, locate the **order\_number** field and add it to the Word Size \(Measures\) section.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15640466931819_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title name, title color, hyperlink, and background color. The updated chart is shown as follows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15640466931820_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15640466931821_en-US.png)

8.  Click **Save** to save the dashboard.

## Delete a chart {#section_xl1_jkn_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

