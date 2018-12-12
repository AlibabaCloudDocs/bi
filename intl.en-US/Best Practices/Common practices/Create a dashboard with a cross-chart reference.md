# Create a dashboard with a cross-chart reference {#concept_jrd_kfz_5db .concept}

When you create a dashboard, you may have a requirement like that. For example, when you click an area of a chart, you want the corresponding fields of other correlated charts to change along with this area.

This section describes how to create a dashboard with a cross-chart reference. Take a sample dataset provided in our data model as an example. This dashboard consists of two charts, divided into two parts the upper half and lower half respectively. In the upper half, a pie chart contains the profit data for each region. In the lower half, a table contains the sales and profit data of cities in each region.

## Prepare sample datasets {#section_pyy_lgz_5db .section}

Create a dataset by using a CSV file. For more information, see[Upload local files](../../../../intl.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

Rename this dataset **demo sales dataset**.

## Create a pie chart that contains profit data of each region {#section_uyf_5d2_vdb .section}

Create a dashboard and then click the pie chart icon in the configuration area of this dashboard. You can configure the dataset of this pie chart as follows.

-   Select **Sales data demo dataset** as the dataset of this pie chart.
-   Select the **area** field as a dataset dimension.
-   Select the **profit\_amt** field as a metric.

Click the **Update** button.

On the **Style** tab, set the title of the pie chart to Regional Data. The result is shown in the following figure.

## Create a table that contains sales and profit details of cities in each region {#section_vkw_ll2_vdb .section}

In the configuration area of this dashboard, click the table icon and then drag it to the lower half of the dashboard. You can configure data attributes of this table as follows.

-   Select **Sales data demo dataset** as a dataset of this table.
-   Select the **area** field and the **city** field as data dimensions.
-   Select the **profit\_amt** field and the **order\_amt** field as metrics.

On the **Style** tab of the table, set the title of this table to **City data details**.

Click the **Update** button. The result is shown as follows.

## Configure a cross-chart reference on the pie chart {#section_yvx_kmf_vdb .section}

On the **Advanced** tab of the pie chart, click the pencil icon next to **Correlate** to correlate the pie chart and the table. You can configure the correlation as follows.

## Preview correlations {#section_utx_tmf_vdb .section}

Click the **Preview** button to view how the correlation works.

Click the **East** region on the pie chart, the data is shown as follows.

Click the **North** region on the pie chart, the data is shown as follows.

## Save the dashboard {#section_nsz_qnf_vdb .section}

Save this dashboard after you complete the previous steps.

## Publish the dashboard {#section_qmt_znf_vdb .section}

If no sensitive data exists in a dashboard, you can publish this dashboard on the Internet.

