# Cross tables {#concept_wc5_zl2_vdb .concept}

This topic describes how to create a cross table. Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_ggy_bmm_xgb .section}

A cross table displays aggregates and sub-aggregates of columns and groups columns. Aggregates include sums, averages, maximums, and minimums.

A cross table consists of rows and columns. Rows are horizontal and based on dimensions such as provinces and product types. Columns are vertical and based on measures such as order numbers and profit amounts.

## Examples {#section_km5_dmm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/155720782839800_en-US.png)

## Notes {#section_cfw_2mm_xgb .section}

Numbers of rows and columns are not limited.

## Scenarios: packages, shipping costs, order numbers, and profit amounts of multiple products based on provinces {#section_mky_gmm_xgb .section}

The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click the **Create Dashboard** icon in the Actions column.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to choose **Standard** or **Full Screen** as the display mode manually. The following example uses **Standard**.

4.  Click the Cross Table icon and an empty chart appears on the dashboard.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, locate the **province**, **product\_type**, and **product\_box** fields and add them to the Rows section. In the Measures list, locate the **order\_number**, **shipping\_cost**, and **profit\_amt**and add them to the Columns section.

    **Note:** Make sure that you have converted the dimension type of the province field from String to Geo.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281722_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, layout, format, and rules.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281724_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_qqd_zmm_xgb .section}

-   In the **Basic Settings** section, you can configure the title and hyperlinks for page jumping as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/155720782831904_en-US.png)

-   In the **Display Settings** section, you can configure the table theme, choose whether to show row numbers and whether to merge duplicate cells, configure freezing rules, and set pagination. The updated chart is shown as follows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281726_en-US.png)

-   In the **Functionality Settings** section, you can configure conditional formatting rules and aggregate rules.

    **Conditional formatting** 

    -   Select a field and select the **Enable Conditional Formatting** check box as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281727_en-US.png)

    -   Click the arrow. From the drop-down list, you can select the field that you want to perform conditional formatting for.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281728_en-US.png)

    -   Enter the beginnings and ends of intervals in the Value fields. Click the arrows and select text colors, background colors, and icons.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281729_en-US.png)

    Select the **profit\_amt** field for conditional formatting. The following formulas are used to determine which format to apply. Value ≥ 1000, Value < 1000 and ≥ 500, and Value < 500. The updated chart is shown as follows.

    -   When a value is greater than or equal to 1000, the background color of the cell is set to red and a green up arrow is displayed.
    -   When a value is greater than or equal to 500 and less than 1000, the background color of the cell is set to grey and an orange flat line is displayed.
    -   When a value is less than 500, the background color of the cell is set to green and a red down arrow is displayed.
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15572078281730_en-US.png)

    **Sort Columns**

    By using the sort columns feature, you can group related fields and set group names. If you do not set groups, dragging and dropping fields only modifies the sequence of columns.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/155720783532216_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/155720783532221_en-US.png)

    **Show Totals**

    By using the show totals feature, you can configure the aggregates of column values as shown in the following figure.

    **Note:** You need to select the **Merge Same Cells** check box in the **Display Settings** section before selecting the Show Subtotals check box.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/155720783533230_en-US.png)

-   In the **Series Settings** section, you can rename fields and set alignments.

## Delete a chart {#section_fg4_bnm_xgb .section}

Click the **More Actions** icon in the upper-right corner of the chart and select **Delete** from the drop-down list to delete a chart.

