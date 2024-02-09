
# Comprehensive Management of Identity and Access with Microsoft Entra ID

## Objective
The objective of this project is to equip participants with the practical skills and knowledge required to manage identities, authenticate, authorize, and control application access effectively using Microsoft Entra ID.


## Overview 

This project is structured into four main components, focusing on the essential aspects of identity and access management. It aims to demonstrate the application of theoretical concepts through practical implementation, enhancing organizational security and efficiency.


### 1. Manage Identities in Microsoft Entra ID

#### Created User Identities
- Individual User Creation: A user named Emily Clark was created with the role of Project Manager.
  ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/1.%20Creating%20User.png)
- Bulk User Creation: Utilized a CSV file for the addition of John Doe and Jane Doe as users.
  ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/2.%20Created%20CSV%20File.png)
  ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/3.%20Bulk%20Users%20created%20successfully.png)
  ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/4.%20Users%20added.png)

#### Configured and Managed Groups
- Assigned Group: Formed the 'Engineering Team' group, adding John and Jane manually.
- Dynamic Group: Established the "Project Managers" dynamic group with a rule to automatically include users with the "Project Manager" job title, adding Emily Clark to the group.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/5%2C%20Create%20Assigned%20group%20and%20Dynamic%20Group.png)
#### Managed External Identities
- Facilitated external collaboration by inviting Alex Taylor via email, integrating external users into internal projects.
-   ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/6.%20Inviting%20external%20User.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/7.%20Updated%20list%20of%20Users.png)

### 2. Manage Authentication Using Microsoft Entra ID
#### Configured MFA
- Enabled MFA for Jane and John, adopting a second verification layer through methods like text messages and app notifications.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/8.%20Enable%20MFA%20for%20Jane%20and%20John.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/8.1%20Configure%20MFA.png)
#### Implemented Conditional Access Policies
- Deployed a "Require MFA for Teams Access" policy, necessitating MFA upon Teams app sign-in. The Engineering Team was included for policy testing, verified through sign-in attempts and sign-in logs auditing.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/9.%20Created%20Conditional%20Access%20policy.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/10.%20Implemented%20Access%20policy%20successfully.png)
#### Configured SSPR
- Properties for SSPR were set for the Engineering Team, selecting diverse authentication methods. Registration prompts and reconfirmation requirements were established, alongside user and admin notifications for password resets. The SSPR process's effectiveness was confirmed through testing.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/11.%20Selected%20Group%20for%20SSPR.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/11.1%20Authentication%20Methods%20for%20SSPR.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/11.2.%20Registration%20for%20SSPR.png)
#### Analyzed Sign-in Logs
- Sign-in logs were filtered and analyzed to investigate failed attempts, enhancing security insights and threat detection.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/12.%20Analyzing%20SIgn%20in%20logs.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/12.1%20Analyzing%20sign%20in%20logs.png)
### 3. Manage Authorization Using Microsoft Entra ID
#### Created Custom Roles
- A 'Custom App Manager' role was crafted, providing specific app management permissions without full administrative access, and assigned to Jane Doe.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/1.%20Created%20Custome%20Role.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/2.1.png)
#### Implemented RBAC
- Emily Clark was assigned the User Administrator role for user management with limited administrative rights. The Engineering Team received the "Contributor" role for specified resource management.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/3.%20%20Assigning%20Roles%20to%20Users.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/4%20Using%20RBAC%20for%20Resource%20management.png)
#### Utilized Azure Policies
- Enforced secure transfers to storage accounts through policy creation, verifying compliance through testing and remediation actions based on Microsoft Defender recommendations.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/5.%20Created%20STorage%20Account%20to%20test%20policy.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/5.1%20Assign%20policy%20to%20enable%20transfer%20over%20HTTPS%20only.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/5.2%20Storage%20account%20is%20non-complaince.png)
### 4. Manage Application Access in Microsoft Entra ID
#### Registered and Configured Application
- The 'Project Management Tool' application was registered and configured for SSO, with permissions added for Microsoft Graph access and admin consent provided for organization-wide application.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/1.%20Created%20an%20app.png)
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/3.%20Manage%20API%20Permissions.png)
#### Implemented Application Access Controls
- Established the 'Project Management Tool Access Control' policy, requiring MFA for external application access, with the Engineering Team designated for policy testing.
- ![App Screenshot](https://github.com/SarthakRana007/Microsoft-Entra-ID-Management/blob/16593d58530124db40b73d5f402f1eab7b25d32e/Screenshots/4.%20Create%20Conditional%20Access%20policy.png)


## Key Highlights

- Practical Application: Hands-on experience with Microsoft Entra ID features, from user management to application access controls.
- Security Enhancement: Implementation of MFA, Conditional Access Policies, and Azure Policies to bolster organizational security.
- Efficiency and Compliance: Streamlined access management and compliance enforcement through RBAC and custom roles
## Conclusion

This project underscores the importance of comprehensive identity and access management within Microsoft Entra ID, offering a blend of security, efficiency, and compliance. Through detailed steps and practical scenarios, participants are better positioned to implement and manage sophisticated identity and access management solutions in their organizations.
