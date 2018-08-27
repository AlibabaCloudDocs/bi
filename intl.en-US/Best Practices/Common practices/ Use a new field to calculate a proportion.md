# Use a new field to calculate a proportion {#concept_bmp_rkg_vdb .concept}

When you use workbooks, the proportion of data under certain conditions need to be calculated. To solve this problem, create a new field. Proportion problems are classified into two types. The first type is the proportion of similar orders. For example, you need to calculate the proportion occupied by the order amount of each product type in "North China" to the total amount in all areas. The other one is the proportion of the number of orders. For example, to calculate the proportion of the number of senior orders, you must calculate the number of senior orders and that of total orders.

The following example uses company\_sales\_record as its dataset.

## Prepare the dataset {#section_yz2_pmg_vdb .section}

Create a dataset based on the table company\_sales\_record and change the geographical dimension of the area parameter to: area.

## The new field shows the order amount in “North China”  {#section_d4s_xmg_vdb .section}

On the dataset editing page, create a measure: order\_amount\_in\_NorthChina, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9194/15353600832031_en-US.jpg)

## Create a field to calculate the proportion of the order amount in North China {#section_xtv_2ng_vdb .section}

On the dataset editing page, create a measure: proportion\_order\_amt\_NorthChina, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9194/15353600832032_en-US.jpg)

## Save and refresh the dataset, and then create a new workbook {#section_ult_kng_vdb .section}

Save the dataset and create a new workbook. Select **product\_sub\_type**, **order\_amount\_in\_NorthChina**, **order\_amt**, and **proportion of order amount in NorthChina**, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9194/15353600832036_en-US.jpg)

## Save the workbook {#section_pjh_wng_vdb .section}

Save the workbook. The amount proportion problem is solved.

## Create a new field to calculate the proportion of the number of senior orders {#section_hjw_yng_vdb .section}

Create a measure to display the proportion of the number of senior orders.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9194/15353600832042_en-US.jpg)

## Save the dataset, and create a new workbook {#section_jw2_f4g_vdb .section}

Select **area**, **proportion\_L1\_order**, and **order\_number**, as shown in the following figure.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9194/15353600832043_en-US.jpg)

## Save the workbook {#section_kln_m4g_vdb .section}

Save the workbook. The number proportion problem is solved.

