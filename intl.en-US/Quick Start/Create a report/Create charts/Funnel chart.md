# Funnel chart {#concept_u3s_1q2_vdb .concept}

This section describes how to create a funnel chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Funnel charts are suitable for analyzing business processes that involve a sequence of activities and span a long period of time. By comparing the business data between different stages, you can easily identify potential problems in the business process. Funnel charts can be used to show the conversion rates between stages of the business process. For example, you can see the percentage of visitors who became paying customers in a funnel chart easily.

A funnel chart consists of a number of tiers with varying labels and widths. The labels of tiers are determined by data dimensions, such as area. The widths of tiers are determined by data measures, such as order amount.

## Note {#section_vtk_cq2_vdb .section}

For each funnel chart, one and only one dimension must be specified to determine the labels of tiers. One and only one measure must be specified to determine the widths of tiers.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order amounts across multiple areas**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Funnel Chart icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measure.

    In the Dimensions list, select **area** and add it to Tier Labels. In the Measures list, select **order\_amt** and add it to Tier Area, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/15447040851752_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title, layout, and legend of the chart.
    -   General Configuration: Specify the main title of the chart, the font color, and the background color.
    -   Layout: Change the position of the legend.
    -   Measure: Change the style of the measure and specify the number of decimal places to keep for the value.
    -   Tier: Specify the color of tiers.
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

