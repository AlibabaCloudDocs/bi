# Pivot tables {#concept_kcw_cqf_vdb .concept}

**Note:** Pivot tables are available only to **Quick BI Enterprise Standard** users.

This topic describes how to create a pivot table. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a pivot table. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_oll_2st_xgb .section}

A pivot table can be used to display the summary statistics of variables and allows you to drill into data in a tree structure. One variable defines the values in the header row while the other variable defines the values in the header column. The intersections of rows and columns contain the results of calculations on the data, such as the sum, average, maximum, minimum, or count of the data.

Similar to [Cross tables](reseller.en-US/User Guide/Create dashboards/Create charts/Cross tables.md#), a pivot table consists of rows and columns. Rows are determined by data dimensions, such as the province and product type. Columns are determined by data measures, such as the order quantity and profit amount.

## Example of a pivot table {#section_dzs_gst_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/155729437239700_en-US.png)

## Precautions {#section_d4n_hst_xgb .section}

For each pivot table, the numbers of dimensions and measures are unlimited.

## Scenario: Compare multiple types of products with different package designs, order quantities, and order amounts across multiple provinces {#section_vnj_3st_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the **Pivot Table** icon. The blank pivot table is automatically displayed in the display section.
5.  In the Graphic Design section, click the Data tab and select the required dimensions and measures.

    In the Dimensions section, double-click **province**, **product type**, and **product box**, or drag and drop them to the Rows \(Dimensions\) section in order. In the Measures section, double-click **order number** and **order amt**, or drag and drop them to the Values \(Measures\) section in order, as shown in the following figure.

    **Note:** Make sure you have changed the data type of the province field value from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721878_en-US.png)

6.  Click **Update**. The system automatically updates the table.
7.  On the Style tab, you can set Title, Layout, and Format, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721880_en-US.png)

    -   In the **Layout** section, you can set Show Row Numbers and Show Totals. Click Update. A similar figure is displayed.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721881_en-US.png)

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721882_en-US.png)

    -   In the **Format** section, set Decimal Places to 1 for order amt. Click Update. A similar figure is displayed.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721884_en-US.png)

8.  Click the **plus** icon in front of a value to drill into the data in a tree structure.

    For example, when you click the plus sign in front of **Shanghai**, data about product types and packet designs is displayed as a tree.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15572943721886_en-US.png)

9.  Click **Save** to save the dashboard.

    Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current table.


## Configure a style {#section_hby_ptt_xgb .section}

-   In the Title section, you can set Show Title.
-   In the Layout section, you can set Show Row Numbers, Show Totals, and Freeze.
-   In the Format section, you can set Thousands Separator and Decimal Places.

Click Update. A similar figure is displayed.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/155729437239703_en-US.png)

## Delete a table {#section_mdj_pst_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current table.

