# Stripe charts {#concept_zm3_422_vdb .concept}

Assume that you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). This section describes how to create a stripe chart. If you want to edit a dataset or create a dataset, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A stripe chart shows comparisons between categories. You can use a stripe chart to visualize data changes over a period of time or comparisons between categories. For example, you can show the working progress of employees in a project group.

Like [Line charts](intl.en-US/Quick Start/Create a report/Create charts/Line charts.md#), a stripe chart consists of the category axis and the value axis.

## Precautions {#section_hyy_q22_vdb .section}

You can set at least one dimension for the category axis such as province and product\_type. In addition, you can set at least one measure for the value axis such as order\_amt and profit\_amt. The Colors \(Dimensions\) area can take only one dimension.

**Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

The following scenario uses the company\_sales\_record dataset.

**Scenario: Compare shipping costs for various products of each municipality.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the Datasets page.
3.  Click **Create Dashboard** on the right side of the company\_sales\_record dataset.
4.  Click the **Stripe** icon and then a stripe chart appears in the display area of a dashboard.
5.  On the Dimensions list, drag **city** to the Filters area.

    You can search for municipalities from cities by using filters as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15447922651691_en-US.png)

6.  Click the **Filter** icon and select **Filter by Enumeration** in the dialog box that appears.
7.  Select four municipalities from the list or enter the names of them manually, and click **OK** as the following figure shows.

    ![](images/11402_en-US.png)

8.  Drag the **city** and **product\_type** fields to the Category Axis \(Dimensions\) area in turn.

    **Note:** You must ensure that you have changed the province field from the string type to the location type.

9.  On the Measures list, drag **shipping\_cost** to the Value Axis \(Measures\) area.
10. Drag **product\_type** to the Colors \(Dimensions\) area.

    **Note:** You can add dimensions to the Colors \(Dimensions\) area when only one measure is added to the Value Axis \(Measures\) area. Otherwise, you are not allowed to add dimensions to the Colors \(Dimensions\) area.

11. Click **Update** to update the chart.
12. On the Style tab, you can change some items such as the title, layout, legend, and axis format of a chart as the following figure shows.

    **Note:** For more information about the Style tab, see [Configure a chart](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Configure a chart.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15447922651693_en-US.png)

    -   In General config, select **Dark** as the background color.
    -   In Style, select **Stacked**.
    -   In Layout, select **Top** to show the legend.
    -   In Axis, select **Display scale** on the X-Axis tab.
    After you complete the configuration, the chart is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9127/15447922651695_en-US.png)

13. Click **Save** to save the dashboard.

If you want to delete the current chart, click More in the top-right corner of the chart and select **Delete** to delete the current chart.

