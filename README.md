# Domain-Controller-Integration-with-Azure-AD

Set up a local domain controller under example.com and integrated it with Azure AD using Microsoft Entra Connect. Created OUs, configured selective sync, resolved TLS and Conditional Access issues, and validated hybrid identity setup with successful user and group sync.
  <br/>
<h2> Initial Setup of Domain Controller</h2>
You started by configuring the domain controller under example.com. This serves as the foundational environment for managing on-premises Active Directory services and testing hybrid identity configurations.
<img width="853" alt="Image" src="https://github.com/user-attachments/assets/6b696a1a-a6f8-45a9-a6f7-3855956da7a7" />
<br/>
<h2>Creating Organizational Units (OUs)</h2>
To organize directory objects efficiently, you created a main OU named Cloudapplication, then structured it further by adding three sub-OUs:

Users

Workstations

Groups

Active Directory Users and Computers (ADUC) view displaying the OU structure: Cloudapplication > Users, Workstations, Groups.
<img width="850" alt="Image" src="https://github.com/user-attachments/assets/db4c2bea-2444-4099-9894-02e94d842f1d" />
