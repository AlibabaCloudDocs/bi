# Dashboard overview {#concept_t2g_g3x_5db .concept}

This topic describes the basic concepts of a dashboard, including the chart types, scenarios, and chart elements.

For more information about the basic operations on a dashboard, see [Dashboard basic operations](reseller.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#).

For more information about creating charts, see [Create a chart](reseller.en-US/User Guide/Create dashboards/Create charts/Create a dashboard.md#).

The dashboard provides a flexible tile view to show the interaction between data. It visualizes data and supports filtering and querying a variety of data types. It displays data in various ways and highlights the keyword segments in the data.

In terms of data visualization, the dashboard guides you through dragging or double-clicking a field to display data explicitly. In terms of data analysis, the dashboard utilizes user-friendly notifications to improve user interaction.

Data visualization performance has improved significantly. On the editing page of the dashboard, you can filter dynamic data.

## Chart types and scenarios {#section_hrd_j3x_5db .section}

You need to use the corresponding charts to display different types of data. Quick BI currently supports 35 types of charts, including line charts, vertical bar charts, bubble maps, and funnel charts.

The following table describes the analysis types and scenarios for each chart.

|Analysis type|Description|Scenarios|Applicable charts|
|:------------|:----------|:--------|:----------------|
|Comparison|Compares the differences between values, or compares the measures based on the dimensions.|Compares the sales/income differences between different countries or regions.|Vertical bar chart, combination chart, horizontal bar chart, radar chart, funnel chart, cross table, pivot table, polar diagram, tornado-leaned funnel chart, and word cloud.|
|Proportion|Displays the percentage of a portion of the whole, or the proportion of a certain value compared to the whole.|Displays the sales of the salesperson who has the greatest percentage of total sales.|Pie chart, funnel chart, gauge, and treemap.|
|Relationship|Displays the relationship between values, or between measures.|You can view the relationship between two measures and learn the influence the first measure has on the second measure.|Scatter chart, treemap, kanban, hierarchy chart, flow analysis chart, and progress bar.|
|Trend|Displays data trends \(especially trends based on the date such as the year/month/day\), or the progress of a data indicator and other possible patterns.|You can view trends in sales or revenue for a product over a period of time.|Line chart and area chart.|
|Geographic map|Displays the relevant data and distribution range for a country or region on the map. The datasets used must include geographic data.|You can view the income for each region in a country.|Bubble map, colored map, and LBS bubble map.|

## The elements of a chart {#section_ixl_n3x_5db .section}

Each chart has three tabs, which are Data, Style, and Advanced, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9109/15640455266898_en-US.png)

-   Settings in the Data tab determine the data shown on the chart.
-   Settings in the Style tab determine the appearance of the chart and the details to be displayed.
-   Settings in the Advanced tab determine whether the data and multiple charts can be linked, and dynamically display the interaction and comparison of the data as needed.

The charts provided by Quick BI present distinct perspectives and data elements for different visualization scenarios. Take the geographic chart as an example. A core data element is latitude. Otherwise, the map cannot display data.

The following table describes the elements of each chart.

|Chart Type|Elements|Chart Configuration|
|:---------|:-------|:------------------|
|Line chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Area chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Stacked area chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|100% stacked area chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Vertical bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Stacked vertical bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|100% stacked vertical bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Circular bar|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Combination chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Horizontal bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Stacked horizontal bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|100% stacked horizontal bar chart|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Pie chart|Labels and central angle|The label contains only one dimension, and the value of the dimension must be less than or equal to 12. The central angle has only one measure.|
|Bubble map|Location and the bubble size|The location contains only one dimension, which is the geographic dimension. The bubble size element can have 1-5 measures.|
|Colored map|Location and colorscale|The location contains only one dimension, which is the geographic dimension. The colorscale element can have 1-5 measures.|
|Geo bubble map|Location and the bubble size|The location contains only one dimension, which is the geographic dimension. The bubble size element can have 1-5 measures.|
|Geo map|Location and colorscale|The location has only one dimension, which is geographic data. The color saturation has only one measure.|
|LBS bubble map|Geographical area and LBS bubble size|The geographical area has only one dimension, which is the latitude. The LBS bubble size element can have at least one and at most five measures.|
|LBS heat map|Location and LBS heat metric|The geographical area has only one dimension, which is the latitude. The LBS bubble size element can have at least one and at most five measures.|
|LBS flying line map|Geo location \(from\), Geo location \(to\), and routes \(measures\).|You can select a maximum of two dimensions for the geo locations. You can select a minimum of one and a maximum of five measures for the routes.|
|Cross table|Row and column|The row has unlimited dimensions. The column has unlimited measures.|
|Gauge|Indicator angle and tooltip|The indicator angle has only one measure.|
|Radar chart|Radius label and radius|You can select a minimum of one and a maximum of two dimensions for the labels. You can select a minimum of one measure for the lengths.|
|Scatter chart|Colors, X-axis, and Y-axis|You can select a minimum and maximum of one dimension for the color legend. The number of the dimension's values is up to 1,000. You can select a minimum of one and a maximum of three measures for the x-axis. You can select a minimum and maximum of one dimension for the y-axis.|
|Bubble chart|X-axis, Y-axis, and bubble size|The X-axis has only one dimension. The Y-axis has only one measure. The bubble size has only one measure.|
|Funnel chart|Tier labels and tier area|The tier labels element has only one dimension. The tier area element has only one measure.|
|Kanban|Labels and metrics|You can select a maximum of one dimension for the labels. You can select a minimum of one and a maximum of 10 measures for the metrics.|
|Treemap|Rectangle label and rectangle size|The rectangle size element has only one dimension, with a value less than or equal to 12. The rectangle size element has only one measure.|
|Polar diagram|Slice label and arc radius|The slice label element has only one dimension, with a value greater than or equal to three and less than or equal to 12. The arc radius element has only one measure.|
|Word cloud|Word size and word|The word size element has only one dimension. The word element has only one measure.|
|Tornado-leaned funnel chart|Comparison and contrast indicator|The comparison element has only one dimension. The contrast indicator has at least one measure.|
|Hierarchy chart|Node label and node metric|The node label has at least two dimensions. The node metric has at least one dimension.|
|Flow analysis|Previous Page, Current Page, and Next Page. Previous Page PV, Previous Page UV, Current PV, Current UV, Next Page PV, Next Page UV, Conversion Rate, and Bounce Rate|Each data element has only one dimension and one measure.|
|Progress bar|Progress Indicator|The progress indicator has a minimum of one and a maximum of five measures.|
|Pivot chart|Row and value|The row has unlimited dimensions. The value has unlimited measures.|

