<h2>Description</h2> 

This project entails the comprehensive setup of an Active Directory environment and network infrastructure. Beginning with the installation of VirtualBox and Windows 10 on a virtual machine, it proceeds to configure the VM, set up network settings, and optimize performance. The Active Directory setup involves installing Domain Services, post-deployment configurations, and creating a dedicated domain admin account. Organizing Active Directory involves structuring organizational units, creating user accounts, and granting domain admin privileges. The network configuration section covers routing, NAT setup, DHCP server installation, lease duration, DHCP options, and specifying the router's IP address. The project also delves into automation with PowerShell scripts for user-related tasks and management via the Active Directory Users and Computers console, providing a comprehensive guide for establishing and managing an Active Directory environment.

<h2>Section 1: Setup Virtual Environment</h2> 

Download VirtualBox:

- Go to the VirtualBox website (https://www.virtualbox.org/) and download the VirtualBox software for your operating system.
  - Install VirtualBox on your host machine.
- Download Windows 10:
  - Obtain a legal copy of the Windows 10 ISO file from the official Microsoft website.

<h2>Section 2: Create and Configure Virtual Machine</h2> 

- Create Virtual Machine:
  - Open VirtualBox and create a new virtual machine (VM).
  - Configure the VM with appropriate settings, including allocating CPU, RAM, and storage.

- Insert Guest Add CD Image:
  - Once Windows 10 is installed on the VM, insert the VirtualBox Guest Additions CD image to enhance VM performance and features.

- Set IP Address:
  - Configure the network settings of your VM, including setting a static or dynamic IP address.

- Rename PC:
  - Change the computer name of the Windows 10 VM as needed.

<h2>Section 3: Active Directory Setup</h2> 

- Install Active Directory Domain Services:
  - Install the Active Directory Domain Services role on the Windows 10 VM.

- Post Deployment Configuration:
  - Complete the necessary post-installation configuration for Active Directory.

- Create Own Dedicated Domain Admin Account:
  - Create a domain admin account for managing Active Directory.

<h2>Section 4: Organize Active Directory</h2> 

- Create an Organizational Unit (OU):
  - Organize your Active Directory structure by creating an OU.

- Create a New User:
  - Create a new user account within the OU.

- Make a Domain Admin:
  - Assign appropriate permissions to the user to make them a domain admin.


<h2>Section 5: Network Configuration</h2> 

- Routing and Remote Access:
  - Configure Routing and Remote Access as needed for remote connections.

- Install NAT (Network Address Translation):
  - Set up NAT for routing internal network traffic.

- Setup a DHCP Server on Domain:
  - Install and configure the DHCP server role on the domain controller.

- DHCP Lease Duration:
  - Configure DHCP lease duration settings.

- Configure DHCP Options:
  - Define DHCP options such as DNS servers, gateway, etc.

- Add an IP Address for Router:
  - Specify the IP address of your router as a DHCP option.

<h2>Section 6: Automation and Management</h2> 

- Source Code for User PowerShell Script:
  - If you need to automate user-related tasks, you can create PowerShell scripts to perform these actions (Code is listed on this repository). 

- Active Directory Users and Computers:
  - Use the Active Directory Users and Computers console to manage user accounts and other AD objects.

<h2>Conclusion</h2> 

Engaging in this project significantly enhances my capabilities as a security analyst. It provides hands-on experience in setting up and configuring critical security components, fostering a keen sense of network security, and honing scripting and automation abilities. Moreover, the project's holistic approach combines technical skills with an understanding of access control and user management, transforming me into a more capable and confident security analyst, ready to protect against emerging threats in today's digital landscape.


