# Conversion path {#concept_u4r_lmf_vdb .concept}

If you have read [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#) and [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#), read this section to learn about how to create a conversion chart. If you need to edit the dataset or create a new dataset, see [Create a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).

A conversion chart illustrates the conversion rate of a webpage by comparing its page traffic or page views \(PV\) and the number of its unique visitors \(UV\), so that users can know the overall operation status of the website and the final transaction volume of a type of products. Vistor\) to determine the conversion rate of the web page, then you can know the overall operating effect of the website and the final volume of a certain kind of merchandise. Source direction charts apply to analysis related to e-commerce or marketing. For example, you can use a source direction chart to analyze which products are the bestsellers and which time periods are traffic peaks.

A source direction chart now only supports three levels of dimensions, which are the previous page, current page, and the next page. The measurements of a source direction chart are PV, UV, the path conversion rate, and the page bounce rate, among which PV and UV are collected from the previous, current, and next pages.

## Notice on creating a conversion chart {#section_xmp_nmf_vdb .section}

The previous, current, and next pages in a conversion chart each can have a maximum of one dimension. The dimension fields must be hierarchical. The sequence of dimensions fields determines their hierarchy displayed on the chart. PV \(for the previous, current, and next page\), UV \(for the previous, current, and next page\), the path conversion rate, and the page bounce rate can have a maximum of one measurement, respectively.

When you create a source direction chart, the three dimensions \(each for the previous, current, and next pages\) and two conversion rates \(path conversion rate and page bounce rate\) are mandatory. However, you can select either the three PV items or three UV items. If an entered dimension or measurement field is incorrect, the system prompts you accordingly.

The following uses the page\_source\_target\_state dataset as an example.

**Scenario: Display the conversion rate and bounce rate between each page based on PV.**

1.  Log on to the Quick BI console.
2.  Click **Datasets** to enter the dataset management page.
3.  Select page\_source\_target\_state, and click **Create Dashboard**. The dashboard editing page is displayed.
4.  Click conversion chart icon.
5.  On the Data tab, select a required dimension field and measurement fields.

    In the dimension list, locate the names of the **previous**, **current**, and **next page**, and enter the names in the corresponding fields in sequence.  The sequence of these pages is the hierarchy displayed on the chart. In the measurement list, locate the page path conversion rate and page bounce rate, enter them in the corresponding fields in sequence, locate the three PV values and/or three UV values, and enter them in the corresponding fields in sequence.

6.  Click **Update**. The system automatically updates the chart.
7.  On the Style tab, you can edit the title and layout of the chart.

    The conversion chart provides three layouts, including highlight of the main path or prompted windows. For example, if you select Highlight Top Path for the layout, the top path is displayed in a different color on the chart.

8.  Click **Save** to save current dashboard.

To delete the current chart, point to the upper-right corner of the chart, and choose **Delete** from the shortcut menu.

