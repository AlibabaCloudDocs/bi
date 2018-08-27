# Pivot table {#concept_kcw_cqf_vdb .concept}

**Note:** Pivot table is only applied to **Quick BI Professional Edition**。

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a table.  If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A Pivot table is used to show the values of a table field and divide the values into two groups. One group is listed on the left of the data table, and the other is listed on the top of the data table. Multiple calculations can be performed in the intersection between a column and a row, for example, sum, average, count, maximum, or minimum.

Similar to [Table](intl.en-US/Quick Start/Create a report/Create charts/Table.md#), a Pivot table also contains rows and columns. The horizontal rows are determined by the data dimension, such as a province or a product type. The vertical columns are determined by the data measurement, such as an order quantity or a profit amount.

## Limitations on creating a Pivot table {#section_gxz_gqf_vdb .section}

No restrictions are imposed on the values of the dimension and measurement to define the rows and columns of a Pivot table.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the product\_box, order\_number, and order\_amt of different types of products in multiple provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**. The dashboard editing page is displayed.
    -   If you are using **Standard** or **Advanced** edition, the page automatically jumps to the Standard edit page.
    -   If you are using **Professional Edition**, you need to manually select either **Standard** mode or **Fullscreen** mode. The following example takes the **Standard** mode as an example.
4.  Click **Pivot table** icon.
5.  On the Data tab, select a required dimension field and measurement field.

    In the dimension list, locate the **province**, **product\_type**, and **product\_box** options and add them to the row area in sequence. In the measurement list, locate the **order\_number**, **order\_amt** options and add them to the column area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the province field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381878_en-US.png)

6.  Click **Update**.
7.  On the Style tab, you can edit the title and layout.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381880_en-US.png)

    -   In the **layout**, select Show Row number and Show Subtotals, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381881_en-US.png)

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381882_en-US.png)

    -   In the **Set format**, set the number of decimal places for the order\_amt to 1.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381884_en-US.png)

8.  Click the **+**number in front of the data to implement the data tree drill, as shown in the following figure.

    For example, by clicking the plus sign in front of **Xicang**, the data for the product type and product package are displayed layer by layer.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9146/15353584381886_en-US.png)

9.  Click the **Save** icon to save the dashboard.

    In the upper right corner, select **More** \> **Delete ** To delete the current chart.


