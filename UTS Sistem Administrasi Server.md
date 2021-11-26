# UTS Sistem Administrasi Server

Nama : Andreas Juand P

NIM    : 1202192047

Kelas  : IT 02 02

## Installation Windows Server 2022 using VirtualBox

- Download ISO Installer Windows Server 2022

  [Windows Server 2022]: https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022

- Steps To Install Windows Server 2022 using VirtualBox VM
  
  - Open VirtualBox and Create "New"
    ![](D:/Tugas/Sas/open.PNG)
  - Enter name 
    ![](D:/Tugas/Sas/name.PNG)
  - Create Memory Size
    ![](D:/Tugas/Sas/memory.PNG)
  - Select "Create a virtual hard disk now"
    ![](D:/Tugas/Sas/disk.PNG)
  - Select disk type "VDI"
    ![](D:/Tugas/Sas/disk type.PNG)
  - Select "Dynamically allocated"
    ![](D:/Tugas/Sas/dinamik.PNG)
  - Select the size of the virtual hard disk
    ![](D:/Tugas/Sas/size.PNG)
  - Go to the machine configuration and in the “Network” section set “Bridge adapter”
    ![](D:/Tugas/Sas/network.PNG)
  - Back to VM, Click "Start" then select the ISO Windows Server 2022
    ![](D:/Tugas/Sas/iso.PNG)
  - Enter yor language and then click "Next"
    ![](D:/Tugas/Sas/lang.PNG)
  - Click "Install now"
    ![](D:/Tugas/Sas/ins.PNG)
  - Select Windows Server 2022 edition (here I choose Datacenter Evaluation) with GUI (Desktop Experience) then install and click “Next”
    ![](D:/Tugas/Sas/datacenter.PNG)
  - Click "I accept the license terms" then click "Next"
    ![](D:/Tugas/Sas/lisense.PNG)
  - Select "Custom: Install Windows only (advanced)"
    ![](D:/Tugas/Sas/custom.PNG)
  - Select the partition to install Windows Server, Then click "Next"
    ![](D:/Tugas/Sas/parti.PNG)
  - Process installation, wait for it to finish after finish the system will reboot to complete the process
    ![](D:/Tugas/Sas/proses.PNG)
  - Configure the Administrator password and click "Finish"
    ![](D:/Tugas/Sas/admin.PNG)
  - To login as Administrator user, press the combination on the keyboard simultaneously **Ctrl + Alt + Del**
  - Enter Administrator Password and press "Enter"
    ![](D:/Tugas/Sas/lg.PNG)
  - Windows Server 2022 installation with GUI (Desktop Experience) is complete and can be used
    ![](D:/Tugas/Sas/finis.PNG)
  - 

## Installation Active Directory Domain Services

- Step-Step Installation
  - Rename Computer using PowerShell, Then type `rename-computer -Newname Server22`
    ![](D:/Tugas/Sas/rename.PNG)
  - Go to the "Server Manager" menu. Then select the “Manage” option then click “Add Roles and Features”. Then click “Next”
    ![](D:/Tugas/Sas/manage.PNG)
    ![](D:/Tugas/Sas/manage1.PNG)
  - Select “Role-based or feature-based installation”. Then “Next”
    ![](D:/Tugas/Sas/manage2.PNG)
  - Click “Select a server from the server pool” , Then "Next"
    ![](D:/Tugas/Sas/manage3.PNG)
  - Next, check the "Active Directory Domain Services" box. When you check the box, a short description of A.D.D.S appears and how it works. Then click "Add Feature", Then "Next"
    ![](D:/Tugas/Sas/manage4.PNG)
  - Like this, Click "Next"
    ![](D:/Tugas/Sas/manage5.PNG)
  - Click "Next"
    ![](D:/Tugas/Sas/manage6.PNG)
  - Then click "Install"
    ![](D:/Tugas/Sas/manage7.PNG)
  - Wait until the process is complete
    ![](D:/Tugas/Sas/manage8.PNG)
  - Installation complete 
    ![](D:/Tugas/Sas/manage9.PNG)