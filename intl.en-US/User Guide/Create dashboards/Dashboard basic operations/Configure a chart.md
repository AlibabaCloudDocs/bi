# Configure a chart {#concept_agk_n2y_5db .concept}

You can select a chart in the configuration area of a dashboard. After you select a chart, you can configure this chart.

You must ensure that you have selected a dataset on the Data tab before you create a chart. In addition, dimensions and measures are applicable.

For more information about dimensions and measures, see [EN-US\_TP\_9077.md\#](intl.en-US/Quick Start/Create a report/Create dashboards.md#).

1.  After you click a chart icon, the selected chart appears in a dashboard.

    You can switch a chart to other types by clicking Change chart type in the upper-right corner of the page.

2.  On the **Data** tab, select the required dimensions and measures.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9114/15566046371448_en-US.png)

    -   Click the **cross** icon next to a field to remove this field from the Category Axis \(Dimensions\) area.
    -   Click the **triangle** icon next to a field to display the values of this field in ascending or descending order.
3.  Select a field and drag this field to the Colors \(Dimensions\) area.

    The selected field appears in a chart with the specified color. If you fail to drag a field, an error message occurs. You can follow the instruction on the message to add or remove dimensions and measures.

    Take the **product\_type** field as an example.

    1.  Drag the **product\_type** field to the **Colors \(Dimensions\)** area, and then click **Update**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9114/15566046381449_en-US.png)

    2.  Select **Style** \> **Series settings** to change your color matching themes.
4.  Select the time interval that data automatically refreshes on the **Auto refresh** list.
5.  On the Style tab, you can change the visual format of a chart by setting options in General config, Style, Layout, Axis, and Series settings.

    You can change a unit by setting a number in the **Unit** area. You can only multiply the values of a field by the number you set in the Unit area.

    Assume that the previous unit is centimeter. If you want to display data in meters, you must divide the previous unit by 100. In the Unit area, you can enter 0.01 in this case. For a multiplication operation, you can enter 100.

6.  On the Advanced tab, you can associate the current chart with other charts.

    You must ensure at least two charts are created in the display area of a dashboard before you associate charts.


