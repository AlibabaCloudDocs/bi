# Table {#concept_wc5_zl2_vdb .concept}

This section describes how to create a table. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A table can be used to display the distribution and total of specific variables. One variable defines the values in the header row and the other variable defines the values in the header column. The intersections of rows and columns contain the results of calculations on the data, such as the sum, average, maximum, minimum, or count of the data.

A table consists of rows and columns. Rows are determined by data dimensions, such as province and product type. Columns are determined by data measures, such as order quantity and profit amount.

## Note {#section_fxs_bm2_vdb .section}

For each table, the numbers of dimensions and measures are unlimited.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare multiple types of products with different package designs, transportation costs, order quantities, and profit amounts across multiple provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the table icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measures.

    In the Dimensions list, select **province**, **Product\_type**, and **Product\_box**, and add them sequentially to Row. In the Measures list, select **order\_amt**, **shipping\_cost**, and **average\_profit**, and add them sequentially to Column, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15447021191722_en-US.png)

6.  Click **Update** to generate the table.
7.  In the Style tab, you can change the title, layout, style, and rules of the table.

    In the **Rules** section, you can change the style of the data so that viewers can quickly find important data. For example, change the font color, add marks to specific data, or highlight cells based on custom rules.

8.  Click the **Save** icon to save the dashboard.

To delete the table, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

