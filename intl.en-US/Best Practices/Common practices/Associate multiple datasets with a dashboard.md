# Associate multiple datasets with a dashboard {#concept_on2_qwg_4fb .concept}

When you configure a cross-chart reference, you can associate a single dataset or multiple datasets with available charts in a dashboard. When you want to compare data from multiple datasets, you must select an associated field from each dataset. Some values of these selected fields must be the same. Otherwise, you cannot compare multiple datasets. This example is based on the company\_sales\_record\_en\_us and company\_sales\_record datasets.

## Create a dataset {#section_kwv_wwg_4fb .section}

1.  Log on to the Quick BI console.
2.  Choose **Workspace** \> **Datasets** to enter the Datasets page.
3.  Click **Create Data Sources** to select a data source.

    **Note:** For more information about how to create a data source, see [Create a cloud data source](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from an external database](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

4.  Click the **Create Dataset** icon to [Create a dataset](../../../../../reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Create a dashboard {#section_vhf_xwg_4fb .section}

1.  Click **Dashboards** to enter the Dashboards page.
2.  On the Data tab, select the company\_sales\_record\_en\_us dataset.
3.  Select a chart such as table.
4.  Select the required fields.
5.  Click **Update** to update the chart.
6.  Click the **Style** tab, rename the chart to **Overseas report** as shown in the following figure.
7.  On the Data tab, select the company\_sales\_record dataset.
8.  Select a chart and fields, such as table.
9.  Click **Update** to update the chart.
10. Click the **Style** tab, rename the chart **Domestic report**.
11. Click **Save** to save the dashboard.

## Associate multiple datasets with a dashboard {#section_wjl_xwg_4fb .section}

1.  Click the **Filter Bar** control, and drag the control at the top of the dashboard.
2.  On the **data** tab, select a dataset, such as company\_sales\_record.
3.  Select a field to be filtered such as product\_box.
4.  Click the **Set Filter** icon.

    ![](images/11472_en-US.png)

5.  In the **Set Filter** dialog box, click the **Single-Dataset** tab and select Domestic report.
6.  Click the **Multi-Dataset** tab, and click the drop-down arrow of Overseas report to view the field list.
7.  Select the product\_box field.
8.  In the **Set Filter** area, click **Filter by Enumeration** and select **Radio** or **Multiple Select**.
9.  Click the drop-down arrow of product\_ box, select the values to be filtered, and click**OK**.
10. Click **Search** to obtain the query results from both the Overseas report chart and the Domestic report chart.

