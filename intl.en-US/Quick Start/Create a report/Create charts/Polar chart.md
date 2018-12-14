# Polar chart {#concept_wby_whf_vdb .concept}

This section describes how to create a polar chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A polar chart can be used to display data changes over time or compare metric values. It is suitable for enumeration. For example, compare data across different regions.

Similar to [Pie chart](intl.en-US/Quick Start/Create a report/Create charts/Pie chart.md#), a polar chart consists of sectors of varying slice labels and arc radiuses. Slice labels are determined by data dimensions, such as area and product type. Arc radiuses are determined by data measures, such as order quantity and order amount.

## Note {#section_p5q_yhf_vdb .section}

For each polar chart, one and only one dimension must be specified to determine slice labels. This dimension must contain 3 to 12 variables. One and only one measure must be specified to determine arc radiuses.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities across multiple areas**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Polar Chart icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measure.

    In the Dimensions list, select **area** and add it to Slice Label. In the Measures list, select **order\_number** and add it to Arc Radius, as shown in the following figure:

    **Note:** Make sure you have changed the data type of area from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9139/15447615751816_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title and legend of the chart, the style of the metric values.
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

