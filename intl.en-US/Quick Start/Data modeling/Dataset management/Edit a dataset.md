# Edit a dataset {#concept_lth_dgr_5db .concept}

You can edit a dataset based on the chart demonstration needs.

1.  Log on to the Quick BI console.
2.  Click **Datasets**. The dataset management page is displayed. 
3.  Select a dataset and click its name. The dataset editing page is displayed.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346888_en-US.png)


Fields in the dataset are automatically classified into **dimensions** and **measurements**. You can edit the dimension and measurement fields based on your table creation requirements. After the dataset is edited, you can save and refresh the edited data using **Toolbar** provided by the system.

## Edit a dimension field {#section_ety_jgr_5db .section}

You can click the operation icon of a dimension field or right-click a dimension field to open the editing menu. For example, if you want to create a bubble or color map, you must set the dimension type to "Geographical Information". Otherwise, you cannot properly make the map.

1.  Select a dimension field,  for example, **order\_level**.
2.  Right-click the selected field. The field editing menu is displayed, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346889_en-US.png)

    -   Edit: To modify the display name and remarks of a dimension field.
    -   Duplicate Dimension: To quickly copy a dimension. **Copy** is automatically displayed for the generated dimension.
    -   Hide in analysis: Hide related dimensions.
    -   Cancel all hidden: Cancel the hide for related dimensions.
    -   Delete: To delete a field.
    -   Create Calculated Field \(Dimension\): To create a dimension field and customize the calculation mode.
    -   Move To: To quickly include a dimension field in an existing level for drilling.
    -   Create Level: To quickly include a dimension field in a created level.
    -   Move Up/Move Down: To move a field. You can drag the field or right-click the field to move it.
    -   Convert to Measurement: To convert the current dimension field to a measurement field.
    -   Change Dimension Type: To switch a dimension field to the default, date, or geographical type.

## Edit a measurement field {#section_lw2_4gr_5db .section}

1.  Select a measurement field, for example, **order\_number**.
2.  Right-click the selected field. The field editing menu is displayed, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346890_en-US.png)

    -   Edit: To modify the display name and remarks of a measurement field.
    -   Duplicate Measure: To quickly copy a measure. **Copy** is automatically displayed for the generated measure.
    -   Hide in analysis: Hide related measures.
    -   Cancel all hidden: Cancel the hide for related measures.
    -   Delete: To delete a field.
    -   Create Calculated Field \(Measurement\): To create a measurement field and customize the calculation mode.
    -   Move To: To quickly include a measurement field in an existing folder.
    -   Move Up/Move Down: To move a field. You can drag the field or right-click the field to move it.
    -   Convert to Dimension: To convert the current measurement field to a dimension field.
    -   Number Format: To set the display format of a number.
    -   Aggregations: You can select an aggregation mode, such as sum, max, or min, on the menu.
    -   Change Measure Type: To switch a measure field to the default, date, or geographical type.

## Toolbar {#section_nk5_rgr_5db .section}

You can use the toolbar shown in the following figure to save, refresh, or synchronize datasets.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346891_en-US.png)

-   Sync Table Schema: To combine new table fields added to an online physical table. This operation can be used when an online physical table is changed, for example, a field is added. In this case, fields can be easily synchronized online. If a field of the online table is deleted or renamed, the corresponding dimension/measurement of the dataset is not deleted.
-   Refresh Preview: To refresh and preview data of a dataset.  If you want to view the latest data in real time, save the dataset and then refresh data.
-   Save: To save a dataset.
-   Save As: To save the current dataset as a new one. This operation can be used to quickly copy a new dataset or back up a dataset.

## Join tables {#section_gpz_5gr_5db .section}

**Note:** Professional edition supports Multi-Dataset type, and it only applies to the MaxCompute, MySQL, and Oracle data source. Other editions don't support.

mysql Oracle

The Multi-Dataset type is not supported

The following two joining modes are supported.

-   Inner Join
-   Left outer join

If you have two data tables that are from the same dataset, you can click **Join Table** to join one or multiple fields in the second table to the table that is currently edited. The joined table fields are automatically added to the dimension and measurement areas of the first table as folders.

1.  Click the **Join Table** icon. The data table joining page is displayed.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901341322_en-US.png)

2.  Click **+ Table Join** and add the data table to be joined.
3.  Click the drop-down arrow of Dataset Field and select the dataset field to be joined.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901341323_en-US.png)

4.  Click the drop-down arrow of **Join Type** and select the join mode.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346892_en-US.png)

5.  Click the drop-down arrow of **Associate dimension table name** and select a joined table name.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901341325_en-US.png)

6.  Click the drop-down arrow of **Join On** and select a joined field.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901341326_en-US.png)

7.  Click **OK**. The joined table is added.
8.  Click the preview icon to switch to preview mode, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15332901346893_en-US.png)

9.  Click **Save** to save the current dataset.

**Joined table example**

1.  On the dataset management page, select company\_sales\_record1.
2.  Click its name and enter the dataset editing page.
3.  Click the **Join Table** icon. The joined table editing page is displayed.
4.  Click **+** to open the associated model dialog box.
5.  Click **Dataset Field** drop-down arrow to select an associated field.
6.  Click the **Join Type** drop-down arrow to select a join type, such as **left outer join**.
7.  Click the drop-down arrow of **Associate dimension table name** and select an associated dataset.
8.  Click **Join On** drop-down arrow to select an associated field.
9.  Click **OK**. The joined table is added.
10. Click **Preview** icon to preview the data.
11. Click **Save** to save the dataset.

