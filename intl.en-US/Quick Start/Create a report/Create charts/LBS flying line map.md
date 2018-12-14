# LBS flying line map {#concept_pgm_jpv_k2b .concept}

**Note:** LBS flying line map is only applied to **Quick BI Professional Edition**.

This section describes how to create an LBS flying line map. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Edit a dataset.md#).

An LBS flying line map is a map that uses LBS flying line metrics to display the relations between data across two or more geographic regions.

An LBS flying line map consists of geographic regions connected with LBS flying line metrics. Regions are determined by data dimensions, such as province and city. LBS flying line metrics are determined by data measures, such as transportation cost and order quantity.

## Note {#section_pdr_xpv_k2b .section}

For each LBS flying line map, two dimensions must be specified to determine regions. This dimension must be about geographic information, such as area, province, and city. One and only one measure must be specified to determine LBS flying line metrics.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Display the costs of transportation from areas to provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you are using the **Pro** edition, you need to select between the **Standand Mode** and **Full Screen Mode**. The following example uses the **Standard Mode**.

4.  Click the **LBS flying line map** icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measure.

    In the Dimensions list, select **area** and add it to Geographic area/Latitude and longitude \(from\). Select **province** and add it to Geographical area/Latitude and longitude \(to\). In the Measures list, select **shipping\_cost** and add it to LBS flying line metric, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Area and Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15447555556992_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and layout of the diagram, and change series settings as follows:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15447555556993_en-US.png)

    In the Layout section, you can set the basemap to AMAP and move the Legend to the bottom of the map. The updated diagram is as follows:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/15477/15447555556994_en-US.png)

    **Note:** A dot is moving along each LBS flying line metric to indicate the direction of traffic. You can set Time to adjust its speed. A greater value indicates a lower speed.

8.  Click the **Save** icon to save the dashboard.

    To delete the diagram, move the mouse to the upper-right corner and click **More** \> **Delete** in the toolbar that appears.


