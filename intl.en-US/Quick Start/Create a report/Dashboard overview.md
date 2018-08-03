# Dashboard overview {#concept_t2g_g3x_5db .concept}

This section introduces basic concepts of the dashboard, including the types, application scenarios, and data elements of charts in the dashboard.

For more information about the basic operations on a dashboard, see [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#).

To learn how to create other types of charts, see [Charts overview](intl.en-US/Quick Start/Create a report/Create charts/Charts overview.md#).

Dashboards use a more flexible tile layout to show interactions between data. A dashboard not only visualizes data but also supports data filtering and query and multiple data display modes to highlight the key fields of data.

In terms of data display, dashboards display data in a more intuitive and clearer way through the wizard and drag, drop, and click operations on fields. In terms of data analysis, dashboards improve interaction experience of users by friendly prompts.

The data display performance is also greatly improved. You can query dynamic data on the dashboard editing page.

## Types and application scenarios of data charts {#section_hrd_j3x_5db .section}

Different data needs to be displayed using different chart types. Currently, Quick BI supports 17 types of data charts, including line charts, bar charts, bubble map, and funnel charts.

The following table lists the analysis type and common application scenarios of each type of chart.

|Analysis type|Description|Scenario|Applicable chart|
|:------------|:----------|:-------|:---------------|
|Comparison|Compare the differences between each value or display a simple comparison of measurements between different categories.|Compare the sales/income differences of different countries or regions.|Bar chart, radar chart, funnel chart, table, polar chart, tornado chart, and word cloud|
|Percentage|Display the percentage of a part or the ratio of a value to the whole.|Display which salesperson contributes the most to the total sales.|Pie chart, funnel chart, gauge, and tree chart|
|Relation|Display relationship between each value or compare multiple measurement values.|View the relativity between two values and display the affect of the first value on the second value.|Scatter chart, tree chart, card chart, hierarchy chart, and conversion chart|
|Trend|Display the trend of a value \(especially the trend changes with time \(for example, by year, month, or day\) or the progress or possible modes of an indicator.|View the sales or income trend of a product in a period of time.|Line chart|
|Geographic chart|Intuitively show the size and distribution of related data indicators in a country or region on a map.  The datasets used must contain geographical data.|View the income of each region in a country.|Geo bubble and geo|

## Data elements of a data chart {#section_ixl_n3x_5db .section}

Each chart contains the Data, Style, and Advanced tabs, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9109/15332604136898_en-US.png)

-   The Data tab determines data displayed on the chart.
-   The Style tab determines the chart appearance and displayed details.
-   The More tab determines whether data is associated with multiple charts and whether to dynamically display interaction and comparison between data based on your needs.

Each chart is differentiated from other charts by its core data elements. For example, the core element of a map is its geographic latitude. Otherwise, data cannot be displayed on the map.

The following table lists the core data elements of each type of chart.

|Chart name|Data elements|Composition of data elements|
|:---------|:------------|:---------------------------|
|Line chart|Category axis and value axis|The category axis has at least one dimension, and the value axis has at least one measurement.|
|Area map|Category axis and value axis|The category axis has at least one dimension, and the value axis has at least one measurement.|
|Bar chart|Category axis and value axis|The category axis has at least one dimension, and the value axis has at least one measurement.|
|Code Charts|Category axis and value axis|The category axis has at least one dimension, and the value axis has at least one measurement.|
|Pie Chart|Slice label and slice angle|Slice labels have only one dimension, and the dimension value is smaller than or equal to 12. The slice angle has only one measurement.|
|Geo bubble map|Geographic region and bubble size|Geographic regions have only one dimension, which is the geographic latitude. The bubble size has one to five measurements.|
|Geo map|Geographic region and color saturation|Geographic regions have only one dimension, which is the geographic latitude. The color saturation has one to five measurements.|
|Table|Row and column|Rows have unlimited dimensions, and columns have unlimited measurements.|
|Gauge|Pointer angle and tooltip|A gauge has only one measurement.|
|Radar chart|Branch label and branch length|Branch labels have one to two dimensions, and the branch length has at least one measurement.|
|Scatter chart|Color legend, X axis, and Y axis|Color legends have only one dimension, and the maximum number of dimension members is 1000. The X axis has one to three measurements, and the Y axis has only one measurement.|
|Funnel chart|Funnel layer label and funnel layer width|Funnel layer labels have only one dimension, and the funnel layer width has only one measurement.|
|Card chart|Panel label and panel indicator|Panel labels have at most one dimension. Panel indicators have at least one and at most 10 measurements.|
|Tree map|Color block label and color block size|Color block labels have only one dimension, and the dimension value is smaller than or equal to 12. The color block size has only one measurement.|
|LBS map|Geographic region and LBS bubble size|Geographic regions have only one dimension, which is the geographic latitude. The LBS bubble size has one to five measurements.|
|Polar chart|Slice label and slice length|Slice labels have only one dimension, and the dimension value ranges from 3 to 12. The slice length has only one measurement.|
|Word cloud|Word size and word label|The word size has only one dimension, and word labels have only one measurement.|
|Tornado chart|Comparison subject and comparison indicator|The comparison subject has only one dimension, and comparison indicators have at least one measurement.|
|Hierarchy chart|Tree parent and child node label and tree parent and child node indicator|Tree parent and child node labels have at least two dimensions. Tree parent and child node indicators have at least one measurement.|
|Conversion chart|Previous page, current page, and next page; PV of the present, current, and next pages, UV of the present, current, and next pages, path conversion rate, and page bounce rate|Each data element has only one dimension or measurement.|
|Progress bar|Progress indication|The Progress indication has one to five measurements.|
|Pivot table|Row and column|Rows have unlimited dimensions, and columns have unlimited measurements.|

