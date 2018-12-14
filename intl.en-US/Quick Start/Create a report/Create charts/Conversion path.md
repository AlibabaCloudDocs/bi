# Conversion path {#concept_u4r_lmf_vdb .concept}

This section describes how to create a conversion path. For more information, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Basic dashboard operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Basic dashboard operations.md#). If you need to edit or create datasets, see [Create a dataset](intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

A conversion path uses metrics such as page visits, page views \(PVs\) and unique visitors \(UVs\) to calculate the conversion rates on your website. This helps you understand the overall performance of marketing campaigns and measure the sales volume of certain products. Conversion paths are suitable for analyzing digital marketing campaigns and e-commerce websites. For example, you can use conversion paths to find out which products are in great demand and what are the peak hours of your business.

Currently, conversion paths support the following three dimensions: previous page, current page, and next page, and include the following measures: PV, UV, conversion rate, and bounce rate. You need to specify the PVs or UVs for all three pages.

## Note {#section_xmp_nmf_vdb .section}

For each conversion path, one and only one dimension must be specified for each of the three pages. The dimensions must have hierarchical relationship. The order of the dimensions determines the hierarchical relationship in the diagram. One and only one measure must be specified for each of the three PVs or UVs, the conversion rate, and the bounce rate.

The three dimensions, the conversion rate, and the bounce rate are required fields. You can choose to specify only the PVs or UVs for all three pages. Error messages are shown if fields are incorrectly specified when adding the dimensions and measures.

The following uses the page\_source\_target\_state dataset as an example.

**Scenario: Use PVs to demonstrate the conversion and bounce rates on different pages**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to open the dataset management page.
3.  Select the page\_source\_target\_state dataset and click **Create Dashboard**.
4.  Click the Conversion Path icon and the corresponding legend is displayed.
5.  Click the Data tab to select data dimensions and data measures.

    In the Dimensions list, select the **Previous Page**, **Current Page**, and **Next Page**, and add them to the corresponding fields. This order determines the hierarchical relationship between pages in the diagram. In the Measures list, select the **Conversion Rate** and **Bounce Rate**, and add them to the corresponding fileds. You also need to select three PVs or UVs for the corresponding pages.

6.  Click **Update** to generate the diagram.
7.  In the Style tab, you can change the title and layout of the diagram.

    The conversion path provides three layouts and allows you to highlight the main path or popup windows.

8.  Click the **Save** icon to save the diagram.

To delete the diagram, move the mouse to the upper-right corner and click **Delete** in the toolbar that appears.

