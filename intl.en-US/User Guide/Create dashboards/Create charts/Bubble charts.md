# Bubble charts {#concept_265020 .concept}

This topic provides you with an overview and applicable scenarios for bubble charts. You will also learn how to delete bubble charts.

Before reading this topic, you can familiarize yourself with the [Dashboard overview](reseller.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [Basic dashboard operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) topics. If you want to edit a dataset or create a new dataset, see [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Overview {#section_267_ovs_vdd .section}

Bubble charts visualize the distribution and aggregation of data based on bubble locations and sizes.

Each bubble chart has an X-axis and Y-axis. The X-axis is based on a dimension, such as province. The Y-axis and bubble size are each based on a measure such as order\_amt.

## Sample bubble chart {#section_dzg_7bb_kfc .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/218470/156265337347246_en-US.png)

## Precautions {#section_p3k_nks_mr1 .section}

X Axis \(Dimensions\): represents only one dimension.

Y Axis \(Measures\): represents only one measure.

Bubble Size \(Measures\): represents only one measure.

## Create a bubble chart {#section_o45_l9h_3k4 .section}

Sample scenario: compares the unit prices and the order quantities of different products. The following example is based on the company\_sales\_record dataset.

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the Datasets page.
3.  Locate the company\_sales\_record dataset and click **Create Dashboard** next to the dataset.

    **Note:** If you are using **Quick BI Enterprise Standard**, you need to select **Standard** or **Full Screen** to as the display mode. The following takes the **Standard** mode as an example.

4.  Click the Bubble Chart icon to add a bubble chart to the dashboard.
5.  On the Data tab, select the required dimension and measures.

    On the list of dimensions, locate the **product\_type** dimension and add the dimension to the X Axis \(Dimensions\) field. On the list of measures, locate the **price** measure and add it to the Y Axis \(Measures\) field, and then locate the **order\_number** measure and add it to the Bubble Size field.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/218470/156265337347249_en-US.png)

6.  Click **Update** to update the chart.
7.  In the Style tab, you can change the title, layout, and legend of the chart as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/218470/156265337447251_en-US.png)

8.  Click **Save** to save the dashboard.

## Configure settings on the Style tab {#section_pg5_ji6_ghi .section}

-   In the Basic Information section, you can configure the title of a chart.
-   In the Layout section, you can select where to show a legend and whether to show a tooltip.

Click Update after you complete configurations. A sample bubble chart is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/218470/156265337447252_en-US.png)

## Delete a chart {#section_om4_3c4_nxc .section}

If you want to delete a chart, click the **More** icon in the upper-right corner of the chart and select **Delete** from the drop-down list.

