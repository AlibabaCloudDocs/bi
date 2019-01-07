# Bar charts {#concept_bnq_fd2_vdb .concept}

Assume that you have read [EN-US\_TP\_9109.md\#](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [EN-US\_TP\_9111.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create a line chart. If you want to create a dataset or eidt a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A bar chart shows comparisons among discrete categories. You can use a bar chart to visualize data changes over a period of time or comparisons among discrete categories. For example, you can show the comparison of the traffic flow of vehicles over different periods of time at a crossing.

Like [EN-US\_TP\_9124.md\#](intl.en-US/User Guide/Create dashboards/Create charts/Line charts.md#), a bar chart consists of the category axis and the value axis.

## Precautions {#section_pxd_3d2_vdb .section}

You can set at least one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Colors \(Dimensions\) area can take only one dimension.

**Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

The following scenario is based on the company\_sales\_record dataset.

**Scenario: Compare the shipping cost for different products of provinces of East China.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click the **Create Dashboard** icon on the right side of the company\_sales\_record dataset.
4.  Click the **Bar** icon, a bar chart appears in the display area of the dashboard.
5.  On the dimensions list, drag **area** to the Filters area.

    You can search for the East China area by using filters as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15468528391685_en-US.png)

6.  Click the **Filter** icon. Select **Filter by Enumeration** in the Set Filter dialog box that appears as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9126/15468528391686_en-US.png)

7.  Select East China and click **OK**.
8.  Drag **province** and **product\_type** to the Category Axis \(Dimensions\) area in turn.

    **Note:** You must ensure that you have changed the province field from the string type to the location type.

9.  On the Measures list, drag **shipping\_cost** to the Value Axis \(Measures\) area.
10. Drag the **product\_type** field to the Colors \(Dimensions\) area.

    **Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

11. Click **Update** to update the chart.
12. On the Style tab, you can change some items such as the title, layout, legend, and axis format of a chart.

    **Note:** For more information about the Style tab, see [EN-US\_TP\_9114.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Configure a chart.md#).

13. Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the top-right corner of the chart and select **Delete**.

