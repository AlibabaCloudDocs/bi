# LBS bubble Map {#concept_glz_t4f_vdb .concept}

**Note:** LBS bubble map is only applied to **Quick BI Professional Edition**。

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a LBS bubble map. If you need to edit a dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

Similar to a [Geo bubble](intl.en-US/Quick Start/Create a report/Create charts/Geo bubble.md#), an LBS bubble map uses a map profile as its background and attaches bubbles to the map to indicate data values. The basemap style of an LBS bubble can be switched among Amap Electronic Map, Google Map and GeoQ, intuitively showing the related data indexes and distribution ranges of a country or region. For example, an LBS bubble map can be used to show passenger flows of multiple tourist sites or per capita incomes of multiple regions.

A bubble map consists of a geographical region and a bubble size. The geographical area is determined by data dimension, such as province. The LBS bubble size is determined by data measure, such as transportation cost or order amount.

## Limitations on creating an LBS bubble map {#section_ezb_x4f_vdb .section}

You can set only one dimension for the geographical area of an LBS bubble map and the dimension type must be the geographical information. You can set up to five bubble size measures.

The following scenario uses the company\_sales\_record dataset and standard dashboard mode as an example.

**Scenario: Create an LBS bubble map to show order number and profit amounts of each province.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**. The dashboard editing page is displayed.
    -   If you are using **Standard** or **Advanced** edition, the page automatically jumps to the Standard Edit page.
    -   If you are using **Professional Edition**, you need to manually select either **Standard** or **Fullscreen** mode. The following takes the **Standard** mode as an example.
4.  In the dashboard configuration area, click the **LBS bubble Map** icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the **province** option and add it to the Geographical area/Latitude and longitude. In the measurement list, locate the **order\_number** and **profit\_amt** options and add them to the bubble size area in sequence, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15353594351870_en-US.png)

6.  Click **Update**.
7.  On the Style tab, you can edit the title, layout, and series setting of a chart, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15353594351871_en-US.png)

    -   In the **Layout** configuration, you can set the basemap of an LBS bubble map, resize the map, and adjust the longitude and latitude of the map. For example, set the Basemap to GeoQ, as shown in the following figure. For example, set the underlay to **GeoQ**, and the updated chart is shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15353594351872_en-US.png)

    -   In the series settings, set the number of decimal places for the order amount to 2, the updated chart is shown below.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15353594361874_en-US.png)

8.  Click **Save** to save current dashboard.

    In the upper right corner, select **More** \> **Delete **To delete the current chart.


