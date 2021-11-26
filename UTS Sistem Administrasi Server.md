# UTS Sistem Administrasi Server

Nama : Andreas Juand P

NIM    : 1202192047

Kelas  : IT 02 02

## Installation Windows Server 2022 using VirtualBox

- Download ISO Installer Windows Server 2022
  [Windows Server 2022] : https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022

- Steps To Install Windows Server 2022 using VirtualBox VM
  
  - Open VirtualBox and Create "New"
    ![open](https://user-images.githubusercontent.com/49325037/143591562-ada4d108-ed09-4b21-9b1c-538c1b145cbd.PNG)
  - Enter name 
    ![name](https://user-images.githubusercontent.com/49325037/143591626-f826b8a2-697d-459b-9a23-c67ebc5f0aa4.PNG)
  - Create Memory Size
    ![memory](https://user-images.githubusercontent.com/49325037/143591772-00574fc8-85ed-45fa-94dd-e1ace8627398.PNG)
  - Select "Create a virtual hard disk now"
    ![disk](https://user-images.githubusercontent.com/49325037/143591916-14eeb976-8556-48c0-8d78-556e0a16fb30.PNG)
  - Select disk type "VDI"
    ![disk type](https://user-images.githubusercontent.com/49325037/143591949-e3c631e5-0d3f-4b41-bfe7-92e657cc41de.PNG)
  - Select "Dynamically allocated"
    ![dinamik](https://user-images.githubusercontent.com/49325037/143592003-a1eb670a-377d-456b-bb59-29a72ef5a1ef.PNG)
  - Select the size of the virtual hard disk
    ![size](https://user-images.githubusercontent.com/49325037/143592061-b342d448-9670-409c-9929-9c9db986d45d.PNG)
  - Go to the machine configuration and in the “Network” section set “Bridge adapter”
    ![network](https://user-images.githubusercontent.com/49325037/143592143-ee18b566-6ee3-49aa-af15-8a0437266d6d.PNG)
  - Back to VM, Click "Start" then select the ISO Windows Server 2022
    ![iso](https://user-images.githubusercontent.com/49325037/143592203-a4ab2208-b5b8-4ed7-8509-d0b2ac25a9fb.PNG)
  - Enter yor language and then click "Next"
    ![lang](https://user-images.githubusercontent.com/49325037/143592213-f68eff29-1a14-47de-b9ef-2ec2cb69474c.PNG)
  - Click "Install now"
    ![ins](https://user-images.githubusercontent.com/49325037/143592444-d9092cb1-5d60-4909-b0cc-de27f5d92868.PNG)
  - Select Windows Server 2022 edition (here I choose Datacenter Evaluation) with GUI (Desktop Experience) then install and click “Next”
    ![datacenter](https://user-images.githubusercontent.com/49325037/143592287-c2a6a46a-33cf-477b-997b-d2a33c50ac04.PNG)
  - Click "I accept the license terms" then click "Next"
    ![lisense](https://user-images.githubusercontent.com/49325037/143592314-56720cce-a403-4004-ac8a-29446c1dddca.PNG)
  - Select "Custom: Install Windows only (advanced)"
    ![custom](https://user-images.githubusercontent.com/49325037/143592656-96a8de54-fe62-4220-aa31-03882188f58d.PNG)
  - Select the partition to install Windows Server, Then click "Next"
    ![parti](https://user-images.githubusercontent.com/49325037/143592645-7fdb75ba-b564-4757-8c45-84c2448b2f16.PNG)
  - Process installation, wait for it to finish after finish the system will reboot to complete the process
    ![proses](https://user-images.githubusercontent.com/49325037/143592653-7dbca1b5-0066-4cfe-b22b-8f9d6da6b52e.PNG)
  - Configure the Administrator password and click "Finish"
    ![admin](https://user-images.githubusercontent.com/49325037/143592830-5a5be060-c31c-4d79-9857-f6a140289d11.PNG)
  - To login as Administrator user, press the combination on the keyboard simultaneously **Ctrl + Alt + Del**
  - Enter Administrator Password and press "Enter"
    ![lg](https://user-images.githubusercontent.com/49325037/143592812-ad8ab8f3-bc41-4768-abd2-2e09d7f80ace.PNG)
  - Windows Server 2022 installation with GUI (Desktop Experience) is complete and can be used
   ![finis](https://user-images.githubusercontent.com/49325037/143592921-4695600b-0bcd-4703-a4e7-6758ea9fd94e.PNG)
  - 

## Installation Active Directory Domain Services

- Step-Step Installation
  - Rename Computer using PowerShell, Then type `rename-computer -Newname Server22`
    ![rename](https://user-images.githubusercontent.com/49325037/143593069-59e05d7b-6657-4262-bf51-18c96c885c78.PNG)
  - Go to the "Server Manager" menu. Then select the “Manage” option then click “Add Roles and Features”. Then click “Next”
    ![manage](https://user-images.githubusercontent.com/49325037/143593166-f762f63d-5df6-43d8-b932-494cb19bfa59.PNG)
    ![manage1](https://user-images.githubusercontent.com/49325037/143593133-1cafbd3b-8e2d-414b-9241-36054c0d0f8b.PNG)
  - Select “Role-based or feature-based installation”. Then “Next”
    ![manage2](https://user-images.githubusercontent.com/49325037/143593143-f7ff94b5-d1f5-4c48-9bd0-4f4f5486970e.PNG)
  - Click “Select a server from the server pool” , Then "Next"
    ![manage3](https://user-images.githubusercontent.com/49325037/143593147-a5ca827b-92db-4666-9849-2262e7c5ea29.PNG)
  - Next, check the "Active Directory Domain Services" box. When you check the box, a short description of A.D.D.S appears and how it works. Then click "Add Feature", Then "Next"
    ![manage4](https://user-images.githubusercontent.com/49325037/143593148-fe405425-0bfe-4dbd-8caf-e43fbe3c1bc5.PNG)
  - Like this, Click "Next"
    ![manage5](https://user-images.githubusercontent.com/49325037/143593152-ca72b605-0cdc-44cb-9b8d-30809ff438b5.PNG)
  - Click "Next"
    ![manage6](https://user-images.githubusercontent.com/49325037/143593155-fb84c529-eda2-4c54-ad9a-3a2f6b5123ce.PNG)
  - Then click "Install"
    ![manage7](https://user-images.githubusercontent.com/49325037/143593160-1bae3eb3-59ad-4182-9ac4-21ab9e578e3c.PNG)
  - Wait until the process is complete
    ![manage8](https://user-images.githubusercontent.com/49325037/143593161-65aab77e-3b79-480b-86bd-410b24577154.PNG)
  - Installation complete 
    ![manage9](https://user-images.githubusercontent.com/49325037/143593162-9fdf5a80-c2f4-4ee7-a165-1c4af9244cdc.PNG)
