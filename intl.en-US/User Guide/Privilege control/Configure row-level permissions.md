# Configure row-level permissions {#concept_evp_hjl_bfb .concept}

Row-level permissions are performed based on datasets. Quick BI supports the following authorization modes: **User/User Group Authorization** and **Tag Authentication**. Currently, only Quick BI Pro and Quick BI Professional Edition support performing row-level permissions based on datasets.

The User/User Group Authorization mode applies to scenarios that involve a small number of members. The Tag Authentication mode applies to scenarios that involve a large number of members. Tag Authentication authorizes all users at once instead of implementing authorization for users/user groups separately. In scenarios that involve a large number of members, using Tag Authentication reduces costs and complexity for configuring row-level permissions and makes it easier for management.

## User/User Group Authorization {#section_plk_rk5_1fb .section}

1.  Log on to the Quick BI console.
2.  Select a workspace. If you need to create a workspace, see [Create a workspace](reseller.en-US/User Guide/Organization management/Manage workspaces/Create a workspace.md#).
3.  Click the **Datasets** icon to jump to the Datasets page.
4.  Select a dataset. Click the **More** icon in the Actions column or right click the dataset.
5.  Select **Row-Level Permissions**.
6.  Select the**Enable Row-Level Access Control** \> **User/User Group Authorization**check box to enable row-level permissions.
7.  Click the drop-down arrow. Select the fields to perform row-level permissions, such as province and metrics, as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21112/155834642112613_en-US.png)

    The values of the **metrics** field are the metrics in the dataset. By performing row-level access permissions on the metrics field, users have access to different data rows that are corresponding to the values of the metrics field.

8.  Click the **province** field in the **Permissions** list. Then all values of the province field are listed as shown in the following figure.
9.  Select a member. Then select the values of the **province** field to grant row-level permission to the user as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21112/155834642112913_en-US.png)

    The member can only view the data rows where the value of the province field is Shanghai or Yunnan.

    **Note:** Specify for all members of the workspace whether they have permissions to access the data rows that are corresponding to the values of the field, on which row-level permissions have been performed. Members, who haven't been specified the permission for, do not have permissions to access any data reports generated from the dataset by default.

10. Click **Add** to complete the configuration of row-level permissions.

## Tag Authentication {#section_qzd_nz5_1fb .section}

Scenario: Users can only access the data rows in the company\_sales\_record dataset where the value of the **shipping\_type** is **truck** or **air**.

**Set member tags**

1.  On the **Settings** page, select **Edit Member Tags** in the Actions column for the member to authorize as shown in the following figure.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21112/155834642112932_en-US.png)

2.  In the **Edit Member Tags** dialog box, set the value of the **area** tag to **air, truck** and click**OK**.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21112/155834642112933_en-US.png)


After setting the member tags, set tag authentication in the Row-Level Access dialog box for the dataset.

**Set tag authentication**

1.  Select the company\_sales\_record dataset. Click the **More**icon in the Actions column or right click the dataset.
2.  Select **Row-Level Permissions**.
3.  Select the **Enable Row-Level Access Control** \> **Tag Authentication** check box to enable row-level permissions.
4.  From the **Field** drop-down list, select **shipping\_type**. Select **area** as **Tag Parameter**. Click **OK** to complete the settings.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21112/155834642112940_en-US.png)


After tag authentication is complete, the user can only access data rows where the **shipping\_type** is **air** or **truck**.

