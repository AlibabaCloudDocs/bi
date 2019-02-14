# Example: Create dashboards {#concept_i5b_zgp_5db .concept}

This topic describes how to create a dashboard and how to use the dashboard to create a report. This example involves only some of the chart types. For more information about basic dashboard operations and chart creation procedures, see [Basic dashboard operations](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#) and [Use dashboard to create charts](intl.en-US/User Guide/Create dashboards/Create charts/Create charts in a dashboard.md#).

Dashboard only supports two display modes.

-   Standard mode
-   Full-screen mode \(only available for Quick BI Enterprise\)

Create a dashboard using the dataset named company\_sales\_reco. For more information about basic dataset operations, see [Example: Create datasets](intl.en-US/Quick Start/Preparations/Example: Create datasets.md#).

## Create dashboards {#section_klk_qjp_5db .section}

1.  Log on to the Quick BI console, and click **Workspace**.
2.  In the left-side navigation pane, click **Dashboards** to go to the dashboard management page.
3.  Click **Create Dashboard** to go to the dashboard editing page.
4.  Select a display mode, as shown in the following figure.

    **Note:** The full-screen mode is only available in the Workspace of Quick BI Pro or Quick BI Enterprise. The Personal Space only supports the standard mode. Quick BI Basic does not support the full-screen mode.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379031241_en-US.png)


**Add datasets to a dashboard**

1.  Click the **Switch** icon, and select a dataset, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379036908_en-US.png)

2.  Click the workbook company\_sales\_record. The data in the workbook is listed in the dimension list and the measure list respectively, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379036909_en-US.png)


If the dataset list is empty, click **Datasets** to return to the dataset management page and check whether the dataset has been successfully created.

**Create charts \(standard mode\)**

This topic only describes how to create a column chart in standard mode. For more information about how to create other charts, see [Use dashboard to create charts](intl.en-US/User Guide/Create dashboards/Create charts/Create charts in a dashboard.md#).

For more information about the data elements and applicable scenarios of each chart, see [Dashboard overview](intl.en-US/User Guide/Create dashboards/Dashboard overview.md#).

For more information about basic dashboard operations, see [Basic dashboard operations](intl.en-US/User Guide/Create dashboards/Dashboard basic operations/Basic dashboard operations.md#).

1.  Click the column chart icon.
2.  Double-click a field on the Data tab page. The field data is automatically filled in a specified area, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379036910_en-US.png)

3.  Click **Update**. The system automatically draws a chart.

    If a large amount of data needs to be displayed, you can enable the**Color Legend** feature. Drag and drop a dimension field to the color legend area. Information of this field is displayed in different colors in the chart.

    **Note:** This feature is only available when the Value Axis area is filled with only one measure field. When the color legend is unavailable, the system automatically provides prompts and reasons. You can manually adjust the dimension fields and measure fields as prompted.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379036911_en-US.png)

4.  Click **Update**. The updated chart is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379031246_en-US.png)

5.  When you hover your mouse cursor over a set of data, the details of the data \(ToolTip\) are listed automatically, as shown in the following figure.

    You can choose **Style** \> **Layout** \> **Tooltip**to clear the Tooltip option.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379031247_en-US.png)

6.  On the Style tab page, you can modify the titles, layouts, formats, and axis styles, and select a legend type, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379036912_en-US.png)

    -   General configuration: You can set the title and the background color of the chart, as well as the font and the color of the title, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379046913_en-US.png)

    -   Style: You can set the display style of the chart on the Style tab page. For example, you can select Secondary Y Axis, Stacked Percentage, or Stacked, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379046914_en-US.png)

    -   Layout: You can set the legend type and whether to show the tooltip of the chart, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126915_en-US.png)

    -   Axis: You can set the title and the display style of axes, the display mode of axis values, and the coefficient, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126916_en-US.png)

    -   Series Settings: You can set the alias, display type, and color for a series of data. You can also set the format, decimal digits of the values, and decide whether to display the labels.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126917_en-US.png)


To delete the current chart, click **More** \> **Delete** to delete the chart.

**Create charts \(full-screen mode\)**

This topic only describes how to create a geo bubble chart in full-screen mode.

