# Geo bubble charts {#concept_zrl_kk2_vdb .concept}

Assume that you have read [Dashboard overview](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [EN-US\_TP\_9111.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create a line chart. If you want to edit a dataset or create a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A geo bubble chart is a map of a country or an area that is attached with bubbles to represent the amount of data. You can use a geo bubble chart to graphically display metrics for each country or area and the distribution of these countries or areas. For example, you can show the traffic flow of tourists for each tourist attraction or show the per capita income for each area.

A geo bubble chart consists of locations and bubbles of different sizes. Locations are determined by a dimension such as the province field and the size of bubbles are determined by a measure such as shipping\_cost and order\_amt.

## Precautions {#section_g5n_mk2_vdb .section}

You can set up to one dimension and the dimension type must be geographic information, such as area, province, and city. In addition, the bubble size area can be set from one to five measures.

The following scenario uses the company\_sales\_record dataset.

**Scenario: Compart the number of orders and the amount of profit for each province.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.
4.  Click the Geo Bubble icon and a geo bubble chart appears in the display area of a dashboard.
5.  On the Data tab, select the required dimensions and measures.

    On the Dimensions list, drag **province** to the Location \(Dimension\) area. On the Measures list, drag **order\_amt** and **profit\_amt** to the Bubble Size \(Measures\) area in turn as shown in the following figure.

    **Note:** Ensure that you have changed the province field from the string type to the location type.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9129/15499437321713_en-US.png)

6.  Click **Update** to update the chart.
7.  On the Style tab, you can change some items such as the title, layout, and legend of a chart.
8.  Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the upper-right corner of the chart and select **Delete** to delete the current chart.

