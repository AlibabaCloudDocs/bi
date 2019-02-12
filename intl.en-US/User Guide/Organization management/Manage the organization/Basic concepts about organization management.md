# Basic concepts about organization management {#concept_bmn_mqv_tdb .concept}

Organization management is a feature provided by Quick BI Pro that allows you to develop data collaboratively with other members in the organization. Quick BI Pro is officially released. Users of Quick BI Basic can upgrade to Quick BI Pro in the Quick BI console .

## What is an organization {#section_pgz_xrv_tdb .section}

Generally, organizations refer to small and medium-sized enterprises \(SMEs\), public institutions, schools, or departments of large companies.

If your organization values data security highly and data analysis needs to be performed collaboratively by more than 10 members, we recommend that you purchase Quick BI Pro. Quick BI Pro brings the following benefits:

-   Members have different access permissions to reports based on the departments that they belong to.
-   Members have different access permissions to a report based on their roles.

We recommend that you use Quick BI Basic if the number of users is fewer than 10.

Organization member management refers to adding Alibaba Cloud users that need to work collaboratively into the same organization.

Organization management includes:

-   Managing organizational information
-   Managing member information
-   Managing workspaces

Only administrators of an organization have permissions to manage the members of the organization. The creator of an organization is set as an administrator by default.

The roles of members in an organization include administrator and user.

## What is a workspace {#section_bk4_fvv_tdb .section}

Workspaces group the members that are in an organization based on the data objects to develop collaboratively. In a workspace, the members in different roles cooperatively create and modify data sources, datasets, workbooks, dashboards, and portals. Data objects \(data sources, datasets, workbooks, dashboards, and portals\) are based on workspaces. A data object is unique to the workspace that it is based on.

Workspace management refers to adding members of an organization to workspaces based on the scope of the work and job responsibilities of the members.

You can create workspaces corresponding to the departments of the organization. For example, administrators can create workspaces for the sales department and the HR department of the organization and then add the employees as members to the corresponding workspaces.

Workspaces are similar to DingTalk groups. For example, employees can share information and communicate with each other through the DingTalk group that is corresponding to the department that they belong to.

## Manage workspaces {#section_xk4_hvv_tdb .section}

Administrators of a workspace are responsible for workspace management. Members of a workspace are appointed to be administrators by the administrator of the organization that creates the workspace. Administrators of a workspace have permission to set other members in the workspace to be administrators.

Workspace management includes:

-   Creating a workspace
-   Modifying a workspace
-   Setting a default workspace

## The differences between a personal workspace and a workspace {#section_zxf_lvv_tdb .section}

In Quick BI Basic, the working space of a user is called a personal workspace.

The main differences between a personal workspace and a workspace are as follows:

-   A personal workspace is created automatically after the first logon. A workspace is created manually by an administrator of the organization.
-   A personal workspace is unique to each Alibaba Cloud account or RAM user. It cannot be deleted.
-   You are not allowed to add other members to a personal workspace. Therefore, a personal workspace does not support collaboration or sharing.
-   For a personal workspace, data objects can be transferred to or shared with any Alibaba Cloud accounts. For a workspace, data objects can only be transferred to or shared with the members of the workspace.

