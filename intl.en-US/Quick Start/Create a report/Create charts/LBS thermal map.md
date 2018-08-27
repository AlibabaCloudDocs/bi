# LBS thermal map {#concept_brr_dnf_vdb .concept}

**Note:** LBS thermal map is only applied to **Quick BI Professional Edition**。

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create an LBS thermal map.  For more information about dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

Similar to a [Geo map](intl.en-US/Quick Start/Create a report/Create charts/Geo map.md#), an LBS thermal map uses different colors to demonstrate the data values and ranges.

An LBS thermal map consists of geographical areas and LBS thermal depths. Geographical areas are determined by data dimension, longitude, and latitude, such as province. LBS thermal depths are determined by data measures, such as order amount or profit amount.

## Limitations on creating an LBS thermal map {#section_l3p_hnf_vdb .section}

You can set only one dimension for the geographical region of a LBS thermal map and the dimension type must be the geographical information. You can set up to five LBS Thermal depths \(measures\).

The following scenario uses the company\_sales\_record dataset and standard dashboard mode as an example.

**Scenario: Create an LBS thermal map to show shipping cost and order amount of each province.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select the company\_sales\_record dataset, and click **Create Dashboard** to go to the dashboard editing page.
    -   If you are using **Standard** or **Advanced** edition, the page automatically jumps to the **Standard** edit page.
    -   If you are using **Professional Edition**, you need to manually select either **Standard** or **Fullscreen** mode. The following takes the **Standard** as an example.
4.  Click the **LBS thermal map** icon, and the legend of the LBS fly line map is automatically displayed in the dashboard display area.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **province** option and add it to the Geographical area/Latitude and longitude. In the measurement list, locate the **shipping\_cost** and **order\_amt** options and add them to the bubble size area in sequence, as shown in the following figure.

    **Note:** Make sure that the dimension type of the area field has been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15353594011865_en-US.png)

6.  Click **Update**.
7.  On the Style tab, you can edit the title, layout, and series setting of a chart, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15353594011866_en-US.png)

    -   In the **Layout** configuration, set the Basemap to **GeoQ**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15353594011867_en-US.png)

8.  Click the **Save** icon to save the dashboard.

    In the upper right corner, select **More** \> **Delete **to delete the current chart.


