# 即席分析SQL建模 {#concept_1322831 .concept}

在数据建模过程中，一些复杂逻辑可以通过使用即席分析SQL创建数据集实现。即席分析SQL支持动态传参。基于SQL传参实现建模分析，扩展敏捷BI支撑的场景深度，满足复杂的数据分析场景诉求。

## 操作步骤 {#section_epf_mir_n33 .section}

1.  在**数据源**页面单击右上角**即席分析SQL**。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836552647_zh-CN.png)

2.  在即席查询SQL页面，您可以修改指定数据源。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836552648_zh-CN.png)

3.  确定数据源后输入SQL语句。

    示例：

    ``` {#codeblock_3ds_93c_o9f}
    SELECT  report_date,
            order_level,
            shipping_type,
            area,
            price,
            order_number
    from    company_sales_record
    where   ${report_date :report_date}
    and     ${order_level :order_level}
    and     ${order_number :order_number}
    ```

4.  单击**执行**，运行SQL语句。
5.  查看执行结果

    在执行结果界面您可以查看SQL执行结果。

    1.  单击**执行结果**页签。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836652654_zh-CN.png)

    2.  单击**历史记录**页签可查看当前即席分析SQL执行时间、对应的SQL语句以及SQL执行耗时。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836652657_zh-CN.png)

        -   单击**复制**，复制对应SQL语句，可将其粘贴到SQL输入框中。
        -   单击**创建数据集** 可直接将历史SQL语句创建为数据集。
        -   单击![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836652658_zh-CN.png)收起执行结果。
    即席分析sql支持动态参数，在SQL建模时，在where语句后面追加SQL参数，参数格式为$\{物理字段名:参数别名\}，该参数可以在查询控件中被引用。

    **说明：** 参数字段在数据集中不显示，在查询控件中会显示。

    SQL示例：

    ``` {#codeblock_k8o_20y_5bj}
    SELECT  report_date,
            order_level,
            shipping_type,
            area,
            price,
            order_number
    from    company_sales_record
    where   ${report_date :report_date}
    and     ${order_level :order_level}
    and     ${order_number :order_number}
    ```

6.  参数设置

    可新增参数变量和修改变量类型。目前支持文本、数值、日期-年月日、日期-年月、日期-年五种变量类型。

    -   单击**新增参数变量**新增参数别名和变量类型，此参数别名需要以$\{物理字段名：参数变量名\}格式添加到SQL语句where条件中。
    -   单击**快速提取**自动获取SQL语句中的参数别名，变量类型默认为文本，可手动修改。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836652662_zh-CN.png)

    -   单击**格式化**可格式化SQL语句。
7.  单击**创建数据集**填写数据集名称和保存位置完成数据集创建。创建成功后，页面会自动跳转到数据集管理页面，新创建的数据集会带有New的图标，方便快速定位新的数据集。

    在数据集列表页选择此数据集右键选择**修改SQL**可修改此即席分析SQL语句。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836653490_zh-CN.png)

    **说明：** 即席分析sql不支持MySQL 5.7版本数据库表名别名，不支持DDL语句。


## SQL参数在查询控件中的使用 {#section_nnd_br0_g0i .section}

1.  单击查询控件选择数据集，若数据集中含有SQL参数，在数据集选择区除展示对应的维度、度量外还会展示数据集中的SQL参数。SQL参数显示为橙色。

    **说明：** SQL参数不支持设置级联查询。

2.  选择参数项，单击设置**过滤条件**图标，对筛选项进行设置。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836653498_zh-CN.png)

    日期类型、数值类型及文本型的**按条件筛选**参数查询设置请参见[查询控件](cn.zh-CN/用户指南/仪表板制作/通用控件/查询控件.md#)。

    文本型**按枚举筛选**参数项设置需先设定枚举值范围，手动输入参数项。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836653508_zh-CN.png)

    查询时选择对应参数即可。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1054403/156526836653513_zh-CN.png)


