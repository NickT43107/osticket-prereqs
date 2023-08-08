<p align="center">
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

<h2>List of Prerequisites</h2>

- Step 1: launching Azure virtual machine.
- Step 2: Opening IIS and enableing IIS.
- Step 3: Downloading all necessary files.
  

<h2>Installation Steps</h2>

<p>

<img width="169" alt="image" src="https://github.com/NickT43107/osticket-prereqs/assets/139840658/4d846699-407d-4017-9280-e02a3802a0d6">


</p>
<p>
Step 1: When you are done signing in or signing up to azure, you will see options 1 & 2 on the home screen of azure. First you will need to start a resource group in or to make a virtual machine. Once you have that taken care of you can start to make your virtual machine. 
  
</p>
<br />

<p>
<img width="212" alt="image" src="https://github.com/NickT43107/osticket-prereqs/assets/139840658/5b2c9db8-0d15-452e-b7f1-7ab7dd4c29c6">
</p>
<p>
Step 2: Once everything is downloaded, you'll want to go ahead and start installing everything on to the virtual machine. You'll first want to create a directory for PHP, by first installing "PHP manager for IIS". Then you will want to create a file folder in "this PC" for PHP Zipped file download, take the contents from the "ZIPPED PHP 7.3.8" download and dump them into the file folder for PHP in "this PC", or C:/php for short. Install Rewrite Module/VC_redist.x86.exe. Now you will want to install MYSQL, once installed click typical setup->Launch Configuration Wizard->Standard Configuration. Then just create your username and Password for MYSQL. 

  Step 3: From here you will want to open IIS as admin, and register PHP within IIS. Next will be to Download osTicket from the Installation Files Folder
Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

<br />

<p>
  
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


