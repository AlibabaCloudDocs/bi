# Drilling, filter interaction, and hyperlink {#concept_arc_kmb_bfb .concept}

Quick BI supports drilling, filter interaction, and hyperlinks for multi-dimension data analysis. This topic describes the scenarios and instructions about these features.

## Overview {#section_wrl_chx_pgb .section}

-   Drilling: In the dashboard, click a section in a chart or a field in a table in the dashboard. The granularity of analysis changes as the dimension level changes.
-   Filter interaction: In the dashboard, click a section in a chart. Other charts related to the chart change accordingly.
-   Hyperlink: In the dashboard, click a field in a chart and you are taken to the linked page. You can use global parameters and URLs for page jumping.

    **Note:** 

    Hyperlinks only apply to cross tables and scatter charts. Using global parameters for page jumping only applies to group workspaces. For more information about group workspaces, see [Concepts](reseller.en-US/User Guide/Organization management/Manage workspaces/Concepts.md).


## Scenarios { .section}

The following example describes how to perform filter interactions among charts, drill through a hierarchy to change the granularity of data analysis, and jump to the Order information pages by using hyperlinks in Quick BI.

The example uses the company\_sales\_record dataset. You can click [sample sales data](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/47483/cn_zh/1483006983645/company_sales_record_utf8.csv?spm=a2c4g.11186623.2.4.PhbClR&file=company_sales_record_utf8.csv) and create the same dataset based on the downloaded CSV file. For more information about datasets, see [Upload local files](reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#) and [Create a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Procedure:

1.  [Edit a dataset](reseller.en-US/User Guide/Create dashboards/Visualization analysis/Drilling, filter interaction, and hyperlink.md#section_lfw_xnc_bfb)
2.  [Create a dashboard](reseller.en-US/User Guide/Create dashboards/Visualization analysis/Drilling, filter interaction, and hyperlink.md#section_ttn_x3c_bfb)
3.  [Set drilling](reseller.en-US/User Guide/Create dashboards/Visualization analysis/Drilling, filter interaction, and hyperlink.md#section_hdh_nrc_bfb)
4.  [Set filter interactions](reseller.en-US/User Guide/Create dashboards/Visualization analysis/Drilling, filter interaction, and hyperlink.md#section_pgd_gnc_bfb)
5.  [Set hyperlinks](reseller.en-US/User Guide/Create dashboards/Visualization analysis/Drilling, filter interaction, and hyperlink.md#section_ytw_xsc_bfb)

## Edit a dataset {#section_lfw_xnc_bfb .section}

Make sure that you have converted the dimension type of the **area**, **province**, and **city** fields to Geo and have added them to the same hierarchy.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311424_en-US.png)

## Create a dashboard {#section_ttn_x3c_bfb .section}

-   Create the **company's market data** dashboard

    1.  Create a dashboard named **company's market data** based on the company\_sales\_record dataset.
    2.  Create a pie chart as shown in the following figure and name it **Regional order proportion analysis**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311418_en-US.png)

    3.  Create a colored map as shown in the following figure and name it **Regional sales**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311419_en-US.png)

    4.  Create a cross table as shown in the following figure and name it **Order information**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311420_en-US.png)

    After the creation, the **company's market data** dashboard is as follows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311422_en-US.png)

-   Create the **Order profits** dashboard

    Create a dashboard to show order profits. Name the dashboard **Order profits** and create a cross table called **Order profits**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161311423_en-US.png)


## Set drilling {#section_hdh_nrc_bfb .section}

You need to manually enable the drilling feature. Click the Drilling icon as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161332108_en-US.png)

You can set a drilling hierarchy as follows.

-   Use the hierarchy in the dataset: When the selected dimension of a dataset contains a hierarchy, the hierarchy is displayed by default. You can modify the hierarchy as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161332109_en-US.png)

-   Customize the hierarchy: When the selected dimension of a dataset does not contain a hierarchy, you can customize the hierarchy and drag the drill dimension to the **Drill \(Dimensions\)** section.

**Note:** You can enable drilling for a maximum of three dimensions in a cross table. Other charts support a maximum of one drill dimension. You can set a maximum of six levels of a hierarchy.

After the settings are complete, the drill icon appears on the left of the chart title as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161332110_en-US.png)

-   Drill down: In the **Regional order proportion analysis** pie chart, click the **South** slice and the pie chart based on the provinces of **South** appears. In the lower-left corner of the chart, the values of drill dimensions with higher levels are displayed.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411433_en-US.png)

-   Drill up: Click **area** to drill up to the area-level data.


## Filter interactions {#section_pgd_gnc_bfb .section}

1.  In the **company's market data** dashboard, select the **Regional order proportion analysis** pie chart and click the **Advanced** tab in the **Graphic Design** panel .

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411478_en-US.png)

2.  Click the pen icon next to **Filter Interaction** .
3.  In the **Filter Interaction** dialog box that appears, select the linked field **area**, the cross table **Order information**, and the colored map **Regional sales**. Click **OK**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411429_en-US.png)

4.  In the **Regional order proportion analysis** pie chart, click a slice. Click the **South** slice and click Filter Interaction.

Both the **Order information** cross table and the **Regional sales** colored map show the sales details in the **Se** area. Move the pointer over the upper-right corner of the colored map and the filter value appears.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411431_en-US.png)

## Hyperlinks {#section_ytw_xsc_bfb .section}

**Parameter**

Scenario: Click **Office** in the **Order information** cross table and the **Order profits** dashboard is jumped to automatically. All **Office** orders are displayed.

-   **Configure global parameters** 

    **Note:** The following example uses global parameters for page jumping. You need to set global parameters first.

    1.  On the **Order profits** dashboard page, click the **Global Variables** icon.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161441312_en-US.png)

    2.  In the **Global Variables** dialog box that appears, perform the configurations as shown in the following figure and click **OK**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411435_en-US.png)

-   **Configure a hyperlink** 

    1.  In the **company's market data** dashboard page, select the **Order information** cross table, click the **Advanced** tab in the **Graphic Design** panel.
    2.  Click the pen icon next to **Hyperlink**.
    3.  In the **Hyperlink** dialog box, perform the configurations as shown in the following figure and click **OK**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/20226/155712161411438_en-US.png)

    After configurations are complete, the **product\_type** column values in the **Order information** cross table are displayed as hyperlinks.

-   **Page jumps** 

    Click **Office** in the **Order information** cross table, the **Order profits** dashboard is jumped to automatically. Only orders with **Office** as the value of the corresponding **product\_type** field are displayed.


**External link**

You can jump to specified URLs such as web UIs of customer systems by using the external link feature.

1.  Select the **Order information** cross table and click the **Advanced** tab in the **Graphic Design** panel.
2.  Click the pen icon next to **Hyperlink**.
3.  On the **Hyperlink** dialog box, select the fields that you want to hyperlink and select **External Link** as the hyperlinking method. Enter a URL and click **OK**.

    **Note:** You can add parameters to URLs by entering them manually or by double-clicking the fields in the Add Dimensions list.

4.  Click the hyperlinked field values and the corresponding URL is jumped to.

