# Geo bubble {#concept_zrl_kk2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a geo bubble map. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A bubble map uses a map profile as its background and attaches bubbles to the map to indicate data values. It intuitively shows the related data indexes and data ranges of a country or region. For example, a bubble map can be used to show the passenger flows of multiple tourist sites or the per capita incomes of multiple regions.

A bubble map consists of a geological region and a bubble size. The geological region is determined by the data dimension, such as a province. The bubble size is determined by the data measurement, such as a transportation cost or an order quantity.

## Notice on creating a geo bubble map {#section_g5n_mk2_vdb .section}

You can set only one dimension for the geological region of a bubble map, and the dimension type must be of geological information, such as a region, a province, or a city. Set at least one bubble size and a maximum of five measurements.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order amount and average profits of multiple provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click Geo bubble icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **province** option and add it to the geological area. In the measurement list, locate the **order\_amt** and **order\_number** options and add them to the bubble size area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15353614441713_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and legends of the chart.
8.  Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

