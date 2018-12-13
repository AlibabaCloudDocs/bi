# TreeMap {#concept_q2y_4gf_vdb .concept}

This section describes how to create a treemap. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Treemaps can be used to compare the proportions between variables easily.

A treemap consists of nested rectangles of multiple different sizes and labels. The labels of rectangles are determined by data dimensions, such as package design. The sizes of rectangles are determined by data measures, such as transportation cost.

## Note {#section_byf_rgf_vdb .section}

For each treemap, one and only one dimension can be specified to determine the labels of rectangles. This dimension can have a maximum of 12 dimension values. One and only measure can be specified to determine the sizes of rectangles.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities of different products**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the TreeMap icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measure.

    In the Dimensions list, select **Product\_type** and add it to Rectangle Label. In the Measures list, select **order\_number** and add it to Rectangle Size, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9137/15447045061803_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and legend of the treemap.
8.  Click the **Save** icon to save the dashboard.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

