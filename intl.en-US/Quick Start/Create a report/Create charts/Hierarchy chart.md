# Hierarchy chart {#concept_esg_blf_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a hierarchy chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A hierarchy chart displays the organizational relationship of hierarchical data using a tree structure and organizes objects using a parent-child structure. It can be used for enumeration. For example, if you want to view the income of each prefecture-level city in a province, you can use a hierarchychart to show the parent-child relationship of the province and its prefecture-level cities. Hierarchy charts apply to analysis related to organizational structures, for example, staff structure of a company or department structure of a hospital.

A hierarchy chart consists of node metrics and node labels. The node label is determined by the data dimension, such as the region or product type. The node metrics is determined by the data measurement, such as the order quantity or order amount.

## Notice on creating a hierarchy chart {#section_jg5_2lf_vdb .section}

The node labels must have at least two dimensions, and the dimension fields have parent-child relationship. The node metrics must have at least one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity of different products in provinces in different regions.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**. The dashboard editing page is displayed.
4.  Click hierarchy chart icon
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **area**, **province**, and **product\_type** options and add them to the node label area in sequence. The sequence of these options is the parent-child relationship displayed on the chart. In the measurement list, locate the **order\_number** option and add it to the node metrics area, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/15332650361844_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set the title, layout, and design of the chart.
    -   A hierarchy chart supports three layouts. You can select the expansion mode \(root nodes are merged by default\) and display mode of parent and child nodes based on your needs.
    -   You can edit the display hierarchy of the chart in the design menu and manually enter the number of hierarchy levels. You can select a main path through the corresponding field. The main path is displayed in a different color from other paths. You can load the toolbar to the chart so that you can edit the chart in preview mode or on the dashboard.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

