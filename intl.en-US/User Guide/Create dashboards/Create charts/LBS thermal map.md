# LBS thermal map {#concept_brr_dnf_vdb .concept}

**Note:** LBS thermal maps are only available to **Quick BI Pro** users.

This section describes how to create an LBS thermal map. For more information, see [Dashboard overview](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#) and [EN-US\_TP\_9111.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Similar to [EN-US\_TP\_9130.md\#](intl.en-US/User Guide/Create dashboards/Create charts/Geomap.md#), LBS thermal maps use the gradation of color to reflect data distribution across regions.

An LBS thermal map consists of geographic regions with different colors. Regions are determined by data dimensions, or the latitude and longitude values of the location, such as province. Colors are determined by data measures, such as order amount and profits.

## Note {#section_l3p_hnf_vdb .section}

For each LBS thermal map, one and only one dimension must be specified to determine the regions. This dimension must be about geographic information. One to five measures can be specified to determine the colors of regions.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the transportation costs and order quantities across provinces**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.

    **Note:** If you are using the **Professional** edition, you need to select between the **Standand Mode** and **Full Screen Mode**. The following example uses the **Standard Mode**.

4.  Click the **LBS thermal map** icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and measures.

    In the Dimensions list, select **province** and add it to Geographical area/Latitude and longitude. In the Measures list, select **order\_amt** and **shipping\_cost**, and add them to LBS Thermal depth, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15502209031865_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and layout of the diagram and the style of specific fields.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15502209031866_en-US.png)

    -   In the **Layout** section, you can set the basemap to **Google Maps** and the updated diagram is as follows:

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15502209031867_en-US.png)

8.  Click the **Save** icon to save the dashboard.

    In the upper right corner, select **More \>** \> **Delete**to delete the diagram.


For more information about the administrative regions of China, see [Administrative regions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

