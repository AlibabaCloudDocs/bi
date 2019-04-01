# Use Filter Bar to filter data by a date range {#concept_hd2_mtg_4fb .concept}

You can use the Filter Bar widget to filter data by a date range. You can obtain target data that falls within a specified range of dates. This example is based on the company\_sales\_record dataset.

## Create a dataset {#section_kh3_rtg_4fb .section}

1.  Log on to the Quick BI console.
2.  Click **Workspace** \> **Datasts** to enter the Datasets page.
3.  Click **Create Data Sources** to select a data source.

    **Note:** For more information about how to create a data source, see [Create a cloud data source](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from an external database](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

4.  Click the **Create Dataset** icon to [Create a dataset](../../../../../reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Create a dashboard {#section_xzs_rtg_4fb .section}

1.  Click **Dashboards** to enter the Dashboards page.
2.  On the Data tab, select the **company\_sales\_record** dataset.
3.  Select a chart such as Pie.
4.  Select a field as shown in the following figure.

    **Note:** If you want to filter a dataset by date, the dataset must include at least one field of the Date type.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15541036681887_en-US.png)

5.  Click **Update** to update the chart.

## Filter data by a date range {#section_mnz_rtg_4fb .section}

1.  Click the **Filter Bar** icon.
2.  Select **company\_sales\_record** as the dataset.
3.  Select the **report\_date\(month\)** field as a filter field as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/24375/155410366842112_en-US.png)

4.  Click the **Set Filter** icon.
5.  In the **Set Filter** dialog box, select **Single-Dataset** and select Charts-Bar as a correlated chart. You can configure the options in the **Set Filter** dialog box. as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/24375/155410366842113_en-US.png)

6.  Click **OK** to complete the filter configuration.
7.  Click **Search** to update the chart based on the specified filter conditions.

