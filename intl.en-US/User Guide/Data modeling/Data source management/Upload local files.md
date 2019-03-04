# Upload local files {#concept_jxt_21r_5db .concept}

You can upload local CSV files and Excel files \(.xls and .xlsx files\) to the explore space as a data source.

The explore space is a data source type that is used only in the personal workspace. Each user has 1 GB storage space.

In addition, you can import data resources from the Data IDE.

**Note:** The method that you upload local files through **Create Data Source** \> **Local Files** is only available in personal workspaces.

## CSV file {#section_hmp_w1r_5db .section}

CSV files in UTF-8 format are decoded without errors. CSV files in GBK or GB2312 format are automatically decoded, but the decoding may fail in some special cases.

If your CSV files cannot be decoded correctly, use text editors such as Notepad to convert the encoding of the files to UTF-8. Otherwise, the content of the uploaded files is shown as gibberish.

1.  Use **Notepad** to open a CSV file.
2.  Choose **File \> Save As**.
3.  Click the drop-down arrow of **Encoding**.
4.  Select UTF-8.

After you have changed the encoding, upload the CSV file to the explore space.

1.  Log on to the Quick BI console.
2.  Click **Data Source** to enter the Data Sources page.
3.  Choose**Create** \> **Local Upload** \> **CSV file**.
4.  Enter a display name for the file.
5.  Click **Select a file** to select the file to upload, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9086/155168674933512_en-US.png)

6.  Click **OK** to upload the file.

## Excel file {#section_nmp_tbr_5db .section}

When you upload Excel files, the first sheet in each excel file is uploaded by default. To make the editing and maintenance more flexible, you can only select one sheet in one Excel file at a time.

1.  Choose**Create** \> **Local Upload** \> **EXCEL file**.
2.  Enter a display name for the file.
3.  Click **Select a file** to select the file to upload, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9086/155168674933511_en-US.png)

4.  Click **OK** to complete uploading the file.

## Data IDE {#section_d3p_bcr_5db .section}

**Note:** Only supports importing data sources from the China \(Shanghai\) region, and you must add your account to the project.

1.  Choose**Create** \> **From Other** \> **Data IDE**.
2.  Select the data source from the list.
3.  Click **Import** to complete the importing of the data source.

## Update table data according to the local data source {#section_uzm_gcr_5db .section}

The local data source feature of Quick BI is designed to meet the analysis requirements for your changing and growing business.

After you have uploaded a file, new files are generated as the business grows. You can append the new files to the table corresponding to the previously uploaded file to analyze business data consistently over a long period of time.

The new file can be in a format different from the previously uploaded file. For example, if you have uploaded a CSV file, you can import data from a sheet in an Excel file. Make sure that the field names and the field types in the files to be uploaded are the same as those in the previously uploaded file.

1.  Click **Data Source** to enter the Data Sources page.
2.  Click **Explore Space** to enter the Explore Space page.
3.  Select a file, and then click **Update**.
4.  Click **Append** to upload the file that needs to be appended, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9086/155168674933506_en-US.png)

5.  Click **OK** to append the data.

## Delete the data of the table corresponding to a local data source {#section_lcx_kcr_5db .section}

If a file that you have appended contains dirty data, which decreases the accuracy of the data, you can delete the file with dirty data that is corresponding to the table in the uploaded file list. The corresponding dashboard displays corrected data without any manual changes. Therefore, the analysis results of data are accurate at all times.

1.  Click **Data Source** to enter the Data Sources page.
2.  Click **Explore Space** to enter the Explore Space page.
3.  Select a file, and then click **Update**.
4.  Locate the file that needs to be deleted, and then click the **Delete** icon, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9086/155168674933504_en-US.png)


## Example of local files {#section_xvt_qcr_5db .section}

To help you learn to use local data source files, we provide a sample CSV file here: [Sales data examples](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/47483/cn_zh/1483006983645/company_sales_record_utf8.csv?spm=a2c63.p38356.a3.1.613841274yUUi1&file=company_sales_record_utf8.csv).

The structure of the sales data is shown in the following table.

|*Field*|*Field type*|*Description*|
|:------|:-----------|:------------|
|order\_id|varchar|Order ID|
|report\_date|datetime|Order date|
|customer\_name|varchar|Customer name|
|order\_level|varchar|Order grade|
|order\_number|double|Order quantity|
|order\_amt|double|Order amount|
|back\_point|double|Discount|
|shipping\_type|varchar|Shipping type|
|profit\_amt|double|Profit amount|
|price|double|Unit price|
|shipping\_cost|double|Shipping cost|
|area|varchar|Region|
|province|varchar|Province|
|city|varchar|City|
|product\_type|varchar|Product type|
|product\_sub\_type|varchar|Product subtype|
|product\_name|varchar|Product name|
|product\_box|varchar|Product packing box|
|shipping\_date|Datetime|Shipping date|