1.  Click the **Geo Bubble** icon, as shown in the following figure.

    The map contains global map components and can display data outside China.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126918_en-US.png)

2.  Double-click a field on the Data tab page. The field data is automatically filled in a specified area.

    **Note:** Make sure you have changed the dimension type of Province from String to Location.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126919_en-US.png)

3.  Click **Update**, and the system automatically updates the chart.
4.  Click the Style tab to edit the title and legend of the chart.
5.  Click **Page Setting** to set the page scale, the background color, the time interval of data update, and the time interval of data carousel, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126921_en-US.png)


To delete the current chart, click the **Delete** icon in the lower right corner of the chart.

**Add widgets**

A dashboard supports the following five widgets.

-   Standard mode

    -   Filter Bar
    -   Text Area
    -   IFrame
    -   TAB
    -   Image
-   Full-screen mode

    -   Text Area
    -   IFrame
    -   Image

-   **Add filter bars**

    You can click **Filter Bar** to search one or more charts for specific data.

    1.  Click the **Filter Bar** icon, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126925_en-US.png)

    2.  Click the **Filter Bar** widget to open the editing menu.
    3.  Select a dataset that can be operated, for example, company\_sales\_record.
    4.  Select a field to be searched, for example, product\_type.

        The filter bar supports filter interactions for datasets from different sources or from the same source. This example uses the datasets from the same source. For more information about filter interactions for datasets from different sources, see [Common widgets](intl.en-US/User Guide/Create dashboards/Common widgets.md#).

    5.  Click the **Set Filter** icon, select **Current Dataset**, and then select a chart.
    6.  Click **Style** to edit the title of the widget.
    7.  In the **Set Filter Criteria** dialog box, click **Filter by Enumeration** and select **Ratio** or **Multiple Select**.
    8.  Click the drop-down arrow and select the item to be searched.

        **Note:** If you have selected Ratio, you can select only one item. Otherwise, you can select multiple items.

    9.  Click **Search**, and the charts that contain the queried items are updated.
    To delete the current widget, click**More** \> **Delete** to delete the current widget.

    You can also search a field by date or value. For more information about how to use the Filter Bar widget, see [Common widgets](intl.en-US/User Guide/Create dashboards/Common widgets.md#).

-   **Add Text Area**

    You can enter a text in Text Area to specify content such as a report title.

    1.  Click the **Text Area** icon.
    2.  Enter a text, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126934_en-US.png)

    To delete the current widget, click **More** \> **Delete** to delete the current widget.

-   **Add IFrame**

    You can use IFrame to insert required webpages to query web data in real time and browse webpages related to the data on the current dashboard.

    1.  Click the **IFrame** icon.
    2.  Enter a web address, as shown in the following figure.

        **Note:** The web address must start with **https**.

        To delete the current widget, click **More** \> **Delete** from the shortcut menu.

-   **Add TAB**

    You can use TAB to display multiple charts on different tab pages.

    1.  Click the **TAB** icon.
    2.  Click **Add TAB Page** to add a new tab page, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379126937_en-US.png)

    3.  Click a tab to open a tab page and insert a chart to the page. For example, click TAB1, and the color of TAB1 turns blue, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379121267_en-US.png)

    4.  Click the required chart icon, and a chart is automatically inserted to the TAB1 tab page.
    5.  Create the chart by following the chart creation process. After the chart is created, the created TAB widget is shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379131268_en-US.png)

        To delete the current widget, click **More in the upper-right corner of the widget, and choose** \> **Delete** to delete the current widget.

-   **Add pictures**

    You can use the PIC function to insert a picture as required.

    1.  Click the picture icon.
    2.  Enter the picture URL.
    3.  Click the drop-down arrow and select the picture display style, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379136938_en-US.png)

        To delete the current widget, click **More** \> **Delete** from the shortcut menu.


## Preview a dashboard {#section_byd_spp_5db .section}

After a dashboard is edited, you can preview the charts in the dashboard.

Click **Preview**, choose PC Preview or Mobile Preview, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379136940_en-US.png)

## Save dashboards {#section_zrj_wpp_5db .section}

After the dashboard is edited, you can click Save to save the dashboard.

Click **Save**, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15501379136941_en-US.png)

