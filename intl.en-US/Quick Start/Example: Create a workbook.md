# Example: Create a workbook {#task_p4j_qqp_5db .task}

The workbook is only available for workspace in Quick BI Pro and Quick BI professional edition. In the personal workspace, the workbook function is invalid.

We can obtain a commodity sales trade table by using the Quick BI.

## Log on to Quick BI main page. {#task_vzq_hrp_5db}

1.   Click Console \> Workspace to go to Quick BI. 
2.   Select a workspace to enter a workspace workbench.  

## Add a data source {#task_x4b_4rp_5db}

When using Quick BI to analyze data,  you must specify the data source for raw data. After adding data sources, you can use tables of different data sources as datasets and classify and filter data. After adding a data source, you can use a tables in the data source to create the dataset. The following uses adding a MySQL data source as an example.

1.   Log on to the Quick BI console. 
2.   Select **Workspace** \> **Data sources**. The data source management page is displayed. 
3.  Switch to a workspace by clicking the Switch icon.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9078/15342161566291_en-US.png)

 
4.   Click **Create \> MySQL**, to add a new data source. 
5.   Enter the connection information, as shown in the following figure. 

    **Note:** The following figure only shows an example to add a data source, please enter the information based on an existing environment.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9078/15342161566292_en-US.png)

    -   Name: Enter a display name
    -   Host name: rm-bp180925lcrm7xtc6.mysql.rds.aliyuncs.com \(To obtain the host name, see [Setup Quick BI with ApsaraDB for RDS](intl.en-US/Quick Start/Setup Quick BI with ApsaraDB for RDS.md#).\)
    -   Port: Default 3306
    -   Database: bi\_demo
    -   User name: bi\_demo
    -   Password: Database password
6.   Click **Test Connection** to test whether the database can be connected. 
7.   Click **Add**. The data source is added. 

## Create a dataset {#task_lyk_53q_5db}

1.  Find the expected table on the right side of data sources page, for example **company\_sales\_record**. 
2.   Click **Create Dataset**, to create a new dataset. 

    After the dataset is created, the dataset page is automatically displayed.


## Create a workbook {#task_vcl_djq_5db}

The columns in the workbook are classified into dimensions and measurements based on certain rules. Generally, columns of the String type are in the dimension category, while columns of the Double or Bigint type are in the measurement category.  You can select columns from the dimension and measurement categories as the rows or columns of the workbook and configure appropriate filtering criteria.

1.  Click **Workbooks** to enter the workbook management page. 
2.   Click **Create \> Workbook** icon, the workbook editing page is displayed. 
3.   Click **Select All** icon, or the data cannot be displayed normally. 

    You can also select the scope to be displayed on the workbook, and the data can be displayed in partitions. For more information, see [Area show](intl.en-US/Quick Start/Create a report/Area show.md#).

4.  Double-click order\_amt field and prodcut\_type field, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9078/15342161566296_en-US.png)

 
5.   Click **Update**, the data content is automatically update. 
6.   Click **Save**, and select a location to store the workbook. 

    In **Quick BI Professional edition**, you can save the current workbook to local directory.

7.  Enter **Commodity sales trade table** as a table title, and click **OK**. 

## Insert Chart \(Quick BI Professional edition\) {#task_psy_4jq_5db}

If you have purchased a **Quick BI professional edition**, you can insert charts and widget in the workbook.

Currently, the workbook provides 8 charts and 1 widget to you. You can insert charts and widget to display data based on your actual needs.

1.  Click **More**, and select a chart. For example select a bar chart. 
2.  In the workbook, Select data that needs to be used to make a chart. 
3.  Click **OK**, the chart automatically displays in the workbook. 
4.  In the chart, click the icon in the upper right corner, and select **Refresh**, **Settings**, and **Delete**functions. 
5.   Click on the chart to drag the chart to other locations. 

## Insert query editor \(Quick BI Professional edition\) {#task_sfw_zjq_5db}

1.  Click **Query** editor to open the query menu. 
2.  Click **+** to add a query widget. 
3.   Click drop-down arrow to select a dataset. 
4.  Select a field that needs to be querying from the field list. 
5.   Select a chart that the widget needs to work, the widget automatically displays on the top of the workbook. The widget is automatically displayed on the upper of the table. 

    Currently, the workbook supports Single-dataset and Multi-dataset, the following steps use the **Single-dataset** as an example.

6.  Click Settings icon in the widget, and set up a query range of the widget. 
7.  Enter a query range value manually, and click OK. 
8.   Click **Search** to filter the data. 
9.  Click **Delete** icon in the widget to delete the current field, but the widget is still available. 
10. Click Delete icon in the query menu to delete the current widget. 

    For more operations about the workbook, see [Area show](intl.en-US/Quick Start/Create a report/Area show.md#) and [Add query tools](intl.en-US/Quick Start/Create a report/Add query tools.md#).


