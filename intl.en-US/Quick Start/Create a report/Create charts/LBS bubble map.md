# LBS bubble map {#concept_glz_t4f_vdb .concept}

**Note:** LBS bubble map is only applied to **Quick BI Professional Edition**.

This section describes how to create an LBS bubble map. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Similar to [Geo bubble](intl.en-US/Quick Start/Create a report/Create charts/Geo bubble map.md#), an LBS bubble map is a map that uses the sizes of bubbles distributed across the map to reflect data. It provides multiple basemaps for you to choose from, such as AMAP, Google Maps, and GeoQ. LBS bubble maps allow you to understand the distribution and values of metrics across countries and regions in an easy and visual way. For example, LBS bubble maps can display the passenger numbers across tourist attractions or the per capita incomes across regions.

An LBS bubble map consists of geographic regions with bubbles of varying sizes. Regions are determined by data dimensions, such as province. LBS bubble sizes are determined by data measures, such as transportation cost and order quantity.

## Note {#section_ezb_x4f_vdb .section}

For each LBS bubble map, you must only specify one dimension to determine the regions. This dimension must be about geographic information, such as area, province, and city. One to five measures can be specified to determine LBS bubble sizes.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the order amounts and profit amounts across provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you are using the **Professional** edition, you need to select between the **Standand Mode** and **Full Screen Mode**. The following example uses the **Standard Mode**.

4.  Click the **LBS Bubble Map** icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measures.

    In the Dimensions list, select **province** and add it to Location. In the Measures list, select **order\_number** and **profit\_amt**, and add them to LBS bubble size, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15447539951870_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and layout of the diagram and the style of specific fields.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15447539951871_en-US.png)

    -   In the **Layout** section, you can change the basemap, resize the map, and adjust the coordinates of the longitude and latitude. For example, when the basemap is set to **GeoQ**, the updated diagram is as follows:

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15447539951872_en-US.png)

        ![](images/1873_en-US.png)

    -   In the **Series Settings** section, you can change the number of decimal places of order amounts to 2. The updated diagram is as follows:

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9145/15447539961874_en-US.png)

        ![](images/1876_en-US.png)

8.  Click the **Save** icon to save the dashboard.

    In the upper-right corner, select**More \>** \> **Delete**to delete the diagram.


