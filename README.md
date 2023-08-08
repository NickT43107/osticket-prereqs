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
- Step 2: Opening IIS and enableing IIS with CGI.
- Step 3: Downloading all necessary files.
  

<h2>Installation Steps</h2>

<p>

<img width="169" alt="image" src="https://github.com/NickT43107/osticket-prereqs/assets/139840658/4d846699-407d-4017-9280-e02a3802a0d6">

</p>
<p>
Step 1: When you are done signing in or signing up to azure, you will see options 1 & 2 on the home screen of azure. First you will need to start a resource group in or to make a virtual machine. Once you have that taken care of you can start to make your virtual machine. 
  
  - 1. Select the resourse group name.
  - 2. Create a name of the virtual machine. 
  - 3. Select windows for imagine.
  - 4. Select the size of the CPU that you can afford, though I would recomend using 4VCPU with 16GIB for fast computing.
  - 5. Create username and password to your chosing. 
  - 6. Click the box at the end of the page for licensing.
  - 7. Click Review and create.
    
  
  Once azure is done loading, you can click the home button and it will bring you back to the home page where you can click on virtual machines. From there you can copy the virtual machines IP address, can go down to your computers search bar and type remote desktop. Type in your username and password, and you'll promptly be logged into your virtual machine.
</p>
<br />

<p>
<img width="182" alt="image" src="https://github.com/NickT43107/osticket-prereqs/assets/139840658/5cd61782-eb2a-41de-be97-040c28def059">
</p>
<p>
Step 2: In order to open and enable IIS, go down to the search bar and type "Control panel" go to programs and features->window features on or off. Then select everyting that is selected in the photo. Then go to the browser and type in localhost to check and make sure everything was done correctly.

<br />

<p>
<img width="224" alt="image" src="https://github.com/NickT43107/osticket-prereqs/assets/139840658/faf12ca2-c329-411a-9670-6a8b3e115c1c">
</p>

<p>
  Step 3: This last step for this slide will be to download everything in the picture. Installation and setup will be in the next slide. Here is a link to everything that will neeed to be downloaded. https://drive.google.com/drive/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
</p>
<br />


