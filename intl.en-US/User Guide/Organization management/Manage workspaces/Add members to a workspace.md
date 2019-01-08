# Add members to a workspace {#concept_zpv_yhd_5db .concept}

You need to assign a role to the member after you add it to a workspace. Roles have different permissions. Each member can be assigned a maximum of one role.

Roles include Space Manager, Developer, Analyst, and Viewer.

## Mappings for roles and permissions {#section_glv_c3d_5db .section}

Mappings for roles and permissions are fixed and not modifiable. To grant permission to the member of a workspace, you only need to specify the role for the member.

**Note:** The classic workbook feature is in beta and will not be supported in future versions. A classic workbook does not support custom grouping fields, data type conversions, dataset joins based on snowflake schemas, and joins for databases from different data sources.

|Permission|Developer|Analyst|Viewer|
|:---------|:--------|:------|:-----|
|Datasets/Data sources|Supported|Not supported|Supported|
|Classic Workbooks/Workbooks|Supported|Supported|Supported|
|Dashboards|Supported|Supported|Supported|
|Portals|Supported|Supported|Supported|

|Permission|Developer|Analyst|Viewer|
|:---------|:--------|:------|:-----|
|Create Data Sources|Supported|Not supported|Not supported|
|Modify data sources|Only modifying own data sources is supported|Not supported|Not supported|
|Delete data sources|Only deleting own data sources is supported|Not supported|Not supported|
|Use data sources|Supported|Not supported|Not supported|
|Create datasets|Supported|Not supported|Not supported|
|Modify datasets|Only modifying own datasets is supported|Not supported|Not supported|
|Delete datasets|Only deleting own datasets is supported|Not supported|Not supported|
|Use datasets|Supported|Supported|Not supported|

|Permission|Developer|Analyst|Viewer|
|:---------|:--------|:------|:-----|
|Create classic workbooks|Supported|Supported|Not supported|
|Modify classic workbooks|Only modifying own classic workbooks is supported|Only modifying own classic workbooks is supported|Not supported|
|Delete classic workbooks|Only deleting own classic workbooks is supported|Only deleting own classic workbooks is supported|Not supported|
|View classic workbooks|Supported|Supported|Supported|
|Share classic workbooks|Only sharing own classic workbooks is supported|Only sharing own classic workbooks is supported|Not supported|
|Reference classic workbooks|Supported|Supported|Not supported|

|Permission|Developer|Analyst|Viewer|
|:---------|:--------|:------|:-----|
|Create workbooks|Supported|Supported|Not supported|
|Modify workbooks|Only modifying own workbooks is supported|Only modifying own workbooks is supported|Not supported|
|Delete workbooks|Only deleting own workbooks is supported|Only deleting own workbooks is supported|Not supported|
|View workbooks|Supported|Supported|Supported|
|Share workbooks|Only sharing own workbooks is supported|Only sharing own workbooks is supported|Not supported|
|Reference workbooks|Supported|Supported|Not supported|

|Permission|Developers|Analysts|Viewer|
|:---------|:---------|:-------|:-----|
|Create dashboards|Supported|Supported|Not supported|
|Modify dashboards|Only modifying own dashboards is supported|Only modifying own dashboards is supported|Not supported|
|Delete dashboards|Only deleting own dashboards is supported|Only deleting own dashboards is supported|Not supported|
|View dashboards|Supported|Supported|Supported|
|Share dashboards|Only sharing own dashboards is supported|Only sharing own dashboards is supported|Not supported|
|Reference dashboards|Supported|Supported|Not supported|
|Publish dashboards|Only publishing own dashboards is supported|Only publishing own dashboards is supported|Not supported|

|Permission|Developer|Analyst|Viewer|
|:---------|:--------|:------|:-----|
|Create portals|Supported|Supported|Not supported|
|Modify portals|Only modifying own portals is supported|Only modifying own portals is supported|Not supported|
|Delete portals|Only deleting own portals is supported|Only deleting own portals is supported|Not supported|
|View portals|Supported|Supported|Supported|
|Share portals|Only sharing own portals is supported|Only sharing own portals is supported|Not supported|

## Add members to a workspace {#section_pg2_44d_5db .section}

1.  Log on to the Quick BI console.
2.  Choose**Settings** \> **Workspaces**.
3.  Click the **Members** tab to jump to the Members tab page.
4.  Click **Member Added to Workspace** as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9164/15469415441174_en-US.png)

5.  Search for the member that you want to add by the nickname and assign a role to it as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9164/15469415441175_en-US.png)

6.  Click **OK** to complete adding the member.

