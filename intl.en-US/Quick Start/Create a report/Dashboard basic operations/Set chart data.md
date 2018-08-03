# Set chart data {#concept_agk_n2y_5db .concept}

In the dashboard configuration area, you can select a chart and configure attributes for it.

Before creating a chart, make sure that you have selected a dataset in the dataset selection area and finished editing dimension and measurement types.

To edit dimension and measurement types, see [Example: Create a dashboard](intl.en-US/Quick Start/Example: Create a dashboard.md#).

1.  Double-click a chart type icon, a chart of this type is displayed in the dashboard display area.

    To switch to a chart of another type, click another chart type icon.

2.  On the **Data** tab, select the expected dimension and measurement fields. See the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9114/15332612031448_en-US.png)

    -   To delete a field from the data element area, click **Delete** behind the field.
    -   To sort the values of a field in ascending or descending order in the chart, click the **up or down arrow** behind the field.
3.  Drag a dimension field to the Color Legend area.

    The values of this field are marked by different colors in the chart.  If a dimension field cannot be dragged to the Color Legend area, the system reports an error message. Add or delete dimension or measurement fields according to the error message.

    The following procedure uses the **Product\_Type** field as an example.

    1.  Drag the **Product Type** field from the dimension list to the **Color Legend** area and click **Update**.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9114/15332612031449_en-US.png)

    2.  Select **Style** \> **Settings**， you can change the color scheme.
4.  Click **Refresh** to select a time interval to automatically refresh the data.
5.  On the Style tab, you can change the display style, layout, axis, and settings through the Common Settings.

    You can set **Coefficient** to change the conversion unit of the original value. The Coefficient parameter supports only multiplication.

    For example, if the unit of the original value is centimeter and you want the value to be expressed in units of meters, you must divide the original value by 100. To achieve this, enter 0.01 in the Coefficient text box. Reversely, if the unit of the original value is meter and you want the value to be expressed in units of centimeters, enter 100 in the Coefficient text box.

6.  Click the More tab, you can associate the chart with other charts.

    Before associating charts, ensure that at least two charts are available in the dashboard display area.


