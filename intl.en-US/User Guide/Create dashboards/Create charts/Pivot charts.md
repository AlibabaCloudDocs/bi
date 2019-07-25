# Pivot charts {#concept_kcw_cqf_vdb .concept}

This topic describes the overview, examples, and deletion of a pivot chart.

**Note:** Pivot tables only apply to **Quick BI Enterprise Standard**.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_oll_2st_xgb .section}

A pivot table can be used to display the aggregates of variables and allows you to drill into data in a tree structure. One variable defines the values in the header row while the other variable defines the values in the header column. Aggregates include sums, averages, maximums, and minimums.

Similar to a [cross table](reseller.en-US/User Guide/Create dashboards/Create charts/Cross tables.md#), a pivot table consists of rows and columns. Rows are horizontal and based on dimensions such as provinces and product types. Columns are vertical and based on measures such as order numbers and profit amounts.

## Samples {#section_dzs_gst_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/156404634439700_en-US.png)

## Notes {#section_d4n_hst_xgb .section}

For each pivot table, the number of dimensions and measures is unlimited.

## Examples {#section_vnj_3st_xgb .section}

Scenario: compares multiple types of products with different package designs, order quantities, and order amounts across multiple provinces. The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard** as the display mode.

4.  Click the **Pivot Table** icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measures.

    In the Dimensions list, select **province**, **product\_type**, and **product\_box**, and add them sequentially to Rows \(Dimensions\), select **order\_number** and **order\_amt**, and add them sequentially to Values \(Measures\), as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15640463441878_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the basic information, chart type, axes, functionality, and series settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/156404634444268_en-US.png)

8.  Click the **Plus \(+\)** sign in front of the value to drill into the data in a tree structure.

    For example, when you click the plus sign in front of **Shanghai**, data about product types and product boxes is displayed in a tree structure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15640463451886_en-US.png)

9.  Click **Save** to save the dashboard.

## Configure the style {#section_hby_ptt_xgb .section}

-   In the **Basic Information** section, you can configure the title and hyperlink of a chart.

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the **Display Settings** section, you can configure whether to show row numbers, to freeze columns, and to enable word wrap. This example shows row numbers.
-   In the **Functionality Settings** section, you can configure conditional formats and whether to show aggregates. See [Functionality settings](reseller.en-US/User Guide/Create dashboards/Create charts/Cross tables.md#ul_whc_hvb_ygb). This example displays conditional formats and aggregates.
-   In the Series Settings section, you can configure the names of series, alignment, and number formats.

The updated chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/156404634544270_en-US.png)

## Delete a chart {#section_mdj_pst_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

