<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>OsTicket-Prerequisites and Installation</h1>
This is the tutorial for OsTicket-Prerequisites and Installation Lab 3 .<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Resource Group then use that resource group to create a new Virtual mechine (VM) in Microsoft Azure with a regeion of your choice and make a virtual mechine (VM) with 2-4 virtual CPU.
-open Remote Desktop to access the virtual mechine(VM)
- Install / Enable IIS in Windows WITH CGI
- download and install PHP Manager for IIS 
- download and install the Rewrite Module (rewrite_amd64_en-US.msi)
- download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP
- download and install VC_redist.x86.exe.
- download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- download and install HeidiSQL.
- Continue Setting up osticket in the browser
- Congratulations, hopefully it is installed with no errors!
- Login to the osTicket system as Admin Panel

<h2>Installation Steps</h2>
<p>
<img src="https://user-images.githubusercontent.com/95878059/229222998-2a42ecea-4111-415a-8ef5-fac718b95a33.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p><p>
This is VM-OsTicke that i have created in the Windows 10 Virtual Machine in Microsoft Azure
</p>
<br />
<p>
<img src="https://user-images.githubusercontent.com/95878059/229243869-bba4da25-8bd3-447d-86a1-80ccb63c5d18.jpg"/>
</p>
<p>
Go to the VM-OsTicket overview and copy the ip Address.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229244257-54df8fb7-a539-421e-96bf-34a7f4673fea.PNG"/>
</p>
<p>
Am on MacOS, I'll be using the Microsoft Remote Desktop App to access the virtual Mechine(Vm) and paste the ip address you copies from step two in the PC name.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229244555-a4f8f6fd-c785-4572-b1cd-a08a031056ec.PNG"/>
</p>
<p>
Go to the control panel, click the Turn windowns feautures on or off and check the internel information system and check CGI.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229245490-29fcbe90-0319-4660-b0eb-00e619257d23.PNG"/>
</p>
<p>
download and install the Rewrite Module (rewrite_amd64_en-US.msi)
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229245786-cab3d218-19af-49bb-95aa-e4bc8b27e510.PNG"/>
</p>
<p>
download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246060-2ee10216-a2f0-4d36-950c-76cdb02a2224.PNG"/>
</p>
<p>
Install osTicket v1.15.8

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246189-cb4bdf55-e468-47e6-b318-ebafd030a83b.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy the UPLOAD folder and paste it into C - inetpub - wwwroot, then restart Internet Information Services Manager. IIS Manager can be found in the start menu.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246488-dac3303e-6c4b-484a-9806-3b5b3a958d22.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to sites -> Default -> osTicket
On the right, click “Browse *:80”

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246594-e503be3a-143e-455f-a0f6-e8b7563da5c3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open osTicket in your web browser and start filling out the basic installation.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246823-ec6281f2-5167-442e-a145-264eeff2571f.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and Install HeidiSQL 
Create a new session, root/Password1
Connect to the session
Create a database called “osTicket”
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229247629-ba898b58-739e-48b0-b754-700d868b50f9.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
create a password for root your going to need to enter the password in the basic installation.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229247247-001508b4-24cc-4373-b71e-fb819cdefdb3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Start creating a database called osticket.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229247783-2567743b-dbee-4a9a-9af3-394d332fefcd.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to the osTicket Admin Panel
</p>
<br />
