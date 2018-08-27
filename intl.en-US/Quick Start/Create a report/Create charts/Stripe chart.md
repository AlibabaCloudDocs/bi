# Stripe chart {#concept_zm3_422_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a Stripe chart. For more information about dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A Stripe chart can be used to show data variations in a specific period of time, or to compare different items \(for example, to compare the schedule of different members in a project\) to show differences between multiple groups of data.

The Stripe chart and [Line chart](intl.en-US/Quick Start/Create a report/Create charts/Line chart.md#) have similar components. They both include a category axis and a value axis.

## Limitations on creating a Stripe chart {#section_hyy_q22_vdb .section}

Set at least one dimension for the category axis of a Stripe chart, such as a province or a product type. Set at least one measurement for the value axis, such as the order number or order amount. Color legends only support dimension fields, and a maximum of one dimension can be set for each color legend.

**Note:** The color legend is available only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the shipping costs of different products in different municipalities.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click **Stripe chart** icon.
5.  In the dimension list, select **city** field, and add it to the filter.

    In this example, municipality is selected from the city list, as shown in the following figure

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15353582981691_en-US.png)

6.  Click the **filter** icon and select **Enum** from the displayed dialog box.
7.  Select from the list or manually enter the names of the four municipalities, and click **OK**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15353582981692_en-US.png)

8.  In the dimension list, find the province and product\_type options, and add them to the category axis area in sequence.

    **Note:** Make sure that the type of city fields has been switched from string to geographical information.

9.  In the measurement list, locate the **shipping\_cost** option, and add it to the value axis area.
10. Add the **product\_type** field to the color legend.

    **Note:** The color legend can be used when only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

11. Click **Update**. The system automatically updates the chart.
12. On the Style tab, you can edit the title, layout, and design of the chart.

    **Note:** For more information about Styles, see[Set chart data](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Set chart data.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15353582981693_en-US.png)

    -   In the Common Settings, select **Dark**color as the background color.
    -   In the Style, select **stack**.
    -   In the layout, the display legend settings are displayed on **top**.
    -   In the axis, check **Display scale** in the vertical left axis.
    After updating, the chart is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15353582981695_en-US.png)

13. Click **Save** to save current dashboard.

In the upper right corner, select **More** \> **Delete ** To delete the current chart.

