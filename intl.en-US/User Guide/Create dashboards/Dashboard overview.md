# Dashboard overview {#concept_t2g_g3x_5db .concept}

This topic describes the basic concepts of the dashboard, including the dashboard data types, scenarios, and data that composes the charts.

For more information about basic operations of the dashboard, see [EN-US\_TP\_9111.md\#](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#).

For more information about the procedure of creating various charts, see [EN-US\_TP\_9123.md\#](intl.en-US/User Guide/Create dashboards/Create charts/Create charts in a dashboard.md#).

The dashboard provides a flexible tile view to show the interaction between data. It renders data visually and supports filtering and querying a variety of data types. It displays data in various ways and highlights the keyword segments in data.

In terms of data visualization, the dashboard guides you and allows you to drag or double-click a field to display data explicitly. In terms of data analysis, the dashboard utilizes user-friendly notifications to improve user interaction.

Data visualization performance has been improved significantly. In the editing page of the dashboard, you can filter dynamic data.

## Data chart types and scenarios {#section_hrd_j3x_5db .section}

You need to use the corresponding charts to display different types of data. Quick BI currently supports 21 types of data charts, including line charts, bars, bubble maps, and funnels.

The following table describes the analysis types and scenarios for each chart.

|Analysis types|Description|Scenarios|Applicable chart|
|:-------------|:----------|:--------|:---------------|
|Comparison|Compares the differences between values, or compares the measures based on the dimensions.|Compares the sales/income differences between different countries or regions.|Bar, stripe, radar, funnel, table, pivot table, polar, tornado, and word cloud.|
|Percentage|Displays the percentage of a part in the whole, or the proportion of a certain value compared to the whole.|Displays the sales of the salesperson who has the greatest percentage of total sales.|Pie, funnel, dashboard, and treemap.|
|Relation|Displays the relation between values, or between measures.|You can view the relation between two measures and learn the influence the first measure has on the second measure.|Gauge, treemap, card, hierarchy, conversion path, and progress.|
|Trends|Displays data trends \(especially trends based on the date such as year/month/day\), or the progress of data indicator and other possible patterns.|You can view trends in sales or revenue for a product over a period of time.|Line and area.|
|Regional map|Displays the relevant data and the distribution range for a country or region on the map. The datasets used must include geographic data.|You can view income information for each region in a country.|Geo bubble and geo.|

## The data elements of a data chart {#section_ixl_n3x_5db .section}

Each chart has three tabs, which are Data, Style, and Advanced, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9109/15499427536898_en-US.png)

-   Settings in the Data tab determine the data shown on the chart.
-   Settings in the Style tab determine the appearance of the chart and the details to be displayed.
-   Settings in the Advanced tab determine whether the data and multiple charts can be linked, and dynamically display the interaction and comparison of the data as needed.

The charts provided by Quick BI present distinct perspectives and data elements for different visualization scenarios. Take the geographic chart as an example. A core data element is latitude. Otherwise, the map cannot display data.

The following table describes the core data elements of each chart.

|Graph name|Data element|Data element description|
|:---------|:-----------|:-----------------------|
|Line|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Area|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Bar|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Stripe|Category axis and value axis|The category axis must have at least one dimension. The value axis must have at least one measure.|
|Pie|Slice label and arc angle|The slice label contains only one dimension, and the value of the dimension must be less than or equal to 12. The arc angle has only one measure.|
|Geo bubble|Location and the bubble size|The location contains only one dimension, which is the geographic dimension. The bubble size element can have 1-5 measures.|
|Geo|Location and colorscale|The location contains only one dimension, which is the geographic dimension. The colorscale element can have 1-5 measures.|
|Table|Row and column|The row has unlimited dimensions. The column has unlimited measures.|
|Gauge|Indicator angle and tooltip|The indicator angle has only one measure.|
|Radar|Radius label and radius|The radius label contains either one or two dimensions. The radius has at least one measure.|
|Scatter|Colors, X-axis, and Y-axis.|The colors element has only one dimension and the member number of the dimension can be up to 1000. The X-axis has at least one and at most three measures. The Y-axis has only one measure.|
|Funnel|Tier labels and tier area|The tier labels element has only one dimension. The tier area element has only one measure.|
|Card|Card labels and card metrics|The card labels element has at most one dimension. The card metrics element has at least one measure and at most ten measures.|
|TreeMap|Rectangle label and rectangle size|The rectangle size element has only one dimension, with a value less than or equal to 12. The rectangle size element has only one measure.|
|LBS map|Geographical area and LBS bubble size|The geographical area has only one dimension, which is the latitude. The LBS bubble size element can have at least one and at most five measures.|
|Polar|Slice label and arc radius|The slice label element has only one dimension, with a value greater than or equal to three and less than or equal to 12. The arc radius element has only one measure.|
|Word cloud|Word size and word|The word size element has only one dimension. The word element has only one measure.|
|Tornado|Comparison and contrast indicator|The comparison element has only one dimension. The contrast indicator has at least one measure.|
|Hierarchy|Node label and node metric|The node label has at least two dimensions. The node metric has at least one dimension.|
|Conversion path|Previous Page, Current Page, and Next Page. Previous Page PV, Previous Page UV, Current PV, Current UV, Next Page PV, Next Page UV, Conversion Rate, and Bounce Rate.|Each data element has only one dimension and one measure.|
|Progress|Progress Indicator|The progress indicator has at least one measure and at most five measures.|
|Pivot|Row and value|The row has unlimited dimensions. The value has unlimited measures.|

