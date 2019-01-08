# Use filters in a dashboard {#concept_of3_r5g_4fb .concept}

In a dashboard, you can use filters to filter data to refine the results for a report. You can obtain the required data that meets the specified filter conditions.

Scenario: Compare shipping costs for East China, South China, and North China based on the company\_sales\_record dataset.

## Create a dataset {#section_nz1_hvg_4fb .section}

1.  Log on to the Quick BI console.
2.  Choose **Workspace** \> **Data Source** to enter the Data Sources page.
3.  Click **Create Data Sources** to select a data source.

    **Note:** For more information about how to create a data source, see [Create a cloud data source](../../../../../intl.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source from an external database](../../../../../intl.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../../intl.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

4.  Click the **Create Dataset** icon to [create a dataset](../../../../../intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

## Create a dashboard {#section_nxn_hvg_4fb .section}

1.  Click **Dashboards** to enter the Dashboards page.
2.  Click the Switch dataset icon, and select the **company\_sales\_record** dataset.
3.  Select a chart such as a pie chart.
4.  Select a field as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15469410071914_en-US.png)

5.  Click **Update**. A chart is generated automatically.

## Filter data {#section_jh5_hvg_4fb .section}

1.  Drag the **area** field to the **Filters** area as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15469410071932_en-US.png)

2.  Click **Filters** icon to set filter conditions as shown in the following figure.

    ![](images/11467_en-US.png)

3.  Choose **Enum** \> **Multiple Select**and click the drop-down arrow to list all options as shown in the following figure.

    ![](images/11468_en-US.png)

4.  Select **East**, **North**, and **South** and click **OK**.
5.  Click **Update** to update the chart. The chart shows only the comparison results of shipping costs for East China, North China, and South China as shown in the following figure.

    ![](images/11469_en-US.png)


