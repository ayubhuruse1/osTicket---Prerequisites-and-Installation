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

- Create a Resource Group in Microsoft Azure with a region of your choice.
- Use the Resource Group to create a new Virtual Machine (VM) with 2-4 virtual CPUs in Microsoft Azure.
- Open Remote Desktop to access the newly created Virtual Machine (VM).
- Install and enable Internet Information Services (IIS) in Windows with CGI.
- Download and install PHP Manager for IIS.
- Download and install the Rewrite Module (rewrite_amd64_en-US.msi).
- Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP.
- Download and install VC_redist.x86.exe.
- Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi).
- Download and install HeidiSQL.
- Continue setting up osTicket in the browser.
- Congratulations! Hopefully, osTicket is installed with no errors.
- Log in to the osTicket system as Admin Panel.

<h2>Installation Steps</h2>
<p>
<img src="https://user-images.githubusercontent.com/95878059/229222998-2a42ecea-4111-415a-8ef5-fac718b95a33.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p><p>
To provide further context, VM-OsTicket is the name of the Virtual Machine (VM) that you have created in Windows 10 using Microsoft Azure. It will be used to install and run osTicket, the open-source ticketing system, on your machine.
</p>
<br />
<p>
<img src="https://user-images.githubusercontent.com/95878059/229243869-bba4da25-8bd3-447d-86a1-80ccb63c5d18.jpg"/>
</p>
<p>
To access your VM, you will need to copy its IP address. Please follow these steps:

- Go to the VM-OsTicket overview in Microsoft Azure.
- Locate the IP address of the VM.
- Copy the IP address to your clipboard.
- You will need the IP address to access the VM using the Microsoft Remote Desktop App or any other remote desktop client.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229248114-e1f4ea9e-1554-46e5-b5fc-6aeb73be9541.jpg" height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>
<p>
If you are using macOS, you can use the Microsoft Remote Desktop App to access the Virtual Machine (VM). Please follow these steps:

- Open the Microsoft Remote Desktop App on your macOS.
- Paste the IP address that you copied from Step 2 into the "PC name" field.
- Click on "Add" to establish a remote desktop connection to the VM.
- Enter your login credentials for the VM when prompted.
Once you have successfully logged in to the VM, you can continue with the next steps of your installation process.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229244555-a4f8f6fd-c785-4572-b1cd-a08a031056ec.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To enable CGI in Windows 10, please follow these steps:

- Go to the Control Panel on your Windows 10 machine.
- Click on "Programs and Features."
- Click on "Turn Windows features on or off."
- Locate "Internet Information Services" and expand the node.
- Locate "World Wide Web Services" and expand the node.
- Locate "Application Development Features" and expand the node.
- Check the box next to "CGI."
- Click "OK" to save the changes.
- CGI is now enabled on your Windows 10 machine and you can proceed with installing and configuring osTicket..
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229245490-29fcbe90-0319-4660-b0eb-00e619257d23.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
Install osTicket v1.15.8. Copy the UPLOAD folder and paste it into C - inetpub - wwwroot, then restart Internet Information Services Manager. IIS Manager can be found in the start menu.

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246189-cb4bdf55-e468-47e6-b318-ebafd030a83b.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Extract and copy “upload” folder to c:\inetpub\wwwroot Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246488-dac3303e-6c4b-484a-9806-3b5b3a958d22.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To access the osTicket installation page, please follow these steps:

- Open Internet Information Services (IIS) Manager.
- Locate and click on "Sites" in the left-hand pane.
- Click on "Default Web Site."
- Locate the folder for your osTicket installation.
- On the Right-click on the folder and select "Browse *:80" from the context menu.
- You will be redirected to the osTicket installation page in your web browser. From there, you can proceed with setting up osTicket as per the installation instructions.

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229246594-e503be3a-143e-455f-a0f6-e8b7563da5c3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin the basic installation of osTicket, please follow these steps:

- Open your web browser.
- Enter the IP address or domain name of your osTicket installation in the address bar.
- Press "Enter" to navigate to the osTicket installation page.
- Fill out the basic installation form with the required information, including your database details and administrator account credentials.
- Click "Install" to begin the installation process.
- Once the installation is complete, you will be able to access the osTicket helpdesk and start providing support to your users.</p>
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
To proceed with the basic installation, you will need to create a password for the root user. Please ensure that your password meets the complexity requirements and security best practices.</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229247247-001508b4-24cc-4373-b71e-fb819cdefdb3.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin setting up osTicket, you will need to create a database. Please follow the instructions above to create a database called "osticket".</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/95878059/229247783-2567743b-dbee-4a9a-9af3-394d332fefcd.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To access the osTicket Admin Panel, please enter your credentials and log in. From there, you will be able to manage and customize your osTicket installation.
</p>
<br />
