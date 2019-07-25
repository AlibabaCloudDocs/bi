# Gauges {#concept_mmt_3n2_vdb .concept}

This topic describes the overview, examples, and deletion of a gauge.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_lsw_snm_xgb .section}

Similar to a dashboard on a car, a gauge shows the range of a specific indicator. You can view the progress of the current task or if a metric will exceed its range. For example, you can use a gauge to show the inventory status of a category of items, whether it is sufficient or needs to be replenished.

The pointer angle of a gauge is determined by the measure, such as the discount and profit amount.

## Notes {#section_cvw_44m_xgb .section}

You can select up to one measure for the pointer angle.

## Samples {#section_sy4_5nm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/156404639339623_en-US.png)

## Examples {#section_gc1_s4m_xgb .section}

Scenario: Uses a gauge to display the order amount. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the **Gauge** icon and an empty chart appears.
5.  On the Data page, select a measure.

    In the Measures list, select **order\_amt** and add it to Pointer Angle \(Measures\), as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/15640463931734_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, layout, whether to show the legend, and whether to show tick marks.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/156404639344657_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_mv4_t4m_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the Layout section, you can configure whether to show tooltips, tick marks, and the legend.
-   In the Value Ranges section, you can set value ranges and the corresponding colors. This example uses 100 as the start value and 1000 as the end value of a range. The title of the range is named "net profit".
-   In the Series Setting section, you can configure the alias of the measure and number of decimal places that each value shows.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/156404639439624_en-US.png)

## Delete a chart {#section_nvf_54m_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

