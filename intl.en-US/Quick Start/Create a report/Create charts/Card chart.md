# Card chart {#concept_k5j_cr2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a card chart. If you need to create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

An indicator panel can intuitively show the data or sales performance so that participants of a project can promptly know the sales information or management status and quickly take countermeasures. Therefore, indicator panels are one of the most efficient and intuitive methods of discovering and solving problems.

An indicator panel consists of panel labels and panel indicators. Card labels are determined by the data dimension, such as the region. Card metrics are determined by the data measurement, such as the order quantity or order amount.

## Notice on creating a card chart {#section_dx2_2r2_vdb .section}

Card labels have up to one dimension. Card metrics have at least one, and up to 10 measurements.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare order quantity, order amount, transportation costs, and profit amount of different provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click card chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **province** option and add it to the card label area. In the measurement list, locate the **order\_number**, **order\_amt**, **shipping\_cost**, and **profit\_amt** options, and add them to the card metrics area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the province field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/15332645441760_en-US.png)

6.  Click **Update**.
7.  On the Style tab, you can edit the title and template of the card chart and set the number of labels displayed on each line.
    -   General config: configure the title of the chart, the color of the font, and the background color.
    -   Card settings: sets the template type and display style.
    -   Series settings: sets the alias of the relevant field and the number of decimal places that the numeric values need to retain.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

