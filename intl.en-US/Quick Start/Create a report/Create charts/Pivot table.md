# Pivot table {#concept_kcw_cqf_vdb .concept}

**Note:** Pivot tables are only applied to **Quick BI Professional Edition**.

This section describes how to create a pivot table. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A pivot table can be used to display the summary statistics of variables and allows you to drill into data in a tree structure. One variable defines the values in the header row and the other variable defines the values in the header column. The intersections of rows and columns contain the results of calculations on the data, such as the sum, average, maximum, minimum, or count of the data.

Similar to [Table](intl.en-US/Quick Start/Create a report/Create charts/Table.md#), a pivot table consists of rows and columns. Rows are determined by data dimensions, such as province and product type. Columns are determined by data measures, such as order quantity and profit amount.

## Note {#section_gxz_gqf_vdb .section}

For each pivot table, the numbers of dimensions and measures are unlimited.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare multiple types of products with different package designs, order quantities, and order amounts across multiple provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
    -   If you are using the **Professional Edition**, you need to select between the **Standand Mode** and **Full Screen Mode**. The following scenario uses the **Standard Mode** as an example.
4.  Click the **Pivot Table** icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measures.

    In the Dimensions list, select **province**, **product\_type**, and **product\_box**, and add them sequentially to Row. In the Measures list, select **order\_number** and **order\_amt**, and add them sequentially to Column, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331878_en-US.png)

6.  Click **Update** to generate the table.
7.  In the Style tab, you can change the title, layout, and style of the table as follows:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331880_en-US.png)

    -   In the **Layout** section, select Show Row Numbers and Add Summary Statistics. The updated table is as follows:

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331881_en-US.png)

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331882_en-US.png)

    -   In the **Set Format** section, set the number of decimal places of order\_amt to 1. The updated table is as follows:

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331884_en-US.png)

8.  Click the **Plus** sign ahead of a value to drill into the data in a tree structure.

    For example, when you click the plus sign ahead of **Shanghai**, data about product types and packet designs are displayed in a tree structure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15447930331886_en-US.png)

9.  Click the **Save** icon to save the dashboard.

    In the upper-right corner, select **More** \> **Delete** to delete the table.


