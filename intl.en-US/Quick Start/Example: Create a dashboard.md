# Example: Create a dashboard {#concept_i5b_zgp_5db .concept}

This section describes how to use a dashboard to quickly prepare a report. As the example cannot describe all charts, for more information about the basic operations on a dashboard and creation process of each chart, see [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#) and [Charts overview](intl.en-US/Quick Start/Create a report/Create charts/Charts overview.md#).

The dashboard supports the following two modes.

-   Standard dashboard
-   Full-Screen mode \(Quick BI pro only\)

## Create a data set {#section_sx4_3hp_5db .section}

Before creating a dashboard, you must prepare a dataset. As datasets are created using data sources, this section describes how to create a data source first.

This section uses the connection to a MySQL data source as an example to describe how to create a data source.

1.  Log on to the Quick BI console.
2.  Choose **Workbench** \> **Data Sources** . The data source management page is displayed.
3.  Click **Create \> MySQL \(From Cloud Database\)**. The data source connection menu is displayed.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218911233_en-US.png)

4.  Enter the data source connection information and click **Test Connection** to check whether the data source is successfully connected.

    You can use the following MySQL connection address. For more information, see [Example: Create a workbook](intl.en-US/Quick Start/Example: Create a workbook.md#).

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218921234_en-US.png)

    If the data source cannot be connected, a corresponding message is returned. You can try to fix this problem by referring to [How to diagnose a data source connection exception](https://help.aliyun.com/document_detail/54950.html?spm=a2c4g.11186623.2.8.I5jjCh).

5.  Click **Add**. The data source is automatically added to the data source list.
6.  Click the **Create Dataset** icon next to a table, for example, company\_sales\_record, to create a dataset.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218921235_en-US.png)


After the dataset is created, it is automatically saved to the **My Dataset** folder. New is displayed for the newly created dataset, which allows you to fast locate the dataset.

## Edit Dataset {#section_rsj_43p_5db .section}

After a dataset is created, you can simply edit the dataset accordingly to meet the actual chart demands, for example, switching the field type or adding a calculated field.

Take company\_sales\_record as an example.

1.  Click **Datasets**. The dataset management page is displayed.
2.  Click a dataset name, for example, company\_sales\_record. The dataset editing page is displayed.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926901_en-US.png)

    To create a map chart, such as a geo bubble or geo map, select dimension fields that contain geographical information, and then switch their field type from String to Geographical Information. Otherwise, the map cannot be displayed.

3.  In the dimension list, select Area.
4.  Right-click the dimension, and select **Change Dimension** \> **Location** \> **Region**. As shown in the following figure.

    **Note:** Note that the selected geographic information must match the field. For example, if the field is Area, you must select Area in the location information list. Otherwise, the field type cannot be switched.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926903_en-US.png)

5.  Switch Province field and City field in the same way.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926904_en-US.png)

6.  After the dataset is edited, click **Save**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926906_en-US.png)

7.  Select **Synchronize \> Refresh Preview**. The data is automatically displayed in the table.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926907_en-US.png)


For more information about how to edit a dataset, see [Edit a dataset](intl.en-US/Quick Start/Data modeling/Dataset management/Edit a dataset.md#).

## Edit a dashboard {#section_klk_qjp_5db .section}

After a dataset is edited, you can use a dashboard to create a report.

1.  Click **Dashboards** in the left-side navigation pane. The dashboard management page is displayed.
2.  Select **Create ** \> **Dashboards**. The dashboard editing page is displayed.
3.  Select a dashboard display mode.

    **Note:** The full-screen mode is available for Quick BI professional edition,  and the standard dashboard mode is available for Quick BI Basic and Quick BI Pro. Quick BI Basic has no Full-screen mode.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218921241_en-US.png)


**Add a dataset to a dashboard**

1.  Click the **Switch** icon and select a dataset.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926908_en-US.png)

2.  Choose company\_sales\_record as a target dataset. The data is listed in the dimension and measurement lists, respectively.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926909_en-US.png)


If the dataset list is empty, click **Datasets** to return to the dataset management page and check whether the dataset is successfully created.

**Create a data chart \(Standard dashboard\)**

This section only describes how to create a bar chart. For more information about how to create other types of charts, see [Charts overview](intl.en-US/Quick Start/Create a report/Create charts/Charts overview.md#).

For more information about the data elements and application scenarios of each type of chart, see [Dashboard overview](intl.en-US/Quick Start/Create a report/Dashboard overview.md#).

For more information about other basic operations on a dashboard, see [Dashboard basic operations](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Dashboard basic operations.md#).

1.  Click the bar chart icon.
2.  Double-click a field on the Data tab. The data is automatically filled in the field, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926910_en-US.png)

3.  Click **Update**. The following figure shows the updated chart.

    If too much data is displayed, you can enable color legend.  Drag and drop a dimension field to the color legend area. Information of this field is displayed in different colors in the chart.

    **Note:** Color legend is available when only one measurement field is in the value axis area. Otherwise, it cannot be used. When color legend is unavailable, you may receive a message on why it cannot be used. To enable the function, adjust the measurement and dimension fields as prompted.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218926911_en-US.png)

4.  Click **Update**. The following figure shows the updated chart.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218931246_en-US.png)

