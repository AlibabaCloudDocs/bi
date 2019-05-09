# Add, search, edit, and remove members {#concept_l2w_rql_ngb .concept}

You can add a member to an organization by adding an Alibaba Cloud account or RAM user. You can use the import members function to add multiple members to an organization. You can also search for or remove members.

## Add a member {#section_uvm_grl_ngb .section}

**Add an Alibaba Cloud account** 

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members**.
3.  Click **Add Member** as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824745240_en-US.png)

4.  On the **Add Member** page, click the **Tenant Account** tab.

    **Note:** Make sure that you enter an account ID. An account ID is a numeric string.

5.  Enter the Alibaba Cloud account and an alias for the member. You can select **Set As Admin** to specify the member as an administrator, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824745241_en-US.png)

6.  Click **OK** to add the member.

**Add a RAM user** 

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members** \> **Add Member**.
3.  Click the **RAM User** tab.
4.  Enter the Alibaba Cloud account, the RAM user, and an alias. You can select **Set As Admin** to specify the member as an administrator, as shown in the following figure:

    **Note:** Make sure that you enter an account ID. An account ID is a numeric string. For RAM users, enter the RAM username in "RAM username@Default domain or enterprise alias.onaliyun.com". For example, if your RAM user account is zhangsan@.test.onaliyun.com, enter zhangsan.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824745242_en-US.png)

5.  Click **OK** to add the member.

**Import members** 

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members**.
3.  Click **Import Members**, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824745243_en-US.png)

4.  Click **Upload Excel** to upload a list of members from the local disk, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824745244_en-US.png)

5.  Click **OK** to import the members.

## Search members {#section_mbv_gqq_ngb .section}

You can search for members by alias or Alibaba Cloud account.

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members**.
3.  Enter an alias or Alibaba Cloud account into the search bar, as shown in the following figure:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824845245_en-US.png)

4.  Click the **Search** icon to search for the member.

## Edit a member {#section_bgs_wwq_pgb .section}

Administrators can edit the information of members.

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members**.
3.  Select a member, and click **Edit** in the Actions column.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824845246_en-US.png)

4.  You can edit the alias of the member, and choose whether to specify the member as an administrator by setting the **Set as Admin** option.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824845247_en-US.png)

5.  Click **OK** to submit the changes.

## Remove a member {#section_tyl_hqq_ngb .section}

Administrators can remove members. The remove operation is irreversible. Use with caution. To rejoin an organization, you must contact an administrator to add you to the organization as a member.

1.  Log on to the Quick BI console.
2.  Choose **Settings** \> **Organization** \> **Members**.
3.  Select a member, and click **Remove** in the Actions column.

    **Note:** If the member is in a workspace, the system prompts the following error message:

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/115408/155738824841187_en-US.png)

    You cannot remove a user who is a member of a group workspace. For more information about removing a member from a workspace, see [Delete a member](intl.en-US/User Guide/Organization management/Manage workspaces/Add, edit, search, and delete workspace members.md#section_qgp_tzq_pgb).

4.  Click **OK** to remove the member.

