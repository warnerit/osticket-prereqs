<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL


<h2>Installation Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/e36639fa-fdc4-4fc4-9e73-b7095aa0ce64)

</p>
<p>
Go to Microsoft Azure and open virtual machines, click on create a new virtual machine, and create a Windows 10 VM with at least 2-4 vCPUs and 8 GB of memory, once you do that you can make a username and password to login to the virtual machine.


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/32d283f2-c764-47bd-a62d-85235ac98741)

</p>
<p>
Now that you have created your virtual machine you can now ahead go and log into it through using the Remote Desktop Connection application on your current computer.


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/ce9337e0-5194-4471-9881-a3b4e2e7f9ee)

</p>
<p>
Now that you are connected to your VM you will have to enable IIS. Go and access the control panel then select uninstall a program. Off to the left select "Turn windows features on or off". A list will appear then you will enable Internet Information Services.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/c6dd7a4e-3f23-4b10-a00a-4e83bec4abea)

</p>
<p>
Now that you have enabled IIS we need to install Web Platform Installer. I have provided a link here: (https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD) That link will provide you with all of the material you need to download to get osTicket up and running. Simply click the link and install the Web Platform Installer
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/dc23632c-15cd-467c-98f1-0b04b4b7fac7)

</p>
<p>
Once you have installed Web Installer Platform open it. From inside the application you are going to install MySQL 5.5 Afterwards install x86 version of PHP up until 7.3. There are some failed files such as C++ redistributable package as well as PHP 7.3.8 and PHP Manager for IIS those files can be found with the install link.


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/3cb1f4b9-2864-49ae-9628-4da689697e3e)

</p>
<p>
Next download osTicket. Then extract and copy the "upload" folder into c:\inetpub\wwwroot. Afterwards rename the folder to osTicket.

</p>
<br />

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/c497ce84-d798-4feb-8896-137602abf115)

</p>
<p>
Next you will want to download the "rewrite_amd64_en-US application which is also know as IIS URL Rewrite Module 2.

</p>
<br />


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/ee167e8b-3771-4452-97a8-936656b8a9a5)

</p>
<p>
Open the VC_redist.x86 application and also click install on that, this is Microsoft Visual C++ which is neccessary for this installation.


</p>
<br />


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/5946e9f5-a803-489a-a80b-c79b49fc0b47)

</p>
<p>
Now make the PHP folder in your C drive and select the PHP zip folder to extract to that folder, this will be the files that ticket system uses on the C drive.

</p>
<br />


</p>
<br />


</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/e26180a0-dc3c-4006-81e2-363648f092fe)

</p>
<p>
Go to the IIS, also known as the Internet Information Services and open the PHP manager and click register a new php version, and go to your C drive and find the php.cgi

</p>
<br />


</p>
<br />



</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/cd4f8d16-1ea7-48a2-9e99-b60c14fdb87b)

</p>
<p>
Next download osTicket. Then extract and copy the "upload" folder into c:\inetpub\wwwroot. Afterwards rename the folder to osTicket.

</p>
<br />


<p>
  
![image](https://github.com/user-attachments/assets/351201ac-9f28-440c-9dfc-a541b1f10d18)

</p>
<p>
Open IIS Manager and restart the server. Once inside IIS manager go to Sites->Default->osTicket on the right, click "Browse*.80" from there your default browser should open osTicket webserver.

</p>
<br />


</p>
<br />


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next download osTicket. Then extract and copy the "upload" folder into c:\inetpub\wwwroot. Afterwards rename the folder to osTicket.

</p>
<br />


</p>
<br />


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next download osTicket. Then extract and copy the "upload" folder into c:\inetpub\wwwroot. Afterwards rename the folder to osTicket.

</p>
<br />
