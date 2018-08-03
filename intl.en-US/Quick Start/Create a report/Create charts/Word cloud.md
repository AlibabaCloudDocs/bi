# Word cloud {#concept_lnr_m3f_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a word cloud. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A word cloud intuitively shows the word frequency. It can be used to prepare user persona and user labels.

A word cloud consists of word labels and the word size. The word is determined by the data dimension, such as the customer name or product type. The word size is determined by the data measurement, such as the profit or unit price.

## Notice on creating a word cloud {#section_p14_43f_vdb .section}

Word of a word cloud can have only one dimension, and the word size can have only one measurement.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order quantity of different provinces.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**.
4.  Click word cloud icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the province option and add it to the word area. In the measurement list, locate the **order\_number** option and add it to the word size area, as shown in the following figure.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9140/15332648311819_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set the title and legends of the chart.
8.  Click the **Save** icon to save the dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

