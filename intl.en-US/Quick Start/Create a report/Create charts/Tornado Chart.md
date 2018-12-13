# Tornado Chart {#concept_vl3_hjf_vdb .concept}

This section describes how to create a tornado chart. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A tornado chart is the combination of a tornado diagram and a funnel chart. Tornado diagrams can be used to compare different metrics between two objects, for example, the income and education levels between residents in two cities. Funnel charts can be used to show the conversion rates between stages of the business process and are suitable for business process analysis. You can see the percentage of visitors who turned into paying customers in a funnel chart easily.

A tornado chart combines the features of tornado diagrams and funnel charts. For example, when you compare the percentage of the migrant population, employment rate, and commercial housing transactions in Beijing and Shanghai, if a conversion relation exists between two items, the tornado chart can show the difference between multiple metrics, and also display the conversion rates between comparative items.

If no conversion relation exists, the diagram functions the same as a tornado diagram. If a conversion relation exists between two comparative items and only one metric is defined, the diagram functions the same as a funnel chart.

A tornado chart consists of a comparative item and multiple metrics. Comparative items are determined by data dimensions, such as area and product type. Metrics are determined by data measures, such as order quantity and order amount.

## Note {#section_vrj_jjf_vdb .section}

For each tornado chart, one and only one dimension must be specified to determine the comparative item. At least one measure must be specified to determine metrics.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantities, profits, and average profits of different types of products.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the tornado chart icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measures.

    In the Dimensions list, select **Product\_type** and add it to Comparative Item. In the Measures list, select **order\_number**, **profit\_amt**, and **average\_profit**, and add them sequentially to Metric, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15447055541824_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and layout of the diagram and hide the conversion rate.
    -   tornado charts offer two types of layouts. You can also change the layout based on your habits.
    -   You can also change the position of the legend, adjust the color scheme of the diagram, and hide the conversion rates.
8.  Click the **Save** icon to save the dashboard.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

