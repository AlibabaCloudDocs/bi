# Example: Create workbooks {#task_p4j_qqp_5db .task}

You can only create workbooks in the Workspace of Quick BI Enterprise or Quick BI Pro. The workbook feature is unavailable in Personal Space. This example uses a dataset named company\_sales\_record to create a commodity sales and trading table.

## Create workbooks {#task_vcl_djq_5db}

Quick BI categorizes data in a dataset into dimensions and measures based on certain rules. In most cases, data of String type falls into the category of dimensions, while data of Double type or Bigint type falls into the category of measures. You can select proper fields from the dimensions and measures to place them in rows or columns, and perform data analysis with proper filtering conditions.

1.  Log on to the Quick BI console, and click **Workspace**. 
2.  Click **Workbooks** to go to the workbook management page. 
3.   Click **Create Workbook** to go to the workbook editing page. 
4.   Click the **All** icon, or the data cannot be displayed normally. 

    You can also specify the scope of data to be displayed on the workbook. The data can be displayed in partitions.

5.  Locate the company\_sales\_record dataset. Double-click the **product\_type** field and the **order\_amt** field, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9078/15502129326296_en-US.png)

 
6.   Click **Update** to update the data. 
7.   Click **Save** and select a location to save the workbook. You can also save the workbook to a local disk.
8.  Enter **Commodity sales and trading table** as a table title, and click **OK**. 

## Insert charts \(for Quick BI Enterprise\) {#task_psy_4jq_5db}

If you use **Quick BI Professional Edition**, you can insert charts and a filter bar in the workbook.

Workbook supports eight charts and one filter bar. You can insert charts and widgets to display data based on your needs.

1.  Click the chart icon or click **More**. Select a chart type. For example, you can select a column chart, as shown in the following figure. 
2.  In the workbook, select the data source used to make a chart, as shown in the following figure. 
3.  Click **OK**. A chart is automatically displayed in the workbook, as shown in the following figure. 
4.  In the chart, click the icon in the upper right corner, and you can select **Refresh**, **Settings**, or **Delete**, as shown in the following figure. 
5.   You can drag and drop the chart to any position. 

## Insert filter bars \(for Quick BI Enterprise\) {#task_sfw_zjq_5db}

1.  Click **Filter Bar**. 
2.  Click **+Add Correlated Datasets** to add a filter. 
3.   Click the drop-down arrow and select a data source from the drop-down list. 
4.  Select a field to be queried, for example, the **shipping-cost** field. Double-click or drag and drop the field to Filter Fields. 
5.  Click the **Set Filter** icon, select the query scope and the target chart, and click **OK**. The filter bar supports the association of datasets from different sources or from the same source. This example uses the **Current Dataset** association.
6.   Click **Filter**, and the data in the table with shipping costs above 1,000 will be automatically filtered. 
7.  Click the **Delete** icon to delete the current field. 
8.  Click the close button to delete the current filter bar. 

