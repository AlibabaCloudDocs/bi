# Tornado-leaned funnel charts {#concept_vl3_hjf_vdb .concept}

This topic describes how to create a tornado-leaned funnel chart. We recommend that you read [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) before you create a tornado-leaned funnel chart. You also can edit or create a dataset. For more information, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_k4c_bln_xgb .section}

A tornado-leaned funnel chart is the combination of a tornado chart and a funnel chart. Tornado charts can be used to compare different metrics between two objects, such as the income and education levels between residents in two cities. Funnel charts are used to show the rate of conversion between each step of a process. It can be used to analyze complex business procedures. For example, you can use a funnel chart to clearly show the rate of visitors that finally buy any product after they access the website.

A tornado-leaned funnel chart combines the features of tornado charts and funnel charts. For example, when you compare the percentage of the migrant population, employment rate, and commercial real estate transaction in Beijing and Shanghai, if a conversion relation exists between these metrics of the two cities, the tornado-leaned funnel chart can show the difference and conversion rates for each city between these metrics.

If no conversion relations exist, the chart functions as a tornado chart. If a conversion relation exists between metrics and only one object is defined for these metrics, the chart functions as a funnel chart.

A tornado-leaned funnel chart consists of objects and metrics. Objects are determined by data dimensions, such as the area and product type. Metrics are determined by data measures, such as the order quantity and order amount.

## Example of a tornado-leaned funnel chart {#section_uf5_dln_xgb .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/155721420439664_en-US.png)

## Precautions {#section_zcc_fln_xgb .section}

Only one dimension can be set for the objects. Set at least one measure for metrics.

## Scenario: Compare the order quantities, profits, and average profits for different types of products {#section_x3m_gln_xgb .section}

The following scenario is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  On the homepage, click the Workspace tab. In the left-side navigation pane, enter a group workspace name in the text box, or click the triangle next to the text box and select a group workspace from the drop-down list. Click **Datasets** to go to the All Items tab.
3.  Click the **Create Dashboard** icon in the Actions column corresponding to the company\_sales\_record dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you must select **Standard** or **Full Screen**. The following scenario uses **Standard** as an example.

4.  In the toolbar, click the Tornado-leaned Funnel Chart icon. The blank tornado-leaned funnel chart is automatically displayed in the display section.
5.  Click the Data tab and select the required measures and dimension.

    In the Dimensions section, double-click **product type**, or drag and drop it to the Metrics \(Dimensions\) section. In the Measures section, double-click **order number**, **profit amt**, and **average profit**, or drag and drop them to Metrics \(Measures\) in order, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15572142051824_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can set Show Title, Layout, and Show Conversion Rates, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15572142051825_en-US.png)

    -   Tornado-leaned funnel charts support two display modes. You can also select one mode as needed.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15572142051827_en-US.png)

    -   You can also set Legend Position and Show Conversion Rates, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9141/15572142051828_en-US.png)

8.  Click **Save** to save the dashboard.

## Delete a chart {#section_c3p_lln_xgb .section}

Move the pointer over the upper-right corner of the window. Click the More icon that appears and choose **More Actions** \> **Delete** to delete the current chart.

