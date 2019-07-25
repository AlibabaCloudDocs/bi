# Cross tables {#concept_wc5_zl2_vdb .concept}

This topic describes the overview, examples, and deletion of a cross table.

Make sure that you have read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before reading this topic. For creating a dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_ggy_bmm_xgb .section}

A cross table displays aggregates and sub-aggregates of columns and groups columns. Aggregates include sums, averages, maximums, and minimums.

A crosstab consists of rows and columns. Rows are horizontal and based on dimensions such as provinces and product types. Columns are vertical and based on measures such as order numbers and profit amounts.

## Samples {#section_km5_dmm_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629739800_en-US.png)

## Notes {#section_cfw_2mm_xgb .section}

For each crosstab, the numbers of dimensions and measures are unlimited.

## Examples {#section_mky_gmm_xgb .section}

Scenario: Compare multiple types of products with different package designs, transportation costs, order quantities, and profit amounts across multiple provinces The following example uses the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to go to the Datasets page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you use **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** as the dashboard display mode. The following example uses **Standard**.

4.  Click the Cross Table icon and an empty chart appears.
5.  On the Data tab page, select dimensions and measures.

    In the Dimensions list, select **province**, **product\_type**, and **product\_box**, and add them sequentially to Rows \(Dimensions\), select **order\_number**, **shipping\_cost**, and **profit\_amt**, and add them sequentially to Values \(Measures\), as shown in the following figure.

    **Note:** Make sure that you have converted the dimension type from String to Geo for the province dimension. For more information, see [Change the dimension type](reseller.en-US/User Guide/Data modeling/Dataset management/Change field types.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15640462971722_en-US.png)

6.  Click **Update** and the chart is updated.
7.  On the Style tab page, you can configure the chart title, layout, format, and rules.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629744658_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure the style {#section_qqd_zmm_xgb .section}

-   In the **Basic Information** section, you can configure the title and hyperlinks for page jumping as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629731904_en-US.png)

    **Note:** For jumping to a report or an external page, select **Show Hyperlink** and enter a name and an address.

-   In the **Display Settings** section, you can configure the table theme, choose whether to show row numbers and whether to merge duplicate cells, configure freezing rules, and set pagination. The updated chart is shown as follows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15640462971726_en-US.png)

    **Note:** **Pagination** is disabled if you select **Merge Same Cells**.

-   In the **Functionality Settings** section, you can configure conditional formatting rules and aggregate rules. Conditional formats include **Icons** and **Data bars**.

    **Icon**

    1.  Select a field and select **Icon** as the format.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629744253_en-US.png)

    2.  Select an icon theme from the Theme drop-down list.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629844254_en-US.png)

    3.  You can specify the rules for data that needs to be marked out and click the downward arrow button to specify the style of the data.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629844261_en-US.png)

    Take the **profit\_amt** column as an example. The following rules are set for different data values. The updated table is shown in the following figure:

    -   If values are greater than or equal to 1000, their cells are highlighted in red and a green up arrow appears next to each value.
    -   When the data value is between 500 and 1000, the background color of the cell containing the data is set to orange and an orange horizontal line appears next to the data.
    -   If values are less than 500, their cells are highlighted in green and a red down arrow appears next to each value.
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629844265_en-US.png)

    **Data bar**

    1.  Select a field and select **Data Bar** as the format.
    2.  Set the upper limit, lower limit, and fill color.

        **Note:** Upper and lower limits can be set automatically or manually.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629844267_en-US.png)

    **Sort columns**

    You can sort columns and group columns. When grouping columns, you need to set group names as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629832216_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629832221_en-US.png)

    **Show totals**

    By using the Show Totals feature, you can configure aggregates, sub-aggregates, and aggregation functions such as SUM, AVG, and MAX. You can also create an expression on which to perform the aggregation as shown in the following figure.

    **Note:** Before configuring sub-aggregates, you need to select **Merge Same Cells** in the **Display Settings** section.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/156404629933230_en-US.png)

-   In the **Series Settings** section, you can configure field names, alignment, and the number format.

## Delete a chart {#section_fg4_bnm_xgb .section}

Click the **More Actions** icon in the upper-right corner of a chart and select **Delete** from the drop-down list to delete the chart.

