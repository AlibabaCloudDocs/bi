# Gauge {#concept_mmt_3n2_vdb .concept}

This section describes how to create a gauge. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Similar to the dashboard in your car, a gauge clearly displays the range of a metric. You can view the progress of the current task or if a metric will exceed its range. For example, you can use a gauge to show the inventory status of an item and replenish the item accordingly.

A gauge displays the value of a metric using a pointer that moves along a scale. The angle of the pointer is determined by a data measure, such as discount or profit amount.

## Note {#section_w4x_kn2_vdb .section}

For each gauge, one and only one measure must be specified to determine the angle of the pointer.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Use a gauge to display order amounts**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the **Gauge** icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data measure.

    **Note:** The system automatically adjusts the angle of the pointer and the text displayed in the tooltip.

    In the Measures list, select **order\_amt** and add it to indicator angle area or tooltip area, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9132/15447031691734_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title, layout, and tooltip of the diagram and hide the scale.
    -   General Configuration: Specify the main title of the diagram, the font color, and the background color.
    -   Layout: Specify whether to hide the legend.
    -   Color Ranges: Configure subranges.
    -   Series Setting: Specify the alias of the metric and the number of decimal places to keep for the metric value.
8.  In the **Color Ranges** section, click **Add** to add a subrange and enter the start and end values of this range.

    For example, you can set the start value to 100 and end value to 1000. The title of the subrange can be set to Net Profit, as shown in the following figure:

9.  Click **Update** and the subrange appears in the gauge.
10. Click the **Save** icon to save the dashboard.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

