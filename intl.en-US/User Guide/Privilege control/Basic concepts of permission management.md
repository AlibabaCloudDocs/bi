# Basic concepts of permission management {#concept_kg4_ttw_5db .concept}

Permission management include data object management and row-level permission management.

Data objects include data sources, datasets, workbooks, dashboards, and portals. Data object management is classified based on the workspace types, which include the personal workspace and the workspace.

## Row-level permission {#section_bvc_www_5db .section}

You do not need to configure row-level permission for all fields in a dataset. Configure row-level permission for certain fields as needed.

Currently, for a single field, the maximum number of values that can be shown on the list is 500. If the number of values exceeds 500, you can add the excess values to the list manually.

You can find the **All** check box on the list. If you select the All check box \(equivalent to selecting all values of a field\) for a member of the organization, then the member can access the dataset without restriction from this field. You do not need to reselect the All check box after adding or deleting values for this field.

Significant time for configuring permissions is saved for administrators through selecting the All check box.

## Manage data objects in a workspace {#section_pyd_dzx_5db .section}

Quick BI supports sharing and publishing data objects in a workspace.

**Share data objects in a workspace**

Quick BI supports sharing workbooks, dashboards, and portals . Shared data objects are read-only for other Alibaba Cloud accounts and RAM users. Other Alibaba Cloud accounts and RAM users do not have permission to modify, delete or save the data objects.

-   Only the owner of the data object and the administrators of the workspaces have permissions to share the data object.
-   If you clear the Works can be authorized checkbox for a workspace, then the data objects in this workspace cannot be shared.
-   Currently, data objects can only be shared with Alibaba Cloud accounts and RAM users of the same organization.

Members can access the data objects in the workspace that they belong to.

Data objects can be shared with members of the same organization. Authorized users can view the shared data objects in their own **personal workspaces**.

**Publish data objects in a workspace**

Data objects that have been published can be accessed by everyone using the URLs. We recommend that you do not publish data objects that involve private business data.

## Manage data objects in the personal workspace {#section_v5w_tzx_5db .section}

Only the owner of a personal workspace has permission to perform operations on the data objects.

**Share data objects in the personal workspace**

Quick BI supports sharing workbooks, dashboards, and portals . Shared data objects are read-only for other Alibaba Cloud accounts and RAM users. Other Alibaba Cloud accounts and RAM users do not have permissions to modify, delete or save the data objects.

-   Only the owner of the data objects has permission to share them.
-   Data objects can only be shared with users of Alibaba Cloud Quick BI.

Authorized users can view the shared data objects in their own personal workspaces.

**Publish data objects in the personal workspace**

Data objects that have been published can be accessed by everyone using the URLs. We recommend that you do not publish data objects that involve private business data.

