**WINDOWS SERVER ADMINISTRATION LAB**

A hands-on Windows Server administration project built in VirtualBox to simulate a small business IT environment.

**PROJECT OVERVIEW**
This lab involved deploying and administering a Windows Server environment with a Windows 10 Pro domain-joined workstation.

The project focused on practical administration tasks including Active Directory, Group Policy, DNS, DHCP, SMB file sharing, NTFS permissions, and user account management.

**LAB ENVIROMENT**

**Component        Details**
Server             Windows Server
Server Name        Server1
Client             Windows 10 Pro
Client Name        CLL01
Virtualization     Oracle VirtualBox
Domain              company.local


**KEY TASKS COMPLETED**
* Configured a Windows Server domain environment.
* Created and organized Active Directory OUs.
* Created and managed domain users and security groups.
* Joined a Windows 10 Pro workstation to the domain.
* Created and applied Group Policy.
* Configured and verified DNS resolution.
* Configured DHCP for automatic IP address assignment.
* Created and secured an SMB file share.
* Configured Share and NTFS permissions.
* Implemented role-based access for IT, Operations, HR, and Finance.
* Tested departmental access to shared resources.
* Performed basic Active Directory user account administration.
* Used PowerShell to configure and verify Windows infrastructure.

**ACCESS CONTROL**
The CompanyData file share was configured using role-based permissions.

**Security Group    Share Access**
IT-Admins             Full
Operations-Users      Change
HR-Users              Read
Finance-Users         Read
Access was tested using domain accounts to verify that users could perform only the actions permitted by their assigned roles.

**TESTING & VERIFICATION**

The environment was tested to verify:
* Domain connectivity
* Domain authentication
* DNS resolution
* DHCP address assignment
* Group Policy application
* SMB share accessibility
* Department-based file permissions
* Active Directory account administration

All major tests produced the expected results.

**SKILLS DEMONSTRATED**
* Windows Server Administration
* Active Directory Administration
* User and Group Management
* Group Policy Management
* DNS & DHCP Administration
* File Server Administration
* NTFS & Share Permissions
* Role-Based Access Control
* PowerShell
* Network Troubleshooting
* Access Control Testing

**DOCUMENTATION**
Detailed project documentation, including configuration steps and screenshots, is available in the project PDF.

Documentation: documentation/Windows-Server-Administration-Lab.pdf
