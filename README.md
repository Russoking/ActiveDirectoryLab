# Active Directory Home Lab
# Description
Built a home lab to simulate an enterprise Active Directory environment using virtual machines. Deployed a Windows Server VM as a Domain Controller, installed and configured Active Directory Domain Services (AD DS), and used PowerShell to automate user account creation and management. This project strengthened my skills in identity and access management, automation, and Windows Server administration.
# Tools Used
✅ Oracle VirtualBox ✅ PowerShell ✅ VMware ✅ Windows Server & Windows 10

# Takeaways
This project gave me practical, hands-on experience with deploying and managing an Active Directory environment. I strengthened my skills in Windows Server setup, domain configuration, and scripting with PowerShell—foundational knowledge for enterprise IT administration and cybersecurity roles.
# Project walk-through:
Step 1 - Download and Install Oracle VirtualBox: I started by downloading and installing Oracle VirtualBox on my computer from the official website. Once installed, created a VM then chose "Windows Server" as the operating system and allocated appropriate resources (CPU, RAM, and disk space) for the server.
AD Steps
<img width="1594" height="848" alt="image" src="https://github.com/user-attachments/assets/5476ed37-dafb-454b-a260-6a839e0e2c77" />

Step 2 - Install Windows Server on the VM: Downloaded the Windows Server ISO file from the official Microsoft website. Next, started the VM and mounted the Windows Server ISO file. After installation, I configured the server settings which included setting a strong password for the admin account and adjusted network settings. I also added in guest additions.
Disk Sanitization Steps

Step 3 - Install and Configure Active Directory Domain Services (AD DS): On the VM, opened the Server Manager and added the Active Directory Domain Services role. Then, using the AD DS Configuration Wizard, promoted the server to domain controller. I specified a domain name and followed the prompts to complete the configuration. After the server rebooted, I verified that the domain controller was functioning correctly by checking the server roles.
Disk Sanitization Steps Disk Sanitization Steps
<img width="1910" height="1025" alt="image" src="https://github.com/user-attachments/assets/d8651713-cebb-4d80-9141-47e257a0b57b" />

Last Step: - Add Users to Active Directory with Powershell: Opened Powershell as an administrator on the domain controller. Then, created user accounts by executing Powershell scripts in Active Directory. The scripts included commands to define user properties.
Disk Sanitization Steps


# Results:
Successfully built a home lab running Active Directory on a Windows Server VM using Oracle VirtualBox. I installed and configured AD DS, promoted the server to a domain controller, and used PowerShell to automate user account creation and management.
