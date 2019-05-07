# Progress bars {#concept_fzz_3rf_vdb .concept}

This topic describes how to create a progress bar. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a progress bar. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_vbt_4wt_xgb .section}

A progress bar displays the progress of the current task.

A progress bar consists of multiple progress metrics. Progress metrics are determined by data measures, such as the order quantity.

## Example of a progress bar {#section_fkb_cyt_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/155722281139707_en-US.png)

## Precautions {#section_vbx_cyt_xgb .section}

-   For each progress bar, one to five measures can be specified to determine the progress metrics.
-   To use a progress bar, choose **Style** \> **Series Settings** to specify the maximum and minimum values of each progress metric.

## Scenario: Use a progress bar to display the order quantity {#section_hkw_gyt_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Progress Bar icon. The blank progress bar is automatically displayed in the display section.
5.  Click the Data tab to select data measures.

    In the Measures section, double-click **order number** or drag and drop it to the Poniter \(Measures\) section, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15572228111892_en-US.png)

6.  Click **Update**. The system automatically updates the bar.
7.  On the Style tab, you can set Show Title, Show Hyperlink, Show Legend, and Alias, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15572228121893_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure a style {#section_rx3_3zt_xgb .section}

-   In the Basic Settings section, you can set Show Title, Show Hyperlink, and Background Color. Set Background Color to Dark in this example.
-   In the Layout section, you can set Show Legend and Show Tooltip.
-   In the Series Settings section, you can set Alias, Minimum, Maximum, AutoFit Mode, and Decimal Places.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/155722281239705_en-US.png)

## Delete a bar {#section_ak4_jyt_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current bar.

