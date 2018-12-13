# Geo map {#concept_vsg_jl2_vdb .concept}

This section describes how to create a geo map. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

Similar to [Geo bubble](intl.en-US/Quick Start/Create a report/Create charts/Geo bubble map.md#), geo maps use the gradation of color to reflect data values and distribution.

A geo map is a geographical map with colors assigned to specific regions. Regions are determined by data dimensions, such as province. Colors are determined by data measures, such as order amount and profit amount.

## Note {#section_ilk_ll2_vdb .section}

For each geo map, one dimension must be specified to determine the regions. This dimension must be about geographic information. One to five measures can be specified to determine the colors of regions.

The following scenario uses the company\_sales\_record dataset as an example.

**Scenario: Compare the transportation costs, orders amounts, and profits across multiple areas**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the company\_sales\_record dataset and click **Create Dashboard**.
4.  Click the Geo map icon and the corresponding legend is displayed.
5.  Click the Data tab to select the data dimension and data measures.

    In the Dimensions list, select **area** and add it to Location. In the Measures list, select **order\_amt**, **profit\_amount**, and **shipping\_cost**, and add them to colorscale, as shown in the following figure:

    **Note:** Make sure you have changed the data type of Area from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9130/15447016401720_en-US.png)

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title of the diagram, the legend, and the value range of each color.
8.  Click the **Save** icon to save the dashboard.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

For more information about the different administrative regions of China, see [Administrative regions of China](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/48322/cn_zh/1534241743586/%E5%90%84%E5%9C%B0%E5%8C%BA%E8%AF%A6%E7%BB%86%E4%BF%A1%E6%81%AF%E5%AF%B9%E7%85%A7%E8%A1%A8.xls).

