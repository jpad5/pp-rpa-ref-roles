
# Power Platform RPA Reference Roles

## RPA Reviewer Custom Security Role

In many organizations, it is typical for makers not to be granted access to production environments. However, to be able to view the workflow run history and other data relevant to daily operational activities, makers need access to this data.
By creating a custom security role called "RPA Reviewer," platform administrators can allow these makers read-only access to important automation information that resides within a production environment.

RPA Reviewer role can perform within the production environment.

  1. In Power Automate Portal
     1. View Desktop flows created by the user.
     2. View Desktop flow runs.
     3. View Desktop flow activity
  2. In Power Automate Desktop
     1. View-only Desktop flow in designer

To implement this custom role in an environment, download the solution and import the security role to support the needs around having a read-only role for production environments.

Solution with Custom Security Role - RPA Reviewer - [PADCustomRoleReviewer_1_0_0_1](https://github.com/jpad5/pp-rpa-ref-roles/blob/main/PADCustomRoleReviewer_1_0_0_1.zip)

## RPA Maker Custom Security Role

For creating automations using Power Automate, makers need access to create and manage cloud flows, desktop flows, connections and able to manage solutions as well. By creating a custom security role called "RPA Maker," platform administrators can allow these makers access to creating automations that reside within a development environment.

While establishing the minimum privileges, RPA Maker role can perform below actions within the development environment.

1. In Power Automate Portal
   1. View Desktop flows created by the user only
   2. View Desktop flow runs
   3. View Desktop flow activity
2. In Power Automate Desktop
   1. Create, read (Execute), edit Automation (create, edit, and delete Desktop flows in designer)
3. Share Desktop Automation
4. Create, Update, Delete Connection
5. Manage Machine Group
6. Import Solution
7. Export Solution
8. Update/Upgrade Solution

To implement this custom role in an environment, download the solution and import the security role to support the needs around having a maker role for developing automations within the development environments.

Solution with Custom Security Role - RPA Maker - [PADCustomRoleMaker_1_0_0_1](https://github.com/jpad5/pp-rpa-ref-roles/blob/main/PADCustomRoleMaker_1_0_0_1.zip)

