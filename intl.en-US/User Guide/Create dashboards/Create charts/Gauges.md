# Gauges {#concept_mmt_3n2_vdb .concept}

This topic describes how to create a gauge. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_lsw_snm_xgb .section}

Similar to an auto gauge, a gauge shows the value range of a certain indicator. You can view the progress of a task or whether an indicator value is about to exceed the valid range. For example, you can use a gauge to display the inventory status of a product to see whether the inventory is sufficient.

A gauge is based on the pointer angles and filters. The pointer angles and filters are both based on data measures such as discount points and profit amounts.

## Notes {#section_cvw_44m_xgb .section}

For both the pointer angle and filters, you can select a maximum of one measure.

## Examples {#section_sy4_5nm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/155720904439623_en-US.png)

## Scenarios: order amounts represented by gauges {#section_gc1_s4m_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode manually. The following example uses **Standard**.

4.  Click the **Gauge** icon and an empty chart appears.
5.  On the Data tab page, select measures as needed.

    **Note:** \[DO NOT TRANSLATE\]

    In the Measures list, select **order\_amt** and add it to the Angle.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/15572090441734_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, layout, legend, and tick marks.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/15572090441735_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_mv4_t4m_xgb .section}

-   In the Basic Setting section, you can configure the chart title, hyperlinks for page jumping, and the background color.
-   In the Layout section, you can configure whether to show tooltips, tick marks, and the legend.
-   In the Value Ranges section, you can configure the interval and the color. In this example, the start value is 100 and the end value is 1000. The title of the interval is set to net profit.
-   In the Series Settings section, you can configure the field aliases and the number of decimal places.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/155720904439624_en-US.png)

## Delete a chart {#section_nvf_54m_xgb .section}

Click the **More Actions** icon in the upper-right corner of the chart and select **Delete** from the drop-down list to delete a chart.

