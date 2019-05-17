# Join data tables {#concept_yzb_qxr_ngb .concept}

If you have multiple tables based on the same data source, you can use the **Table Joinb** function to join multiple tables by using the snowflake model. For example, when you join Table A with Table B and join Table B with Table C, Quick BI automatically adds join fields involved in hierarchies to the dimension and measure lists of Table A.

## Description of joined data tables {#section_gpz_5gr_5db .section}

**Note:** 

-   You cannot associate multiple datasets with charts in Quick BI Basic and Quick BI Pro.
-   You can associate multiple datasets with charts in Quick BI Enterprise Standard. Now, this feature is only available when the data source type is MaxCompute, MySQL, and Oracle.
-   The associated data table can only be the original table in the database. Currently, it cannot be associated with created datasets.

Currently, you can use the following three joins in Quick BI:

-   Inner join
-   Left outer join
-   Full join

    **Note:** You cannot use a full join on a MySQL data source.


## Example of joining data tables {#section_yfk_czr_ngb .section}

1.  Click the **Join** icon to enter the **Table Join** page as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/116859/155806022537882_en-US.png)

2.  Click the **+** icon to add a table that you want to join.
3.  Click the drop-down arrow for **Dataset Field** to select a field as the following figure shows.

    ![](images/34000_en-US.png)

4.  Click the drop-down arrow for **Join Type** to select a type as the following figure shows.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9093/15580602256892_en-US.png)

5.  Click the drop-down arrow for **Associate Table** to select a table as the following figure shows.

    ![](images/34003_en-US.png)

6.  Click the drop-down arrow for **Join On** to select a field.
7.  Click **OK** to add a join table as the following figure shows.
8.  Click the **Preview** icon to switch to the preview mode as the following figure shows.

    ![](images/37883_en-US.png)

9.  Click **Save** to save the dataset.

    **Note:** Before saving the dataset, you can click **Set filter conditions** to filter the data in the current dataset to reduce searches for non-relevant data when using this dataset.

    ![](images/37886_en-US.png)


