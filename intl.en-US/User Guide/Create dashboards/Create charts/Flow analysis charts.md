# Flow analysis charts {#concept_u4r_lmf_vdb .concept}

This topic describes how to create a flow analysis chart. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a flow analysis chart. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_qnx_jks_xgb .section}

A flow analysis chart illustrates the conversion rate of a Webpage by comparing the page traffic or number page views \(PV\) against the number of unique visitors \(UV\), so that the Webpage operators can gain insights into the operating status of the Website and the final transaction volume for a type of product. A flow analysis chart is suitable for analyzing digital marketing campaigns and e-commerce websites. For example, you can use a flow analysis chart to find out which products are in highest demand and what are the peak hours of your business.

Currently, a flow analysis chart supports the following three dimensions: previous page, current page, and next page. The measures of a flow analysis chart include PV, UV, conversion rate, and bounce rate. You need to specify the PVs or UVs for all three pages.

## Example of a flow analysis chart {#section_jdz_lks_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9143/155722219539668_en-US.png)

## Precautions {#section_a5r_mks_xgb .section}

Only one dimension can be set for each of the three pages. The dimension fields must be hierarchical. The order of the dimensions determines the hierarchical relationship in the chart. Only one measure can be set for each of the three PVs or UVs, the conversion rate, and the bounce rate.

The three dimensions, the conversion rate, and the bounce rate are required fields. You can choose to specify only the PVs or UVs for all three pages. Error messages appear if fields are incorrectly specified when you add the dimensions and measures.

## Scenario: Use PVs to demonstrate the conversion and bounce rates on different pages {#section_gcn_nks_xgb .section}

The following uses the page\_source\_target\_state dataset as an example.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Select the page\_source\_target\_state dataset and click **Create Dashboard**.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Flow Analysis icon. The blank flow analysis chart is automatically displayed in the display section.
5.  Click the Data tab and select the required measures and dimensions.

    In the Dimensions section, double-click **Previous Page**, **Current Page**, and **Next Page**, or drag and drop them to the corresponding fields. This order determines the hierarchical relationship between pages in the diagram. In the Measures section, double-click **Conversion Rate** and **Bounce Rate**, or drag and drop them to the corresponding fields. You must also select three PVs or UVs for the corresponding pages, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9143/15572221951859_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9143/15572221951860_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set Show Title and Layout.

    In the Layout section, you can select one of the three modes and select Highlight Primary Path or Highlight Bounce Path for the mode.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9143/15572221951861_en-US.png)

8.  Click **Save** to save the dashboard.

## Delete a chart {#section_fj1_tks_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.

