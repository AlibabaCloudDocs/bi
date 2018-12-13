# Card chart {#concept_k5j_cr2_vdb .concept}

This section describes how to create a card chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A card chart displays business data or sales performance, which enables you to visually gain insight into the business environment and quickly make strategic adjustments to optimize sales processes. It offers an effective and direct solution to discover and fix problems.

A card chart consists of a sequence of cards with multiple labels and metrics. Labels are determined by data dimensions, such as area. Metrics are determined by data measures, such as order quantity and order amount.

## Note {#section_dx2_2r2_vdb .section}

For each card chart, one and only one dimension must be specified to determine labels. 1 to 10 measures can be specified to determine metrics.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities, order amounts, transportation costs, and profit amounts across multiple provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the **Card Chart** icon, and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measures.

    In the Dimensions list, select **province** and add it to Card Labels. In the Measures list, select **order\_number**, **order\_amt**, **shipping\_cost**, and **profit\_amt**, and add them to Card Metrics, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9136/15447042791760_en-US.png)

6.  Click **Update** to generate the chart.
7.  In the Style tab, you can change the title and style of the chart, and the number of cards in each row.
    -   General Configuration: Specify the main title of the chart, the font color, and the background color.
    -   Card Setting: Specify the template and style of the card.
    -   Series Setting: Specify the alias of the metric and the number of decimal places to keep for the metric value.
8.  Click the **Save** icon to save the dashboard.

To delete the chart, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

