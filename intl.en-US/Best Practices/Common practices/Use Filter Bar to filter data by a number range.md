# Use Filter Bar to filter data by a number range {#concept_zbj_wxg_4fb .concept}

You can use the Filter Bar widget to filter data by a number range. You specify a range to filter data based on your requirements.

Scenario: Filter the company\_sales\_record dataset by provinces and cities with values between 2,500 and 4,500.

## Create a dataset {#section_gq4_hyg_4fb .section}

1.  Log on to the Quick BI console.
2.  Click **Workspace** \> **Datasets** to enter the Datasets page.
3.  Click **Create Data Sources** to select a data source.

    **Note:** For more information about how to create a data source, see [Create a cloud data source](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from an external database](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

4.  Click the **Create Dataset** icon to [create a dataset](../../../../../reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Create a dashboard {#section_gq1_3yg_4fb .section}

1.  Click **Dashboards** to enter the Dashboards page.
2.  On the Data tab, select the company\_sales\_record dataset.
3.  Select a chart such as Table.
4.  Select a field as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9193/15541067822011_en-US.png)

5.  Click **Update** to automatically generate the chart.

## Filter data by a number range {#section_edh_3yg_4fb .section}

1.  Click the **Filter Bar** icon.
2.  Select the company\_sales\_record dataset as a dataset and order\_amt as a filter field.
3.  Click the **Set Filter** icon.
4.  In the **Set Filter** dialog box, click the **Single-Dataset** tab, and select the table as the associated chart as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/24378/155410678242127_en-US.png)

5.  In the **Filter Bar** widget, set a number range.
6.  Enter two numbers for this filter range, which is greater than 2,500 and less than 4,500 as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/24378/155410678232137_en-US.png)

7.  Click the Search button to automatically update the associated charts. You can obtain the results whose order amount ranges from 2,500 to 4,500 as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9193/15541067822023_en-US.png)


