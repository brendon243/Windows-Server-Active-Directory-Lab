# Windows Server Active Directory Lab

## About The Project

This project demonstrates the deployment and configuration of a Windows Server Active Directory environment. The lab focuses on setting up a domain controller, configuring DNS, managing domain users, groups, and organizational units (OUs), and joining Windows client machines to the domain. The purpose of this project is to simulate common enterprise IT administration and help desk tasks in a controlled environment.


## Built With

- Windows Server  
- Active Directory Domain Services (AD DS)  
- DNS  
- Active Directory Users and Computers  
- Virtualization platform (Azure, VirtualBox, VMware, or Hyper-V)  
- Windows client operating system  


## Project Overview

The following tasks were completed as part of this project:

1. Deployed a Windows Server virtual machine.
2. Installed and configured Active Directory Domain Services.
3. Promoted the server to a domain controller.
4. Configured DNS to support Active Directory domain services.
5. Created and managed domain users, security groups, and organizational units.
6. Joined Windows client machines to the domain.
7. Verified domain authentication using domain user credentials.
8. Performed common administrative tasks such as password resets and account management.


## Screenshots
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/be0bc534-04f4-4c13-86bb-959126042053" />
<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/54f8d7cd-1c6a-4a56-a06b-10689d40d8ee" />

Screenshots documenting the lab setup and configuration can be added here.

Examples:
- Active Directory Users and Computers showing users, groups, and OUs
- Server Manager with AD DS installed
- Windows client successfully joined to the domain


## Lessons Learned

- How Active Directory relies on DNS for authentication and directory services
- Differences between local user accounts and domain accounts
- Best practices for organizing users and resources using OUs and groups
- Troubleshooting domain join and authentication issues


## Skills Demonstrated

- Windows Server administration  
- Active Directory Domain Services  
- DNS configuration  
- User and group management  
- Domain-joined workstation setup  
- Basic network and authentication troubleshooting  


## How To Recreate This Lab

1. Create a Windows Server virtual machine.
2. Install the Active Directory Domain Services role.
3. Promote the server to a domain controller and configure DNS.
4. Create users, groups, and organizational units in Active Directory.
5. Configure a Windows client to use the domain controller as its DNS server.
6. Join the client machine to the domain and test authentication.



