# Bar chart {#concept_bnq_fd2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a bar chart.  If you need to recreate a dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

For its clear demonstration of the differences among multiple groups of data, a bar chart can be used to show data variations in a specific period of time or to compare different items, for example, to compare the traffic flows of a road crossing during different periods.

The bar chart and [Line chart](intl.en-US/Quick Start/Create a report/Create charts/Line chart.md#) have similar components. They both include a category axis and a value axis.

## Notice on creating a bar chart {#section_pxd_3d2_vdb .section}

Set at least one dimension for the category axis of a bar chart, such as a province or a product type. Set at least one measurement for the value axis, such as the order quantity or profit amount. Color legends only support dimension fields, and a maximum of one dimension can be set for each color legend.

**Note:** The color legend can be used when only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the transportation costs of different products in provinces of China East.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click **Bar chart** icon.
5.  In the dimension list, select **area** field, and add it to the filter.

    We need to use the filter to select China East from the region list, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15332775821685_en-US.png)

6.  Click the filter icon and select **Enum** from the displayed dialog box.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15332775821686_en-US.png)

7.  Select East and click **OK**.
8.  In the dimension list, locate the **province** and **product\_type** options, and add them to the category axis area in sequence.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

9.  In the measurement list, locate the **shipping\_cost** option, and add it to the value axis area.
10. You can add the **product\_type** field to the color legend.

    **Note:** The color legend can be used when only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

11. Click **Update**. The system automatically updates the chart.
12. On the Style tab, you can edit the title, layout, and design of the chart.

    **Note:** For more information about Styles, see [Set chart data](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Set chart data.md#).

13. Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

