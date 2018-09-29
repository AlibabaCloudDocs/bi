# LBS flying line map {#concept_pgm_jpv_k2b .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a LBS bubble map. If you need to edit a dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

An LBS flying line map uses a map profile as its background. Dynamic flying lines reflect data values between two or more regions.

An LBS flying line consists of two geographical regions and LBS flying line measures. Geographical regions are determined by data dimension, such as province or city. The LBS flying line size is determined by a data metric, such as transportation cost or order amount.

## Limitations on creating an LBS flying line map {#section_pdr_xpv_k2b .section}

You can set up to two dimensions for the geographical region of an LBS flying line map, and the dimension type must be of geographical information \(such as province and city\). You can create only one LBS flying line metric.

The following uses the company\_sales\_record dataset as an example.

**Scenario: Create an LBS flying line map to show the transportation cost between regions. **

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select company\_sales\_record dataset, and click **Create Dashboard**. The dashboard editing page is displayed.
    -   If you are using **Standard** or **Advanced** edition, the page automatically jumps to the Standard edit page.
    -   If you are using **Professional Edition**, you need to manually select either **Standard** or **Fullscreen** mode. The following takes the **Standard** as an example.
4.  Click the **LBS fly line map** icon, and the legend of the LBS fly line map is automatically displayed in the dashboard display area.
5.  On the Data tab, select a required dimension field and measurement field.

    In the dimension list, locate the **area** and add it to the Geographic area/Latitude and longitude \(from\) field in the region. Locate the **province** and add it to the Geographic are/Latitude and longitude \(to\) field. In the metric list, locate the shipping cost and add it to the LBS line metric area, as shown in the following illustration.

    **Note:** Make sure that the dimension type of the region and province fields have been switched from string to geological information.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15382146106992_en-US.png)

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab,  you can edit the title, layout, and series settings, as shown in the following figure \(optional\).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15382146106993_en-US.png)

    In the Layout configuration,  set the Basemap to GeoQ and set the Show legend to Bottom, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15382146106994_en-US.png)

    **Note:** You can adjust the speed of LBS flying lines by setting the LBS flying line time.  The higher the value, the slower the flying line will be.

8.  Click the **Save** icon to save the dashboard.

    In the upper right corner, select **More** \> **Delete **To delete the current chart.


