# Use the filter bar to search for data by date {#task_uxp_dpf_vdb .task}

The filter bar allows you to search for data by date. You can set the date range to search for required data.

The following example uses company\_sales\_record as its dataset.

## Create a data set {#task_o2m_kpf_vdb}

1.  Log on to the Quick BI console. 
2.  Click **Workspace** \> **Data sources** on the left side pane to go to the data source management page. 
3.  Click **Create Data Sources**, and select a data source. 

    For more information about how to create a data source, see [Create a cloud data source](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a cloud data source.md#), [Create a data source under self-built databases](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a data source from external database.md#), and [Upload local files](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#).

4.  Click the **Create Dataset** icon. For information about how to create a dataset, see [Create a dataset](../../../../intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#). 

## Create a dashboard {#task_c4b_3pf_vdb}

1.  Click **Dashboard** to go to the dashboard management page. 
2.  Click the dataset to switch to **company\_sales\_record** dataset. 
3.  Select a chart type, such as a bar chart. 
4.  Select a field, as shown in the following figure. 

    **Note:** Data must contain date fields in order to be searched by date.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15401990141887_en-US.png)

5.  Click **Update**. The system automatically draws the chart. 

## Search for data by date {#task_xtb_srf_vdb}

1.  Double-click the **Filter bar** icon. 
2.  Select **company\_sales\_record** as the source dataset. 
3.   Select **report\_date\(month\)** as the field to be searched for.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15401990141894_en-US.png)

 
4.   Click **Single-Dataset**, and select **Bar** as the associated chart, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15401990141898_en-US.png)

 
5.   In the search box, click the field name to open the field filter menu, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15401990141902_en-US.png)

 
6.   Select **Date range** and set the start and end dates in the search box, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9189/15401990141913_en-US.png)

 
7.  Click **Search**. The system updates the chart based on the specified conditions. 

