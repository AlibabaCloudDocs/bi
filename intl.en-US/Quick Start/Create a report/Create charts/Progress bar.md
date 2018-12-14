# Progress bar {#concept_fzz_3rf_vdb .concept}

This section describes how to create a progress bar. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A progress bar displays the progress of the current task.

A progress bar consists of multiple progress metrics. Progress metrics are determined by data measures, such as order quantity.

## Note {#section_bwn_mrf_vdb .section}

-   For each progress bar, one to five measures can be specified to determine the progress metrics.
-   To use progress bars, you need to click **Style** \> **Series Setting** to specify the maximum and minimum values of progress metrics.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Use a progress bar to display the order quantity**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the **Progress bar** icon and the corresponding legend is displayed.
5.  Click the Data tab to select data measures.

    In the Measures list, select **order\_number** and add it to Progress indicator/Measure, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15447568031892_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title and legend of the diagram, and set an alias for the metric, as follows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9147/15447568031893_en-US.png)

8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

