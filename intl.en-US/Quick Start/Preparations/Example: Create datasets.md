# Example: Create datasets {#concept_n4y_b35_42b .concept}

## Create datasets {#section_sx4_3hp_5db .section}

You must prepare a dataset before creating a dashboard. To create a dataset, you must first specify a data source. This chapter describes how to create a data source.

This chapter uses a MySQL data source as an example.

1.  Log on to the Quick BI console.
2.  Click **Workspace** \> **Data Sources** to go to the data source management page.
3.  Click **Create Data Source** and select a data source type. For example, you can click the **Cloud Database** tab, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16449/15555804617490_en-US.png)

4.  Enter the connection information, and click **Test Connection** to check whether the data source has been connected, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16449/15555804637491_en-US.png)

    If the data source cannot be connected, a corresponding message is returned. For more information about how to address this issue, see [How to diagnose a data source connection exception](https://help.aliyun.com/document_detail/54950.html?spm=a2c4g.11186623.2.8.I5jjCh).

5.  Click **Add** to add the data source to the data source list.
6.  Select a table, for example, company\_sales\_record, and click the **Create Dataset** icon.

The created dataset is labeled as new dataset and is automatically stored in folder **My Dataset**. This label allows you to quickly locate newly-created datasets.

## Edit datasets {#section_rsj_43p_5db .section}

After you have created a dataset, you can edit the dataset based on your needs. For example, you can change field types or add calculated fields.

Take company\_sales\_record as an example.

1.  Click **Datasets** to go to the Datasets page.
2.  Select a target dataset, for example, company\_sales\_record, and click Edit to go to the dataset editing page.

    To create a map chart, such as a geo bubble map or a geomap, select dimension fields containing geographical information and change the dimension type from String to Location. Otherwise, the map cannot be displayed.

3.  In the dimension list, locate the area option.
4.  Right-click the dimension and choose **Change Dimension Type** \> **Location** \> **Region**.

    **Note:** When the dimension type is changed to geographical information, the selected geographical information must match with the field. For example, if the field is area, you must select Region in the geographical information list. Otherwise, the dimension type cannot be changed.

5.  You can change to Province/Municipality or City in the same way.
6.  After the dataset is edited, click **Save**.
7.  Click **Refresh Preview**. The data is automatically displayed in the table.

For more information about how to edit a dataset, see [Edit a dataset](reseller.en-US/User Guide/Data modeling/Dataset management/Edit a dataset.md#).

