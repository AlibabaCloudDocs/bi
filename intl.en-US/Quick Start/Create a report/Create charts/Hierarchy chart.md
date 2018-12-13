# Hierarchy chart {#concept_esg_blf_vdb .concept}

This section describes how to create a hierarchy. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A hierarchy uses the tree structure to display and organize hierarchical data. It is an implementation of the enumeration method. For example, when reviewing the revenues of the prefecture-level cities in one province, the relationships between the province and prefecture-level cities can be displayed as parent-child structures. Hierarchys are used for analyzing hierarchical data and creating staff organization charts and department organization charts.

A hierarchy contains a sequence of nodes with different labels and metrics. Each node label is determined by data dimensions, such as area and product type. Each node metric is determined by data measures, such as order quantity and order amount.

## Note {#section_jg5_2lf_vdb .section}

For each hierarchy, at least two dimensions must be specified to determine node labels. These two dimensions should have a parent-child relationship. At least one measure must be specified to determine the node metric.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities of different products across provinces and areas**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the hierarchy icon and the corresponding information is displayed.
5.  Click the Data tab to select data dimensions and data measure.

    In the Dimensions list, select **Area**, **Province**, and **Product Type**, and add them sequentially to Node Label. This order determines their hierarchical relationships in the diagram. In the Measures list, select **Order Quantity** and add it to Node Metric, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Area and Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9142/15447067351844_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title, layout, and design of the diagram.
    -   Hierarchys support three types of layouts. You can also change the style of tree nodes based on your habits. The root nodes are merged together by default.
    -   You can edit the levels of hierarchy in the menu bar and manually enter the number of levels. You can specify a primary path based on the field information so that the primary path has a different color to other paths. You can also add a toolbar to the diagram so that you can easily edit the diagram in preview or through the dashboard.
8.  Click the **Save** icon to save the dashboard.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

