# Word clouds {#concept_lnr_m3f_vdb .concept}

This topic describes how to create a word cloud. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a word cloud. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_mx2_rjn_xgb .section}

A word cloud clearly displays the frequency of words. It is suitable for creating user personas and user tags.

A word cloud consists of words with various sizes. Words are determined by data dimensions, such as the customer name or product type. Word sizes are determined by data measures, such as the profit amt or unit price.

## Example of a word cloud {#section_bxd_tjn_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/155721335039658_en-US.png)

## Precautions {#section_ns3_5jn_xgb .section}

Only one dimension can be set for words. Only one measure can be set for word sizes.

## Scenario: Compare the order quantities across different provinces {#section_pyb_gkn_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Word Cloud icon. The blank word cloud is automatically displayed in the display section.
5.  Click the Data tab and select the required measure and dimension.

    In the Dimensions section, double-click province, or drag and drop it to the Word \(Dimensions\) section. In the Measures section, double-click **order number**, or drag and drop it to the Word Size \(Measures\) section, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15572133501819_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set Show Title, Show Hyperlink, and Background Color, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15572133591820_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15572133591821_en-US.png)

8.  Click **Save** to save the dashboard.

## Delete a chart {#section_xl1_jkn_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.

