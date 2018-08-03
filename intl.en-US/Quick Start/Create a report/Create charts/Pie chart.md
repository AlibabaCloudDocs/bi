# Pie chart {#concept_gwq_4f2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a pie chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A pie chart shows a data series. Each data series has a unique color or pattern. A pie chart can be used to show the volume of each item and the percentage of an item in the total amount. For example, you can use a pie chart to show the ratio of the expense of five insurances \(endowment, medical, unemployment, employment injury, and maternity insurances\) and housing fund to the personal income, or the sales of a car brand to the total car sales.

A pie chart consists of multiple slices. The label of each slice is determined by the data dimension, such as the region or product type. The angle \(size\) of each slice is determined by the data measurement, such as the order quantity or order amount.

## Notice on creating a pie chart {#section_cmv_qf2_vdb .section}

The slice label area of a pie chart has at most one measurement, such as the region or product type, and the measurement value must be less than or equal to 12. The slice angle area has at most one measurement, such as the order quantity or profit amount.

The following example uses the company\_sales\_record dataset as an example.

**Scenario: Compare the transportation costs of different regions.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset, and click **Create Dashboard**.
4.  Double-click pie chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area** option and add it to the slice label area. In the measurement list, locate the **shipping\_cost** option, and add it to the slice size area, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9128/15332622361698_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  In the style tab, you can change the title, layout, display legend, measure, and series settings of the chart, as shown in the following illustration.
8.  Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

