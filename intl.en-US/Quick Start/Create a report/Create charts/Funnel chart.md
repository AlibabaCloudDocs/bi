# Funnel chart {#concept_u3s_1q2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a funnel chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

The funnel chart can be used to analyze business procedure that is relatively standard and has a long cycle and many phases. By comparing business data at each phase using a funnel chart, you can intuitively locate the problem and find the cause. The funnel chart can also be used to show the conversion rate between each phase. It can apply to analysis of complex business procedures. For example, a funnel chart can intuitively show the rate of visitors that finally buy any product after accessing the website.

A funnel chart consists of funnel layer labels and the funnel layer width. A funnel layer label is determined by the data dimension, such as the region. A funnel layer width is determined by the data measurement, such as the order amount.

## Notice on creating a funnel chart {#section_vtk_cq2_vdb .section}

Both the tier label and the tier area can have only one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order amount of different regions.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page. 
3.  Select the company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click funnel chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area** option and add it to the tier label area. In the measurement list, locate the **order\_amt** option and add it to the tier area, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9135/15332644761752_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title, layout, and legends of the funnel chart.
    -   General config: Configure the title of the chart, the color of the font, and the background color.
    -   Layout: Configure where the legend is displayed in the chart.
    -   Measure: Format the related measure and set the number of digits displayed for the decimal.
    -   Block: Set the display color of the block.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

