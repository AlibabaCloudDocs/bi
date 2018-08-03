# Tornado chart {#concept_vl3_hjf_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a tornado chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A tornado chart is a combination of a tornado chart and a funnel chart. A tornado can be used to compare the data of different indicators of two objects, for example, the salary and education degree of citizens in two cities. A funnel chart can also be used to show the conversion rate between each phase. It can apply to analysis of complex business procedures. For example, a funnel chart can intuitively show the rate of visitors that finally buy any product after accessing the website.

A tornado chart combines the features of the tornado chart and funnel chart. For example, when you compare the migrant population ratio, employment rate, and transaction volume of commercial residential buildings in Beijing and Shanghai, if there is a funneling between compared, you can use a tornado funnel chart to show the data difference of each indicator between two cities and display the funnel hierarchy of the compared items.

If there is no funneling effect between compared items, a common tornado chart is displayed. If there is a funneling effect between compared items, but these items belong to only one object, a common funnel chart is displayed.

A tornado chart consists of a comparison subject and comparison indicators. Each comparison subject is determined by the data dimension, such as the region or product type. Each comparison indicator is determined by the data measurement, such as the order quantity or order amount.

## Notice on creating a tornado chart {#section_vrj_jjf_vdb .section}

The comparison subject of a tornado chart can have only one dimension. Comparison indicators must have at least one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity, profit amount, and average profit of different types of project.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click tornado chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **product\_type** option and add it to the comparison area. In the measurement list, locate the **order\_number**, **profit\_amt**, and **average\_profit** options and add them to the comparison area in sequence, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15332649551824_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the chart title, layout, and legend positions and set the color scheme and whether to display the conversion rate.
    -   A tornado chart provides two chart layouts for your choice.
    -   In the Style menu, you can change legend positions, set the color scheme of the chart, and set whether to display the conversion rate on the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

