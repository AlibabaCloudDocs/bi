# Filter bars {#concept_rtm_qwb_dhb .concept}

You can use a **filter bar** to filter data in one or more charts. A dashboard can contain multiple filter bars. You can pin a maximum of one filter bar each time.

1.  Click a **filter bar**.
2.  Select a dataset and select the fields to be added to the filter bar as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575347578_en-US.png)

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575344555_en-US.png)

    **Note:** You can select **Enter a filter** for a dimension field. After doing this, queries can be performed only when you select a value for the field.

3.  On the **Style** tab page, you can perform the following operations.
    -   Settings: configures the name of the filter bar, whether to show the name, whether to pin the filter bar, arrangement of filters in the bar, and whether to hide the Query button.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575343674_en-US.png)

    -   Bar style: configures the height of the filter bar, alignment of filters in the bar, and label position.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575343678_en-US.png)

    -   Field style: configures the style of filters and width of search fields.

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575343679_en-US.png)


Currently, a filter bar supports filter interactions between charts of the current dataset or charts of different datasets.

**Filter interaction example for the current dataset**

1.  Select **Current Dataset**. In the current dataset field list, select charts by the field type, as shown in the following figure.
2.  Click **Style** to edit the display name of the filter bar.
3.  Click **Search** to filter the associated charts.

**Filter interaction example for different datasets**

Filter bars can also filter data from different datasets. However, in the associated items, the data members must have the same fields. Otherwise, the interaction does not work.

1.  Select a chart, such as a table.
2.  Select the required fields, and then click **Update**.
3.  Click the **Style** tab, and then change the display name and layout of the table. For example, set the display name of the table to **overseas data**.
4.  Click the icon that switches datasets to change to another dataset.
5.  Select a chart, such as a table.
6.  Select the required fields, and then click **Update**.
7.  Click the Style tab, and then change the display name and layout of the table. For example, set the display name of the table to **domestic data**.
8.  Click the **Filter Bar** icon, and then select the dataset and add filter fields to the filter bar.
9.  Select **Other Dataset**. In the Other Dataset list, select the associated items based on the field type.
10. Click the **Style** tab to specify the display name of the widget.
11. Click **Search** to update the charts filtered by the fields.

**Cascade filter example**

The filter bar supports cascade filtering, which simplifies the steps of setting multiple filters.

1.  Create line charts on the dashboard editing page, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575347586_en-US.png)

2.  Click the **filter bar** widget and then select the dataset and fields to be filtered. In this example, we select the **province** field as the filter, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575347587_en-US.png)

3.  Click the cascade icon. On the **Configure Field Cascade** page, click **+ Add cascading relationship** to add the fields to be cascaded, and then click **OK**. In this example, we select the **city** field and the **product type** field.

    **Note:** 

    -   The cascade filter supports three-level cascades, with lines connected between the parent nodes and child nodes.
    -   The cascade filter supports renaming the cascade fields.
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447588_en-US.png)

4.  Click **Set Filter** to set the filters and then click **OK**. In this example, we select Tile cascade display and Multiple Select, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447589_en-US.png)

    **Note:** The cascade display supports Tree cascade display and Tile cascade display. You can select Cognate inheritance and Manually set default values.

5.  In the search widget, click **Search**. The result is shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447590_en-US.png)

    **Note:** To view the detailed information of the cascade, you can hover over the cascade icon in the upper-right corner.


**Filter by date**

When you filter data in date type, you can select the date range of the filter, manually set default values, and customize shortcuts, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447591_en-US.png)

1.  In the Data tab, select the dataset and the fields to be filtered, such as the order date \(month\).
2.  Select a chart that needs to be filtered, and then click **Set Time Range**.
3.  In the **Set Time Range** dialog box, enable Set Time Range, specify the time range, and then click **OK**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447592_en-US.png)

4.  Select **Manually set default values** or **Customize shortcuts** to select a date range, and then click **OK**.

    **Note:** The date currently supports types of month and day for you to customize the date range.

5.  Click **Search**. All the charts that are filtered by the widget are updated.

**Filter by text data**

When you filter data in text type, you can set the enumeration range as shown in the following figure .

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575447594_en-US.png)

1.  In the Data tab, select the dataset and fields to be filtered, such as the product package.
2.  Select a chart that needs to be used, and then click **Set Enumeration Range**.
3.  In the **Enumeration Range** dialog box, enable Set Enumeration Range, click Manually set values or add available values such as **middle box**, **large box**, **small package**, and **small box**, and then click **OK**, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575547595_en-US.png)

4.  Select **Filter by Enumeration** and **Multiple Select**, and then click the drop-down menu. The system automatically adds the available values of this field to the filter bar, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575547596_en-US.png)

    **Note:** Select **Add by Select Sequence** to sort and display values by the sequence in which you select the values.

5.  Manually specify the value or select the available values for the field to be filtered, and then click **OK** \> **OK**.
6.  Click **Search**. The charts that are filtered by the filter bar are updated.

**Filter by numeric data**

1.  On the Data tab page, select a dataset and filter fields. The following example uses order\_number.
2.  Select charts to be linked. Click **OK** as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/140555/156404575547597_en-US.png)

3.  Click **Query** and charts that are linked by the filter bar update.

