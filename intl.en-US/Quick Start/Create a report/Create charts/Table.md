# Table {#concept_wc5_zl2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a table.  If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A table is used to show the values of a table field and divide the values into two groups. One group is listed on the left of the data table, and the other is listed on the top of the data table. Multiple calculations can be performed in the intersection between a column and a row, for example, sum, average, count, maximum, or minimum.

A table consists of rows and columns. The horizontal rows are determined by the data dimension, such as a province or a product type. The vertical columns are determined by the data measurement, such as an order quantity or a profit amount.

## Notice on creating a table {#section_fxs_bm2_vdb .section}

No restrictions are imposed on the values of the dimension and measurement to define the rows and columns of a table.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the packages, transportation costs, order quantities, and average profits of different types of products in multiple provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click table icon.
5.  On the Data tab, select a required dimension field and measurement field.

    In the dimension list, locate the **province**, **product\_type**, and **product\_box** options and add them to the row area in sequence. In the measurement list, locate the **order\_amt**, **shipping\_cost**, and **average\_profit** options and add them to the column area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9131/15332639281722_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and layout.

    In the **Rule** menu, you can edit the data display effect for the table, for example, you can change the font color, add a data identifier, or highlight a data area, to help readers efficiently locate their expected data.

8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

