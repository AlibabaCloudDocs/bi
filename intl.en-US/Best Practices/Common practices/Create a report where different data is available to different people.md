# Create a report where different data is available to different people {#concept_h4r_z1g_vdb .concept}

For example, if a sales team serves customers across the country, they must be able to track sales data for more than 30 provinces and their cities and county regions for any time period. As the business continuously grows and scales, the team views an ever-increasing amount of sales data. With such a large amount of data, it will greatly improve efficiency and avoid data leaks if only the sales data of a region that a person is responsible for is available to them.

Row-level permissions of Quick BI make different data of a report be available to different people. This section describes the feature by taking the company\_sales\_record dataset as an example. For more information about how to create a dataset, see [Create a dataset](../../../../intl.en-US/User Guide/Data modeling/Dataset management/Create a dataset.md#).

**Note:** Currently, row-level permissions are only available in Quick BI Pro and Quick BI Professional. If you want to activate Quick BI Pro or Quick BI Professional, see [Quick BI purchase, upgrade, and renew](../../../../intl.en-US/Pricing/Purchase, upgrade, and renew Quick BI services.md#).

## Configure row-level permissions {#section_kjm_2bg_vdb .section}

You can configure the row-level permissions of a dataset in the workspace.

You must configure the row-level permissions of a dataset when it is used to create a dashboard. If the dataset does not exist in a workspace, you must add this dataset to the workspace.

1.  Log on to the Quick BI console.
2.  Click the **Workspace** tab, and select a workspace.
3.  Click **Dataset** to enter the dataset management page of this workspace.
4.  Select the required dataset. Click the ellipsis icon or right-click this dataset, and select **Row-Level Permissions** as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9191/15450326271956_en-US.png)

5.  Select the **Enable Row-Level Access Control** check box, and select **User / User Group Authorization**.
6.  Click the drop-down arrow and select a field such as area, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9191/15450326271958_en-US.png)

7.  Select a member in the list.

    After you select a member, the field automatically appears in the **Permissions** area as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9191/15450326271961_en-US.png)

8.  Click **area** to expand all information contained in the field.
9.  Select an area such as the selected region, and then click **Add**.

    After you add a member, this member can only view the sales data of Northeast China.

    **Note:** When you configure row-level permissions for a field of a dataset, you must configure the permissions for each member to access the dataset field. If you do not configure permissions for a member to view the data, all requests to access the configured data by the member will return no data.

10. Click **Close** to complete the configuration.

## Verify row-level permissions {#section_d3r_3cg_vdb .section}

1.  Click **Personal workspace**.
2.  Click **Dashboard** to enter the dashboard management page.
3.  Locate a dashboard, click the **Share** icon next to this dashboard.
4.  Enter the account name of the person with whom you want to share the dashboard, and select an expiration date.

    **Note:** Row-level permissions must be granted to the account of the person with whom you want to share the dashboard. Otherwise, you cannot check whether the permissions for the account work on the dashboard.

5.  Click **Save** to share the report.

If row-level permissions are granted to the person with whom you want to share the dashboard, the person will be able to view the data they are authorized for, and only the data they are authorized for.

