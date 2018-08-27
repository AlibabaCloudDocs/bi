# Use filters in a dashboard {#task_jlp_q5f_vdb .task}

In the dashboard, you can use filters to filter data and view more precise content in the report. You can find desired data based on configured filters.

Scenario: Compare shipping costs in "East China", "South China", and "North China".

The following example uses company\_sales\_record as its dataset.

## Create a dataset {#task_yj4_55f_vdb}

1.  Log on to the Quick BI console. 
2.  Click **Workspace** \> **Data sources** to go to the data source management page. 
3.  Click **Create Data Sources**, and select a data source. For more information about how to create a dataset, see [Create cloud data source](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a cloud data source.md#), [Create a data source in the self-built database](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a data source from external database.md#), and [Upload a local file](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#).
4.  Click the **Create Dataset** icon. For information about how to create a dataset, see [Create a dataset](../../../../intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#). 

## Create a dashboard {#task_w5s_dvf_vdb}

1.  Click **Dashboards** to go to the dashboard management page. 
2.  Click the dataset to switch to the **company\_sales\_record** dataset. 
3.  Select a chart type, such as a pie chart. 
4.   Select a field, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600221914_en-US.png)

 
5.  Click **Update**, and the system automatically draws a chart. 

## Implement data filtering {#task_m51_gwf_vdb}

1.   Drag the **area** field to the **Filters** area, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600221932_en-US.png)

 
2.   Click **Filters** to set the filters, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600221933_en-US.png)

 
3.   Click **Enum**. All the options in the field are listed automatically, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600231937_en-US.png)

 
4.   Select **East**, **North**, and **South**, and then click **OK**, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600231940_en-US.png)

 
5.  Drag the filtered **area** field to return to the dimension area. 
6.   Click **Update** to update the chart. The chart shows only the comparison results of shipping costs in "East", "North", and "South", as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9190/15353600231942_en-US.png)

 

