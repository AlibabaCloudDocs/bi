# Pie charts {#concept_gwq_4f2_vdb .concept}

Assume that you have read [Dashboard overview](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [EN-US\_TP\_9111.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create a line chart. If you want to edit a dataset or create a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A pie chart shows a series of values for items in a dimension. Each item shown in a pie chart has a unique color or texture. Each sector in a pie chart represents one item in the dimension. Sector size represents the proportion of the value for the selected measure that the item represents compared to the whole dimension. For example, you can show the expenditure of five social insurances and one housing fund in proportion to the total personal income or the sales volume of a certain automobile brand in proportion to the total sales volume of all the brands.

A pie chart consists of sectors. The label of a sector is determined by a dimension such as the area field and the product\_type field. The degree of an angle is determined by a measure such as order\_amt and profit\_amt.

## Precautions {#section_cmv_qf2_vdb .section}

You can set at least one dimension in which the number of different values is less than or equals to 12 for the Slice Label \(Dimensions\) area such as area and product\_type. In addition, you can set at least one measure for the Arc Angle \(Measures\) area such as order\_amt and profit\_amt.

The following scenario uses the company\_sales\_record dataset.

**Scenario: Compare shipping costs for various areas.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.
4.  Click the Pie icon, a pie chart appears in the display area of the dashboard.
5.  On the Data tab, select required dimensions and measures.

    On the dimensions list, drag **area** to the Slice Label \(Dimensions\) area. On the Measures list, drag **shipping\_cost** to the Arc Angle \(Measures\) as shown in the following figure.

    **Note:** You must ensure that you have changed the province field from the string type to the location type.

6.  Click **Update** to update the chart.
7.  On the Style tab, you can change some items such as the title, layout, legend, and axis format of a chart.
8.  Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the upper-right corner of the chart and select **Delete**.

