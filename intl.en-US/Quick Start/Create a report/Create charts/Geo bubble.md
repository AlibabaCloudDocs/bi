# Geo bubble {#concept_zrl_kk2_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a geo bubble map. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A bubble map uses a map profile as its background and attaches bubbles to the map to indicate data values. It intuitively shows the related data indexes and data ranges of a country or region. For example, a bubble map can be used to show the passenger flows of multiple tourist sites or the per capita incomes of multiple regions.

A bubble map consists of a geological region and a bubble size. The geological region is determined by the data dimension, such as a province. The bubble size is determined by the data measurement, such as a transportation cost or an order quantity.

## Notice on creating a geo bubble map {#section_g5n_mk2_vdb .section}

You can set only one dimension for the geological region of a bubble map, and the dimension type must be of geological information, such as a region, a province, or a city. Set at least one bubble size and a maximum of five measurements.

[Chinese and English names of countries](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/55644/cn_zh/1499054271452/%E5%9B%BD%E5%AE%B6%E4%B8%AD%E8%8B%B1%E6%96%87%E5%90%8D%E7%A7%B0%E5%8C%B9%E9%85%8D.csv) and [Name of city-province\_municipality-region](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/55644/cn_zh/1499054305079/%E5%B8%82-%E7%9C%81_%E7%9B%B4%E8%BE%96%E5%B8%82-%E5%8C%BA%E5%9F%9F%E5%90%8D%E7%A7%B0%E5%8C%B9%E9%85%8D.csv) are provided here for your download and reference.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order amount and average profits of multiple provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click Geo bubble icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **province** option and add it to the geological area. In the measurement list, locate the **order\_amt** and **order\_number** options and add them to the bubble size area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15332635781713_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and legends of the chart.
8.  Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

