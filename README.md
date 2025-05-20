
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/7d310b5e-6cbf-44eb-a16e-f908c40caf9c)

- Creating a virtual machine enviroment to install osTicket.

![image](https://github.com/user-attachments/assets/9231fc66-e346-4d3a-82e0-df32c140afea)  ![image](https://github.com/user-attachments/assets/d00b24a5-4fa1-4e04-883e-ec36636677dc)

- Downloading the osTicket files and extracting them.

![image](https://github.com/user-attachments/assets/f7fff968-8a82-4ed2-843d-8da781819c0b)

- installing\Enabling IIS services with CGI on virtual machine.

![image](https://github.com/user-attachments/assets/15e472d7-7d2a-47a2-9d06-a6ec64d980e9)

- Installing PhP Manager for IIS.

![image](https://github.com/user-attachments/assets/30338958-669c-4494-a3f2-da23b06ef622)

- Installing IIS rewrite module.

![image](https://github.com/user-attachments/assets/779383ba-b036-46ee-9052-56a90ec76b42)  ![image](https://github.com/user-attachments/assets/153ba5ae-9b74-4688-9bb6-164f7ebcc99d)

- Creating PHP Folder on C drive and extracting PHP files onto it.

![image](https://github.com/user-attachments/assets/6ddef90b-a9b4-497e-93d3-752aabf36163)

- Installing Microsoft Visual C++

![image](https://github.com/user-attachments/assets/449a6743-c119-4052-93d3-a7e6f854c353) ![image](https://github.com/user-attachments/assets/1ea3f9c4-9ffd-4c0d-a856-1d0149aff94f)

- Installing MySql server and configuring Mysql Server instance.

![image](https://github.com/user-attachments/assets/f980ba5a-b57a-4e6e-86fe-2ad4ffab2bfe) ![image](https://github.com/user-attachments/assets/ba4df560-18b3-4f59-9622-41097684285d)


- Registering our Php version inside IIS and restarting our osTicket inside IIS.

![image](https://github.com/user-attachments/assets/361c2b8c-950f-4b9c-a028-a8cebf9b5478)

- Extracitng osTicket files.

![image](https://github.com/user-attachments/assets/f6e8d26f-af8f-46f1-a7b0-e4f9ff5b9433) ![image](https://github.com/user-attachments/assets/46f82c76-204d-497b-a1a7-47d8f2b741b8) 

- Moving upload folder from osTicket folder to Root server Folder and renaming upload folder to osTicket.

![image](https://github.com/user-attachments/assets/6fd07179-e38c-417e-8899-7a22fd3d426e)

- Opening osTicket in the browswer through IIS Manager.

![image](https://github.com/user-attachments/assets/66069e60-25ef-408f-9222-38c8ff452de7)

- Enabling php_imap.dll Php_opcache.dll php_intl.dll

![image](https://github.com/user-attachments/assets/64618dc2-c5e0-43e8-9da4-a3698cdd2b81)

- Refreshing osTicket Page and verifying that the new extensions have been activated.

![image](https://github.com/user-attachments/assets/3970ba78-74ab-4f12-8cb7-29cf14c1d673)

- Renaming ost-sampleconfig.php to ost-config.php.

![image](https://github.com/user-attachments/assets/8246c9d8-a52f-4f57-8b6b-447005d548d4)

- Giving everyone full control so osTicket can make the filechange in the backend(i know this isnt good to do but is for the sake of and the lab and i dont know what username osticket goes by).

![image](https://github.com/user-attachments/assets/86755e65-b6c6-4e99-88a2-60fcfd0dba00)

- Installing Heidisql.

![image](https://github.com/user-attachments/assets/7b24ea57-6ddd-458e-a046-ae5c3e022735)

- Opened Heidi sql Created a new session and connected to the session.

![image](https://github.com/user-attachments/assets/253f682a-413a-4235-819d-65d8e595368a)

- created a new database inside of Heidi Sql named osTicket.

![image](https://github.com/user-attachments/assets/94040798-7b5f-452c-81fd-50f382e88ece)

- Installing osTicket.

![image](https://github.com/user-attachments/assets/e35b4ad3-798d-430f-b7e3-12a1b8b53f4d)

- installation successfully done.

![image](https://github.com/user-attachments/assets/18078ee4-1e88-4f28-85e3-7c0d60dfe206)

- Accessing the osTicket Main interface as an agent\admin and end user.
