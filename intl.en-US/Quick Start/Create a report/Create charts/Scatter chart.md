# Scatter chart {#concept_w3v_cp2_vdb .concept}

This section describes how to create a scatter chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Scatter charts display the distribution and correlation of data.

Scatter charts use the X and Y axes to plot data points. The colors of data points are determined by data dimensions, such as product type. The X and Y axes are determined by data measures.

## Notes {#section_nqt_2p2_vdb .section}

For each scatter chart, one dimension must be specified to determine the colors of data points. This dimension may contain up to 1,000 variables.

One to three data measures can be specified for the X axis.

One data measure can be specified for the Y axis.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the unit prices and order amounts of different products**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Scatter Chart icon and the corresponding information is displayed.
5.  Click the Data tab to select the data dimension and data measures.

    In the Dimensions list, select **product\_type** and add it to Color. In the Measures list, select **price** and **order\_number**, and add them to the Y axis and X axis respectively, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9134/15447038781750_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title, layout, and legend of the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

