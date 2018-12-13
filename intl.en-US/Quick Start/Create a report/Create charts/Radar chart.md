# Radar chart {#concept_xkk_b42_vdb .concept}

This section describes how to create a radar chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Radar charts can be used to compare multiple variables under different metrics. You can easily understand the distribution of metrics across different variables. For example, you can use a radar chart to compare sales across multiple areas.

A radar chart consists of a sequence of radius labels with varying radius. Radius labels are determined by data dimensions, such as product type. Radius are determined by data measures, such as transportation cost.

## Note {#section_xbs_d42_vdb .section}

For each radar chart, one or two dimensions can be specified to determine radius labels. The specified dimensions must contain 3 to 12 variables. At least one measure must be specified to determine Radius.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities and order amounts across areas**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Radar icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measures.

    In the Dimensions list, select **area** and add it to radius label. In the Measures list, select **order\_number** and **order\_amt**, and add them sequentially to radius, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Area from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9133/15447036551744_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the **Style** tab, you can change the title, layout, and legend of the chart as follows:
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

