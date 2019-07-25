# Progress bars {#concept_fzz_3rf_vdb .concept}

This topic describes the overview, examples, and deletion of a progress bar.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For more information about how to create a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_vbt_4wt_xgb .section}

A progress bar displays the progress of a task.

A progress bar consists of multiple progress metrics. Progress metrics are determined by data measures such as the order number.

## Samples {#section_fkb_cyt_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/156404685939707_en-US.png)

## Notes {#section_vbx_cyt_xgb .section}

-   You can select a minimum of one and a maximum of five measures for a progress bar.
-   Choose **Style** \> **Series Settings** and set the minimum and maximum values that a progress bar can display.

## Examples {#section_hkw_gyt_xgb .section}

Scenario: displays the order number. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses the **Standard** display mode.

4.  Click the Progress Bar icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select measures.

    On the Measures list, locate the **order\_number** field and add it to the Pointer \(Measures\) section as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15640468591892_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the title, background color, hyperlink, legend, and measures' aliases as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15640468591893_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_rx3_3zt_xgb .section}

-   In the Basic Information section, you can configure the title, hyperlink, and background color of a chart. This example uses Dark as the background color.
-   In the Layout section, you can select the position of legend and choose whether to show the tooltips.
-   In the Series Settings section, you can configure the measures' aliases, value ranges, data formats, and numbers of decimal places.

Click Update and the chart is updated.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/156404685939705_en-US.png)

## Delete a chart {#section_ak4_jyt_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

