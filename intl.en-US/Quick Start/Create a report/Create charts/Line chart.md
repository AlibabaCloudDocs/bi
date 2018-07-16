# Line chart {#concept_mrr_y1z_5db .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a line chart. If you need to recreate a data set, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A line chart shows the trend of data changes using lines and displays the continuous time-varying data. It can be used to analyze and display the data trend at equal time intervals. A line chart also can be used to analyze the changing mutual affect between multiple groups of data in a period of time. For example, use a line chart to show how the sales volume of a type of or some types of products changes with time, and further predict the future sales performance.

A line chart consists of a category axis and a value axis. A category axis is horizontal and contains only dimension fields such as the date, province, and product type. The value axis is vertical and contains only measurement fields, such as the business indicator of the analysis object and order quantity.

In the dashboard, the system automatically matches the category axis, value axis, and dimension field, measure field of the line diagram, as shown in the following figure. You only need to follow the system prompts and select the expected fields from the dimension and measurement lists.

## Notice on creating a line chart {#section_tvz_dbz_5db .section}

Select at least one dimension for the category axis and at least one measurement for the value axis. If you want to use the color legend function, select a maximum of one measurement for the color legend.

**Note:** The color legend can be used when only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Order amount of each type of products in each province in each year**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset ,  and click **Create Dashboard**. The dashboard editing page is displayed.
4.  Double-click **line chart** icon. The line chart sample is displayed.
5.  Select required dimension fields and measurement fields.

    In the dimension list, locate the order date \(year\), province, and product type options and add them to the category axis area in sequence. In the measurement list, locate the order quantity option and add it to the value axis area, as shown in the following figure.

    **Note:** Make sure that the dimension type of the province field has been switched from string to geological information. For details about how to switch the dimension field type, see [Example: Create a dashboard](intl.en-US/Quick Start/Example: Create a dashboard.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9124/1589_en-US.png)

6.  On the Style tab, you can edit the title, layout, and legends of the chart.

    **Note:** For more information about Styles, see[Set chart data](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Set chart data.md#).

7.  Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

