# Area chart {#concept_rvx_tyd_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a bar chart.  For more information about dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

An Area chart shows a trend of data changes using customized chart area, and displays continuous time-varying data. It can be used to analyze and display a data trend at equal time intervals, and changes between multiple groups of data over a period of time \(such as the sales volume of a type of or some types of products\), which can help predict future trends.

An Area chart consists of a category axis and a value axis. A category axis is horizontal and contains only dimension fields such as the date, province, and product type. The value axis is vertical and contains only measurement fields, such as the business indicator of the analysis object and order quantity.

In the dashboard, the system automatically matches the category axis, value axis, and dimension field, and measure field of the line diagram. You only need to follow the system prompts and select the expected fields from the dimension and measurement lists.

## Limitations on creating an Area chart {#section_esy_dc2_vdb .section}

You must select at least one dimension for the category axis and at least one measurement for the value axis. If you want to use the color legend function, you must select one measurement for the color legend.

**Note:** The color legend is available only when one measurement field is set for the value axis. Otherwise, this feature is unavailable.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Show order number of each type of product in each province per year.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset ,  and click **Create Dashboard**.
4.  Click **Area chart** icon.
5.  Select required dimension fields and measurement fields.

    In the dimension list, locate the province and product\_type options and add them to the category axis area in sequence. In the measurement list, find the order\_number option and add it to the value axis area. 

    **Note:** Make sure that the dimension type of the province field has been switched from string to geographical information. For more information about how to switch the dimension field type, see [Example: Create a dashboard](intl.en-US/Quick Start/Example: Create a dashboard.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15332774451679_en-US.png)

6.  Drag the **product\_type** field to the color legend and click **Update**.

    **Note:** The color legend can be used when only one measurement field is set for the value axis. Otherwise, this feature is unavailable.

7.  On the **Style** tab, you can edit the title, layout, and legends of the chart.

    **Note:** For more information about Styles, see[Set chart data](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Set chart data.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15332774451680_en-US.png)

    -   In the Common Settings, select a **Dark**color as the background color.
    -   On the Style tab, select **stack**.
    -   On the layout tab, the display legend settings are displayed on **Right**.
    -   In the Axis, set the title of the horizontal axis as **Province**.
    -   In the Settings, set the color of **order\_number** as orange.
    After updating, the chart is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9125/15332774451682_en-US.png)

8.  Click **Save** to save current dashboard.

In the upper right corner, select **More** \> **Delete ** To delete the current chart.

