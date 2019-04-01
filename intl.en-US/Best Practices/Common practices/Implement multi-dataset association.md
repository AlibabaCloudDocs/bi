# Implement multi-dataset association {#task_jby_zcg_vdb .task}

The dashboard supports both single-dataset associations and multi-dataset associations to help you associate multiple charts.

The dashboard supports both single-dataset associations and multi-dataset associations to help you associate multiple charts.

Multi-dataset association can associate data from different datasets. Make sure that the values of data members of association items are consistent. Otherwise, the association is invalid.

The following examples use the multi-dataset association function with the example of company\_sales\_record\_en\_us and company\_sales\_record, queries report content from different datasets.

## Create a dataset {#task_yw1_q2g_vdb}

1.  Log on to the Quick BI console. 
2.  Click **Workspace** \> **Data sources** to go to the data source management page. 
3.  Click **Create Data Sources**, and select a data source. 

    For more information about how to create a data source, see [Create a cloud data source](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create cloud data sources.md#), [Create a data source under self-built database](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Create a data source on a self-built database.md#), and [Upload local files](../../../../../reseller.en-US/User Guide/Data modeling/Data source management/Upload local files.md#).

4.  Click **Create Dataset** to create a dataset. 

    For more information about how to create a dataset, see [Create a dataset](../../../../../reseller.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).


## Create a dashboard {#task_i5h_bfg_vdb}

1.  Click **Dashboard** to go to the dashboard management page. 
2.  Click the dataset switch icon to select the company\_sales\_record\_en\_us dataset. 
3.  Select a chart type, for example, Table. 
4.   Select a field, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003211986_en-US.png)

 
5.  Click **Update**.  
6.   Click the **Style** tab, and rename the chart as **Overseas report form**, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003211987_en-US.png)

 
7.  Click the dataset to switch to the company\_sales\_record dataset. 
8.  Select a data chart, for example, Table. 
9.   Select the required field, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003211988_en-US.png)

 
10. Click **Update**. The system automatically draws the chart. 
11.  Click **Style**, and rename the chart as **Domestic report form**.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003221992_en-US.png)

 
12.  Click **Save** to save the dashboard, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003221994_en-US.png)

 

## Implement multi-dataset association {#task_khg_lgg_vdb}

1.  Click the Filter Bar control and drag the control to the top of the dashboard. 
2.   On the data tab, select a dataset that needs to function, for example, maid, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003221995_en-US.png)

 
3.   Select a required field, for example, product\_box.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003221996_en-US.png)

 
4.   Click **Single-Dataset**, and select the domestic report form.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003222003_en-US.png)

 
5.  Click **Multi-Dataset**, and click the drop-down arrow next to the overseas report form to open the field list. 
6.   Select the field you selected on the Data page \(product\_box\).![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003222005_en-US.png)

 
7.  In the control, click **Product box** area to open the field filter menu. 
8.   Select **Enum** as the field filtering condition, and then select **Radio** or **Multiple Select**, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003222006_en-US.png)

 
9.   Click the drop-down arrow of the product box, and select the item to be filtered.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003222007_en-US.png)

 
10.  Click **Search**, and the control performs the query on both the domestic and overseas report forms.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9192/15541003222008_en-US.png)

 

