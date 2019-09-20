# Quick BI v3.4.3 版本说明 {#concept_1942317 .concept}

本次版本更新主要针对以下功能问题进行升级和修复：

## 发布日期 {#section_qah_hwz_8wg .section}

2019年09月19日

## 新增内容 {#section_uv4_zak_91q .section}

-   高级版新增支持以下功能：

    -   云数据源：Hive、OSS、DRDS。
    -   自建数据源：Hive、Vertica、SAP IQ（Sybase IQ）、SAP HANA、IBM DB2 LUW。
    -   支持钉钉微应用功能。
    -   支持数据填报。
-   仪表板编辑界面新增**公开**功能，在编辑页面可以快速设置公开链接。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659316_zh-CN.png)

-   翻牌器加载界面优化，**背景设置**新增颜色模板，提供6套背景模板可供选择。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659314_zh-CN.png)

-   专业版交叉表新增**创建取数**和**取数任务**功能。可不受预览行数限制，下载一百万行数据。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659319_zh-CN.png)

    **创建取数**可创建新的取数任务，**取数任务**可离线下载历史取数任务。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659318_zh-CN.png)

-   查询控件新增**锁定筛选条件**功能，勾选后，预览页面不支持切换筛选条件。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659511_zh-CN.png)


## 更新内容 {#section_zbo_ia1_r3g .section}

-   图表功能优化及问题修复：
    -   辅助线重叠体验优化，不遮挡纵坐标值展示。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659313_zh-CN.png)

    -   专业版类目管理增加报表来源路径。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659320_zh-CN.png)

    -   数据表关联支持模糊搜索。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659322_zh-CN.png)

    -   邮件收件人支持一次选择多个。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659323_zh-CN.png)

    -   级联筛选可支持四级级联。

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/1541048/156894343659512_zh-CN.png)

-   bug类修复
    -   修复查询控件，筛选字段默认值过长时，鼠标hover显示不全的问题。
    -   修复仪表板编辑态有emoji表情无法保存、查询项有emoji表情查询时报错的问题。
    -   修复饼图加载时会刷新两次的问题。
    -   修复组合图线图样式，设置标记点后，标记点显示undifined的问题。
    -   修复ADB2.0数据源自动发现响应速度慢的问题。