5.  When mouse points to a set of data, the data details are automatically listed by using the tooltip function, as shown in the following figure.

    Choose **Style** \> **Style** \> **Tooltip**, to disable this function.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218931247_en-US.png)

6.  On the Style tab, edit the title, layout, and legend of the chart.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936912_en-US.png)

    -   Common Settings: you can set the title, the font color, and the background color, as shown in the following illustration.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936913_en-US.png)

    -   Layout: You can set chart display styles, for example, Double Y-axis, the percentage stacked, and stacked. See the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936914_en-US.png)

    -   Style: You can set the legend and tooltip, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936915_en-US.png)

    -   Axis: you can set the axis title, the Axis display style, and the axis value formatting and coefficients.
    -   Settings: you can set the alias, display type, and color of a class of data, including labels, value formats and decimals.

To delete the current chart, choose **More operations** \> **Delete**, in the upper-right corner of the chart.

**Create a data chart \(Full screen dashboard\)**

This section only describes how to create a Geo Bubble chart.

1.  Click the **Geo Bubble** chart icon.

    The chart contains the global map component, which can display data besides the Chinese area.

2.  Double-click a field on the Data tab. The data is automatically filled in the field.

    **Note:** Make sure that the dimension type of the province field has been changed from string to geographical information.

3.  Click **Update**. The system automatically updates the chart.
4.  On the Style tab, edit the title, layout, and legend of the chart.
5.  Click **Settings** to configure the page proportion, skin color, data update interval, and time interval of data carousel.

To delete the current chart, choose **More \> Delete** in the upper-right corner of the chart.

**Add a widget**

A dashboard supports the following widgets.

-   Standard dashboard

    -   Filter bar
    -   Text box
    -   IFrame
    -   TAB
    -   Image
-   Full-screen dashboard

    -   Text area
    -   IFrame
    -   Image

-   **Add query conditions**

    You can select the **Filter Bar** to query data in one or multiple charts.

    1.  Click the **Filter bar** icon, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936925_en-US.png)

    2.  Click the **Filter bar** on the dashboard show area. The editing menu of the control is displayed.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936926_en-US.png)

    3.  Select the expected dataset, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936928_en-US.png)

    4.  Select a field to be queried, for example, product\_type field.

        The Filter bar control supports Single-Dataset and Multi-Dataset. The following uses the Single-Dataset as an example. For more information about the Multi-Dataset, see [Common widgets](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Common widgets.md#).

    5.  Click **Single-Dataset** and select an expected chart, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936929_en-US.png)

    6.  Click **Style** to edit the Filter bar title.
    7.  Point to the field to be queried. A blue dashed line box is automatically displayed for the field. Click the dashed line box. The editing page of the field to be queried is displayed, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936930_en-US.png)

    8.  Click **Enumeration** and select **Radio** or **Multiple select**, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936932_en-US.png)

    9.  Click the drop-down arrow and select the option to be queried, as shown in the following figure.

        **Note:** If Radio is selected, you can select only one option. Otherwise, you can select multiple options.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936933_en-US.png)

    10. After the selection, click **Search**. The charts to which the queried field applies are automatically updated.
    To delete the current widget, choose **More operations** \> **Delete** in the upper-right corner of the widget.

    You can also query a field by date or quantity. For more information about how to use the widgets, see [Common widgets](intl.en-US/Quick Start/Create a report/Dashboard basic operations/Common widgets.md#).

-   **Add a text area**

    You can enter fixed text in a text box and use the text as a report title.

    1.  Click the text area icon.
    2.  Enter text in the text area.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936934_en-US.png)

    To delete the current widget, select **More operations** \> **Delete** in the upper-right corner of the widget.

-   **Add an IFrame**

    IFrame enables you to insert a required webpage in a dashboard to query network data in real time or to browse the webpage or website related to the current data.

    1.  Click the **IFrame** icon.
    2.  Enter a webpage address.

        **Note:** The webpage addresses must start with **https**.

        To delete the current widget, select More \> Delete in the upper-right corner of the widget.

-   **Add a tab**

    The TAB feature enables multiple charts to be displayed in different tabs.

    1.  Click the **TAB** icon.
    2.  Click **Add TAB Page** to add a new tab, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218936937_en-US.png)

    3.  Click a tab and insert a chart in it. For example, click TAB1. TAB1 then becomes blue, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218941267_en-US.png)

    4.  Click the required chart icon. A chart is automatically inserted in TAB1.
    5.  Create the chart by following the chart creation process. After the chart is created, the tab control is as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218941268_en-US.png)

        To delete the current widget, select **More operations** \> **Delete** in the upper-right corner of the widget.

-   **Add an image**

    You can use the Image function to insert a picture as required.

    1.  Click the Image icon.
    2.  Enter the picture URL.
    3.  Click the drop-down arrow and select the picture display style, as shown in the following figure.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218946938_en-US.png)

        To delete the current widget, select **More operations** \> **Delete** in the upper-right corner of the widget.


## Preview the dashboard {#section_byd_spp_5db .section}

After the dashboard is edited, you can preview the chart demonstration effect.

Choose **Preview \> PC or Mobile**, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218946940_en-US.png)

## Save the dashboard {#section_zrj_wpp_5db .section}

After the dashboard is edited, you can save it.

Click **Save** to save the dashboard.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9077/15342218946941_en-US.png)

