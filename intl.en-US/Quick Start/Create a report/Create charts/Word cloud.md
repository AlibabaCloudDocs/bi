# Word cloud {#concept_lnr_m3f_vdb .concept}

This section describes how to create a word cloud. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A word cloud displays the frequency of words clearly. It is suitable for creating user personas and user tags.

A word cloud consists of words of varying sizes. Labels are determined by data dimensions, such as customer name and product name. Metrics are determined by data measures, such as profit amount and unit price.

## Note {#section_p14_43f_vdb .section}

For each word cloud, one and only one dimension must be specified to determine labels. One and only one measure must be specified to determine metrics.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities across different provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Word Cloud icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measure.

    In the Dimensions list, select **province** and add it to Word. In the Measures list, select **order\_number** and add it to Word Size, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15447048001819_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title of the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

