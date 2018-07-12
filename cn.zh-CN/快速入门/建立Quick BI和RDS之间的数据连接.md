# 建立Quick BI和RDS之间的数据连接 {#concept_q2b_y2d_5db .concept}

本章节将以MySQL数据库作为示例，为您描述如何建立Quick BI和RDS之间的数据连接。

在建立连接之前，我们假设您已经有了一个真实的MySQL数据库，而且数据库中数据可以被使用。

建立数据连接包含以下三个部分。

-   配置Quick BI
-   新建仪表板
-   发布仪表板

## 前提条件 { .section}

-   获取MySQL使用权限。

    更多信息，请参阅 [MySQL 5.7高可用版/5.5/5.6创建数据库和账号](https://help.aliyun.com/document_detail/26129.html?spm=a2c4g.11186623.2.4.xYWI1p)， [MySQL 5.7基础版创建数据库和账号](https://help.aliyun.com/document_detail/49015.html?spm=a2c4g.11186623.2.5.xYWI1p)和[创建高权限账号](https://help.aliyun.com/document_detail/26130.html?spm=a2c4g.11186623.2.6.xYWI1p)。

-   获取Quick BI免费试用版或者其它可购买的版本。

    更多信息，请参阅[Quick BI购买、升级与续费](../../../../cn.zh-CN/产品定价/Quick BI购买、升级与续费.md#)。


## 配置Quick BI {#section_gd5_ffd_5db .section}

**从Quick BI复制IP地址**

1.  登录Quick BI控制台。
2.  单击**工作空间** \> **数据源**，进入数据源管理页面。
3.  单击**新建数据源** \> **云数据库** \> **MySQL**， 从云数据库创建一个新的MySQL数据源。
4.  复制蓝色区域中给出的IP地址，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1134_zh-CN.png)


**从RDS获取数据库端点地址**

1.  登录RDS控制台。
2.  选择一个目标实例所在的区域。
3.  单击实例名称，进入基本信息页面。

    网络地址就是数据库端点地址。


**在RDS上设置IP地址白名单**

1.  在左边导航栏中单击**数据安全性**，进入数据安全性管理页面。
2.  在白名单设置标签页，单击**修改**，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1137_zh-CN.png)

3.  单击**清空**，清除现有的127.0.0.1IP地址。
4.  单击**添加白名单分组**，添加一个新的白名单组。
5.  输入一个新的分组名称，并且将复制好的IP地址粘贴到白名单区域。
6.  单击**确定**完成白名单分组设置。

    更多信息，请参阅[设置白名单](https://help.aliyun.com/document_detail/26198.html?spm=a2c4g.11186623.2.8.xYWI1p)。


**验证数据源连接**

1.  回到Quick BI数据源管理页面。
2.  单击**新建数据源** \> **云数据库** \> **MySQL**。
3.  输入数据源连接信息，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1140_zh-CN.png)

    -   显示名称：数据源的显示名称。
    -   数据库地址：数据库的网络地址。
    -   端口：输入正确的数据库端口地址。
    -   数据库：数据库名称。
    -   用户名：数据库的用户名。
    -   密码：数据库的密码。
4.  单击**连接测试**验证数据源是否能够正常连通。

    如果数据源可以正常连通，系统会给出连通成功提示。

5.  单击**添加**。数据源被成功添加。

    更多信息，请参阅[新建云数据源](cn.zh-CN/快速入门/数据建模/管理数据源/新建云数据源.md#)、[新建自建数据库下的数据源](cn.zh-CN/快速入门/数据建模/管理数据源/新建自建数据库下的数据源.md#)和[上传本地文件](cn.zh-CN/快速入门/数据建模/管理数据源/上传本地文件.md#)。


## 创建仪表板 {#section_w2n_phd_5db .section}

1.  在数据源管理页面，选择一张数据表。
2.  单击**创建数据集**，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1149_zh-CN.png)

3.  单击**仪表板**，进入仪表板管理页面。
4.  单击**新建仪表板**，进入仪表板编辑页面。
5.  从下拉菜单中选择一个需要分析的数据集，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1150_zh-CN.png)

    更多信息，请参阅[仪表板基本操作](cn.zh-CN/快速入门/报表制作/仪表板基本操作/仪表板基本操作.md#)。

6.  双击一个图表图标，例如**线图**。线图的示例会自动展示到页面上。
7.  选择需要的维度字段和度量字段，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1152_zh-CN.png)

8.  单击**更新**完成线图创建。
9.  单击**保存**，保存该仪表板。

## 公开仪表板 {#section_ns4_g3d_5db .section}

1.  在仪表板管理页面，选择一个仪表板。
2.  单击**公开**，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1158_zh-CN.png)

3.  选择一个发布结束时间，并且允许生成新链接，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9076/1162_zh-CN.png)

4.  复制URL地址到您的浏览器，就可以阅读报表内容了。

## 更多参考 {#section_ug2_43d_5db .section}

您可以通过以下链接了解更多关于Quick BI和RDS的信息。

-   [ApsaraDB for RDS](https://www.alibabacloud.com/zh/product/apsaradb-for-rds?spm=a2c4g.11186623.2.13.xYWI1p)
-   [Quick BI](https://data.aliyun.com/product/bi?spm=5176.8142029.388261.372.49766d3edpNZ1V)

