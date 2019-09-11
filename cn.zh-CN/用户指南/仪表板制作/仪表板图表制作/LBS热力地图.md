# LBS热力地图 {#concept_brr_dnf_vdb .concept}

本章节为您介绍LBS热力地图的概述、应用示例、配置样式和如何删除LBS热力地图。

**说明：** LBS飞线地图只可用于**Quick BI专业版**。

## 前提条件 {#section_jmh_4tg_6b4 .section}

-   已[登录Quick BI控制台](https://account.aliyun.com/login/mixlogin.htm?)。

-   已完成[仪表板概述](cn.zh-CN/用户指南/仪表板制作/仪表板概述.md#)和[仪表板基本操作](cn.zh-CN/用户指南/仪表板制作/仪表板基本操作/仪表板基本操作概述.md#)。
-   如果需要对数据集做进一步的编辑，或者想重新创建一个数据集，请参见[创建数据集](cn.zh-CN/用户指南/数据建模/管理数据集/创建数据集.md#)。

## LBS热力地图概述 {#section_mcg_3qs_xgb .section}

与[色彩地图](cn.zh-CN/用户指南/仪表板制作/仪表板图表制作/色彩地图.md#)类似，LBS热力地图用热力的深浅来展示数据的大小和分布范围。

LBS热力地图是由地理区域和LBS热力深度构成的。地理区域由数据的维度或者经纬度决定，如省份；LBS热力深度由数据的度量决定，如订单金额，利润金额等。

**说明：** 

-   LBS热力地图的地理区域只能取1个维度，并且维度类型必须为地理信息；LBS热力深度最少取1个，最多取5个度量。
-   有关各地区详细信息对照表请参见：[国家省市区的标准名](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/128200/cn_zh/1564644494031/%E5%9B%BD%E5%AE%B6%E7%9C%81%E5%B8%82%E5%8C%BA%E7%9A%84%E6%A0%87%E5%87%86%E5%90%8D.xlsx)。

## LBS热力地图应用示例 {#section_eyh_4qs_xgb .section}

以下场景均以company\_sales\_record数据集和常规仪表板为例。

1.  单击**数据集**，进入数据集管理页面。
2.  选择company\_sales\_record数据集，单击数据集所在行的![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1068751/156820711259213_zh-CN.png)图标。

    **说明：** 如果您使用的是**专业版**，需要您手动选择进入**常规模式**或者**全屏模式**。以下示例以**常规模式**为例。

3.  单击![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/156820711260077_zh-CN.png)图标，LBS热力地图的图例会自动显示在仪表板展示区。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/156820711260078_zh-CN.png)

4.  在数据标签页，选择需要的维度字段和度量字段。

    在维度列表中，找到省份，并将其添加到地理区域中；在度量列表中，找到订单数量和运输成本，并将它们依次添加到LBS热力深度区域中。

    **说明：** 请确保省份字段的维度类型已经从字符串切换为了地理信息，如需了解如何切换维度字段类型，请参见[字段类型切换](cn.zh-CN/用户指南/数据建模/管理数据集/字段类型切换.md#)。

5.  单击**更新**，系统自动更新图表。
6.  在样式标签页可更改图表的标题，布局和某一个字段的显示格式，如下图所示：

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/15682071121866_zh-CN.png)

7.  单击**保存**图标，保存该仪表板。

## 配置样式 {#section_c5d_rrs_xgb .section}

-   在基础信息中，可设置主标题、备注、展示跳转链接和背景设置。

    **说明：** 

    -   本示例中选用深色系。
    -   通过展示跳转链接功能用户可以在图表界面中直接跳转至需要的报表和外部链接，实现方式简单，只需在基本信息中添加相关的显示文案和链接即可。
-   在布局中，可设置显示图例、地图底图、地图缩放和地图中心。
-   在系列设置中，可设置度量的别名和样式。

更新后如下图所示：

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9144/156820711239682_zh-CN.png)

## 删除图表 {#section_0qt_fxz_48m .section}

如果您想删除当前图表：

1.  单击图表右上方![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1068751/156820711358783_zh-CN.png)图标。
2.  选择**删除**，当前图表即可被删除。

